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

- Run `puppeth`, name your network, and select the option to `configure a new genesis block`. I named my PoA network `dlchain`.

- Choose the `Clique` (Proof of Authority) consensus algorithm.

- Paste both account addresses from the first step one at a time into the list of accounts to seal.

- Paste both accounts again in the list of accounts to pre-fund. This is required since there are no block rewards in PoA.

- Choose no for pre-funding the pre-compiled accounts (0x1 .. 0xff) with wei.

- Complete the rest of the prompts, and when you are back at the main menu, choose the "Manage existing genesis" option.

- Export genesis configurations. This will fail to create two of the files, but we only need `dlchain.json`.

## Initialize the Nodes with the Genesis' Json File

Using geth, we initialize each node with the new `dlchain.json`.

Open side by side two Git Bash windows, one for Node 11 and the other for Node 22, and run the following commands:

`./geth --datadir node11 init dlchain.json`

`./geth --datadir node22 init dlchain.json`
