# AI Flappy Bird

An AI-powered Flappy Bird game that uses the NEAT (NeuroEvolution of Augmenting Topologies) algorithm to train neural networks to play the game autonomously.

## What It Does

This project implements a Flappy Bird game where multiple AI birds learn to navigate through pipes using evolutionary neural networks. The AI starts with random behavior and evolves over generations, gradually improving its ability to avoid obstacles and survive longer.

## Concepts Covered

- **NEAT Algorithm**: NeuroEvolution of Augmenting Topologies for evolving neural network architectures
- **Neural Networks**: Feed-forward networks that make decisions based on game state
- **Genetic Algorithms**: Population-based evolution with fitness-based selection
- **Game Development**: Pygame for rendering, physics, and game mechanics
- **Object-Oriented Programming**: Classes for Bird, Pipe, and Base game elements
- **Collision Detection**: Pixel-perfect collision using pygame masks
- **Physics Simulation**: Gravity, velocity, and acceleration mechanics

## How It Works

The neural network receives three inputs:
- Bird's vertical position
- Distance to the top pipe
- Distance to the bottom pipe

Based on these inputs, the network decides whether the bird should jump. Birds that survive longer and pass more pipes receive higher fitness scores, and their genetic material is more likely to be passed to the next generation.

## Requirements

- Python 3.x
- pygame
- neat-python

## Usage

Run `main.py` to start the evolution process. Watch as the AI birds learn to play Flappy Bird over multiple generations!
