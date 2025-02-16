FINAL SOLUTION OF SATGE 1 # Project Overview

This project includes several functions that help with:

- Translating a DNA sequence into a protein sequence
- Simulating logistic population growth with random variations in growth phases
- Generating 100 different population growth curves
- Calculating the Hamming distance between two strings (e.g., usernames)

## Features

### 1. DNA to Protein Translation
This function takes a DNA sequence as input and translates it into a corresponding protein sequence . This task is crucial in understanding how genetic information is transcribed into proteins, which play essential roles in various biological processes. 

### 2. Logistic Growth Curve Simulation
The logistic growth simulation function models population growth that follows a logistic curve, with the added complexity of random variations in the lag and exponential phases. This model can be applied to various biological measurements such as:
Population size vs. time , Cell density vs. time  , Optical Density (OD) vs. time  ...

This simulation provides insight into how populations grow and stabilize over time, which is valuable for understanding biological trends.

### 3. Generating 100 Growth Curves
This feature uses the logistic growth model to generate 100 distinct growth curves. This dataset is helpful for performing further analysis on population dynamics, allowing researchers to examine different population behaviors under varying conditions.



### 4. Hamming Distance Calculation
The Hamming distance function computes the difference between two strings by comparing corresponding characters. This function is particularly useful for comparing sequences like usernames from different platforms (e.g., Slack and Twitter/X). If the strings are of different lengths, the function will pad them with extra characters to ensure a valid comparison.

## Requirements

This project is implemented in Python and uses the following libraries:

- numpy: For numerical calculations.
- pandas: For handling and analyzing data.
- matplotlib: For visualizing the generated growth curves
- 
  ## Author
  Fabuyi Favour
