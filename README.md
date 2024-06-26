
## Important note
Please note that we use a patched jupros implementation (contained in this repo), so make sure that the notebook folder also contains the python file (`jupyros_action_client_patched.py`). The patch fixes a bug in the jupyros action_client ([fix PR is also opened on official Jupyros repository](https://github.com/RoboStack/jupyter-ros/pull/163)) and also implements some missing functionality in jupyros action_client (such as sent goal callback, cancelled goal callback etc.)


# How to run this notebook
In order to run this notebook, you need to setup the ros workspace. The steps to set it up is as follows: 

## download, source and make the workspace
```
git clone https://github.com/mehhdiii/assignment-2-with-monitoring-package
cd %workspace-folder% && source devel/setup.bash && catkin_make
```

## run the simulation

`roslaunch monitoring_package start_monitoring.launch`

## run the notebook as follows: 

Make sure the terminal has the workspace sourced. Then launch jupyter using the following command: 

`jupyter notebook --allow-root --ip 0.0.0.0`

Now you can open the notebook from jupyter. 

