# Neural Network Car Simulation
This project implements a simple car simulation using a neural network powered by the NEAT (NeuroEvolution of Augmenting Topologies) algorithm. The simulation involves cars navigating a track with the goal of maximizing their distance traveled.

## Project Overview
* Car Simulation: Cars are represented as sprites on a track and controlled by neural networks. The cars can move left, right, speed up, or slow down.

* NEAT Algorithm: The NEAT algorithm is used to evolve neural networks for controlling the cars. It creates and evolves neural networks with varying structures to optimize their performance.

* Pygame: The simulation uses Pygame for creating a graphical interface, drawing the track, and displaying the cars.

## How to Run the Simulation
1. **Install Dependencies**: Install the required Python dependencies by running:

```bash
pip install -r requirements.txt
```
2. **Run the Simulation**: Execute the main file to start the simulation:

```bash
python main.py
```
3. **NEAT Configuration**: The NEAT configuration is specified in the config.txt file. This file defines parameters for neural network structure, mutation rates, and other evolutionary aspects.

4. **Simulation Control**: The cars are controlled by neural networks, and their goal is to maximize the distance traveled. The simulation runs for a set number of generations, and the cars evolve over time.

## NEAT Configuration (config.txt)
The `config.txt` file contains configuration parameters for the NEAT algorithm. Key settings include:

* **Node Activation Options**: Define options for node activation functions, mutation rates, and default values.

* **Genome Compatibility Options**: Tune parameters related to genome compatibility for species determination.

* **Connection Add/Remove Rates**: Control the probabilities of adding or removing connections.

* **Node Add/Remove Rates**: Specify probabilities for adding or removing nodes in the neural network.

* **Network Parameters**: Set the number of inputs, outputs, and hidden nodes in the neural network.

* **Connection Weight Options**: Configure parameters for connection weights, including initialization, mutation, and replacement rates.

## Project Structure
* **main.py**: The main file that initializes the NEAT algorithm, runs the simulation, and handles Pygame display.

* **car.py**: Defines the Car class, including methods for updating the car's position, handling collisions, and drawing on the screen.

* **config.txt**: Configuration file for the NEAT algorithm.

## Acknowledgments
* The code structure and NEAT implementation are adapted and optimized from the work of the YouTuber Cheesy AI and NeuralNine.

* The car simulation concept is inspired by the NEAT algorithm's ability to evolve neural networks for complex tasks.

#### Feel free to explore and modify the code to experiment with different parameters and enhance the simulation!
