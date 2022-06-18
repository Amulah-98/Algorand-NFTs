# Algorand-NFTs
<h2> Explore Algorand dev features and endpoints using terminal, python script/notebook and Dappflow </h2>

<h3> Business Need </h3>

 10 Academy has partnered with Algorand to use the Algorand Blockchain as the foundational element of the NFT, and this must now be implemented.  In this project you will build end-to-end Web3 dapps on the Algorand Blockchain that will help 10 Academy generate and distribute Non-Fungible Tokens (NFTs) as certificates that will represent the successful completion of a weekly challenge to trainees, and allow trainees with NFTs to interact with a smart contract to perform pre-defined actions

# Algorand Auction Demo

This demo is an on-chain NFT auction using smart contracts on the Algorand blockchain.

## Usage

The file `auction/operations.py` provides a set of functions that can be used to create and interact
with auctions. See that file for documentation.

## Development Setup

This repo requires Python 3.6 or higher. We recommend you use a Python virtual environment to install
the required dependencies.

Set up venv (one time):
 * `python3 -m venv venv`

Active venv:
 * `. venv/bin/activate` (if your shell is bash/zsh)
 * `. venv/bin/activate.fish` (if your shell is fish)

Install dependencies:
* `pip install -r requirements.txt`

Run tests:
* First, start an instance of [sandbox](https://github.com/algorand/sandbox) (requires Docker): `./sandbox up nightly`
* `pytest`
* When finished, the sandbox can be stopped with `./sandbox down`
