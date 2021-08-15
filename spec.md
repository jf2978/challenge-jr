# Exactly Finance Technical Challenge (Jr.)

**Author:** Jeffrey Fabian
**Last Updated:** August 15, 2021

## Background

I recently reached out to the Exactly Finance team in hopes for a chance to prove my skills helpful in their goal to building an open, non-custodial financial protocol for fixed-rate lending and borrowing. Other protocol and platforms exist to a similar end, but all (that I'm aware of) do so at the cost of decentralization itself (e.g. Nexo, Celcius), income predictability (e.g. Aave, Compound) and/or ease of use (e.g. Yield Farming/Liquidity mining as a whole).

In short, I'm super interested in DeFi and recognize that the best way to learn is to start buildng.

## Problem Statement

I want to design, test and deploy a smart contract that decides and rewards games of rock, paper scissors -- smart enough to always reward the winning move

See the full details in [README.md](https://github.com/exactly-finance/challenge-jr).

## Goals

- Learn some Solidity + building smart contracts on Ethereum
- Create `RockPaperScissors` smart contract
- Design a barebones game whereby two players can: enroll in a game, wager bets, and submit a move (rock, paper or scissors)
- Design a smart contract which outlines: the contract logic (in plain English), data structure (Solidity), possible states, and network considerations (txn speed, gas fees, failures, etc.)
- Discuss edge cases, potential security vulnerabilities and social expactations (uncooperative players, locked up funds, etc.)
- Outline a test & deployment strategy -- e.g. [Hardhat tests](https://hardhat.org/tutorial/testing-contracts.html), leverage testnet, consider easy-out-of-the-box web app deployment tools

### Future Goals (probably-out-of-scope improvements)

- Let players bet previous winnings
- Minimize gas costs

### Non-Goals

- Deploy a live game with real money at stake
- Design a beautiful game interface
- Create a shareable version of the game (beyond `git clone`-ing this code)

## Proposed Implementation

## Rejected Alternatives

## Related Links