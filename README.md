# user specific article recommendations study

### Summary


### Motivation

### Data sources: 

### Install/run instructions:
1. Install python >= 3.11 and the packages denoted in requirements_working_configuration.txt preferably in a virtual environment as exemplarily shown for the windows command prompt:
```
      projectfolder:> python -m venv .venv
      projectfolder:> cd .venv\Scripts
      projectfolder\.venv\Scripts> .\activate.bat
      projectfolder\.venv\Scripts> cd ..\..
      projectfolder:> python -m pip install -r requirements_working_configuration.txt
```
      Within your project folder "projectfolder" use the "python" command as long as the virtual environment is activated
      (if not working with/on the project, the virtual environment should be deactivated by executing projectfolder\.venv\Scripts\deactivate.bat).

      Important note: If you are using requirements.txt (no package versions provided) instead of requirements_working_configuration.txt, make shure to install ipykernel before (python -m pip install ipykernel). The order seems imnportant.

2. In the programming IDE select .venv\Scripts\python.exe as Kernel.

1. Run all code blocks in "Recommendations_with_IBM.ipynb"

### Files in the repository
```
Recommendations_with_IBM.ipynb # main jupyter file
README.md
requirements.txt                       # list of required packages
requirements_working_configuration.txt # packages covering a working configuration

```