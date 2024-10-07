

---

# Freelancer Escrow Smart Contract

## Vision

The Freelancer Escrow Smart Contract aims to bridge the trust gap between clients and freelancers by providing a decentralized platform for managing work contracts. This project aims to create a secure escrow mechanism where funds are held until project milestones are successfully completed, ensuring fair and transparent payments for both parties involved.

## Features

- **Escrow Creation**: Clients can create an escrow agreement with a freelancer, specifying the funds to be held securely until the completion of the project.
- **Milestone-based Release**: Clients can release funds to the freelancer upon successful completion of defined milestones.
- **Trustless Payment Mechanism**: Ensures that payments are only released when both parties fulfill their contractual obligations, removing the need for intermediaries.

## Contract Address

- **Network**: Aptos Devnet
- **Contract Address**: `0x9b8c6208c493b766783c48c5a17ea6e15673d432c05489420b2eadae0f4b0a90`

## How It Works

1. **Create Escrow**:

   - A client can initiate an escrow agreement by calling the `create_escrow` function.
   - The client's address, freelancer's address, and the amount to be held in escrow are stored on the blockchain.

2. **Release Funds**:
   - Once the freelancer completes the project or milestone, the client can call the `release_funds` function to release the funds.
   - The escrow contract marks the agreement as "released," and in future iterations, the funds will be transferred directly to the freelancer.

## Future Scope

- **Milestone-based Escrow**: Allow the escrow to be divided into multiple milestones, with partial releases upon each milestone's completion.
- **Dispute Resolution Mechanism**: Introduce a decentralized arbitration system where disputes can be resolved if disagreements arise.
- **Automatic Fund Transfers**: Implement functionality for automated fund transfers once the escrow is released, ensuring the payment is made directly to the freelancer without manual intervention.
- **Rating System**: Introduce a rating system for clients and freelancers to help participants evaluate potential partners based on past experience.
- **Integration with Freelance Marketplaces**: Collaborate with existing freelance platforms to integrate this escrow functionality to make the payment process seamless.

## Getting Started

- Clone this repository and install the required dependencies for the Aptos blockchain.
- Deploy the contract using your preferred deployment tool.
- Once deployed, clients and freelancers can interact with the smart contract to create and manage escrow agreements.

---


