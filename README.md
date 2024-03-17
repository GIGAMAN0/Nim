# Nim Game with Reinforcement Learning AI

This project implements an AI that learns to play Nim through reinforcement learning.

## Introduction

Nim is a mathematical game of strategy where players take turns removing objects from heaps or piles. The player who removes the last object loses. In this project, we aim to teach an AI to play Nim by itself using reinforcement learning, specifically Q-learning.

## Files

- `nim.py`: Contains the implementation of the Nim and NimAI classes along with the functions for training and playing the game.
- `play.py`: Script to play Nim against the trained AI.
- `requirements.txt`: List of required Python packages.

## Usage

To train the AI and play Nim against it, run the following command:

python play.py



The AI will train itself by playing multiple games against itself. Once training is complete, you can play Nim against the trained AI.

## How It Works

The project utilizes Q-learning, a model-free reinforcement learning algorithm, to teach the AI to play Nim. The AI learns by playing games against itself and updating Q-values based on the outcomes of those games. It then uses these Q-values to make decisions about which actions to take in a given state.

