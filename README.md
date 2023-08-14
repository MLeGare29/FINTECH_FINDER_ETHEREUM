# FINTECH FINDER

## OVERVIEW
In this project, the power of the Ethereum blockchain technology will be used to create a platform will allow users to select Fintech professionals from a list, hire them, and pay them with cryptocurrency. The following objectives will be completed:

1. Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

2. Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

3. Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work

4. Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

5. Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.


## TECHNOLOGIES

The installation requirements for this code are as follows:

[Python](https://www.python.org/downloads/) - Enables the user to use the powerful Python programming language.

[VSCode](https://code.visualstudio.com/download) OR [JupyterLab](https://jupyter.org/) - Access to the VSCode IDE or the web-based IDE, JupyterLab, to run create and run this Python-based code and document. 

[Streamlit](https://docs.streamlit.io/library/get-started) - An open-source app framework for machine learning and data science that enables users to create web apps using the Python programming language.

[Pandas](https://pandas.pydata.org/) - Grants access to the open-source Pandas data analysis tool, which is powered by Python.


## USAGE

For the functionality of crypto_wallet.py code, you must call the following imports from the Pandas Library:

```python
import os
import requests
from dotenv import load_dotenv
load_dotenv()
from bip44 import Wallet
from web3 import Account
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy
```

For the functionality of fintech_finder.py code, you must call the following imports from the Pandas Library:


```python
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))
from crypto_wallet import generate_account, get_balance, send_transaction
```

Accessing JupyterLab in Bash: `Jupyter Lab`

Running the fintech_finder.py code on the Streamlit web app in the IDE Command Line: `streamlit run fintech_finder.py`




## CONTRIBUTORS

*Marcus LeGare (Author, Developer)*

### LICENSE

**COLUMBIA UNIVERISTY FINTECH BOOTCAMP**