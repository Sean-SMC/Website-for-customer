# Chroma Canvas User Manual

**Version**: 1.0  
**Date**: 10/31/2023

## Table of Contents
- [Introduction](#introduction)
- [Explaining the Experiment](#explaining-the-experiment)
- [Setting Up the Experiment](#setting-up-the-experiment)
- [Running the Experiment](#running-the-experiment)
- [Displaying Results](#displaying-results)
- [Creating Graphs](#creating-graphs)
- [Continuing or Starting Anew](#continuing-or-starting-anew)

## Introduction
Welcome to **Chroma Canvas**, a fun and educational website that allows you to experiment with colors and explore the effects of mixing different paint drops on a grid canvas. This user manual will guide you through the website's features and help you make the most of your experiments.

## Explaining the Experiment
Chroma Canvas is designed to simulate the random painting of a grid canvas using various colors. The experiment involves selecting parameters and running simulations to observe the effects of mixing paint drops. Key terms you'll encounter:
- **Independent Variable**: The factor you choose to vary in the experiment.
- **Dependent Variables**: The results you observe, which are based on the independent variable(s).

## Setting Up the Experiment
Before you start the experiment, you'll need to set up the input settings:
- **Grid Size (X, Y)**: Determine the dimensions of the grid canvas.
- **Colors (C1, C2, C3)**: Choose three colors from a set of eight options.
- **Stopping Criteria (S)**: Select one of three stopping criteria:
  1. Every square is full.
  2. A single square was double dripped on.
  3. `(2 x grid size)` color drops have fallen.
- **Number of Repetitions (R)**: Define how many times the experiment will be repeated.

Ensure that appropriate values are input. If an error occurs, a descriptive error message will guide you. For limits and justifications, refer to the documentation.

## Running the Experiment
Follow these steps to run the experiment:
1. Select one of the independent variables:
   - Single dimension for both x and y axis
   - X dimension
   - Number of Repetitions
2. Provide a list of increasing values for the chosen independent variable.
3. Set values for the remaining variables according to your choice.
4. Click **"Paint"**.

The website will simulate painting on the grid according to your parameters. The progress will be displayed to assure you that the computations are ongoing.

## Displaying Results
Once the simulations are complete, a table of results will be presented. The table includes the independent variable, fixed values, and calculated values (`A`, `A1`, `A2`, `A3`, `B`, and `C`). Use this data to analyze the outcomes:
- **A**: The number of paint drops put on the canvas before the painting halts.
- **A1**: The number of paint drops on the canvas for Color 1.
- **A2**: The number of paint drops on the canvas for Color 2.
- **A3**: The number of paint drops on the canvas for Color 3.
- **B**: The maximum number of paint drops on any given square when the painting halts.
- **C**: The average number of paint drops over all the squares when the painting halts.

## Creating Graphs
You can visualize the data by selecting one or two dependent variables from the following options:
- Total # of paint drops put on the canvas before the painting halts.
- The number of paint drops on the canvas for Color 1.
- The number of paint drops on the canvas for Color 2.
- The number of paint drops on the canvas for Color 3.
- The maximum # of paint drops on any given square when the painting halts.
- The average # of paint drops over all the squares when the painting halts.

Click **"Continue"** to display a graph with the independent variable on the horizontal axis and the selected dependent variable(s) on the vertical axis. Customize the graph as needed.

## Continuing or Starting Anew
After viewing the graph, you have three options:
1. Make a new table/graph from the current data.
2. Abandon the current experiment and start a new one.
3. Quit the program.

Choose the desired option, and the website will respond accordingly.
