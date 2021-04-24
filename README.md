# xMVPA Version 1.2

================================
## Requirements

xMVPA was developed in scripts written in C and Matlab for performance purposes. The software has been compiled using a C compiler in a Linux enviroment only due to internal library requirements, so please use a linux distribution to use this software or a linux terminal emulator in your operating system.

Windows and OSX native environments are currently not supported.

In Windows, a workaround could be to install WSL (Windows Subsystem for Linux) https://ubuntu.com/tutorials/ubuntu-on-windows#1-overview and install Matlab runtime and running the software from this environment subsystem.

Due to the the very rescritive approval software policies and certifications required to run an application for OSX, we will not provide native support for this Mac/OS in the future. There is not a widespread linux emulator for OSX either, like for Windows.

Another workaround that can work for both Windows and OSX would be to install a linux distribution in a virtualizer such as VirtualBOX https://www.virtualbox.org/ or VMware https://www.vmware.com/products/workstation-player.html 
 
## Installation Instructions


***** STEP 1 ******

Download the MATLAB Runtime installer at the latest update level for the selected release from the website at https://www.mathworks.com/products/compiler/matlab-runtime.html and dowload the latest version for Linux environments.


***** STEP 2 ******

Go to folder where Matlab runtime has been downloaded. The file should be called MATLAB_Runtime_XXX_glnxa64.zip where XXX is the version of the runtime. 

Open a terminal in this folder and type:

unzip -d mrun MATLAB_Runtime_XXX_glnxa64.zip

A folder called "mrun" has been created, go into this folder with the terminal

***** STEP 3 ******

With the terminal pointing to this folder type the following command:

sudo -H ./install

Follow the intructions of the dialog box Confirm your choices and click Next. Finally click on finish to exix the installer

## Running instructions

Go the directory where you unzipped xmvpa.zip either using your file system explorer or through the linux terminal using unzip command.

Open a terminal and go to this directory, then type

./run_xmvpa.sh <<Matlab runtime directory>>

replace <<Matlab runtime directory>> by the path of where your Matlab runtime directory. This is usually /usr/local/MATLAB/MATLAB_Runtime/vXXX where XXX is the number of the version you have installed, for example /usr/local/MATLAB/MATLAB_Runtime/v910. The number of the version you have dowloaded and installed can by found in the download page https://uk.mathworks.com/products/compiler/matlab-runtime.html








