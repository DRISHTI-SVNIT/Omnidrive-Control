# Omnidrive-Control

Omnidrive control is a project developed by DRISHTI which aims at developing robust open loop as well as closed loop control over an omnidrive chassis. It also aims at designing and developing systems that are able enough to drive a chassis with known configuration in a straight line, go to rendezvous points, control heading as per required and follow any pattern of path. This repository does not deal with path planning.

Complete documentation link : http://omnidrivecontrol.readthedocs.io/en/latest/

# Installation

## Setup

The complete setup of the robot and hardware description can be found here : 

[https://omnidrivecontrol.readthedocs.io](https://omnidrivecontrol.readthedocs.io)

Please follow it to setup the hardware as well as software for using codes from this repository.

## Commands
> The project is not ready yet to write this section of readme. As soon as a version is released with command level handling of the chassis to be driven, this will be updated. Currently, the points are manually written in codes and rebuilt and burnt in the onboard computers of the robot.


# How to contribute?

## To learn

This section will just introduce you to the concepts that will be handy in general for working with this repository. 
**Disclaimer** : With the version changes of the robot the following suggestions might get completely useless as a tool but there is a guarantee of it being useful as a knowledge to understand the methods used in new version. An exact tutorial of things of a particular version shall be incorporated in the [readthedocs link](#setup).


If you are a complete newbie to microcontrollers or embedded systems, you can follow this series of mircontroller tutorial videos by Patrick Hood Daniel : https://www.youtube.com/watch?v=JMMamSVy1Zs&list=PLE72E4CFE73BD1DE1




## Coding standards

Maintain the coding standards of the organization as mentioned here :
https://drive.google.com/open?id=0B_xhbTN9ggV-TmlyR0YzN3VJRTA



## Hardware upgrades
Changes in hardware should be explicitly incorporated in the documentation with :

* hardware model/number/datasheet

* what did it replace?

* why did it replace?

* experimental plots, if required



## Maintain versions

Every major change in the flow of the omnidrive control scheme should be pushed to master as a new version. Preserving the older versions for easy comparision between two systems or in case the older configuration is required for some other purpose. *NO VERSION SHOULD BE OVERWRITTEN OR ERASED*



## readthedocs
The readthedocs should be maintained simlutaneously while working by the developers. A good project is a waste if you cannot make people comphrehend what it does. And what is more suitable than  a timely, apt and elaborate documentation of it. Learn about how to write a readthedocs documentation using Sphinx Generator here :
https://pythonhosted.org/an_example_pypi_project/sphinx.html



## Merging of pull requests
A pull request shall be merged only if the above mentioned guidelines for contributions are followed and ofcourse, if the codes are tested for no runtime errors with desired response. While pulling a request, please update the readthedocs as well as the readme.md accordingly.
