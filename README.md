# BlockChain-with-Python

Building a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions and to verify the integrity of the data in the ledger.

---

## Technologies

This project leverages python 3.9 with the following package:

* [VSCode](https://code.visualstudio.com/) - Code editor redefined and optimized for building and debugging modern web and cloud applications.

* [Pandas](https://pandas.pydata.org/) - Entry point, open source data analysis and manipulation tool.

* [Streamlit](https://streamlit.io/) - Open-source app framework for Machine Learning and Data Science teams.

* [haslib](https://docs.python.org/3/library/hashlib.html) - Secure hash and message digest algorithm library.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
!pip install streamlit
```

Next, import required libraries and dependencies.

```python
from asyncio import SendfileNotAvailableError
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib
```

---

## Usage

To use this application simply clone the repository and run the **pychain.py** with:

```python
  pychain.py
```
### How to run it locally using following commands
```
pip install streamlit
```
from your local terminal clone the repo then type
```
streamlit run pychain.py
```

<img width="1438" alt="stapp" src="https://user-images.githubusercontent.com/105394703/195165952-da0378a7-fd42-4c2e-b978-719cb54479d4.png">


<img width="1440" alt="stapp2" src="https://user-images.githubusercontent.com/105394703/195168728-18bea325-df8f-404c-9305-c0e0873792a3.png">


---

## Contributors

This project brought to you by Agnes.

---

## License
[MIT](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)
