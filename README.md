# Fruit Plucker Arm 
This is the initial code for a fruit plucker arm that detects ripe fruits and plucks them.
The code is in its initial stages and is far from a working prototype


<h2>Steps to use the code </h2>
<ul>
  <li><h3>Clone the repo</h3><code>git clone https://github.com/abhinavtk97/Fruit-Plucker-Arm.git</code><br></li>
  <li><h3>Create environment in Anaconda for the project and install tensorflow and openCV</h3>
    <pre><code>conda create --name tensorflow
conda activate tensorflow
conda install -c conda-forge tensorflow
conda install -c conda-forge opencv</code></pre>
  </li>
  <li><h3>Install necessary dependancies</h3>
    <pre><code>sudo apt-get install protobuf-compiler python-pil python-lxml python-tk
pip install --user Cython
pip install --user contextlib2
pip install --user pillow
pip install --user lxml
pip install --user jupyter
pip install --user matplotlib</code></pre></li>
  <li><h3>Download protobuf compiler </h3><code>https://github.com/protocolbuffers/protobuf/releases</code></li>
  <li><h3>cd to the root directory of project and run </h3><code>protoc object_detection/protos/*.proto --python_out=.</code></li>
  <li><h3>In Linux </h3><code>export PYTHONPATH=$PYTHONPATH:`pwd`:`pwd`/slim</code><br><h3>In Windows </h3> add PYTHONPATH as the root of the project</li>
  <li><h3>run the code</h3><code>python final.py</code></li>
</ul>
