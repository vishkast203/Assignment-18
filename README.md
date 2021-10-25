# Assignment-18
Building Blockchains
Executive Summary:  The asssigned project required that as a lead developer, I build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger. The BLockCHain ledeger system was built as per user instructions, but failed to generate the necessary user  inpus  namely sender value, receiver value & amount. However the code successfully executed using the Streamlit application. The testing of the completed `PyChain` ledger and user interface by running the Streamlit application and storing some mined blocks in the `PyChain` ledger failed.

Imports & Libraries: The following libraries & dependencies were utilized:
    import streamlit as st
    from dataclasses import dataclass
    from typing import Any, List
    import datetime as datetime
    import pandas as pd
    import hashlib
Steps followed:  The instructions providede by the Users were strictly followed. The first step was to Create a Record Data Class that consists of the `sender`, `receiver`, and  `amount` attributes. Next we had to Rename the `data` attribute to `record`, and set the data type to `Record` which was completed. 
Finally in Step#3, we successfully followed instructions to:
    1.Delete the `input_data` variable from the Streamlit interface
    2.Add an input area where you can get a value for `sender` from the user.
    3.Update `new_block` so that `Block` consists of an attribute named `record`, which is set equal to a `Record` that contains the `sender`, `receiver`, and `amount` values

    Now the file was ready to be executed. The following output was seen:
    ![image](https://user-images.githubusercontent.com/85462153/138625519-29486aba-61c8-4f02-b56b-9e7cf1c4212d.png)


    Conclusions:  The code to execute the Streamlit application executed without a flaw. However the prompts for entries to Sdnder,  Receiver & Amount Values were not generated by Streamlit. Investigatios into the code provided did not generate any additional insights. It is recommended that the User team meet with the lead developer to validate the intial code structure provided
