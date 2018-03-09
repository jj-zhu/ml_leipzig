# ML practice sessions

## Preparation

Do the following steps before the workshop. If you have problems at some point, we can try to solve them together during the first practical session.

### Install anaconda

Windows:

    https://repo.continuum.io/archive/Anaconda3-5.1.0-Windows-x86_64.exe
    
Linux:

    https://repo.continuum.io/archive/Anaconda3-5.1.0-Linux-x86_64.sh
    
or use your package manager.

After downloading, follow the installation instructions.

### Create a new anaconda environment

On windows, open the anaconda prompt

    conda create --name ML-workshop
    
### Install tensorflow and extensions inside the environment

First, activate the new environment (on windows, in the anaconda prompt)

    source activate ML-workshop
    
Next install scikit-learn, matplotlib and pandas

    conda install scikit-learn matplotlib pandas
    
Now, install keras for the deep learning session
    
    conda install keras
    
Finally, install the jupyter notebook extensions and configurator

    conda -C conda-forge jupyter_contrib_nbextensions jupyter_nbextensions_configurator
    
### Test your installation

If it is not active yet, activate the environment (on windows, in the anaconda prompt)

    source activate ML-workshop
    
Navigate to the workshop folder

    cd /path/to/workshop/folder
    
Start the jupyter notebook (from the anaoconda prompt, inside the ML-workshop environment)

    jupyter notebook
    
A new browser window should open automatically, otherwise follow the instructions.

In the new window, open the Nbextensions tab in the upper part of the screen

Activate the following extensions:

* Exercise
* Table of Contents
* Collapsible Headings
* Exercise2
* ExecuteTime

If everything worked fine so far, you are well prepared for the workshop.

JJ & Sebastian  
MPI-IS
