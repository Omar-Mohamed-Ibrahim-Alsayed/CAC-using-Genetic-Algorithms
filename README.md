# Constant Area Coding (CAC) with Genetic Algorithm

## Project Overview
This project demonstrates the implementation of a sophisticated data encoding technique called Constant Area Coding (CAC) for image compression using a Genetic Algorithm. CAC is designed to ensure that encoded data occupies a constant area, enabling efficient and consistent storage space utilization, particularly useful in real-time applications requiring constant data flow.

Table of Contents
Introduction
Code Structure
How to Run
Results
License

## Table of Contents
1. [Introduction](#introduction)
    - [Constant Area Coding (CAC)](#Constant-Area-Coding-(CAC))
    - [Genetic Algorithm](#Genetic-Algorithm) 
2. [Code Structure](#Code-Structure)
    - [Main Components](#Main-Components)
    - [Genetic Algorithm Operations](#Genetic-Algorithm-Operations)
3. [Results](#Results)



## Introduction
### Constant Area Coding (CAC)
CAC is a data encoding method used primarily for image and video compression. It divides an image or video frame into uniformly sized parts and encodes each region to occupy the same predetermined area. This approach offers advantages such as simplified data management, reduced computational complexity, and predictable memory requirements.

### Genetic Algorithm
The Genetic Algorithm (GA) is employed to optimize the selection of kernel dimensions for encoding the image using CAC. The algorithm iterates through a series of steps to evolve the best possible solution for image compression.

## Code Structure
### Main Components
Fitness Function: Evaluates the suitability of different kernel dimensions for encoding an image.
Constant Area Coding: Applies the CAC method to an image, dividing it into blocks and encoding each block.

### Genetic Algorithm Operations:
Selection: Selects the most fit chromosomes for reproduction.
Crossover: Performs crossover between two parent chromosomes to generate offspring.
Mutation: Introduces random changes to a chromosome to maintain genetic diversity.
Utility Functions: Helper functions for decoding binary representations, concatenating chromosomes, and reconstructing the original image.


## Results
The algorithm evolves the population over several epochs, selecting the best kernel dimensions for image compression. The output includes the fitness values at each epoch and the final encoded and decoded image.
