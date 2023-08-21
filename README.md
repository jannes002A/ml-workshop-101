### Deutsch

Dies ist das Repo für den Machine Learning 101 Workshop.
Das Repo enthält 4 Jupyter-Notebooks

- NN_in_Numpy.ipynb ist eine Implementierung eines neuronalen Netzes in purem Numpy
- NN_in Pytorch.ipynb ist eine Implementierung eines neuronalen Netzes in Pytorch
- Data_poisoning.ipynb ist eine Implementierung von Data Poisoning
- Model_stealing.ipynb ist eine Implementierung von Model Stealing

Es wird vorausgesetzt, dass eine Version von python3 installiert ist, damit es funktioniert. Wenn dies der Fall ist, macht folgendes

```
git clone https://github.com/jannes002A/ml-workshop-101.git

python3 -m venv ws

source ./ws/bin/activate

pip3 install -r requirements.txt

pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu

jupyter-lab
```

Im Terminal wird eine url angezeigt (wahrscheinlich 127.0.0.1:8888). Kopiert die url aus dem Terminal und gebt sie in Ihren Webbrowser ein.

Es sollte nun möglich sein, auf die Notebooks zuzugreifen.

----
Um die Python environment wieder zu verlassen, muss man einfach im Terminal

```
deactivate 
```

eingeben.

---
Um die Notebooks nach der Installation noch mal zu starten muss man folgendes machen

```
cd ml-workshop-101

source ./ws/bin/activate

jupyter-lab
```


### English

This is the repo for the Machine Learning 101 Workshop.
The repo contains 4 jupyter notebooks

- NN_in_Numpy.ipynb is a implementation of a neural network in plain numpy
- NN_in Pytorch.ipynb is a implementation of a neural network in pytorch
- Data_poisoning.ipynb is a implementation of data poising
- Model_stealing.ipynb is a implementation of model stealing


In order to work it is assumed that a version of python3 is installed. If this the case do the following

```
git clone https://github.com/jannes002A/ml-workshop-101.git

python3 -m venv ws

source ./ws/bin/activate

pip3 install -r requirements.txt

pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu

jupyter-lab
```
The in the terminal a url is shown (probably 127.0.0.1:8888). Copy the url from the terminal and put it into your webbrowser.

You should now be able to access the notebooks.

----
To deactivate the Python environment just type into the terminal

```
deactivate 
```


---
If you want to start the notebooks after the installation, do the following

```
cd ml-workshop-101

source ./ws/bin/activate

jupyter-lab
```




------------
Especially the NN_in_python notebook was taken from here [SkalskiP](https://github.com/SkalskiP/ILearnDeepLearning.py/blob/master/01_mysteries_of_neural_networks/03_numpy_neural_net/Numpy%20deep%20neural%20network.ipynb )
Thanks for this cool work!


