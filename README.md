# Made-With-ML
This is a tutorial from Made With ML, where we learn how to combine Machine Learning with Software Engineering to design, develop, deploy and iterate on production ML applications.


On MacOS, when setting the python environment to 3.10.11, after doing
```
pyenv global 3.10.11
```
do the following immediately after:
```
eval "$(pyenv init -)"
```
Make sure that you are working on the correct python version by doing
```
python3 --version
```
In order to run jupyter lab, if getting an error of the sort 'zsh: command not found: jupyter', add the path to the library to PATH. First, look for jupyterlab path:
```
pip3 show jupyterlab | grep Location
```
And then, add the path to jupyterlab to PATH:
```
export PATH=/path/to/jupyterlab:$PATH
```
