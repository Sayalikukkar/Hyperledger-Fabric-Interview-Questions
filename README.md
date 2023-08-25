# Hyperledger Fabric Interview Questions



  ## 1. What is Hyperledger?
    Hyperledger is an open-source global collaboration that helps in creating and developing enterprise-grade and destributed ledger frameworks,
    to support the business transactions and to advance cross-industry blockchain technologies, hosted by the linux foundation.


  ## 2. What is Hyperledger Fabric?
    Hyperledger Fabric is the Distributed Ledger Technology framework for building business blockchain applications.
    There are four aspects of Hyperledger Fabric Ditribued Ledger Technology that makes it suitable for implementing blockchain application for business.
    1. Permissioned Network
    2. Confidential Transactions
    3. No Cryptocurrency
    4. Programmable


  ## 3. Difference Between Private and Public Blockchain?
    • In Public Blockchain Network the participants don't have to reveal the identity. They can just download a software and start transacting on the public network.
    • In private blockchain anonymity is not the way things works. The members of the private blockchain network would alwyas be known entities and 
      the participants will be able to take actions based on the rules.
    • In case of a public blockchain network, all transactions are visible to everyone.
    • In the case of private Blockchain network, it may not be a desirable thing. Sometime in private blockchain network like to keep their transactions confidential 
      and visible only to the counterparty. 

 
  ## 4. What are the major components of Hyperledger Fabric?
    • Membership Service Provider (MSP)
    • Client
    • Peer
    • Orderer
    • Chaincode
    

 ## 5. What is MSP and why we need MSP?
    blockchain participants need a way to prove their identity to the rest of the network in order to transact on the network. Certificate Authorities issue identities by generating a public 
    and private key which forms a key-pair that can be used to prove identity. This identity needs a way to be recognized by the network, which is where the MSP comes in.
    
    For example, a peer uses its private key to digitally sign, or endorse, a transaction. The MSP is used to check that the peer is allowed to endorse the transaction. The public key from the peer’s certificate is then 
    used to verify that the signature attached to the transaction is valid. Thus, the MSP is the mechanism that allows that identity to be trusted and recognized by the rest of the network.


## 6. What are the clients in Hyperledger Fabric?
    Clients are applications that act on behalf of a person to propose transactions on the network.


## 7. Types of Peers in Hyperledger Fabric?
    Peers Maintain the state of the network and a copy of the ledger. 
    There are two different types of peers:
    • Endorsing Peer
    • Committing Peer
    However, there is an overlap between endorsing and committing peers, in that endorsing. Peers are a special kind of committing peers.
    Endorsers simulate and endorse transactions
    Committers verify endorsements and validate transaction results, prior to committing transactions to the blockchain.

## 8. What is Orderer?
    The ordering service accepts endorsed transactions, orders them into a block, and delivers the blocks to the committing peers.

## 9. What is Chaincode?
    Smart contracts are computer programs that contain logic to execute transactions and modify the state of the assets stored within the ledger (world state). 
    Hyperledger Fabric smart contracts are called chaincode and are written in Go , Java, Javascript, Typescript. 
    The chaincode serves as the business logic for a Hyperledger Fabric network, in that the chaincode directs how you manipulate assets within the network.

## 10. What is Organization?
    An organisation conceptually is an entity which has access to channels ( ledgers ) and can issue identities to participants so that every transaction's source is clear and identifiable.

#  11. What is genisis Block?
    which stores configuration information about the channel policies, members and anchor peers.
 

  
  
      
