### Blockchain_Ledger
blockchain ledger with user friendly web interface
### libraries used
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib
## Step 1 Create a Record Data
In this step I defined a data class called Record, followed by adding three attributes, sender, reciever,
and amount
## Step 2 Modify the existing block data class to store the recorded data
In this step I renamed the data variable to record in order to keep a record of the data we created in the
previous section.
## Step 3 add revelant user inputs to stream lit
In this section we coded additional inputs in our stream lit web application which included,
sender data, reciever data, and amount data.
## Step 4 Test the application
In this section I tested the application and took screenshots of the results which can be seen below.

![image](/Users/jacobburnett/Documents/GitHub/Blockchain_Ledger/streamlit_validation.png)

![image](/Users/jacobburnett/Documents/GitHub/Blockchain_Ledger/streamlit_validation_2.png)
