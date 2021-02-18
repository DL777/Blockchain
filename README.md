# Building the Proof of Authority Blockchain
 
 ## 
 In this project, I built my custom PoA blockchain using the following tools:

•  Puppeth - to generate the genesis block

•  Geth, a command-line tool, to create keys, initialize nodes, and connect the nodes together

•  The Clique Proof of Authority algorithm.

The Proof of Authority (PoA) algorithm is typically used for private blockchain networks as it requires pre-approval of, or voting in of, the account addresses that can approve transactions (seal blocks).

In what follows, I present the instructions for setting up the PoA blockchain.

# Instructions

## Create Blockchain Nodes
Because the accounts must be approved, you need to generate two new nodes with new account addresses that will serve as the pre-approved sealer addresses.

For this purpose we will use **Geth** and create two nodes, **Node 11** and **Node 22** Using the following commands:

**Create Node 11:**

`./geth --datadir node11 account new`

**Create Node 22:**

`./geth --datadir node2 account new`





