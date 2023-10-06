# Blackjack AI Simulation

## Overview

This project is a simulation of the game of Blackjack, where we've implemented three different AI players, each using a unique strategy. Through simulating 100,000 games, we've analyzed how often each AI manages to win against the bank.

## AI Implementations

### 1. Easy AI (Bot 1)

This AI was designed to play in a very simplistic manner. Its strategy is based solely on the value of its hand, drawing cards until the hand value reaches or exceeds 17. This basic approach allows us to compare its effectiveness against more strategic bots.

### 2. Intermediate AI (Bot 2)

Inspired by the third AI's strategy, this intermediate bot has certain gameplay options restricted. Specifically, it cannot split or double down, limiting its strategic depth compared to the advanced bot.

### 3. Advanced AI (Bot 3)

The advanced AI aims to play the game "perfectly", optimizing its chances of winning to the fullest. It adheres to a strategy chart that provides the best possible moves in Blackjack, ensuring that it minimizes losses over the long term.

## Project Outcomes

The primary goal of this project was to create a game environment where a player could face off against the dealer's AI and indirectly compete with the three other AIs (easy, intermediate, advanced). Over a large number of games, the randomness fades, as evident from the simulations. Our team's prior experience working together greatly facilitated our communication, enabling efficient organization regarding game choice, AI strategies, and language selection.

## How to Try the Project

1. Ensure you have Java installed on your computer.
2. Clone the GitHub repository.
3. Run the `TestCartes.java` file.
4. Type "2" to choose Bot testing.
