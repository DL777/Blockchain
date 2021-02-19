# Building the Proof of Authority Blockchain
 
 ## 
 In this project, I built my custom PoA blockchain using the following tools:

•  Puppeth - to generate the genesis block

•  Geth, a command-line tool, to create keys, initialize nodes, and connect the nodes together

•  The Clique Proof of Authority algorithm.

The Proof of Authority (PoA) algorithm is typically used for private blockchain networks as it requires pre-approval of, or voting in of, the account addresses that can approve transactions (seal blocks).

In what follows, I present the instructions for setting up the PoA blockchain.

# Instructions

## Generate Blockchain Nodes
Because the accounts must be approved, you need to generate two new nodes with new account addresses that will serve as the pre-approved sealer addresses.

For this purpose we will use **Geth** and create two nodes, **Node 11** and **Node 22** by running the following commands in Git Bash:

**Create Node 11:**

`./geth --datadir node11 account new`

**Create Node 22:**

`./geth --datadir node2 account new`

You need to run these commands from the folder in which you have your Geth installed. Once the two nodes have been generated, there will be two folders created – node11 and node22 – each containing a folder with a keystore for that node.

## Generate your Genesis Block
Next we will use **puppeth** to generate your genesis block:

Run `puppeth`, name your network, and select the option to `configure a new genesis block`. I named my PoA network `dlchain`.

Choose the `Clique` (Proof of Authority) consensus algorithm.

