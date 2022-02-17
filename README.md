# CommandLineWorkshop

ou can do data science in jupyterlab and Visual Studio Code, and using your operating system's file manager. But this is like driving a Ferrari in the slow lane.

Data Science is usually done on unix-like systems, and it is important to learn the skills that let your Ferrari purr. You want to be able to deal with multiple pieces of data fast, set up repeatable data science analysis pipelines, and put code into production.

## What you will learn

All of these require learning the Unix Command Line.

This workshop aims to do just that. It will teach you Unix Command Line basics. 

We will start with the very basic file and folder manipulations. From here you will learn the concepts of standard input and standard output, and how you can organize your work into pipelines. You will learn some useful unix commands and how these are organized into pipelines.

You will learn how to download data and process it end-to-end, including putting your usual notebook based python analysis code into the pipeline. And then you will learn how to run this pipeline on multiple data files, a usual situation in many data science projects.

At the end of this workshop, there is a homework. By completing this workshop and this homework, you will have increased the efficiency and productivity of your data science work. Stick with using the command line: over time you will learn new tricks and skills and become super fast at organizing and automating your analysis pipelines.

### Setup

To follow along (and you should follow along), you can stay on this notebook on Colab. But it may be even better for you to do the following.

- On Linux, open up a terminal. It will dump you in a "Unix Shell", most likely, the shell `bash`.
- On Mac search for the Terminal.app application (comes with MacOS) (or iterm2 application if you have installed it). It will dump you into the `zsh` shell.
- On Windows, download `git-bash` from [here](https://gitforwindows.org). This will give you a nice unix like `bash` shell for windows. Look for the `git-bash` terminal application and start it. It will dump you into a `bash` shell.

If you decide to stay here on Colab, run the next cell. It will set up a terminal with a `bash` shell on colab for you. Or you can get a terminal directly on Colab if you have paid for Colab Pro (check geography before you do this).

[![Open Workshop In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/univai-ghf/CommandLineWorkshop/blob/main/LearningTheCommandLine.ipynb)

*The Colab terminal software is still buggy. Exit out of each xterm session or you will have an infinite scroll of html code in those sessions*

On Colab:

```python
!pip install git+https://github.com/rahuldave/colab-xterm
%load_ext colabxterm
```