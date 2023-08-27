# Proveably Random Raffle Contracts

## About

This code is to create a proveably random smart contract lottery.

## What we want to do?

1. Users can enter by paying for a ticket
   1. The ticket fees are going to go to the winner during the draw
2. After X period of time, the lottery will automatically draw a winner
   1. And this will be done programatically
3. Using Chainlink VRF & Chainlink Automation
   1. Chainlink VRF -> Randomness
   2. Chainlink Automation -> Time best Trigger

### Cast Command

``` bash
cast send 0x0e45891bb375c5268af7d7Da5D21e3A0EDb6e7A2 "enterRaffle()" --value 0.2ether --rpc-url $SEPOLIA_RPC_URL --private-key $PRIVATE_KEY 
```
 ### Git command
 
 ``` bash
 git add README.md
 git commit -m "first commit"
 git status
 git remote add origin https://github.com/Lihuatx/foundry-smart-contract.git
 git add .
 git branch -m master main #将master分支改成main分支
 git push -u origin main
 ```