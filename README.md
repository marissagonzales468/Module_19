# Module_19
## Fintech Finder Application 
Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.
## Technologies
This project leverages python 3.7 with the following packages:
 * [Web3.py](https://web3py.readthedocs.io/en/stable/overview.html) - For connecting to and performing operations on Ethereum-based blockchains.
* [ethereum-tester](https://pypi.org/project/ethereum-tester/0.1.0a4/) - For providing access to the tools we’ll use to test Ethereum-based applications.
* [mnemonic]https://pypi.org/project/mnemonic/) - For generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard.
* [bip44]https://pypi.org/project/bip44/)- For deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard.
* [Ganache](https://trufflesuite.com/ganache/)- For allowing you to quickly set up a local blockchain, which you can use to test and develop smart contracts.
* [Streamlit](https://streamlit.io/) - For an open source app framework in Python language.
## Installation Guide
Before running the application first install the following dependencies.

```python
  pip install web3==5.17
  pip install eth-tester==0.5.0b3
  pip install mnemonic
  pip install bip44
```
Download Ganache and follow the instructions that are given from Ganache. 
Create a Workspace.
When you open Ganache, you are presented with two options for creating a workspace: Quickstart Ethereum and New Workspace Ethereum. Click Quickstart Ethereum.
---
## Usage
To use the Fintech Finder Application simply clone the repository and run streamlit in the terminal with:

```python
streamlit run fintech_finder.py
```

Upon launching the Fintech Finder Application  you will be greeted with the following prompts.

![Fintech Finder Application Prompts](Images/( Fintech_Finder.png))


---
## Contributors
Brought to you by Marissa Gonzales.
## License
MIT
