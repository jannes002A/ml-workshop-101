This is the repo for the Machine Learning 101 Workshop.
The repo contains 4 jupyter notebooks

- NN_in_Numpy.ipynb is a implementation of a neural network in plain numpy
- NN_ini_Pytorch.ipynb is a implementation of a neural network in pytorch
- Data_poisoning.ipynb is a implementation of data poising
- Model_stealing.ipynb is a implementation of model stealing


In order to work, it is assumed that a version of python3 is installed. If this the case do the following

```
git clone https://github.com/jannes002A/ml-workshop-101.git

cd ml-workshop-101

python3 -m venv ws

source ./ws/bin/activate

pip3 install -r requirements.txt

pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu

jupyter-lab
```
In the terminal a url is shown (probably 127.0.0.1:8888...). Copy the url from the terminal and put it into your webbrowser.

You should now be able to access the notebooks.



------------
Especially the `NN_in_python` notebook was taken from here [SkalskiP](https://github.com/SkalskiP/ILearnDeepLearning.py/blob/master/01_mysteries_of_neural_networks/03_numpy_neural_net/Numpy%20deep%20neural%20network.ipynb)
Thanks for this cool work!
