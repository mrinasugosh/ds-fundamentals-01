# Data Science Fundamentals Workshop 01 - Analyzing Data and Building a Dashboard

*Skills* - `Jupyter`, `Python`, `Pandas` `IBM Cloud`, `IBM Cloud Object Storage`, `IBM Watson Studio`

Extracting essential data from a data set and displaying it is a necessary part of data science. Understanding analytics and trends through displayed data is the purpose of a dashboard.

### Running the Workshop

There are two ways to run this workshop (IBM Watson Studio / Locally)

#### IBM Watson Studio(Recommended):
We would recommend using IBM Watson Studio so you don't have to worry about installing Jupyter Notebooks locally.

##### Step 1: Create Watson Studio Service

1. Log in to your IBM Cloud Account (create one if you don't have one already)

2. Navigate to <a href="https://cloud.ibm.com/catalog/services/watson-studio">Watson Studio</a>

##### Step 2: Create Watson Studio Project
A project is how you organize your resources to achieve a particular goal. Your project resources can include data, collaborators, and analytic assets like notebooks and models.

Follow the steps to <a href="https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/projects.html?audience=wdp">Create a Project</a> in Watson Studio

##### Step 3: Create Jupyter Notebook in Watson Studio
After you set up a project and configured the environment, you can create a notebook file. Note: This repository provides a sample notebook to get you started. 
 - Clone this repo:
 `$ git clone https://github.com/mrina24/ds-fundamentals-01`
 - Create a new Notebook. Select the `From File` tab and upload the `ds01-notebook.ipynb` to Watson Studio Project
 - Launch the notebook and follow the steps in there to get started!

#### Setting up the workshop local machine:
You can also complete this workshop locally by installing and running the notebook in this repo locally:
 - Clone this repo:
 `$ git clone https://github.com/mrina24/ds-fundamentals-01`
 - Follow the official quick start guide to <a href="https://jupyter.readthedocs.io/en/latest/install.html#new-to-python-and-jupyter"> Install and Run iPython/Jupyter Notebook </a>
 - Launch the notebook and follow the steps in there to get started!
`$ ipython notebook ds01-notebook.ipynb`
