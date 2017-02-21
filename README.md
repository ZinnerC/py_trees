# Py Trees

[ ![License] [license-image] ] [license]
[ ![0.5.x-Release] [0.5.x-release-image] ] [0.5.x-releases]
[ ![0.4.x-Release] [0.4.x-release-image] ] [0.4.x-releases]

[ ![Docs] [docs-image] ] [docs]
[ ![0.5.x-Docs] [0.5.x-docs-image] ] [0.5.x-docs]

[license-image]: https://img.shields.io/badge/License-BSD%203--Clause-orange.svg?style=plastic
[license]: LICENSE

[0.5.x-release-image]: http://img.shields.io/badge/release-0.5.x-blue.svg?style=plastic
[0.5.x-releases]: https://github.com/stonier/py_trees/tree/release/0.5-kinetic
[0.4.x-release-image]: http://img.shields.io/badge/release-0.4.x-blue.svg?style=plastic
[0.4.x-releases]: https://github.com/stonier/py_trees/tree/release/0.4-indigo-kinetic

[docs-image]: https://readthedocs.org/projects/py-trees/badge/?version=latest&style=plastic
[docs]: http://py-trees.readthedocs.io/en/latest
[0.5.x-docs-image]: https://readthedocs.org/projects/py-trees/badge/?version=release-0.5-kinetic&style=plastic
[0.5.x-docs]: http://py-trees.readthedocs.io/en/release-0.5-kinetic/

## About

This is a python implementation of behaviour trees designed to facilitate the rapid development
of medium sized decision making engines for use in fields like robotics. Brief feature list:

* Sequence, Selector, Parallel and Chooser composites
* Blackboards for data sharing
* Python generators for smarter ticking over the tree graph
* Python decorators for enabling meta behaviours
* Render trees to dot graphs or visualise with ascii graphs on stdout

Refer to the [package documentation](http://py-trees.readthedocs.io/en/latest/) for more detail.


## Installation

From [ppa](https://launchpad.net/~d-stonier/+archive/ubuntu/snorriheim) on Ubuntu/Xenial

```
sudo apt install python-py-trees
```

From [pypi](https://pypi.python.org/pypi/py_trees):

```
pip install py_trees
```

Or in a sandboxed ROS Kinetic environment (coming soon):

```
sudo apt install ros-kinetic-py-trees
```

## Development

You can develop in either a virtualenv (python style):

```
source ./virtualenv.bash
```

or in a catkin environment alongside other ROS py-trees packages:

* https://github.com/stonier/repos_index/blob/devel/kinetic/py_trees.repos
