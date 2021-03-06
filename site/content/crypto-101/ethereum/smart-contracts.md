+++
title = "Smart contracts"
date = 2017-08-02T17:16:29+02:00
description = "Smart contracts are Ethereum's main value proposition: we are now able to automate interactions, relationships, disbursements with computer programs."
draft = false
bref = "Ethereum, Part III"
toc = true
+++

## Differentiation

### Conventional contracts

Conventional contracts are agreements that define stakeholder relationships, be it related to a transaction, inheritance or consumption.  

Typically, valid standard contracts are enforceable by law, meaning if you decide not to honour the terms of a contract, you are vulnerable to legal recourse.   

However, you are not physically forced: there is always a trust factor to consider before entering a contractual relationship with a peer.  

Going legal is at the end of the day an inefficient and resource draining exercise that (most) people would like to avoid. The current legal and judiciary system may take years to resolve a litigation, and sometimes decades in some jurisdictions.

### Smart contracts

Smart contracts try to solve this issue by automating the terms of an agreement with a few lines of code.  
They are computer programs that execute pre-defined contractual conditions, at a certain point of time, to ensure an agreement is ultimately honoured.  

In other words, a smart contract is a programmed transaction protocol that runs desired operations depending on pre-defined scenarios.  
It does not have to be a legal contract per se, rather, it aims to minimise the risks of bad faith, make sure an agreement is honoured and automate tasks.  

Here’s a quick recap of the difference between both.

<div class="container my-4">
  <div class="row">
    <div class="col text-center">
      {{< img src="crypto-101/icons/handshake.svg" class="img-fluid" alt="Handshake" >}}
      <p class="font-weight-bold mt-2 text-center">Formal or informal agreement</p>
      <p class="small text-center">If agreement is not honoured, the following can happen</p>
      <ul>
        <li class="small text-left">1 - Reminder</li>
        <li class="small text-left">2 - Follow – up</li>
        <li class="small text-left">3 - Renegotiation</li>
        <li class="small text-left">4 - Legal recourse</li>
        <li class="small text-left">5 - Settlement in the future</li>
      </ul>
    </div>
    <div class="col text-center">
      {{< img src="crypto-101/icons/smart-contract.svg" class="img-fluid" alt="Smart contract" >}}
      <p class="font-weight-bold mt-2">Smart contract, computer program
      <p class="small">Agreement is always honoured : a smart contract will automate the tasks as per initial terms and conditions.</p>
      <p class="small">Smart contracts are flexible, they can be permissionless or immutable</p>
    </div>
  </div>
 </div>

Ethereum allows developers to smart code contracts on top of its blockchain using its programming language, Solidity.  

Rather than “smart contracts” which is a term introduced in the 1990s, Ethereum refers to them as “automated agents” in its white paper, because it enables the issuance of large-scale computing operations between users and other smart contracts.

## Case study

It might be hard to conceptualise at first so let’s have a look at a real-life smart contract use-case:

### Assumptions

Alice and Bob decide to bet a fraction of their savings on the occurrence of an event.  
Alice wins the bet **if** the S&P 500 reaches its lowest 10-year performance in the next month.  
If the condition isn't met within 15 days, Bob loses.  

### Conventional agreement

1. Alice and Bob enter an agreement (handshake, contract).
2. They decide that the loser will pay the winner after the event.
3. Both track the S&P performance manually.
4. Alice wins the bet.

At this point, there are 3 possible outcomes:  

<div class="container">
  <div class="row text-center">
    <div class="col">
      {{< img src="crypto-101/icons/yes.svg" class="img-fluid" alt="Yes" >}}
      <p class="font-weight-bold">A. Bob pays up</p>
    </div>
    <div class="col">
      {{< img src="crypto-101/icons/three-dots.svg" class="img-fluid" alt="Maybe" >}}
      <p class="font-weight-bold">B. Bob delays payment</p>
    </div>
    <div class="col">
      {{< img src="crypto-101/icons/no.svg" class="img-fluid" alt="No" >}}
      <p class="font-weight-bold">C. Bob refuses to pay up</p>
    </div>
  </div>
</div>

In a conventional agreement, we can therefore affirm that:

* Alice and Bob have to track the event manually.
* Bob might breach the agreement.

### Smart contract

1. Alice and Bob create a smart contract that automates the terms of the agreement and tracks S&P performance.
2. Both send the money to the smart contract that will release the funds, either at the end of the month, or when S&P reaches the predefined metric.
3. Alice wins the bet.

Here, the smart contract releases the funds automatically to Alice.  
Programming the bet on a smart contract offers two tangible benefits:

* Alice and Bob do not need to track the S&P 500. A smart contract automates this task and rewards the winner accordingly.
* They send the money to the smart contract, which disburses the funds directly to the winner. It reduces any risk of bad faith in an agreement and avoids any disputes because it is automated.

Creating such interactions would typically require multiple steps:

* Set the conditions of the bet (deadline, participants, etc.)
* Check S&P 500 performance.
* Hold the money and disburse to the winner based on the above.

Running smart contracts on the network has a cost, and it depends on the computing power required to execute it: this is when Ether transaction fees come in the picture.  

The same way ERP and CRM automate supply chain and client communication, smart contracts can automate any real-life interaction.

## Ethereum Virtual Machine

Ethereum allows its users to set different kinds of operations: not just limited to monetary transactions like with Bitcoin.  
At the epicentre of the Ethereum network sits the Ethereum Virtual Machine (EVM), the environment for smart contract development and execution.  

The EVM has two main characteristics:

* **Turing complete:** meaning it can, in theory, be used to solve any computation problem. Developers can create programs with various coding languages such as Solidity (JavaScript), Serpent (Python) or LLL (Lisp).
* **Isolated:** code and smart contracts running on top of the EVM do not have access to other applications on the network.

Every node on the network (computers connected) runs the EVM and regularly updates the Ethereum database.  

Note that this decentralised computation framework is far less efficient in terms of cost and speed than a traditional hardware set-up. 

Still, it offers valuable benefits :

* Continuously online with no downtime.
* High-level of fault tolerance.
* Immutable and censorship-resistant database.

Furthermore, Ethereum and its EVM are value-agnostic: developers are the ones deciding how to use the platform (not the opposite!). While Bitcoin is suited for peer-to-peer payments, Ethereum can automate interactions between stakeholders and coordinate community actions on its network.   

Using code, we can now design any type of operations between peers, like scheduling a payout to an investor, giving a voting right to stakeholders within an organisation or coordinating a peer-to-peer online marketplace.  

Bitcoin changed the payment industry, Ethereum can very well change any industry where trust, immutability and security are important.
