# Provably Random Raffle Contracts

## About

This code is to create a provably random smart contract lottery.

1. Users can enter by paying for a ticket
    a. The ticket fees are going to go to the winner during the draw
2. After X period of time, the lottery will automatically draw a winner
    a. This will be done programatically
3. Using Chainlink VRF and Chainlink Automation
    a. Chainlink VRF -> Randomness
    b. Chainlink Automation -> Time based trigger