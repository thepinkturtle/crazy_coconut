# crazy_coconut
Hurricane data from [NOAA](https://www.nhc.noaa.gov/data/). Neural Net exploring prediction capabilities based on only a few features, pressure, windspeed and time.

# Tips and tricks
In order to get a VSCode Jupyter virtual environment up and running, so as to have the least amount of Keras and Tensorflow friction flow this setup instructions [source](https://anbasile.github.io/posts/2017-06-25-jupyter-venv/):
- Inside the project folder create a new virtual environment: ```python -m venv projectname```
- Then activate it: ```source projectname/bin/activate```
- Now, from inside the environment install jupyter using pip: ```pip install jupyter```
- And now install a new kernel: ```ipython kernel install --user --name=projectname```
- Then, change your python interpreter in VSCode to the new one you just made