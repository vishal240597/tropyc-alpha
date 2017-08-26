+++
title = "Under The Hood"
date = 2017-08-02T17:14:00+02:00
description = ""
type = "doc"
weight = 20
draft = false
bref = ""
toc = true
+++


# Bitcoin : under the hood


<div class="container">
  <div class="row">
    <div class="col">
     put a pic here
    </div>
    <div class="col">
      put a pic here
    </div>
    <div class="col">
      put a pic here
    </div>
  </div>
   <div class="row">
    <div class="col">
      Mining
    </div>
    <div class="col">
      Blockchain
    </div>
    <div class="col">
      Consensus
    </div>
  </div>
</div>


## Mining

The main difference between fiat and bitcoin, is that the former can be printed without a limit while the latter is capped at 21 million.


### Printing fiat

<div class="container">
  <div class="row">
    <div class="col">
     put a pic here
    </div>
    <div class="col">
      In the current financial system, the amount of floating currencies is regulated by central banks – they can inject or remove money via a centralised system.
      The amount of fiat money is uncapped as Central Banks have the power to print an unlimited supply.e
    </div>
  </div>
 </div>
 
 
### Mining Bitcoin

<div class="container">
  <div class="row">
    <div class="col">
     The creation of Bitcoin is decentralised, transparent and follows an immutable mathematical formula
      Bitcoin are not printed but "mined" by computers plugged on the network.
      There will only be 21 million bitcoins ever mined.
    </div>
    <div class="col">
      put a pic here
    </div>
  </div>
 </div>
 
 
Cryptocurrencies were once priced based on the prequeresites costs to run the network or mining costs.

Mining bitcoin and cryptocurrencies is a resource-draining activity that requires investment



<div class="container">
  <div class="row">
    <div class="col">
     put a pic here
    </div>
    <div class="col">
      put a pic here
    </div>
    <div class="col">
      put a pic here
    </div>
  </div>
   <div class="row">
    <div class="col">
      Hardware
    </div>
    <div class="col">
      Energy
    </div>
    <div class="col">
      Time
    </div>
  </div>
  <div class="row">
    <div class="col">
      Miners allocate their computer horse power to the network : the more powerful the installation, the better the performance
    </div>
    <div class="col">
      Computer equipment consumes power to function continuously. Energy is the main operational expense miners face
    </div>
    <div class="col">
      Resources could be allocated to another network. Miners invest not only their equipment but their time to the task
    </div>
  </div>
</div>


The network rewards miners in such a way, that they are incentivised to keep it secure


<div class="container">
  <div class="row">
    <div class="col">
     put a pic here
    </div>
    <div class="col">
      put a pic here
    </div>
  </div>
   <div class="row">
    <div class="col">
      Transaction fees
    </div>
    <div class="col">
      Mining rewards
    </div>
  <div class="row">
    <div class="col">
      Issuing a transaction incurs a small fee, given to miners.
    </div>
    <div class="col">
      When a new block is generated, new bitcoins are mined and rewarded to the best miners
    </div>
  </div>
</div>


## Blockchain

A publicly available digital ledger that stores bitcoin, cryptocurrency and token information. 

The bitcoin blockchain is a series of blocks that holds transaction data of approximately 10 minutes of network activity.
Miners are the ones creating new blocks by solving a mathematical formula. 
By doing so, the network rewards them with freshly mined bitcoin 

  add a pic  

Each blocks records the information of multiple transaction including
* the time,
* all transactions,
* the sender's public address,
* the recipient's public address,
* the amount
* the mining reward
* an unique idcode called hash.

  add a pic
  
This offers two benefits to blockchain technology
 
 
<div class="container">
  <div class="row">
    <div class="col">
     put a pic here
    </div>
    <div class="col">
      put a pic here
    </div>
  </div>
   <div class="row">
    <div class="col">
      Transparency
    </div>
    <div class="col">
      Immutable
    </div>
  <div class="row">
    <div class="col">
      Issuing a transaction incurs a small fee, given to miners.
    </div>
    <div class="col">
      When a new block is generated, new bitcoins are mined and rewarded to the best miners
    </div>
  </div>
</div>
  

Every bitcoin transactions ever created and confirmed by the network are stored in a single block - depending on the transaction time. 
Every blocks are added on an immutable public distributed ledger, this is the blockchain : a chronological combination of data blocks.



## Consensus

A transaction does not exist until it is generated in a new block. In order to keep the network safe and secure, miners reaches a consensus.


<div class="container">
  <div class="row">
    <div class="col">
     put a pic here
    </div>
    <div class="col">
      put a pic here
    </div>
    <div class="col">
      put a pic here
    </div>
  </div>
   <div class="row">
    <div class="col">
      Sign
    </div>
    <div class="col">
      Generate
    </div>
    <div class="col">
      Verify
    </div>
  </div>
  <div class="row">
    <div class="col">
      Alice wants to send money to Bob.
    </div>
    <div class="col">
      Miners gather data and create their own block.
    </div>
    <div class="col">
      All miners compete to get their block issued on the blockchain.
    </div>
  </div>
</div>



### Sign

Alice builds a transaction from her wallet.
She sets the recipient's public address and the amount
The public address requires the corresponding private key to be accepted
Alice signs the transaction with her private key that can be locked by a password.
The transaction is the sent online to the bitcoin network and blockchain (via wallets)


### Generate

Miners then create a new block from signed transaction and verify they are valid.

The block data is then converted into a hash by miners.

A hash is a fixed-length string that holds large amounts of data. Each blocks has a unique hash because it has a unique set of data. Changing one variable in the data will change the hash completely.

This way, the network knows if a fake transaction was inserted in a previous block, because each block's hash is part of the formula that generate a new block


### Compete

Once miners have a valid block and hash, they compete amongst each other to get their block added to the blockchain by solving a mathematical formula that involves hashing.

Hashing is blabla ? bla bli ! boom.

The network sets a tougher hash solution as more miners compete, this way blocks are generated in a similar fashion, and not all bitcoins are mined simultanously.

Under hood, the network sets every 2 weeks a hash target value : miners need to solve the problem by providing a valid hash inferior to the target.

Retargeting makes hashing difficulty evolve with the number miners connected to the network.



## Methodology

The method of incentivising resource-consuming activities in order to reach a network consensus is called Proof-Of-Work.

This ensures

* generation of bitcoin is known to everyone
* creation of blocks occurs approximately every 10 minutes.
* miner incentivisation to secure the network
* safely prove ownership of a digital asset in a distributed and public network.

Here's a recap of the process : from initiating a transaction to getting it mined on the blockchain.
#### Infographie

<div class="container">
  <div class="row">
    <div class="col">
     Signature
    </div>
    <div class="col">
      Mining
    </div>
    <div class="col">
      Compete
    </div>
    <div class="col">
      Blockchain
    </div>
  </div>
</div>
  
  put pic here
  
<div class="container">
  <div class="row">
    <div class="col">
     Transaction is signed and sent to the network
    </div>
    <div class="col">
      Unconfirmed transaction wait to be added in the next block by miners
    </div>
    <div class="col">
      Miners verify authenticity of transaction by solving proof-of-work problem
    </div>
    <div class="col">
      Blocks get verified and added to the original bitcoin blockchain
    </div>
  </div>
</div>

Miners are tasked with solving a mathematical problem before getting rewarded by the network. If it take more resources to solve a problem than to verify it, this is called Proof-of-Work.
Because the number of miners plugged on the Bitcoin network constantly varies, the mining difficult adjusts itself to the network.

Every 2016 blocks, the mining difficulty changes so that the previous 2016 blocks mined would be mined in exactly two weeks from then. On average, 2016 blocks in two weeks represents one block every 10 minutes.

1. If more miners join the network, then the time to mine one single block reduces.
2. If blocks are getting mined faster, then the mining difficulty will have to increase.
3. When mining difficulte increased, then miners need to more time to solve the Proof-Of-Work problem
4. The time to mine one single block increases.

The Bitcoin network automatically adjusts its difficulty to the network, in order to keep mining one block every 10 minutes.