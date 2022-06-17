# Algorand-NFTs
<h2> Explore Algorand dev features and endpoints using terminal, python script/notebook and Dappflow </h2>

Usage
The file auction/operations.py provides a set of functions that can be used to create and interact with auctions. See that file for documentation.

Development Setup
This repo requires Python 3.6 or higher. We recommend you use a Python virtual environment to install the required dependencies.

Set up venv (one time):

python3 -m venv venv
Active venv:

. venv/bin/activate (if your shell is bash/zsh)
. venv/bin/activate.fish (if your shell is fish)
Install dependencies:

pip install -r requirements.txt
Run tests:

First, start an instance of sandbox (requires Docker): ./sandbox up nightly
pytest
When finished, the sandbox can be stopped with ./sandbox down
