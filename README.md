# ExampleWebPython
## Developer
###Creating an environment from an environment.yml file
Use the terminal or an Anaconda Prompt for the following steps:
Create the environment from the environment.yml file:
```bash
conda env create -f environment.yml
```
_The first line of the yml file sets the new environment's name. For details see Creating an environment file manually._

Verify that the new environment was installed correctly:
```bash
conda env list
```
Activate the new environment: 
```bash
conda activate <<environment_conda>>
```

You can also use conda info --envs.


## Execution
Its command execute project django, with port default.
```bash
python manage.py runserver
``` 

Its command execute project django, with port in specific.
```bash
python manage.py runserver <<port>>
```
Its command execute project django, with ip in specific port in specific.
```bash
python manage.py runserver <<ip>>:<<port>>
``` 