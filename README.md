# udacity_buildmyworld
Submission of Udacity project Build My World, part of [Robotics Software Engineer nanodegree](https://www.udacity.com/course/robotics-software-engineer--nd209).

## Content
In the Build My World project, the students are asked to create their own world with different models, as seen in the _model_ folder:
* _lidar_feature_ is a model for a pole wide-enough to be detected by lidars. Many can be placed to create a reference in a rather empty area.
* _test_course_ is the model for the whole world. It represents an outside test track that could be used by any kind of vehicles.
* _truck_ is a model for a simple 4x4 truck. The truck could be linked to ROS in order to become autonomous.

On top of that, a Hello World script is launched together with the world _test_course.world_, welcoming the user. This is to show that C++ code can be used together with Gazebo.

## Pre-requisites
This project requires a Linux machine with Gazebo, as well as all of its dependencies.
Git is also recommended to clone this repository.

## Installation
Simply `git clone` the repository on your local computer using your favorite Linux terminal.

## Usage
```
cd /change_to_your_local_path_where_this_repo_has_been_cloned/world
gazebo test_course
```

## Support
If you have some questions or need some support, please use the [Discussions](https://github.com/quesiu/udacity_buildmyworld/discussions) section.

## License
None
