# Using Python to Leverage Public Data for Social Impact

## DATA FOR IMPACT 2018

This is a repository for a workshop presented by the Madpy Python Meetup Group.  Our goal is to provide a friendly introduction to programming in Python and how it can be used on public data.

#### Knowledge/experience

Knowing Python is not a prerequisite. It helps if you are familiar with command line/terminal applications. All we ask is you that you bring your curiousity about data.

#### Installing Python

Installing Python can be overwhelming for a beginner, because there are many options and versions.

You should install Python version 3 (not 2).  Note that MacOS and most linux distributions usually come with Python 2 installed.

The two ways I'd recommend are:
- download it directly from [python.org](https://www.python.org/)
- obtain a distribution like [Anaconda](https://docs.anaconda.com/anaconda/install/) use a package manager like [miniconda](https://conda.io/docs/user-guide/install/index.html).

Anaconda is a popular option because the full version provides a GUI for managing your environments, and it has prepackaged Python environments that have all the most popular packages preinstalled.


#### The environment

Once you have your Python environment you can run `pip install <package name>` to install a package.  The only requirements for this tutorial are `jupyter` and `pandas`.

So:

```
pip install jupyter pandas
```

The Anaconda distribution would already have the appropriate packages installed.


### Getting the data

We will be exploring the Police Incident Reports dataset from the [City of Madison Open Data](http://data-cityofmadison.opendata.arcgis.com/) website.  You can download the .csv file [here](https://opendata.arcgis.com/datasets/61c36ee8e2d14cd094a265a288e27151_2.csv).

### Jupyter notebooks

The workshop consists of a Jupyter notebook.  Run `jupyter notebook` to start the jupyter application and navigate to the notebook.
