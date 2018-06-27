## Learning Venv Python

```
sudo apt-get install python3-venv
python3.6 -m venv <venvname> //to create the venv folder
source venv/bin/activate // to activate the virtual environment
pip freeze // see which modules are installed
pip freeze > requirements.txt // move modules and versions to a requirements files
pip install -r requirements.txt // to install the modules that are in the requirements
python <namefile>
```

### Tips
When you install a module dont forget to add it to the requirements.txt using `pip install -r requirements.txt`


### Benefits
You will have an env for each project. Like a box, you will open it just when necessary