# Vader Bagel


## Boiler plate for sorting sentences by sentiment

Some tooling the team are sharing for seting up Vader for Project Bagel.


### VADER

VADER Sentiment Analysis. VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media, and works well on texts from other domains.

[Read more about VADER](https://github.com/cjhutto/vaderSentiment)

## Install Instructions for vader-bagel

This package requires [Python 3](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/installing/) .


## Setup Aotearoa Open Fisca in pyenv

### Step 1: Install pyenv

```sh
curl https://pyenv.run | bash
```

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

#### Step 4: Install Dev dependencies

```sh
pip install -r requirements.txt
```


## Running

Scripts / commands are in the bin directory of this repo
