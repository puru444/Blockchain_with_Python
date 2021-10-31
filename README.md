# BLOCKCHAIN WITH PYTHON

CASE STUDY: As a FinTech Engineer for renowned Financial Institution, I need to build a Blockchain-based Ledger System with a user-friendly Web Interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

# CONTENT:
- Project Description
- Technologies
- Blockchain Web-Application
- Contributor
- License

# PROJECT DESCRIPTION
Decentralized Blockchain Ledger for tracking Sending & Receiving Transactions:

There are 3 data classes are defined:
1. Record
2. Block
3. PyChain

Record: This data class contains: Sender, Receiver & Amount for each transaction.
Block: This data class contains: Record (Defined first data class in previous step), Creator ID, Previous Hash (Previous Block's Hash), Timestamp, Nonce (No. of attempts to satisfy the difficulty of Mined Hash).
PyChain: This data class contains: List of Blocks & the difficulty level by defining prefixes like: "0000" before hash for the miners to Guess & Add Block in Chain, eventually. 

# TECHNOLOGIES
- Python
- Pandas
- Streamlit
- Jupyter Notebook

# BLOCKCHAIN WEB APPLICATION
