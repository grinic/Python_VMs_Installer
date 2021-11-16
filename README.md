# Python_VMs_Installer

1. open environment.yml with any text editor and change the name of the environment to whatever you like (currently "test-env")

2. install environment: 
  * open command prompt in the location of the environment.yml
  * type "conda env create -f environment.yml" and press enter

3. install opencl:
  * open a command prompt in the location of the pyopencl file
  * activate the environment just created: type "activate <ENVIRONMENT_NAME>"
  * type "pip install <PYOPENCL_FILE_NAME>" and press enter

4. install pyclesperanto for fast image processing:
  * in the same command prompt, type "pip install pyclesperant_prototype"
