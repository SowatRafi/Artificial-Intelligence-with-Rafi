**To create a new Environment in Conda**

`conda create -n (environment_name)`

**To run the environment**

`conda activate (environment_name)`

**To stop the environment**

`conda deactivate`

**For requirements**

`conda --list -e > Requirements.txt`

**For executing the Requirements**

`conda create --name <env_name> --file Requirements.txt`