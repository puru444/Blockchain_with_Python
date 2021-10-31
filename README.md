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
- Sender: 'Psharma'
- Receiver: 'Dsmith'
- Amount: '$500'

![TRX_1](https://user-images.githubusercontent.com/86034323/139603967-b8e48013-76ea-4523-aefe-d134b6df8408.png)

- Block_Difficulty_Level: '2'
- Nonce_Count: '356'
- Block_Details: Block(record=Record(sender='Psharma', receiver='Dsmith', amount='$500'), creator_id=42, prev_hash='c91caad3d3438d5b2646eb389c1cd51f0ca6ebaa7b38570ff097c1b7ac4eca70', timestamp='22:11:43', nonce=356)

![Block 1](https://user-images.githubusercontent.com/86034323/139603978-0959fd44-bca2-4f4b-b6ee-f98e81ea260b.png)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**2. TRX_2:** 
- Sender: 'Psharma'
- Receiver: 'Skumar'
- Amount: '$1000'

![TRX_2](https://user-images.githubusercontent.com/86034323/139604185-0ee439a1-57d2-4ec0-8d3f-70f4d35bf8f3.png)


- Block_Difficulty_Level: '2'
- Nonce_Count: '93'
- Block_Details: Block(record=Record(sender='Psharma', receiver='Skumar', amount='$1000'), creator_id=42, prev_hash='009c615c5dba7cbee9ebdec32d5742b1d7a7f9b94602060cb7e2a7ad64c3e14a', timestamp='22:12:35', nonce=93)

![Block 2](https://user-images.githubusercontent.com/86034323/139604191-9cad1c0d-605f-444c-8576-d029cb38a71a.png)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**3. TRX_3:** 
- Sender: 'Psharma'
- Receiver: 'Skumar'
- Amount: '$250'

![TRX_3](https://user-images.githubusercontent.com/86034323/139604261-47846031-9333-4a73-8c5a-131d1cd37b3a.png)


- Block_Difficulty_Level: '2'
- Nonce_Count: '249'
- Block_Details: Block(record=Record(sender='Psharma', receiver='Skumar', amount='$250'), creator_id=42, prev_hash='00407b66d184a3a69a3224afac120225d4570a9a8aa7c7d2f85f47fce7970936', timestamp='22:13:04', nonce=249)

![Block 3](https://user-images.githubusercontent.com/86034323/139604270-caf8501d-30c4-465e-abaf-941da3be5cb3.png)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
