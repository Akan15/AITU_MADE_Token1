# AITU_MADE_Token1
UniversityToken ERC-20 Smart Contract

Overview

UniversityToken is a custom ERC-20 token designed for educational purposes. This smart contract adheres to the ERC-20 standard while adding extra features to log and retrieve transaction details such as the sender, receiver, amount, and timestamp of the most recent transaction.

Key Features

ERC-20 Standard Compliance: Fully compatible with the Ethereum ERC-20 token specification.
Initial Supply: 2000 tokens minted to the deployer's address upon deployment.
Transaction Logging: Logs each transfer with details of the sender, receiver, amount, and timestamp.
Custom Functions:
getLastTransactionSender(): Returns the address of the sender in the most recent transaction.
getLastTransactionReceiver(): Returns the address of the receiver in the most recent transaction.
getLastTransactionTimestamp(): Returns the timestamp of the most recent transaction.
Deployment Details

The contract has been deployed on the Sepolia test network.
Deployed Contract Information

Contract Address: 0xD6D58070cbB0e91FF8fBf2F37cEdDC9B8D945440
Block Explorer: Sepolia Etherscan
Usage Instructions

Requirements

MetaMask: Ensure it is installed and connected to the Sepolia network.
Remix IDE: Used for deploying and interacting with the contract.
Steps to Deploy

Open Remix IDE.
Create a new file named UniversityToken.sol.
Paste the contract code into this file.
Compile the contract using Solidity version 0.8.x.
Deploy the contract using the Injected Provider (MetaMask) with the Sepolia network selected.
Confirm the deployment transaction in MetaMask.
Interacting with the Contract

Use the transfer function to send tokens to another address.
Call the custom functions to retrieve details of the latest transaction:
getLastTransactionSender()
getLastTransactionReceiver()
getLastTransactionTimestamp()
Example Calls

Transfer 10 tokens:
transfer("0xRecipientAddress", 10)
