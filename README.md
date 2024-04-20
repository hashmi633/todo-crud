1. create new project `poetry new todo-crud --app`
2. install fastapi and uvicorn packages using `poetry install fastapi uvicorn`. below is the example of the result of installing fastapi package. 
  * Creating virtualenv app-P8ffJDPA-py3.11 in C:\Users\AB\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.11_qbz5n2kfra8p0\LocalCache\Local\pypoetry\Cache\virtualenvs
3. environment need to select after running above fastapi command. for this, we can follow one of the 3 ways:
  * close the vscode and then reopen your project again. environment will be automatically selected.
  * open the command palette using Ctrl + Shift + P command and then select the option "Python: Select Interpreter". you will see the list of environments. select the one that was shown after running step 2 command.
  * open the command palette using Ctrl + Shift + P command and then select the option "Python: Select Interpreter". you will see a option of "Enter interpreter path". then paste the environment path that was resulted after running step 2 command in the following manner:
    *  C:\Users\AB\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.11_qbz5n2kfra8p0\LocalCache\Local\pypoetry\Cache\virtualenvs/app-P8ffJDPA-py3.11
    * note that the after the provided path in step 2, in last the virtual environment is also mentioned using "/".
  