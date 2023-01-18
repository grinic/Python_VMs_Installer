# Python_VMs_Installer

1. open default_env.yml with any text editor and change the name of the environment to whatever you like (currently "test-env")

2. install environment: 
  * open command prompt in the location of the default_env.yml
  * type ```conda env create -f default_env.yml``` and press enter

*Note:* In case of DLL error message when importing pyclesperanto via:
```
>>> import pyclesperanto_prototype as cle
```
please make sure recent drivers are installed for the GPU/OpenCL device.
Refer to https://github.com/clEsperanto/pyclesperanto_prototype for more information.
Do not install drivers yourself, instead contact IT or MIF.

*Note:* every time you login a VM and want to start working with your personal environment, make sure you activate it by typing
```
activate test-env
```
in a terminal.

# Installation of cellpose environment

Follow the official instructions:
https://github.com/MouseLand/cellpose
