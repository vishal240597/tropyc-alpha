+++
title = "Under the hood"
date = 2017-08-02T17:00:00+02:00
description = "Bitcoin offers a secure environment for transaction thanks to blockchain technology, here, you'll learn how the system works and what's under the hood."
draft = false
bref = "Bitcoin, Part III"
toc = true
+++

<div class="container my-4">
  <div class="row text-center">
    <div class="col">
      {{< img src="crypto-101/icons/mining.svg" class="img-fluid" alt="Mining" >}}
      <p class="font-weight-bold">Mining</p>
    </div>
    <div class="col">
       {{< img src="crypto-101/icons/blockchain.svg" class="img-fluid" alt="Blockchain" >}}
       <p class="font-weight-bold">Blockchain</p>
    </div>
    <div class="col">
       {{< img src="crypto-101/icons/consensus.svg" class="img-fluid" alt="Consensus" >}}
       <p class="font-weight-bold">Consensus</p>
    </div>
  </div>
</div>

## Mining

The main difference between fiat and Bitcoin is that the former can be printed without a limit while the latter is capped at 21 million units

<div class="container my-5">
  <div class="row">
    <div class="col text-center">
      {{< img src="crypto-101/icons/fiat-economy.svg" class="img-fluid" alt="Printer USD dollars" >}}
    </div>
    <div class="col text-left">
    	<h3>Printing fiat</h3>
      In the current financial system, floating currencies are regulated by central banks – they can inject or remove money via a centralised system. The amount of fiat money is uncapped as Central Banks have the power to print an unlimited supply.
    </div>
  </div>
 </div>

<div class="container my-5">
  <div class="row">
    <div class="col text-left">
    	<h3>Mining Bitcoin</h3>
     	The creation of Bitcoin is decentralised, transparent and follows an immutable mathematical formula. Bitcoins are not printed but "mined" by computers plugged on the network. There will only be 21 million bitcoins ever mined.
    </div>
    <div class="col text-center">
       {{< img src="crypto-101/icons/mining.svg" class="img-fluid" alt="mining" >}}
    </div>
  </div>
 </div>

Initially, Bitcoin's price was indexed on the prerequisite costs needed to run the network or mining costs.
As such, mining Bitcoin and cryptocurrencies is a resource-draining activity that requires investment from the fiat economy.

<div class="container my-4">
  <div class="row text-center">
    <div class="col">
       {{< img src="crypto-101/icons/hardware.svg" class="img-fluid" alt="Servers" >}}
       <p class="font-weight-bold">Hardware</p>
       <p class="small">Miners allocate their computing power to the network.</p>
       <p class="small">The more powerful the installation, the better the performance.</p>
    </div>
    <div class="col">
       {{< img src="crypto-101/icons/energy.svg" class="img-fluid" alt="Thunder" >}}
       <p class="font-weight-bold">Energy</p>
       <p class="small">Computer equipment consumes power to function continuously.</p>
       <p class="small">Energy is the main operational expense miners incur.</p>
    </div>
    <div class="col">
       {{< img src="crypto-101/icons/time.svg" class="img-fluid" alt="Sandbox" >}}
       <p class="font-weight-bold">Time</p>
       <p class="small">Resources could be allocated to another network.</p>
       <p class="small">Miners invest not only their equipment but their time to the task.</p>
    </div>
  </div>
</div>

<p class="font-weight-bold text-center mt-4">The network rewards miners in such a way that they are incentivised to keep it secure.</p>

<div class="container my-4">
  <div class="row text-center">
    <div class="col">
      {{< img src="crypto-101/icons/transaction-fees.svg" class="img-fluid" alt="Percentage price" >}}
      <p class="font-weight-bold">Transaction fees</p>
      <p class="small w-75 mx-auto">Issuing a transaction incurs a small fee that is disbursed to miners.</p>
    </div>
    <div class="col">
       {{< img src="crypto-101/icons/mining-rewards.svg" class="img-fluid" alt="Gold cup" >}}
       <p class="font-weight-bold">Mining rewards</p>
       <p class="small w-75 mx-auto">New blocks generates new bitcoins, rewarded to the best miners</p>
    </div>
  </div>
</div>

## Blockchain

A blockchain allows to have shared memory in a decentralized way. It serves as a publicly available and distributed digital ledger that records transactions.

The Bitcoin blockchain is a series of blocks that holds transaction data of approximately 10 minutes of network activity. Miners are the ones creating new blocks by solving a mathematical formula.  
By doing so, the network rewards them with freshly mined Bitcoin.

{{< img src="crypto-101/infographics/info-btc3-1.png" class="img-fluid" alt="Password lock" >}}

Each block records the information of multiple transactions including:

* The time
* Transaction ids
* The sender's public address
* The recipient's public address
* The amount
* The mining reward
* A unique id code called hash

<p class="font-weight-bold text-center mt-4">This offers two tangible benefits to blockchain technology compared to a centralised dataset:</p>

<div class="container my-4">
  <div class="row text-center">
    <div class="col">
     {{< img src="crypto-101/icons/transparent.svg" class="img-fluid" alt="Magnifying glass gold" >}}
     <p class="font-weight-bold">Transparency</p>
     <p class="small">Perfect knowledge of transaction information.</p>
    </div>
    <div class="col">
     {{< img src="crypto-101/icons/lock.svg" class="img-fluid" alt="Lock inside chat bubble" >}}
     <p class="font-weight-bold">Immutable</p>
     <p class="small">Once a block is recorded it becomes permanent.</p>
    </div>
  </div>
</div>

Each blockchain block stores every Bitcoin transaction that was created and confirmed by the network during a ten minute period.  
Once a new block is mined, it is added to an immutable public distributed ledger; this is the blockchain: a chronological combination of data blocks.

## Consensus

A transaction does not exist until recorded in a block. To keep the network safe and secure, miners have to reach a consensus before accepting a transaction.

<div class="container my-5 text-center">
  <div class="row">
    <div class="col">
      {{< img src="crypto-101/icons/signature.svg" class="img-fluid" alt="Pen signature document" >}}
      <p class="font-weight-bold">Sign</p>
      <p class="small w-75 mx-auto">Alice wants to send money to Bob via Bitcoin.</p>
    </div>
    <div class="col">
      {{< img src="crypto-101/icons/generate.svg" class="img-fluid" alt="Production line" >}}
      <p class="font-weight-bold">Generate</p>
      <p class="small w-75 mx-auto">Miners gather data and create their own block.</p>
    </div>
    <div class="col">
      {{< img src="crypto-101/icons/compete.svg" class="img-fluid" alt="Boxing gloves" >}}
      <p class="font-weight-bold">Verify</p>
      <p class="small w-75 mx-auto">All miners compete to get their block approved and issued on the blockchain.</p>
    </div>
  </div>
</div>

<div class="container my-5">
  <div class="row align-items-center">
    <div class="col-sm-6 col-md-4 text-center">
    	{{< img src="crypto-101/icons/signature.svg" class="img-fluid" alt="Pen signature document" >}}
    </div>
    <div class="col-sm-6 col-md-8">
    	<h3>Sign</h3>
    	<ol>
    		<li>Alice issues a transaction from her wallet.</li>
    		<li>She sets the recipient's public address and the amount to disburse.</li>
    		<li>The public address requires a signature from the corresponding private key in order to be accepted.</li>
    		<li>Alice signs the transaction with her private key, stored in a wallet that can be protected by a password.</li>
    		<li>The transaction is then sent online to the bitcoin network to be recorded on the blockchain.</li>
    	</ol>
    </div>
  </div>
</div>

<div class="container my-5">
  <div class="row align-items-center">
    <div class="col-sm-6 col-md-8">
	    <h3>Generate</h3>
	    <p>Miners then create a new block from signed transactions and verify that they are valid.</p>
	    <p>The block's data is then converted into a hash by miners.</p>
	    <p>A hash is a fixed-length string that holds large amounts of data.</p>
	    <p>Each block has a unique hash because it has a unique set of data. Changing one variable in the data will change the hash.</p>
	    <p>This way, the network knows if a fake transaction has been inserted in a previous block because each block's hash is part of the formula that generates a new block.</p>
    </div>
    <div class="col-sm-6 col-md-4 text-center">
   		{{< img src="crypto-101/icons/generate.svg" class="img-fluid" alt="Production line" >}}
    </div>
  </div>
</div>

<div class="container my-5">
  <div class="row align-items-center">
    <div class="col-sm-6 col-md-4 text-center">
    	{{< img src="crypto-101/icons/compete.svg" class="img-fluid" alt="Boxing gloves" >}}
    </div>
    <div class="col-sm-6 col-md-8">
    	<h3>Compete</h3>
    	<p>Once miners have a valid block and hash, they compete amongst each other to get their block added to the blockchain by solving a mathematical formula that involves hashing.</p>
   		<p>Miners need to gather different unconfirmed transactions (input) compute them into a hashing function set by an algorithm and create a new hash (output) with pre-determined conditions (starts with a certain amount of zeros).</p>
    </div>
  </div>
</div>

As more miners compete for rewards, the hash problem gets tougher and tougher. This way, the difficulty to mine a block adjusts itself with the number of miners working.  

Under the hood, the network sets every two weeks a new hash target value: miners need to solve the problem by providing a valid hash inferior to the target.  

Retargeting makes hashing difficulty evolve with the number of miners connected to the network.

## Methodology

The method of incentivising resource-consuming activities to reach a network consensus is called Proof-Of-Work.

This ensures:

* Bitcoin emission rate is transparent.
* Creation of blocks occurs approximately every 10 minutes.
* Miners are incentivised to secure the network.
* Transactions of digital assets are safe and trustless

<p class="mt-3">Here's a recap of the process: from initiating a transaction to getting it mined on the blockchain.</p>

<div class="container my-4">
  <div class="row text-center font-weight-bold">
    <div class="col">
     1 - Signature
    </div>
    <div class="col">
     2 - Mining
    </div>
    <div class="col">
     3 - Compete
    </div>
    <div class="col">
     4 - Blockchain
    </div>
  </div>
</div>

{{< img src="crypto-101/infographics/info-btc3-2.png" class="img-fluid" alt="From signature to blockchain" >}}

<div class="container my-4">
  <div class="row text-center small">
    <div class="col">
      Transaction is signed and then sent to the network by a wallet
    </div>
    <div class="col">
      Unconfirmed transactions waiting to be added in the next block by miners
    </div>
    <div class="col">
      Miners verify authenticity of transaction by solving proof-of-work problem
    </div>
    <div class="col">
      Blocks get verified and added to the original bitcoin blockchain
    </div>
  </div>
</div>

Miners have to resolve a mathematical problem before getting rewarded by the network.  
If it takes more resources to solve a problem than to verify it, the system can be a Proof-of-Work economic measure.  
Because the number of miners plugged on the Bitcoin network varies, the mining difficulty adjusts itself to the network.

Every 2016 blocks, the mining difficulty changes so that the previous 2016 blocks mined would be mined in exactly two weeks from then.

On average, 2016 blocks in two weeks represents one block every 10 minutes.

1. If more miners join the network, then the time to mine one single block reduces.
2. If blocks are getting mined faster, then the mining difficulty will have to increase.
3. When mining difficulty is increased, then miners need more time to solve the Proof-Of-Work problem.
4. Then the time to mine one single block increases.

The Bitcoin network automatically adjusts its difficulty in order to keep mining one block every 10 minutes.
