# Fundraising Smart Contract

This is a simple Ethereum-based fundraising smart contract that allows people to donate Ether to a cause, track donations, and withdraw funds when the goal is reached.

## Features:
- Tracks donations from users
- Allows the contract owner to withdraw funds once the goal is reached
- Donors can request refunds if the goal is not met by the deadline
- Multisig withdrawal for additional security

## How to Deploy:
1. Compile and deploy the contract using Remix or Hardhat.
2. Set the fundraising goal and duration during deployment.
3. Fundraisers can donate to the cause.
4. Once the goal is met, the owners can withdraw the funds.

## Usage:
- Users can donate Ether to the contract using the `donate()` function.
- Donors can request refunds if the goal isn't met by the deadline using the `requestRefund()` function.
- Owners can withdraw funds using the `withdraw()` function once the goal is reached.
