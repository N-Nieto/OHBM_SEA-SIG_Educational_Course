# OHBM_SEA-SIG_Educational_Course
Navigating machine learning pitfalls and explainability in brain-behavioral predictive modeling.


## Running the notebooks locally

### Set-up (this needs to be done only once)

First you need to have Python and Git installed.

1. Open a Terminal/Powershell
2. Clone this repository: `git clone https://github.com/N-Nieto/OHBM_SEA-SIG_Educational_Course.git`
3. Go to the newly cloned directory with the files: `cd OHBM_SEA-SIG_Educational_Course`
4. Install _virtualenv_: `pip install virtualenv`
5. Create a new virual environment: `virtualenv venv`
6. Activate the new virtual environment: `source venv/bin/activate`
7. Install the required packages: `pip install -r requirements.txt`
8. Install jupyter and notebook: `pip install jupyter notebook`

### Run jupyter

If you have closed the terminal, or you are not continuing after the set-up, you need to first open a terminal, go to the directory where you cloned the files in step 3 of the set-up procedure and activate the virtual environment (step 6).

To run the jupyter notebook server, just type:

`jupyter notebook` in the terminal.

The first time you will need to open the `get_files.ipynb` notebook and execute all its cells to download and prepare the data.

