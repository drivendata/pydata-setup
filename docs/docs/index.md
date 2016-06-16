# Setting up your machine for data science in Python

> So you're into snakecharming and crystal balls? Consider this the magic supply shop...

**Time required**: *[~20 - 30 minutes]*

This is a community-maintained set of instructions for installing the Python Data Science stack. If you'll be using the programming language Python and its related libraries for loading data, exploring what it contains, visualizing that data, and creating statistical models this is what you need. Here's how to get your machine setup properly.

## 1. Install Anaconda

Anaconda puts nearly all of the tools that we're going to need into a neat little package: the Python core language, an improved REPL environment called `Jupyter`, numeric computing libraries (`NumPy`, `pandas`), plotting libraries (`seaborn`, `matplotlib`), and statistics and machine learning libraries (`SciPy`, `scikit-learn`, `statsmodels`). We'll use Anaconda's installer to handle setting up the environment that we'll work in.

 * Anaconda installer packages:
    * [Windows](https://repo.continuum.io/miniconda/Miniconda2-latest-Windows-x86_64.exe)
    * [Mac OSX](https://repo.continuum.io/miniconda/Miniconda2-latest-MacOSX-x86_64.sh)
 * Once this downloads, you can follow the instructions for installing on your operating system: [at this link](http://conda.pydata.org/docs/install/quick.html).
 * **Note:** It's easiest just to use Anaconda's defaults in the installer. You don't have to change anything unless you're _sure_ you want something different.

## 2. Download and install the packages that we will use
 * Download this environment file: Remember where you save the file `environment.yml`. You'll need that path shortly. You don't need to open that file right now.
     * [**Windows**](https://github.com/drivendata/pydata-setup/raw/master/environment.windows.yml)
     * [**OSX**](https://github.com/drivendata/pydata-setup/raw/master/environment.osx.yml)
 * Open the commmand line.
     * **Windows** - Hit "Start" and then type "Command Prompt" and use that terminal.
     * **OSX** - Type `Cmd+Space` and then enter `Terminal` in the search box to open the terminal.

 * Run the following commands, which will install the package and put you in the tutorial environment.
     * `conda env create -f <PATH_TO_ENVIRONMENT.YML>` - You'll need to replace `<PATH_TO_ENVIRONMENT.YML>` with the actual path where the file was downloaded. For OSX, that's often (`/Users/<USERNAME>/Downloads/environment.yml`). For Windows, it is usually `C:/Users/<USERNAME>/Downloads/environment.yml`. You'll have to replace `<USERNAME>` with your username on your machine.

 <script type="text/javascript" src="https://asciinema.org/a/7wnh8mi63hzs4cvddsu4vr745.js" id="asciicast-7wnh8mi63hzs4cvddsu4vr745" async></script>

* That will download all of the packages that we'll be using. When it finishes, you can activate the environment with the following command:
    * **Windows** - `activate tutorial`
    * **OSX** - `source activate tutorial`

<script type="text/javascript" src="https://asciinema.org/a/1hq7x65wbuccelwe8ojik20in.js" id="asciicast-1hq7x65wbuccelwe8ojik20in" async></script>

## 3. Run Jupyter notebook!
 * In your command prompt **with the tutorial environment activated**
 * Type the following command `jupyter notebook .`
 * A browser window will open, showing the Jupyer environment. By default, you will be in a file browser view.
 * In the file browser, find where you downloaded the course materials (if you have them yet).
 * Click on one of the notebook (*.ipynb) files to get started!

<script type="text/javascript" src="https://asciinema.org/a/9owid7a4cbt35zu15elhns4ot.js" id="asciicast-9owid7a4cbt35zu15elhns4ot" async></script>

## 4. To stop Jupyter notebook:
 * Hit `Ctrl+c` to stop the Jupyter notebook server running on your machine. (Make sure to use `Ctrl+s` in the notebook to save it first!)

## 5. To leave the tutorial environment (with all our fun packages) and go back to your normal environment:
 * **Windows** - `deactivate tutorial`
 * **OSX** - `source deactivate tutorial`

