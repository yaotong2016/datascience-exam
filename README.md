<div class="clearfix" style="padding: 10px; padding-left: 0px">

<p>
<a href="http://bombora.com"><img src="https://app.box.com/shared/static/e0j9v1xjmubit0inthhgv3llwnoansjp.png" width="150px" class="pull-right" style="display: inline-block; margin: 5px; vertical-align: middle;"></a>
<h1> Bombora Data Science: Interview Exam </h1>
</div>
<img width="200px" src=https://app.box.com/shared/static/15slg1mvjd1zldbg3xkj9picjkmhzpa5.png >

---


# Welcome!

From all of us and Bombora Data Science, we're eager to get to know you! To do so, we'd thought we'd first engage you with a few exercises to demonstrate concepts we're interested and hope you are as well. 

Get comfortable and let's go!

# Instructions

## Overview
We're going to leverage typical analysis and development workflows used by our team to conduct an interview exam. In short, you'll:

- clone this repo, 
- open the exam Jupyter notebook in an environment of your choice (web or local), 
- select a language (kernel) of your choice (you can choose between Scala, R, Haskell, Python 2 or 3, Julia or even Bash), 
- answer two questions of your choice,
- add and commit your solution
- add and commit your resume (and other docs, if you wish)
- push your solution to your remote repo,
- send us a PR with your completed exam submittal.

## Details

### 1. Clone this repo a local machine

On your local machine, with git installed:

    git clone <repo-name-here>

### 2. Create your copy of `ds-interview-exam` nb

Create copy of `ds-interview-exam.ipynb` including your name, with the following command:

	cp ds-interview-exam.ipynb submittals/data-engineer-intern/<mylastname-myfirstname>__ds-interview-exam.ipynb 


### 3. Setup Jupyter Notebook Environment

#### 3.1 Launch Jupyter
You have two options:

1. **Upload the included `ds-interview-exam` notebook to [try.jupyter.com](try.jupyter.com)** (easy and recommended):
	- open [try.jupyter.com](try.jupyter.com),
	- Upload this notebook to [try.jupyter.com](try.jupyter.com)
		- click `upload` in upper right corner
   		- select the local notebook file (`data-science-exam.ipynb`)
    - click on notebook to open.

2. or, **create a local conda env**, if you prefer finer control of packages, (difficult):
    - [install conda / miniconda](http://conda.pydata.org/).
    - create `bombora-datascience-exam` conda environment, via (from repo root): 
        `conda env create -f bombora-datascience-exam.yml`
    - activate conda environment, via: 
        `source activate bombora-datascience-exam`
    - launch Jupyter, via: 
        `jupyter notebook`
    - open `ds-interview-exam.ipynb` notebook 

#### 3.2 Setup Jupyter

**Note**: for those not familiar with Jupyter notebook, 

1. Select a language kernel of your choice (you can choose between Scala, R, Haskell, Python 2 or 3, Julia or even Bash)

	- from menubar, select * Kernel > Change Kernel > <your language>*

2. Read t
 

### 4. Solve TWO problems, one from each section.

1. Take note that there are **two** sections, they are:
	- *1. Algo + Data Structures*
	- *2. Prob + Stats*

2. Take 10-15 minutes to review questions across each section.

3. Select and answer **ONE** question from **EACH** section, or to be totally explicit:
	- select and answer a question from section 1 (e.g., either Q1.1 or Q1.2).
	- select and answer a question from section 2 (e.g., either Q2.1, Q2.2, Q2.3, Q2.4, or Q2.5).

This is you, shining. Think, Hack, Repeat. Enjoy this part. :)


### 5. Commit results and push to a remote repo.

- add and commit solution notebook.
- add and commit your resume with filename `mylastname-myfirstname__resume.myformat`
- push to remote repo

## Finished? 

Thank you for all of your hard work!

- open up PR to `datascience-engineer-intern` branch of our repo.
- Send a notification email to `nhalecky@bombora.com`
- you'll hear back from us, soon. :)
