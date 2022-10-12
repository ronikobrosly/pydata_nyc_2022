# intro-to-causal-inference

A introduction to causal inference using common tools from the python data stack


# Table of Contents

- [Getting Started](#getting-started)
  - [Clone the repository](#clone-the-repository)
  - [Preparing python](#preparing-python)
  - [Install a new IPython kernelspec](#install-a-new-ipython-kernelspec)
  - [Start up jupyter lab and open a notebook](#start-up-jupyter-lab-and-open-a-notebook)
- [Slides](#slides)
- [Feedback](#feedback)


## Getting Started


### Clone the repository

In your terminal, use `git` to clone the repo to your machine.

```bash
git clone git@github.com:ronikobrosly/pydata_nyc_2022.git
```

If you are less comfortable with `git`, there is an easy alternative: [You can simply download a zip file of it here :)](https://github.com/ronikobrosly/pydata_nyc_2022/archive/refs/heads/main.zip)


### Preparing python

Now you'll need to ensure you have a working python environment set up.

**This tutorial requires python version `3.9` for the notebook exercises to properly work.**

Create a new virtual environment for this tutorial. You can do this a number of ways. If you are running Anaconda python, [you can do this through the conda command](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf). Another method is to use the `virtualenv` python package. If you are a Windows or Linux user, please [use this guide](https://www.geeksforgeeks.org/creating-python-virtual-environment-windows-linux/). If you are a MacOS user [you can follow this guide](https://sourabhbajaj.com/mac-setup/Python/virtualenv.html).

Name your environment `causal_modeling`

"Activate" this environment (see the above guide) and then run the following command in the root folder of this repo:
`pip install -r requirement.txt`

This will install all the necessary packages for the tutorial.

As an optional step, you can try to run the `check_environment.py` file (in the root folder of the repo)
while within your virtual environment. You can do so by running `python check_environment.py` in your terminal. It will alert you if you're missing any required python packages.


### Install a new IPython kernelspec

Once the above is complete, you'll need to run the following commands:

`python -m ipykernel install --user --name causal_modeling --display-name "Python (causal_modeling)"`


### Start up jupyter lab and open a notebook

In the terminal, execute `jupyter lab`.

Navigate to the `notebooks` directory and open your notebook of choice. You will probably be asked which environment you would like to use with the notebook. Select the `Python (causal_modeling)` environment you created in the step above.


## Slides

Slides to go along with the tutorial are available as a [Google Doc Presentation](https://docs.google.com/presentation/d/1Gijn05cPROfifXk2LLsjOYZEg5OIXg98nttRMjh-Vb8/edit?usp=sharing).


## Feedback

I love would to hear your feedback on these tutorial materials!
Please send your comments to <roni.kobrosly@gmail.com>.
