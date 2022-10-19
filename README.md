# Crash course in Data Science

## What?
In this document, you will find the steps to start working on 
data science projects from scratch.

I will assume some familiarity with programming languages like:
* for loops, 
* calling functions.

Some familiarity with Mathlab or Mathematica would be valid programming 
experience unless you are thinking of going deep in the process to put models 
in production or building applications that can use models; in that case, you 
will need real software knowledge that initially I do not include in this guide.

You will need knowledge of statistics and mathematics (basic but will be assumed).

This guide will help you to build some basic procedures in Data Science 
(and Machine Learning), But I will suggest following an online video or course; 
the content in this guide will help you to follow any course, and the course will 
help you to deepen the understanding and details that I can’t (because time) put 
in this guide.

## How?

To build the guide, we will use most of the standard tools in the industry; most 
are simple and free tools, but they will help us learn the job, visualize what we 
do and keep our code and model history.

### Git
The first tool in our list is Git; this is a version control system, and you 
need to install it on your computer (if you don’t have it yet). Follow this link 
to learn how to install Git:

https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

As we have Git, we will also need a Repository to have the history, keep track of 
the changes, and, more importantly, share the code.

Now you need to open an account (if you already don’t have one) in GitHub:

https://github.com/

GitHub  
>  is an Internet hosting service for software development and version 
control using Git. It provides the distributed version control of Git plus 
access control, bug tracking, software feature requests, task management, 
continuous integration, and wikis for every project.

So we will use GitHub to store and share our code, and some datasets. 

Why? We will do some code and file sharing, so instead of sending files by e-mail 
and losing track of the changes or risking corrupt files in the process, we will 
use GitHub as a central repository of the information.

Another reason is GitHub is the de facto standard in the industry, and more 
importantly, you will find the solution to many problems inside GitHub or 
inside Gist, as they are public repositories, a lot of people publish there 
they code and solutions, even complete courses. For example this guide will be 
to the public in GitHub.

Now that you have Git and GitHub, go to the following link:

https://github.com/jcamacaro/data_science

If you are reading this is because you have Git installed on your machine, you 
have a GitHub account, and you follow the link, so now, clone this repository 
on your computer, 

`git clone https://github.com/jcamacaro/data_science.git`

### Python

The next step is to check if you have Python installed on your machine, so in the command line, type:

`python -V`

If you have Python now, you know which version you have; if you don’t have Python now, you know you need to install it

https://www.python.org/downloads/

### Anaconda 

We avoid working directly in the Python distribution we just installed, as we will
need to install different packages depending on the problem we are solving. 
Sometimes the dependencies of this package can conflict, so to avoid any problem, 
it is good practice to work inside an environment that can isolate any problem.

There are different flavours of Python environments; from those, we will use 
Anaconda, so now go and install Anaconda:

https://www.anaconda.com/products/distribution

As you will learn, Anaconda helps to keep a curated version of the different data science libraries that we will be using.


### First environment
Now we will create our work environment:

`conda create -n env_ds python=3.9 anaconda`

In this case, we are building an environment with Python 3.9; you can change that version if you have very specific requirements.

*Follow the instruction in the command line.*

Now we will activate our environment (this is the first step you need to do when you work in the future)

`conda activate env_ds`

Now you will install some extra packages to avoid problems in the future:

`conda install -c conda-forge jupyter notebook nb_conda_kernels jupyter_contrib_nbextensions`

`pip install tensorflow keras lightgbm fastcluster hdbscan tslearn`

### Jupyter

Now from the command line where you have been working and running all 
the commands (where you have activated the Anaconda environment), and be sure 
you are inside the folder of the project *data_science*, you will run the 
following command

`jupyter notebook`

This command will launch an interactive tool Jupyter, that will allow you to 
work easily with Python, run the code interactively and see the output and, in 
some cases, interact with this output 


## An IDE

Her,e you can install any IDE you like, there are tooooo many options and 
flavours, and styles; I can suggest Visual Studio Code

https://code.visualstudio.com/















