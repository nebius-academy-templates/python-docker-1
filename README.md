For TR team:

simple_project/simple_project/asgi.py

simple_project/simple_project/wsgi.py

tests/conftest.py

tests/test_container.py

tests/test_env_vars.py

tests/test_image.py

README.md


# python-docker-1

  
### Create a virtual environment

1. Launch the Visual Studio Code editor and through the “File” / “Open Directory” menu open the *Dev/python-docker-1/* folder.
2. Launch a terminal in VS Code, make sure you're running from the */python-docker-1/* directory (if you're on Windows, make sure you're running Git Bash in the terminal and not PowerShell or anything else), and run the command
- Linux/macOS
    
    ```bash
    python3 -m venv venv
    ```
    
- Windows
    
    ```python
    python -m venv venv
    ```
   
A virtual environment will be created in the python-docker-1/ directory and a venv folder will appear in which all project dependencies will be stored. The file structure will be like this:

### Activation of the virtual environment
In the terminal, go to the root directory of the project (Dev/python-docker-1/) and run this command:
- Linux/macOS
    
    ```bash
    source venv/bin/activate
    ```
    
- Windows
    
    ```bash
    source venv/Scripts/activate
    ```
    

Now all commands in the terminal will be preceded by the line `(venv)`.

💡 All further commands in the terminal should be executed with the virtual environment activated.

Update pip:

```bash
python -m pip install --upgrade pip
```

### Installing dependencies from the requirements.txt file:
While in the Dev/python-docker-1/ folder, run the command:

```bash
pip install -r requirements.txt
```

### Launching the project in dev mode

    
In the directory with the "manage.py" file, run this command: 

```bash
python manage.py runserver
```

In response, Django will report that the server is running and the project is available at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).


### Run tests locally
Having finished the task, launch the local tests. In the terminal, go to the root directory of the project *Dev/python-docker-1/* and run this command:
```shell
pytest
```
