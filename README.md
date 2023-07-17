# user specific article recommendations study

### Summary
This study provides common methods used to recommend items to potential users.
It is triggered by the udacity "data-scientist-nanodegree" program (see https://www.udacity.com/).
In particular, the following recommendation topics are exemplary
applied to data from IBM covering user and article relations:
- rank-based recommendations
- user-user based collaborative filtering
- matrix factorization technique
 

### Motivation
Given a huge list of user-article pairs with articles being read, briefly viewed, or clicked by the corresponding user, how can we deduce recommendations
to users in the pool or even new ones?
This study starts by exploring data from IBM and presents different recommendation techniques.
It is an exemplary study for similar problems where the items are not articles but food, movies, or ...


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
Recommendations_with_IBM.ipynb         # main jupyter file
Recommendations_with_IBM.html         # main jupyter file as html file
README.md
requirements.txt                       # list of required packages
requirements_working_configuration.txt # packages covering a working configuration
data
|- articles_community.csv              # data comprising content for each article ID
|- user-item-interactions.csv          # data covering the dataframe of user-article pairs
project_tests.py                       # file used in tests in main jupyter file
top_5.p                                # data used to verify results
top_10.p                               # data used to verify results
top_20.p                               # data used to verify results
user_item_matrix.p                     # data used to verify results

```
