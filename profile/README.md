# ANDA-NI 2026

## Course Overviews

### ANDA (Advanced Neural Data Analysis) Topic Schedule: June 15th-19th, 2026

  - **Monday, June 15th, 2026**: [Sonja Grün: Measuring Neural Interactions in the Brain](https://github.com/ANDA-NI-2026/ANDA-Day1-Spike-Train-Correlations.git)
    - Homework Notebook: [Link](https://github.com/ANDA-NI-2026/ANDA-Day1-Spike-Train-Correlations/blob/main/01_homework/01_hw_stationary_spiketrains.ipynb)
    - Video 1: [Sonja Grün - Part 1 - Measuring and Investigating Neural Interactions in the Brain - Correlations](https://vimeo.com/showcase/12277813?video=990487416)
    - Video 2: [Sonja Grün - Part 2 - Measuring and Investigating Neural Interactions in the Brain - Higher Order Interactions](https://vimeo.com/showcase/12277813?video=1023322200)
      
  - **Tuesday, June 16th, 2026**: [Hideaki Shimazaki: State-space Analysis of Neural Interactions](https://github.com/ANDA-NI-2026/ANDA-Day2-State-Space-Analysis)
    - Homework Notebook: [Link](https://github.com/ANDA-NI-2026/ANDA-Day2-State-Space-Analysis/blob/main/01_homework_binary_population_codes/01_hw_binary_spike_trains.ipynb)
    - Video: [Hideaki Shimazaki - State Space Analysis for Neural Interactions](https://vimeo.com/showcase/12277813?video=1200750829)
      
  - **Wednesday, June 17th, 2026**: [Byron Yu: Dimensionality Reduction of Large-Scale Neural Recordings](https://github.com/ANDA-NI-2026/ANDA-Day3-Dimensionality-Reduction)
    - Homework Notebook: [Link](https://github.com/ANDA-NI-2026/ANDA-Day3-Dimensionality-Reduction/blob/main/01_homework_pca_for_spike_sorting/01_exercises.ipynb)
    - Video: [Byron Yu - Dimensionality Reduction of Large-Scale Neuronal Recordings](https://vimeo.com/showcase/12277813?video=1003925215)
      
  - **Thursday, June 18th, 2026**: Martin Nawrot: Mechanisms Underlying Cortical Variability Dynamics
    - Homework Notebook: [Link](https://github.com/ANDA-NI-2026/ANDA-Day4-Cortical-Variability-Dynamics/blob/main/01_hw_simulating_poisson_neurons/01_hw_exercises.ipynb)
    - Video 1: [Martin Nawrot - Part 1 - Empirical Analysis of Variability](https://vimeo.com/showcase/12277813?video=1019684839)
    - Video 2: [Martin Nawrot - Part 2 - Explaining Cortical Variability Dynamics](https://vimeo.com/showcase/12277813?video=1019684877)
   
  - **Friday, June 19th, 2026**: Udo Ernst: Spectral Analysis

### NI (Neuroinformatics) Topic Schedule: June 22nd-25th, 2026

  - **Monday, June 22nd, 2026**: Repositories and Data Repositories with Git and Datalad
    - Homework: [Link](https://github.com/ANDA-NI-2026/NI-Day1-Code-and-Data-Repositories/blob/main/01_hw_github_and_osf/01_hw_exercises.ipynb)
  - **Tuesday, June 23rd, 2026**: Working with Ephys Data Models with Neo and Nix
  - **Wednesday, June 24th, 2026**: Data Formats and Storage for Electrophysiology with HDF5 and NWB
  - **Thursday, June 25th, 2026**: Multi-Script Worfklows & Repository Organization with Snakemake

### ANDA-NI Retreat Dataset Preparation Day: June 26th, 2026
  - **Friday, June 26th, 2026**: Dataset Presentations and Preparation

## Daily Plan

  - (45 mins): **Homework Review (Notebook 1), Scientific Lecture, and Warm-Up Discussion**
  - (80 mins): **Learning Round 1: (Notebook 2)**
  - (15 mins): *Break*
  - (70 mins): **Learning Round 2: (Notebook 2 or Notebook 3)**
  - (Optional: Max 20 mins): *Post-Session Hang-out**


## Before the Course

### Install Software Dependencies

To run the materials for this course, it is recommended that you:
- Install [Pixi](https://pixi.sh/dev/installation/) or alternatively [Conda](https://conda-forge.org/download/) to create virtual environments
- Install [Git](https://git-scm.com/install/windows) for version control
- Create a [GitHub account](https://github.com/signup)
- Install [VSCode](https://code.visualstudio.com/download) as a code editor

*Note*: VSCode not working for you?  No problem!  All work is done inside Jupyter Notebooks in this course, so if you'd like to use a different editor, please feel free.  
  - For Jupyter Lab: `pixi run install-kernel` then `pixi run jupyter` gets Jupyter Lab working quickly,
  - For Google Collab: A Collab link is provied in every notebook 

## Before Each Session

### 1. Clone the Session's Git Repository

`git clone <repo_url>`

### 2. Set up your Python Environment

`pixi run install-kernel`

### 3. Open the Repo in VS Code or Jupyter Lab

> Note: Jupyter Lab only fits comfortably to the ANDA Course; for NI, we will be using the IDE-focused Visual Studio Code much more.

For jupyer lab: `pixi run jupyter`. After JupyterLab opens, select the `anda-<day>` kernel.

### 4. Watch the Video Lectures

Go to http://anda-lectures.andani.info/ and watch the lectures associated with that day's lecturer.

### 5. Complete the Homework 

Complete the exercises in the jupyter notebook in `01_homework`.  

### 6. Submit the Homework

Once it's complete (or, at least, you've made a solid attempt to complete at least 75% of it, even if you got stuck), please prefix your last name to the filename (e.g. Homer Simpson would make "`simpson_anda_day1_homework.ipynb`") and send it to the course dropbox at https://uni-bonn.sciebo.de/s/pLsAYmGW5zLnnHR.

### 6. Watch the Intro Lecture Video (ANDA only)

Watch the session's lecture to prepare for the high-level scientific topics that will come up that day.

###  7. Come to the Session!

The rest of the day's materials, including exercise, notebooks, datasets, and solutions will appear in this repo during the session.  Just call `git pull` and you'll get the updates.

See you there!
