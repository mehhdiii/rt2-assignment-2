# How to run this notebook

In order to run this notebook, you need to setup the ros workspace. The steps to set it up is as follows: 

## download, source and make the workspace
`git clone https://github.com/mehhdiii/assignment-2-with-monitoring-package`
`cd %workspace-folder% && source devel/setup.bash && catkin_make`

## run the simulation

`roslaunch monitoring_package start_monitoring.launch`

## run the notebook as follows: 

Make sure the terminal has the workspace sourced. Then launch jupyter notebook using the following command: 

`jupyter notebook --allow-root --ip 0.0.0.0`
