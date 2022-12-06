# Module_19_Challenge_FinTech_Finder

GWU FinTech Bootcamp Module 19 Challenge - fintech_finder.py

**An application used to find, hire and pay a FinTech professional with Ethereum using Streamlit as user interface .**

Here is a screenshot of the Streamlit app & Ganache instance showing who we're hiring, how many hours, total pay in ETH BEFORE sending transaction.

![Screenshot](https://github.com/jimhitchcock/Module_19_Challenge_FinTech_Finder/blob/main/Images/app_and_wallet_before_tx.png)

Here is a screenshot of the Streamlit app & Ganache wallet instance AFTER sending transaction.

![Screenshot](https://github.com/jimhitchcock/Module_19_Challenge_FinTech_Finder/blob/main/Images/app_and_wallet_after_tx.png)

Here is a screenshot of the Ganache wallet instance showing the transactions made.

![Screenshot](https://github.com/jimhitchcock/Module_19_Challenge_FinTech_Finder/blob/main/Images/transaction_history.png)

Here is a screenshot of the Ganache wallet instance showing the details of the transaction as well as the recipient's address.

![Screenshot](https://github.com/jimhitchcock/Module_19_Challenge_FinTech_Finder/blob/main/Images/receipient_address_ss.png)

---

## Technologies

[Web3](https://web3py.readthedocs.io/en/v5/)

[DataClass](https://docs.python.org/3/library/dataclasses.html)

[Streamlit](https://streamlit.io/)

[Ganache](https://docs.streamlit.io/)

---

## Installation Guide

```python
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import os
import requests
from dotenv import load_dotenv
load_dotenv()
from bip44 import Wallet
from web3 import Account
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy
```
---

## Conclusions

**Based on the test data, the application does what we expected it to do based on the code written.

---

## Contributors

Parts of this application were written by Jim Hitchcock, starter code provided by GWU FinTech Bootcamp.

---

## License

MIT License.