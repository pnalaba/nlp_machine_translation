# nlp_machine_translation
Repository to document Machine Translation projects that I have worked on. 

The first project here, was done as part of the NLP Nanodegree at [Udacity]( https://www.udacity.com/ )

# Organization
* This README has a brief description of each project/experiment and instructions for re-running the project code.
* The code is in Jupyter notebooks in general and have more detailed descriptions for each step

# Projects

## Basic Machine Translation
We start with a toy dataset of English and French sentences and build Deep Learning models to do machine translation from English to French. The first notebook builds and trains simple RNN based models on the dataset.

To setup the environment, it is suggested to create a python virtual environment as below

```console
foo@bar:~$ cd basic_machine_translation
foo@bar:~$ python -m venv test_env
foo@bar:~$ source test_env/bin/activate

[test_env]foo@bar:~$ pip install -r requirements.txt
## create a jupyter profile for this environment
[test_env]foo@bar:~$ ipython kernel install --user --name=test_env
[test_env]foo@bar:~$ jupyter notebook
```



