# BLOCKCHAIN WITH PYTHON

**CASE STUDY:** As a FinTech Engineer for renowned Financial Institution, I need to build a Blockchain-based Ledger System with a user-friendly Web Interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**CONTENT**
- Project Description
- Technologies
- Blockchain Web-Application
- Contributor
- License
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**PROJECT DESCRIPTION**
Decentralized Blockchain Ledger for tracking Sending & Receiving Transactions:

**A. DATA CLASSES:** There are 3 data classes are defined:

**- Record:** This data class contains: Sender, Receiver & Amount for each transaction.

**- Block:** This data class contains: Record (Defined first data class in previous step), Creator ID, Previous Hash (Previous Block's Hash), Timestamp, Nonce (No. of attempts to satisfy the difficulty of Mined Hash).

**- PyChain:** This data class contains: List of Blocks & the difficulty level by defining prefixes like: "0000" before hash for the miners to Guess & Add Block in Chain, eventually. 



                             
**B. FUNCTIONS:** There are various functions are defined for following purposes:

**- hash_block:** This function's purpose: to hash the data attributes inside the Block Data-class.

**- proof_of_work:** This function's purpose: to set the difficulty level for guessing the prev_hash of block.

**- add_block:** This function's purpose: to add the block in chain after succesfully performed the Proof of Work.

**- is_valid:** This function's purpose: to validate the block in chain.

**- setup():** This function's purpose: to increase the size of chain on addition of each block successfully. 

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**TECHNOLOGIES**
- Python
- Pandas
- Streamlit
- Jupyter Notebook

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**BLOCKCHAIN WEB APPLICATION**
------------------------------

**TRANSACTIONS**
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

**4. TRX_4:** 
- Sender: 'Psharma'
- Receiver: 'Tmiller'
- Amount: '$700'

![TRX_4](https://user-images.githubusercontent.com/86034323/139604402-0cbde8ff-682d-488c-875e-93d261428a5e.png)


- Block_Difficulty_Level: '2'
- Nonce_Count: '59'
- Block_Details: Block(record=Record(sender='Psharma', receiver='Tmiller', amount='$700'), creator_id=42, prev_hash='00b29fecd0c868f72b3605791eb38fd086b2a57a61c1e9e99480fb02fcb5a25a', timestamp='22:14:29', nonce=59)


![Block 4](https://user-images.githubusercontent.com/86034323/139604412-b5d07a56-dbe9-41da-8fe9-4412cc8b9591.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**5. TRX_5:** 
- Sender: 'Psharma'
- Receiver: 'Tmiller'
- Amount: '$300'

![TRX_5](https://user-images.githubusercontent.com/86034323/139604903-8ccd214b-39f0-4196-8bb9-f3f18013a933.png)


- Block_Difficulty_Level: '2'
- Nonce_Count: '16'
- Block_Details: Block(record=Record(sender='Psharma', receiver='Tmiller', amount='$300'), creator_id=42, prev_hash='00706f49736a2ac6cd356a452e06e5a6e407671aba82150ca497592584e36760', timestamp='22:15:16', nonce=16)


![Block 5](https://user-images.githubusercontent.com/86034323/139604919-5a8349d4-36ce-412d-9554-914ef7c07fc8.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**6. TRX_6:** 
- Sender: 'Psharma'
- Receiver: 'PWilliam'
- Amount: '$600'

![TRX_6](https://user-images.githubusercontent.com/86034323/139605063-8b581f98-dd80-406f-afdc-997f466d25bf.png)


- Block_Difficulty_Level: '5'
- Nonce_Count: '992235'
- Block_Details: Block(record=Record(sender='Psharma', receiver='PWilliam', amount='$600'), creator_id=42, prev_hash='00641e67dd01722db6a941705c9f9fca9501131bc81cdf6383a293ce8398e811', timestamp='22:15:43', nonce=992235)


![Block 6](https://user-images.githubusercontent.com/86034323/139605066-ec6a7fca-ad4e-40ba-b04a-ce74f227fa89.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**7. TRX_7:** 
- Sender: 'Psharma'
- Receiver: 'Dsmith'
- Amount: '$800'

![TRX_7](https://user-images.githubusercontent.com/86034323/139605111-ae267cb8-e7eb-416f-8087-e28bd6b4b53a.png)


- Block_Difficulty_Level: '5'
- Nonce_Count: '1011496'
- Block_Details: Block(record=Record(sender='Psharma', receiver='Dsmith', amount='$800'), creator_id=42, prev_hash='0000099cb96435759f0f300db7df107091b252f61c364601e783fb64c31bb742', timestamp='22:16:22', nonce=1011496)


![Block 7](https://user-images.githubusercontent.com/86034323/139605118-43dd413f-7b56-45ec-b166-4db4333ada37.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**8. TRX_8:** 
- Sender: 'Psharma'
- Receiver: 'Pwarren'
- Amount: '$200'

![TRX_8](https://user-images.githubusercontent.com/86034323/139605155-48e36aac-23ac-405f-806c-e0dc0dcbe35e.png)


- Block_Difficulty_Level: '5'
- Nonce_Count: '1903338'
- Block_Details: Block(record=Record(sender='Psharma', receiver='Pwarren', amount='$200'), creator_id=42, prev_hash='00000e0112f7a0c6f4dd0e4da002d9de91678b5ba4f850181f7dd231e7d322a6', timestamp='22:17:29', nonce=1903338)


![Block 8](https://user-images.githubusercontent.com/86034323/139605162-defdf00e-9b48-438d-b410-26391ca6663c.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**9. TRX_9:** 
- Sender: 'Psharma'
- Receiver: 'Susan'
- Amount: '$700'

![TRX_9](https://user-images.githubusercontent.com/86034323/139605247-179bb5db-5313-46b6-b7a8-d2684adc473d.png)


- Block_Difficulty_Level: '3'
- Nonce_Count: '3870'
- Block_Details: Block(record=Record(sender='Psharma', receiver='Susan', amount='$700'), creator_id=42, prev_hash='000000737a70a3e396b3f30a245f1ad848d60b16ca6ac95cae62fb0ac24685ee', timestamp='22:18:15', nonce=3870)


![Block 9](https://user-images.githubusercontent.com/86034323/139605250-e8ff8061-df5c-4bb7-b4c6-f63a4103684e.png)


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**10. TRX_10:** 
- Sender: 'Psharma'
- Receiver: 'Skumar'
- Amount: '$900'


![TRX_10](https://user-images.githubusercontent.com/86034323/139605309-094f4315-68dc-4996-ab1d-4863351ded4c.png)


- Block_Difficulty_Level: '3'
- Nonce_Count: '9248'
- Block_Details: Block(record=Record(sender='Psharma', receiver='Skumar', amount='$900'), creator_id=42, prev_hash='00010afd5d4d36a0a8e0a2fad6372ce6d6b3bd6c2503cffdd116ad3749165355', timestamp='22:18:44', nonce=9248)


![Block 10](https://user-images.githubusercontent.com/86034323/139605321-79f5115f-f4ea-4921-ba61-45a64085b0c4.png)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**CHAIN VALIDATION**

Chain of 10 blocks are validated with Result: True:

![Chain Validation](https://user-images.githubusercontent.com/86034323/139605451-1ba60209-83bf-40ae-8c49-014b9dc0f8c4.png)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**LEDGER WITH 10 TRANSACTIONS**

Blockchain Ledger with 10 Transactions:

![Ledger](https://user-images.githubusercontent.com/86034323/139605502-cfb50b03-475c-4331-9568-6f43829fb4b3.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**CONTRIBUTOR**
- PRATEEK SHARMA

www.linkedin.com/in/prateek-sharma-21a081180

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**LICENSE**

GNU General Public License v3.0
