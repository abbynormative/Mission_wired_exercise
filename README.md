

# Background: Cleaning user data and computing acquisitions per day

This repo contains a Jupyter Notebook intended as a data engineering exercise in merging and filtering data and computing limited basic statistics. Three datasets are merged together, focusing on constituents with a primary email or a specific subscription status. A csv of selected columns is outputted, and then a new csv is created showing the constituent acquisitions per day. The notebook also contains some checkpoints to verify the data corresponds to the expected output.

## Required packages

Running this repo requires Python and the installation of Jupyter Notebook and Pandas. It is recommended that users install [Anaconda](https://docs.anaconda.com/anaconda/install/index.html), which includes both Jupyter and Pandas.

## Usage

Clone this repo. Unzip the two zipped datasets ending in .gz. From inside the directory where the repo was cloned, start Jupyter Notebook via the command line:

```console
foo@bar:~$ jupyter notebook
```
This will open a browser window that shows the files in that directory. Click on the Jupyter notebook for this repo to start the notebook.

Once the notebook is running, each line of code can be run by the pressing the 'Run' button in order to check each step in sequence. Each proceeding line must be run to receive the correct output. Alternatively, the entire notebook can be run by navigating to 'Cell' and then selecting 'Run All'. 

The notebook will first output a 'people.csv' file and then an 'acquisition_facts.csv' file, both of which will appear in the same directory as the notebook.