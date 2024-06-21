# Proveable Random Raffle Contracts

## About

This code is to create proveable random smart contract lottery.
The code was written following Patrick Colins' tutorial on learning Solidity and Foundry.

It takes up the basic concepts of the Solidity language and also integrates modules from the Chainlink oracle, such as random number generation and the notion of time-lapse triggering.

You can find the course at https://updraft.cyfrin.io.

## What we want to do?

1. Users can enter by paying for a ticket
   1. The ticket fees are going to the winner during the draw
2. After X period of time, the lottery will automatically draw a winner
   1. And this will be done progra;atically
3. Using Chainlink VRC & Chainlin Automation
   1. Chainlink VRF -> Randomness
   2. Chainlink Automation -> Time based trigger
