# Effective Data Visualisation

This repository hosts the material connected to a training course developed by **Dave Elsmore** ([Edina](https://edina.ac.uk/)) for CDCS on good data visualisation.
The availability of digitized data has been growing at an exponential rate and utilising this data can lead to a more complex understanding of various research areas. In order to communicate this knowledge effectively, it is often essential to use visualisations to provide a clear picture of your key arguments.

This tutorial covers:  
- What makes a good visualisation?  
- Bar charts, Line graphs, Maps, and Scatter Plots  
- Choosing the right method for the story you want to tell  
- Examples of different technical approaches, Excel, Google Charts, and Python  

## Copyright

This repository has a [![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc/4.0/) license

## How to use this repository

Follow along with the tutorial using the 'tutorial.md' file.
You can download all the files for this tutorial by clicking the green 'Code' button at the top of the page and then clicking 'Download ZIP'.  
Alternatively, if you're familiar with git, you can clone the repository to your computer.
The last section of the tutorial uses a Jupyter Notebook to show how to produce good data visualisation via Python.
These are the files whose names end with '.ipynb'. If your computer has appended '.txt' to the filename during the download process, make sure this is removed.

## How to use the Jupyter Notebooks

### 1. Noteable

If you are part of the University of Edinburgh you can use [Noteable](https://noteable.edina.ac.uk/), a cloud-based computational notebook system which works on your browser from any device.

To get started:

#### Start Noteable

1.  Open the following link in a new tab: [https://noteable.edina.ac.uk/login](https://noteable.edina.ac.uk/login)
2.  Log in with your EASE credentials
3.  Under 'Please select a personal notebook server', select 'Standard Notebook (Python 3)' and then click 'Start'

#### Upload the Notebook to Noteable

1.  From the Noteable home page, click on the 'Upload' button at the top right of the screen and browse to one of the files you saved earlier to select it.
2.  Now click the blue 'Upload' button to load it into Noteable
3.  Once the file has been uploaded, click on the filename to start the Notebook

Alternatively, you can clone this Git repo directly into Noteable to see all the files. To do this, copy this URL: https://github.com/DCS-training/EffectiveDataVisualisation. Then, from the Noteable homepage, click '+GitRepo'. Paste the URL in 'Git Repository URL'; you do not need to fill in any of the other fields. Click 'Clone'. You will now have a folder called 'EffectiveDataVisualisation' containing all the files for this course.

### 2. Installing Python via Anaconda

[Python][python] is great for general-purpose programming and is a popular language for scientific computing as well. Installing all of the packages required for this lessons individually can be a bit difficult, however, so we recommend the all-in-one installer [Anaconda][anaconda].

Regardless of how you choose to install it, please make sure you install Pythonversion 3.x (e.g., Python 3.6 version).

#### Windows - [Video tutorial][video-windows]

1. Open [anaconda.com/download][anaconda-dl] with your web browser.
2. Download the Python 3 installer for Windows.
3. Double-click the executable and install Python 3 using _MOST_ of the default settings. The only exception is to check the **Make Anaconda the default Python** option.

#### macOS - [Video tutorial][video-mac]

1. Open [anaconda.com/download][anaconda-dl] with your web browser.
2. Download the Python 3 installer for macOS.
3. Install Python 3 using all of the defaults for installation.

#### Starting Python

To start Jupyter Notebook Open the Anaconda Navigator and Launch Jupyter Notebook

#### Upload the Notebook

1. Go to Upload
2. Navigate to where you have download your file
3. Select Upload again
4. Double click on the uploaded file

[anaconda]: https://www.anaconda.com/distribution
[anaconda-dl]: https://www.anaconda.com/download/
[python]: https://python.org
[jupyter]: https://jupyter.org/index.html
[jupyter-install]: https://jupyter.org/install.html
[video-mac]: https://www.youtube.com/watch?v=TcSAln46u9U
[video-windows]: https://www.youtube.com/watch?v=xxQ0mzZ8UvA

### 3. Run the notebooks via GoogleColab

Open Google Colab: [https://colab.research.google.com](https://colab.research.google.com).
If you are not already logged you will be prompted to log-in via gmail.
An 'Open notebook' window will pop up. Click on the 'GitHub' tab on the left-hand side, then paste the link to the notebook you want to use and press enter.

## Using the Notebook

The Notebook contains paragraphs of explanatory text interspersed with grey cells containing code blocks. To run a code block and see the result:

1.  Place your cursor within the cell
2.  Click the 'Run' button on the top menu
4.  The results of running this code will appear below
5.  if the results don't appear immediately, check the icon in the browser tab. AN eggtimer icon indicates it is processing the code.
6.  It is best to follow the Notebook from top to bottom as some code blocks will depend on results from previous cells
7.  You can edit code blocks yourself and run them to see the results of your changes

### Clearing the cells

To clear the results and run the code again you can use the 'Cell' menu on the top menu bar

1.  To clear the results of the current cell:  **Cell > Current Outputs > Clear**
2.  To clear the results of all cells:  **Cell > All Output > Clear**
