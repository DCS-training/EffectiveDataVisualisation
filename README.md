# Effective Data Visualisation

This repository host the material connected to a training developed by **Dave Elsmore** ([Edina](https://edina.ac.uk/)) for CDCS on good data visualisation. 
The availability of digitized data has been growing at an exponential rate and utilising this data can lead to a more complex understanding of various research areas. In order to communicate this knowledge effectively, it is often essential to use visualisations to provide a clear picture of your key arguments. 

This tutorial covers:  
- What makes a good visualisation?  
- Bar charts, Line graphs, Maps, and Scatter Plots  
- Choosing the right method for the story you want to tell  
- Examples of different technical approaches, Excel, Google Charts, and Python  

## Copyright

This repository has a [![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc/4.0/) license

## How to use this repository

Follow along the tutorial using the 'tutorial.md' file. The last section of the tutorial uses a Jupiter Notebook to show how to produce good data visualisation via Python 


## How to use the Jupyter Notebooks

### 1. Noteable

If you are part of the University of Edinburgh you can use [Noteable](https://noteable.edina.ac.uk/) the cloud-based computational notebook system which work on your browser from any device.

To get started:

#### Get the Notebook files for this tutorial
Download the files listed on the right to a location on your computer
Make sure you know the location they have been downloaded to (usually your 'Downloads' folder) as you will need to upload them to Noteable. (The filename should end with '.ipynb'. If your computer has appended '.txt' to the end of the file make sure this is removed)
#### Start Noteable
1.  Open the following link in a new tab:  [https://noteable.edina.ac.uk/login](https://noteable.edina.ac.uk/login)
2.  Log in with your EASE credentials
3.  Under 'Standard Notebook' click 'Start'
#### Upload the Notebook to Noteable
1.  From the Noteable home page, click on the 'Upload' button at the top right of the screen and browse to one of the files you saved earlier to select it.
2.  Now click the blue 'Upload' button to load it into Noteable
3.  Once the file has been uploaded, click on the filename to start the Notebook


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
1. Download the notebook on your machine
2. Go to Upload
3. Navigate to where you have download your file
4. Select Upload again
5. Double click on the uploaded file 

[anaconda]: https://www.anaconda.com/distribution
[anaconda-dl]: https://www.anaconda.com/download/
[python]: https://python.org
[jupyter]: https://jupyter.org/index.html
[jupyter-install]: https://jupyter.org/install.html
[video-mac]: https://www.youtube.com/watch?v=TcSAln46u9U
[video-windows]: https://www.youtube.com/watch?v=xxQ0mzZ8UvA

### 3. Run the notebooks via GoogleColab

Open Google Colab: [https://colab.research.google.com](https://colab.research.google.com)
If you are not already logged you will be prompted to log-in via gmail
#### Upload the Notebook to Noteable
1. Go on the GitHub header and copy paste the link to the notebook you want to use and press enter

### 4. Using the Notebook
The Notebook contains paragraphs of explanatory text interspersed with grey cells containg code blocks. To run a code block and see the result:

1.  Place your cursor within the cell
2.  Click the 'Run' button on the top menu
4.  The results of running this code will appear below
5.  if the results don't appear immediately, check the icon in the browser tab. AN eggtimer icon indicates it is processing the code.
6.  It is best to follow the Notebook from top to bottom as some code blocks will depend on results from previous cells
7.  You can edit code blocks yourself and run them to see the results of your changes
### 5. Clearing the cells
To clear the results and run the code again you can use the 'Cell' menu on the top menu bar

1.  To clear the results of the current cell:  **Cell > Current Outputs > Clear**
2.  To clear the results of all cells:  **Cell > All Output > Clear**
