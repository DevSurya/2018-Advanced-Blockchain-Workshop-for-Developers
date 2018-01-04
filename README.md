# Workshop: Advanced Blockchain Workshop for Developers

<img src="https://farm5.staticflickr.com/4689/24631379357_6871402136_m.jpg" width="240" height="160" alt="425 market street">

<a href="http://ibm.biz/advchainsf"><img src="https://farm5.staticflickr.com/4596/39468207682_17288767da_z.jpg" width="983" height="157" alt="advchainsf"></a>


## The workshop materials are all out on: http://ibm.biz/advchainsv

# Housekeeping info:

### Wifi at 425 Marker Street SSID/pass = XXX / XXX
Your instructor: Lennart alf@us.ibm.com, Developer Advocate at IBM, focusing on Blockchain, Fintech and Watson.

Syed Zaidi. Maya Reyes, Juanita Dion.

# Agenda
~~~
6:00: Sign-in, mingle, food, welcome, form teams 
6:20: Lennart: Introduction to IBM Blockchain and Hyperledger  
6:40: Coding starts.
      Lab 1: Let's run our first application in Hyperledger Fabric
      Lab 2: Let's write an app with the Hyperledger Composer
      Lab 3: A full app, Decentralized Energy with Hyperledger Composer
8:15: Coding ends.
      Where do we go from here? 
      Developer Journeys for Blockchain
      Q1 2018: Advanced Blockchain, a Hands-on Workshop.
8:30: Event ends   
~~~ 
# Let's get started, introduction and documentation

## How did it all start?

October 2008 It all started with Satoshi Nakamoto and his paper [Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf) which addressed a key problem in electronic commerce:

<img src="https://farm5.staticflickr.com/4505/24079519258_ab8a80f7ed_o.png" width="769" height="229" alt="Double Spending">

**In this workshop we will use the Hyperledger implementation of Blockchain : http://hyperledger.org/**

Hyperledger, an open source collaborative effort to advance cross-industry blockchain technologies, 
is hosted by The Linux Foundation®. 

Deployed in Docker images.

1. A blockchain emulates a “trusted” computing service through a distributed protocol, 
   run by nodes connected over the Internet. 

2. The service represents or creates an asset, in which all nodes have some stake.

3. The nodes share the common goal of running the service but do not necessarily 
   trust each other for more. 

....

5. On the other hand, blockchains in the “permissioned” model control who participates in validation and
   in the protocol; these nodes typically have established identities and form a consortium

Consensus protocol is pluggable, currently an implementation of Byzantine fault-tolerant con-
sensus using the PBFT protocol.

Source: https://www.zurich.ibm.com/dccl/papers/cachin_dccl.pdf


<img src="https://farm5.staticflickr.com/4494/37926120211_b7dddb090d_o.png" width="682" height="423" alt="Hyperledger Services">

### Hyperledger Composer source code on GitHub https://github.com/hyperledger/composer
Hyperledger Composer is an application development framework which simplifies and expedites the creation of Hyperledger fabric blockchain applications.

### Hyperledger Fabric source code on Github https://github.com/hyperledger/fabric

Hyperledger Fabric is a platform for distributed ledger solutions, underpinned by 
a modular architecture delivering high degrees of confidentiality, resiliency, 
flexibility and scalability. It is designed to support pluggable implementations 
of different components, and accommodate the complexity and intricacies that exist 
across the economic ecosystem.

### [The .bna file](https://hyperledger.github.io/composer/reference/commands.html)
A Business Network Archive (BNA) file is exported by the Hyperledger Composer with 
the extension of .bna, and contains the definitions all the definitions for a Business Network. 
It is deployed in a Hyper Ledger Fabric. 
 
## General information:
[Hyperledger Consensus](https://www.hyperledger.org/wp-content/uploads/2017/08/HyperLedger_Arch_WG_Paper_1_Consensus.pdf)
  
<img src="https://farm5.staticflickr.com/4511/37561438920_efe78c324b_o.png" width="1169" height="199" alt="blockchain-banner2">


# Lab 1: Setting up the environment 
https://ibm-blockchain.github.io/

What do you get?

1. A pre-configured Fabric (blockchain runtime):
   * Three Fabric CAs (one apiece for the orderer org and two peer orgs)
   * Orderer node (running "solo")
   * Two Fabric peer nodes (one apiece for each peer org - org1 & org2)
   * Some example installed and instantiated chaincode
1. Composer Playground (UI for creating and deploying Business Networks to Fabric)
1. The basic-sample-network deployed


### Step 1: Prepare and Setup
https://ibm-blockchain.github.io/setup/

## Step 2 Simple Install
https://ibm-blockchain.github.io/simple/

## Step3: Interacting with your Blockchain

https://ibm-blockchain.github.io/interacting


<img src="https://farm5.staticflickr.com/4684/25629362468_5d1157ca25_m.jpg" width="240" height="133" alt="welcome">


# Lab 2: Let's write an app with the Hyperledger Composer!
<img src="https://farm5.staticflickr.com/4445/37751618086_06402e4b2e_b.jpg" width="383" height="266" alt="Composer Playground">

[Playground Tutorial](https://hyperledger.github.io/composer/tutorials/playground-guide.html)

## Run Hyperledger Composer in your browser https://hyperledger.github.io/composer/

## [Instructions (open in parallel window): Composer Playground and the Perishable Goods Network]

(https://github.com/LennartFr/Blockchain-at-Galvanize/blob/master/Hyperledger%20Composer%20Perishable%20Food%20Network%203.pdf)

This concludes the second lab centered arund the Composer Playground. 

# Lab 3: Decentralized Energy with Hyperledger composer 

This third lab, a Developer Journey written by Raheel Zubairy of IBM, describes a complete blockchain application with a decentralized energy network with a working user interface.

https://developer.ibm.com/code/journey/decentralized-energy-hyperledger-composer/

Lab Instructions: https://github.com/IBM/Decentralized-Energy-Composer?cm_sp=IBMCode-_-decentralized-energy-hyperledger-composer-_-Get-the-Code

## This concludes the lab portion of this workshop

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

# Overview of the Hyperledger architecture

### The flow with one SDK

<img src="https://farm5.staticflickr.com/4479/37162470013_1309212044_b.jpg" width="1024" height="513" alt="Hyperledger Architecture">

### The flow with two and more SDKs

<img src="https://farm5.staticflickr.com/4506/37882671951_5f4f08348a_o.png" width="1142" height="635" alt="Hyper Ivan 2">

### The Blockchain and State database.

<img src="https://github.com/LennartFr/Blockchain-at-Galvanize/blob/master/Hyperledger%20LevelDB.PNG">

### Ordering service

<img src="https://www.ibm.com/developerworks/cloud/library/cl-top-technical-advantages-of-hyperledger-fabric-for-blockchain-networks/fig1.png">

### Blockchain Ledger

<img src="https://farm5.staticflickr.com/4496/37833953496_fa03154139_o.png" width="837" height="421" alt="Ivan Blockchain">

# Hyperledger Fabric and its docker images 

<img src="https://farm5.staticflickr.com/4506/23967210328_2ab9949bdb_o.png" width="701" height="812" alt="hyper docker">

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">


# Where do we go from here?

<img src="https://farm5.staticflickr.com/4338/36822231841_bc13a7147a_z.jpg" width="640" height="164" alt="IBMBlockchain1">

[Blockchain for Dummies](https://public.dhe.ibm.com/common/ssi/ecm/xi/en/xim12354usen/XIM12354USEN.PDF)


## IBM has a series of Developer Journeys covering various aspects of Blockchain, with more being added regularly. 

* https://developer.ibm.com/code/journey/build-your-first-blockchain-application/
* https://developer.ibm.com/code/journey/create-and-execute-blockchain-smart-contracts/
* https://developer.ibm.com/code/journey/implement-fda-food-supplier-verification-program-on-hyperledger-composer/
* https://developer.ibm.com/code/journey/build-a-blockchain-network/
* https://developer.ibm.com/code/journey/decentralized-energy-hyperledger-composer/
* https://developer.ibm.com/code/journey/run-blockchain-technology-on-a-linux-mainframe/
* https://developer.ibm.com/code/journey/create-a-to-do-list-app-using-blockchain/
* https://developer.ibm.com/code/journey/deploy-an-asset-transfer-app-using-blockchain/

# https://www.hyperledger.org/community

## Blockchain in the IBM Cloud: https://console.bluemix.net/catalog/services/blockchain/ 

<img src="http://34b70.http.dal05.cdn.softlayer.net/broker-static/v1-ga1/img4.png">

** Initiate a new blockchain network including setting democratic network policies and inviting new members to join.
** Join a network, as a new member, based on an invite from the network initiator.

* Use Issues to log suggestions to this workshop.
https://github.com/LennartFr/Blockchain-at-Galvanize/issues/1


# Appendix

