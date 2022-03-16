# Python_VMs_Installer

1. open default_env.yml with any text editor and change the name of the environment to whatever you like (currently "test-env")

2. install environment: 
  * open command prompt in the location of the environment.yml
  * type "conda env create -f default_env.yml" and press enter

3. install opencl:
  * open a command prompt in the location of the pyopencl file (or use the prompt from previous step)
  * activate the environment just created: type "activate <ENVIRONMENT_NAME>"
  * type "pip install <PYOPENCL_FILE_NAME>" and press enter

4. install pyclesperanto for GPU-accelerated image processing:
  * in the same command prompt, type "pip install pyclesperanto_prototype"

# Installation of cellpose environment

Follow instructions above, using cellpose_env.yml file.
The environment created will be called "cellpose".
