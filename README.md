# Module-18-Challenge
This is an intro to Block Chain module 


## Intro
----
In this module, we build a blockchain ledger in Streamlit. Streamlit allows us to build a quick web app to test out our code. 

The blockchain is initiated with a genesis block. The chain can take in a information such as receiver a sender, and the amount to send

![intro](/Images/Initial%20app.png)


## Adding a Single Block
---

The blockchain is initiated with a genesis block

![adding_a_block](/Images/Block%201.png)


## Adding More Blocks
---

When we add a block, the prior block is hashed. The difficulty slider determines the difficulty of finding the hash. Increasing difficulty requires the hash to have more leading zeros.

![adding_more_blocks](/Images/adding%20blocks.png)

## Looking Back and Validation 
---

When more blocks are added, we can then check on the prior block using the look-up tool.

![looking_back](/Images/looking%20back%20at%20block%201.png)


Lastly, we can validate the chain using the validate button. The Validate button checks the continuity of the hashes in the chain. 

![validation](/Images/validate%20chain.png)