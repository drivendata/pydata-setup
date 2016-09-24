# TL,DR EDITION
### Setting up your machine for data science in Python

Here's the short version of the commands without much explanation:

 1. Download Miniconda [for Windows](https://repo.continuum.io/miniconda/Miniconda2-latest-Windows-x86_64.exe) or for [Mac OSX](https://repo.continuum.io/miniconda/Miniconda2-latest-MacOSX-x86_64.sh).
 2. Install by either:
     - **Windows**: Double click `Miniconda2-latest-Windows-x86_64.exe` and follow the instructions
     - **Mac OSX**: open the terminal and run `bash Miniconda2-latest-MacOSX-x86_64.sh`

 3. Download the environment file [**for Windows**](https://github.com/drivendata/pydata-setup/raw/master/environment.windows.yml) or [**for OSX**](https://github.com/drivendata/pydata-setup/raw/master/environment.osx.yml).
 4. Create the environment with by either:
     - **Windows**: Open the command prompt and run `conda env create -f environment.windows.yml`
     - **Mac OSX**: Open the terminal and run `conda env create -f environment.osx.yml`

 5. Activate the tutorial by either:
    - **Windows**: Run `activate tutorial`
    - **Mac OSX**: Run `source activate tutorial`

----
### Test things work

6. Run Jupyter notebook by typing the following command `jupyter notebook .`
7. Open a Jupyter notebook file (`.ipynb`). If you don't have one, you can [download this fun Jupyter notebook](http://norvig.com/ipython/How%20to%20Do%20Things%20with%20Words.ipynb).

---
### Leave the tutorial environment
 8. To stop Jupyter notebook hit `Ctrl+c` when you have the terminal open.
 9. 5. To leave the tutorial environment at the command line and go back to your normal environment:
     * **Windows**: `deactivate tutorial`
     * **Mac OSX**: `source deactivate tutorial`
