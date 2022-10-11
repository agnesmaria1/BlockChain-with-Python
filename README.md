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

To use this application simply clone the repository and run the **app.py** with:

```python
  app.py
```

---

## Contributors

This project brought to you by Agnes.

---

## License
[MIT](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)