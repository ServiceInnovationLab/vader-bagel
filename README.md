# Vader Bagel

## Boiler plate for sorting sentences by sentiment

Some tooling the team are sharing for seting up Vader for Project Bagel.

### VADER

VADER Sentiment Analysis. VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media, and works well on texts from other domains.

[Read more about VADER](https://github.com/cjhutto/vaderSentiment)

## Install Instructions for vader-bagel

This package requires [Python 3](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/installing/) .

## Setup Vader Bagel in pyenv

### Step 1: Install pyenv

```sh
curl https://pyenv.run | bash
```

At the end of the run, you should see something like this:

```sh
WARNING: seems you still have not added 'pyenv' to the load path.

# Load pyenv automatically by adding
# the following to ~/.bashrc:

export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

Add _pyenv_ to your path & once done, you'll need to reload your shell.

### Step 2: Clone the repo

```sh
git clone https://github.com/ServiceInnovationLab/vader-bagel.git
cd vader-bagel
```

### Step 3: Install python using pyenv

We want to use the exact version of python this project recommends

```sh
 pyenv install < .python-version
 python --version # This should match the version in .python-version file
```

### Step 4: Install Dev dependencies

```sh
pip install -r requirements.txt
```

### Step 5: Install requests package

If you have pip installed:

```sh
sudo pip install requests (OR pip3 install requests for python3)
```

OR using your systems package manager (for Ubuntu):

```sh
apt-get install python-requests
```

## Running

Scripts / commands are in the bin directory of this repo

Example:

```sh
python bin/process.py
```
