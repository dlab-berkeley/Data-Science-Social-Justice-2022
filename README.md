# Data Science + Social Justice Workshop

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](https://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FData-Science-Social-Justice&urlpath=lab%2Ftree%2FData-Science-Social-Justice%2F&branch=main)
[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Data-Science-Social-Justice/HEAD)

This repository contains the materials for D-Lab / UC Berkeley Graduate
Division's Data Science + Social Justice Workshop. No prior experience with
Python is needed.

## Workshop Goals

This 6-week workshop will give you the opportunity to learn the essential tools
and methods for data science analysis and be introduced to critical frameworks
that will enable you to create a project of your own design and to tell stories
that can counter the market-first mentality of data science. This cohort-based
workshop focuses on inherent prejudice in data sets and analysis and teaches you
to deploy solutions to create social impact with data science.

The course has two basic components. In the workshops, we engage in research in
Python to analyze a language dataset using computational tools. In the
discussions, we will deal with leading thinkers on data feminism, data activism,
ethics, indigenous technologies, and critical race theory. We discuss issues
around data gathering, surveillance, bias in machine learning, and other
critical aspects of data science. The materials in this GitHub repository
correspond to the workshops. For the readings, see the bCourses website.

You are not expected to have prior programming knowledge, and you are not
evaluated on your coding skills. However, this course does make use of Jupyter
Notebooks including Python code, so you will have the chance to work on your
coding skills and your understanding of some techniques and approaches in
Natural Language Processing (NLP).

## Installation Instructions

We will be working in Python and Jupyter Notebooks for the material in this
course. While you can run these tools remotely, it's worth getting them set up
on your personal machine for added flexibility. 

To run Python, we will use a **package management software** called Anaconda.
Anaconda makes it easy to install Python and Jupyter, as well as a bunch of
other packages that are handy for data science. Installing Anaconda is the
easiest way to make sure you have all the necessary software to run the
materials for this workshop. Complete the following steps:

1. [Download and install Anaconda (Python 3.9
   distribution)](https://www.anaconda.com/products/individual). Click
   "Download" and then click 64-bit "Graphical Installer" for your current
   operating system.

2. Follow the instructions to install Anaconda on your computer, using the
   installer you downloaded.
    - You can follow [this
      guide](https://docs.anaconda.com/anaconda/install/windows/) if you're on
      Windows. You can skip Step 2. Do not add Anaconda to your PATH variable
      (Step 8).
    - You can follow [this
      guide](https://docs.anaconda.com/anaconda/install/mac-os/) if you're on
      Mac. Follow the guide for the graphical installer. If you're comfortable
      with the terminal, you can follow the guide for the command-line install.
      You can skip Step 2.
    - You can follow [this
      guide](https://docs.anaconda.com/anaconda/install/linux/) if you're on
      Linux. Feel free to skip Step 2.

3. Launch Anaconda Navigator. This should be a program available on your
   computer. You can follow [this
   guide](https://docs.anaconda.com/anaconda/install/verify-install/https://docs.anaconda.com/anaconda/install/verify-install/)
   for more details.
    - You can skip this step if you're comfortable launching Jupyter from the
      command prompt or terminal.

4. Anaconda Navigator should look something [like
   this](https://docs.anaconda.com/anaconda/navigator/). It's an easy way to
   quickly launch a Jupyter notebook and get started with coding. Once you're
   looking at the home screen, click on "Launch" under Jupyter notebook. You
   should see a browser window pop open, with the url specifying some kind of
   "localhost".

5. You now have a Jupyter notebook open! You can navigate throughout your files
   on this Jupyter notebook. It can open different kinds of files, but you'll be
   mostly interested in files with the extension `.ipynb` (short for IPython
   notebook, the precursor to Jupyter). So, you'll need to download the files
   for this course.

6. Download the [Data-Science-Social-Justice workshop
   materials](https://github.com/dlab-berkeley/Data-Science-Social-Justice):
    - Click the green "Code" button in the top right of the repository
      information.
    - Click "Download Zip".
    - Extract this file to a folder on your computer where you can easily access
      it (we recommend Desktop or a special "Projects" folder).
    - If you're comfortable with SSH, you can feel free to clone the repository.

7. Navigate to the folder that you saved the Data-Science-Social-Justice
   materials in. Click on `lessons`, then on `module1`. Open
   `01_python_fundamentals.ipynb` to get started!

## UC Berkeley DataHub

The UC Berkeley DataHub is a resource you can use to remotely run the materials
in this workshop. Click on the following button to go to the DataHub (it will
ask you to authenticate with your CalNetID):

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](https://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FData-Science-Social-Justice&urlpath=lab%2Ftree%2FData-Science-Social-Justice%2F&branch=main)

The DataHub downloads this repository, along with any necessary packages, and
allows you to run the materials in a Jupyter notebook that is stored on UC
Berkeley's servers. No installation is necessary from your end - you only need
an internet browser and a CalNet ID to log in. By using the DataHub, you can
save your work and come back to it at any time. When you want to return to your
saved work, just go straight to [DataHub](https://datahub.berkeley.edu), sign
in, and you click on the `Data-Science-Social-Justice` folder.

The DataHub is a great resource, but an important goal of this workshop is being comfortable with Python, Jupyter, and Anaconda. We recommend trying the code *both* on your local machine and the DataHub.

## Binder

An alternative to the DataHub is Binder, which does not require a CalNetID to use. Binder operates similarly as DataHub, but on a different set of servers. It also will not save your work. Start a Binder by clicking the following button:

[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Data-Science-Social-Justice/HEAD)

# Other D-Lab Python Workshops

The following publicly available D-Lab workshops may be of interest to you as you work through the materials in this repository.

* [Python Fundamentals](https://github.com/dlab-berkeley/python-fundamentals)
* [Python Data Wrangling](https://github.com/dlab-berkeley/Python-Data-Wrangling)
* [Python Data Visualization](https://github.com/dlab-berkeley/Python-Data-Visualization)
* [Python Text Analysis](https://github.com/dlab-berkeley/Python-Text-Analysis)
* [Python Machine Learning](https://github.com/dlab-berkeley/Python-Machine-Learning-Fundamentals)
* [Fairness and Bias in Machine Learning](https://github.com/dlab-berkeley/fairML)

# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

# Contributors

This materials were heavily based on Tom van Nuenen's Digital Humanities course at UC Berkeley, with many additional modifications by Tom. Additional contributors include:
* Pratik Sachdeva
* Renata Barreto
* Emily Grabowski
