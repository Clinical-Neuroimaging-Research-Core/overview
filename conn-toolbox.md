# CONN Toolbox

CONN (functional connectivity toolbox) is a matlab-based software for the computation, display, and analysis of functional connectivity in fMRI.

CONN can be installed on your local machine, or the software can be used via the Oscar matlab and CONN toolbox modules.

## How to install CONN locally

### Requirements:

* SPM12 
* MATLAB

### Installation:

* Download the conn software package from [NITRC CONN](https://www.nitrc.org/projects/conn/)
* Move unzipped conn folder to /Applications  
![Screen Shot 2022-01-26 at 8 43 34 AM](https://user-images.githubusercontent.com/37027603/151173822-672ae3cf-0896-4980-b301-0cad78268021.png)


* In Matlab, add the /Applications/conn directory to your matlab path 
  - In your matlab ```startup.m``` file, write the following lines of code:
  ```
  addpath('/Applications/spm12')
  addpath('/Applications/conn')
  ```
  
 - This will add both spm12 and conn to your matlab path

### You will now be able to open conn from matlab simply by typing "conn" on the matlab command line

## Using CONN on OSCAR
