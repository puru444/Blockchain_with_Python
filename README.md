# BLOCKCHAIN WITH PYTHON

CASE STUDY: As a FinTech Engineer for renowned Financial Institution, I need to build a Blockchain-based Ledger System with a user-friendly Web Interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

# CONTENT
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
There are 10 different transactions occured in test instance (streamlit) with following details:

**1. TRX_1:** 
Sender: 'Psharma'
Receiver: 'Dsmith'
Amount: '$500'

![TRX_1](https://user-images.githubusercontent.com/86034323/139603967-b8e48013-76ea-4523-aefe-d134b6df8408.png)

Block_Difficulty_Level: '2'
Nonce_Count: '356'
Block_Details: Block(record=Record(sender='Psharma', receiver='Dsmith', amount='$500'), creator_id=42, prev_hash='c91caad3d3438d5b2646eb389c1cd51f0ca6ebaa7b38570ff097c1b7ac4eca70', timestamp='22:11:43', nonce=356)

![Block 1](https://user-images.githubusercontent.com/86034323/139603978-0959fd44-bca2-4f4b-b6ee-f98e81ea260b.png)



