# ipd-tournament-simulator
# Iterated Prisoner's Dilemma Tournament Simulator

A modular and extensible Python framework to simulate a **round-robin tournament** of different player strategies in the **Iterated Prisoner's Dilemma (IPD)**. Supports multiple game modes including memory-based, discounted, and stochastic games.

## Features

- **6 Game Modes**:
  1. Blind Iterative (No Memory, No Discount)
  2. Memory Iterative (No Discount)
  3. Discounted Blind Iterative
  4. Discounted Memory Iterative
  5. Stochastic Blind (Probabilistic Rounds, No Memory)
  6. Stochastic Memory (Probabilistic Rounds with Memory)
- Customizable strategies via user-defined functions.
- Round-robin tournament for pairwise evaluation.
- Supports geometric discounting and probabilistic continuation.
- Easy extension to new strategies or game types.

## Requirements

- Python 3.x
- No external dependencies (uses only the standard library)

## File Structure

