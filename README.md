[<img src="images/logo.png" width="400">](https://ohbm-environment.org/ohbm-satellite-event/)[<img src="images/logo_fzj.png" width="400">](https://www.fz-juelich.de/en/inm/inm-7/research-groups/applied-machine-learning-aml)


# Educational Course: Navigating machine learning pitfalls and explainability in brain-behavioral predictive modeling.

[Nicolás Nieto](https://scholar.google.com/citations?user=0N32qusAAAAJ&hl=de), [Kaustubh Patil](https://scholar.google.com/citations?user=Q-yjJpEAAAAJ&hl=de&oi=ao), [Vera Komeyer](https://scholar.google.com/citations?user=Dv2FKdkAAAAJ&hl=de&oi=ao), [Federico Raimondo](https://scholar.google.com/citations?user=B-dZVCIAAAAJ&hl=de&oi=ao).


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


## Running the Notebooks on Google Colab (you need a Google account)

1. **Go to the file**: Find the file that you want to run in the repo. 
2.  **Click the badge  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> on the top of the file** to launch the Colab.
2.  **Uncomment the first cell** This will download the data and set the path.
3.  **You are good to go!**: Now you can run the code on Google Colab. 


## Running the Notebooks on Binder

You can run these notebooks instantly online without any local setup using Binder.

1.  **Click the badge** to launch the Binder environment:
    [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/N-Nieto/OHBM_SEA-SIG_Educational_Course/HEAD)

2.  **Wait for the environment to build.** This may take a few minutes. Binder is creating a live, interactive server with all the necessary packages and data pre-installed. If the enviroment exist, it will automatically connect.

3.  **Start exploring!** Once the Jupyter interface loads, navigate to the desired notebook (`*.ipynb` file) and click on it to open and run it.