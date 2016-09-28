<div class="clearfix" style="padding: 10px; padding-left: 0px">

<p>
<a href="http://bombora.com"><img src="https://app.box.com/shared/static/e0j9v1xjmubit0inthhgv3llwnoansjp.png" width="150px" class="pull-right" style="display: inline-block; margin: 5px; vertical-align: middle;"></a>
<h1> Bombora Data Science: Interview Exam </h1>
</div>
<img width="200px" src=https://app.box.com/shared/static/15slg1mvjd1zldbg3xkj9picjkmhzpa5.png >

---


# Welcome!

From all of us and Bombora Data Science, we're eager to get to know you! To do so, we'd thought we'd first engage you with a few exercises to demonstrate concepts we're interested and hope you are as well. 


*Note*: We'll be leveraging open tools and public repositories. Ethics and professional aspirations should drive you to work creatively, enthusiastically, and *independently*. Clearly, you should leverage all resources you can, but please, *do not* share this exam or your solutions with anyone else. :)

Thank you so much! Now, get comfortable and let's go!

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

### 1. Fork / clone this repo to your GitHub account.

#### Fork
It's the button above that looks like the one below (you can click either):

<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/bomboradata/datascience-exam/fork" data-icon="octicon-repo-forked" data-style="mega" data-count-href="/bomboradata/datascience-exam/network" data-count-api="/repos/bomboradata/datascience-exam#forks_count" data-count-aria-label="# forks on GitHub" aria-label="Fork bomboradata/datascience-exam on GitHub">Fork</a>

#### Local Clone

On your local machine, with git installed:

    git clone git@github.com:<your-gh-username>/datascience-exam.git

#### Checkout `datascience-engineer-intern` branch

Best if you develop against this branch:

	git checkout datascience-engineer-intern
	

### 2. Create your copy of `ds-interview-exam` nb

Create copy of `ds-interview-exam.ipynb` including your name, with the following command:

	cp ds-interview-exam.ipynb submittals/data-engineer-intern/<mylastname-myfirstname>__ds-interview-exam.ipynb 


### 3. Setup Jupyter Notebook Environment

#### 3.1 Launch Jupyter
You have two options:

1. **Upload the included `ds-interview-exam` notebook to [try.jupyter.com](try.jupyter.com)** (easy and recommended):
	- open [try.jupyter.com](try.jupyter.com),
	- Upload this notebook to 
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

**Note**: for those not familiar with Jupyter notebook, please view the *Welcome to ...* intro noteboooks included in file listing. Also, you can review the [Notebook Basics tutorial](http://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb).

After opening your notebook, you'll need to select a language kernel of your choice, (you can choose between Scala, R, Haskell, Python 2 or 3, Julia or even Bash).

- from menubar of the opened notebook, select * Kernel > Change Kernel > <your language>*

 

### 4. Solve TWO problems, one from each section.

1. Take note that there are **two** sections, they are:
	- *1. Algo + Data Structures*
	- *2. Prob + Stats*

2. Take 10-15 minutes to review questions across each section.

3. Select and answer **ONE** question from **EACH** section, or to be totally explicit:
	- select and answer a question from section 1 (e.g., either Q1.1 or Q1.2).
	- select and answer a question from section 2 (e.g., either Q2.1, Q2.2, Q2.3, Q2.4, or Q2.5).

This is you, shining. Think, Hack, Repeat. Enjoy this part. :)


### 5. Commit results and push to your remote repo.

- add and commit solution notebook.
- add and commit your resume with filename `mylastname-myfirstname__resume.myformat`
- push to remote repo

### 6. Open Pull Request to submit exam

To submit, [please open a PR](https://help.github.com/articles/creating-a-pull-request/) to the `datascience-engineer-intern` branch of the repo.


## Questions?

Open an issue in the GH repo, we provide a button right here, for your convenience. 

<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/bomboradata/datascience-exam/issues" data-icon="octicon-issue-opened" data-style="mega" data-count-api="/repos/bomboradata/datascience-exam#open_issues_count" data-count-aria-label="# issues on GitHub" aria-label="Issue bomboradata/datascience-exam on GitHub">Issue</a>


## Finished, what's next? 

Thank you for all of your hard work and your interest! You'll hear back from us, soon. :)

Go enjoy your day, you deserve it!


<!-- Place this tag in your head or just before your close body tag. -->
<script async defer src="https://buttons.github.io/buttons.js"></script>
