# 🐼 Data analysis with Python 🐼

Notebooks and documentation for a 3.5-hour session at IRE 2019 on using the `pandas` Python library to analyze data.

## Link to this repo: [bit.ly/ire19-pandas](http://bit.ly/ire19-pandas)

- [Session details](#session-details)
- [Running these notebooks at home](#running-these-notebooks-at-home)
- [Starting a new data analysis project using this setup](#starting-a-new-data-analysis-project-using-this-setup)

## Session details

**When and where:** [Saturday, June 15, from 9 a.m. - 12:30 p.m. in River Oaks A](https://www.ire.org/events-and-training/event/3434/4434/)

**Description:** Learn how to use Jupyter notebooks with the popular Python library `pandas` to kickstart your data analysis workflow. In this session, you'll write code to quickly sort, filter, group, clean and join large data sets -- all within a browser-based notebook that doubles as your data diary.

Some familiarity with basic Python syntax is helpful -- you might first check out [the Python 101 session offered separately](https://www.ire.org/events-and-training/event/3434/4581/) -- but not required.

**Class objectives:** Practice using the `pandas` Python library to perform common data analysis tasks in a browser-based notebook environment.

**What we'll (try to) cover:** Importing pandas, loading a data file into a data frame, sorting, filtering, grouping and aggregating data.

## Running these notebooks at home

### Step 1: Install Python and some other tools

There are many ways to install Python and the tools you need to get up and running. [Here's how we suggest doing it](https://docs.google.com/document/d/1cYmpfZEZ8r-09Q6Go917cKVcQk_d0P61gm0q8DAdIdg/edit?usp=sharing). Please feel free to email me if you run into any problems: [cody@ire.org](mailto:cody@ire.org).

### Step 2: Download or clone this repo

If you have git set up already, navigate to your terminal or command prompt and run this command: `git clone https://github.com/cjwinchester/ire-2019-pandas-intro`

If you don't have git set up, you can download the repo as a zipfile [here](https://github.com/cjwinchester/ire-2019-pandas-intro/archive/master.zip) and unzip it. Make note of where the folder lives on your computer.

### Step 3: Install the tools you need

This step assumes that you have already installed the latest version of Python 3 and pipenv.

Open a terminal or command prompt and move into the folder you cloned or downloaded using the `cd` command.

(Not sure what a terminal or command prompt is? If you're on OSX, it'll be a program called Terminal, typically in Applications → Utilities → Terminal, or you can just Spotlight search for it. If you're running windows, the program is called `cmd` -- just click the Windows button and search for `cmd`.)

If your folder lives at `Desktop/ire-2019-pandas-intro`, you would run the command `cd Desktop/ire-2019-pandas-intro`. Replace everything after `cd ` with the actual path to the folder you cloned or downloaded.

Next, make sure you're in the correct directory. If you're on a Mac, run this command: `ls`. If you're on a PC, run this command: `dir`. This will list the contents of the directory you're in -- you should see a `Pipfile` and the other files you see [here](https://github.com/cjwinchester/ire-2019-pandas-intro).

Finally, install the libraries you'll need: `pipenv install`.

### Step 4: Run the notebooks

Once everything has installed, run this command: `pipenv run jupyter notebook`.

This should launch the notebook server in your browser, and your terminal should start spitting out a bunch of information about the server it's running.

Work in your notebooks. When you're done, you can close out of the browser tab. To quit the server in your terminal, hit `Ctrl+C`. That's it!

## Starting a new data analysis project using this setup

This example assumes that you already have Python and pipenv installed and you want to use `jupyter` and `pandas`.

Open your command-line interface and create a directory for your project files: `mkdir your-cool-project`

Now move into that directory: `cd your-cool-project`

Next, install your dependencies: `pipenv install jupyter pandas numpy`

Once your dependencies are done installing, run your notebook server: `pipenv run jupyter notebook`.

Create a new Python notebook and you're off to the races.