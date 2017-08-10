# NT-motor-module

T-STorM32

The T-STorM32's encoder support builds on the NT concept

![Image of NT](http://www.olliw.eu/storm32bgc-wiki/File:Tstorm32-wiring-scheme-sketch.jpg)

v2.x NT motor module hardware:

9.3.2017: T-STorM32 NT motor module v2.4E released

eagle files are on github: https://github.com/olliw42/storm32bgc

all info on the plugs&wires I'm using: https://www.rcgroups.com/forums/show...&postcount=156

info on the ring magnets: https://www.rcgroups.com/forums/show...0&postcount=85

---------------------------------------------------------------------------
AlexMos Brushless Gimbal Controller (SImpleBGC) Tuning Guide

https://aerialpixels.com/support/alexmos-brushless-gimbal-controller-simplebgc-tuning-guide/

#### The first step in the gimbal configuration consists of configuring the NT motor modules, for each axis. 
Two parameters need to be set
- number of motor poles
- offset between mechanical and electrical angle

** These values are stored permanently in the NT motor module, 
and need never be modified once set, unless of course the "NT motor module + motor" unit is modified.

configuration of the NT motor modules is not possible via the GUI, but requires accessing the CLI of 
the NT motor module using a standard terminal program, such as HTerm
