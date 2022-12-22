# Project: Intentional chatting

## Overview

This repository contains the code base of the *Intentional chatting* project for the *Communicative Robots* Course at
the Vrije Universiteit (VU), Amsterdam.

In this repository, we represent dialogue as knowledge graphs and use these representations to create artificial
conversational agents that display specific intentions in their behaviour. For a detailed description of this project,
please see [this document](https://docs.google.com/document/d/1yAyJhZL9LMWbPoVhh-0CUIGN1dSUXEOJFJI2RPdDU68/edit#). In
brief, the methods proposed include:

| Method        | Description | By |
|---------------|-------------|----|
| TBD | In this approach, ... | Student 1 |

The implementations, and instructions of how to run them, can be found in their respective folders.

## Prerequisites

1. An x86 machine running Windows 10 or a Unix-based OS
1. Python 3.7 or higher. Running in a virtual environment (e.g., conda, virtualenv, etc.) is highly recommended.
1. `pip install -r requirements.txt`

### Installation consiiderations

1. Remember that you have to manually clone and install the following libraries: `cltl-knowledgeextraction`
   , `cltl-knowledgelinking`, `cltl-knowledrepresentation`, `cltl-combot`, `cltl-evaluating-conversation-as-ekg`
2. Download the classifier
   from [here](https://drive.google.com/u/0/uc?id=1-33rHc9O2fM-PPaXu8I_oK5xnFwuMlN7&export=download&confirm=9iBg) and
   save it in the `midas-da-roberta` folder.

## Evaluation

TBD

### graph to metric evaluation
To generate metrics from graph, please run the file `graph2metric.ipynb`
1. the code will change the directory of the scenarios folder for the library to iterate over all graphs for evaluations via graph_evaluation in library `cltl-evaluating-conversation-as-ekg`
2. the code will iterate all trig files in each scenario and generate a CSV file called `graph_evaluation.csv` in a file call `evaluation` in each scenario folder, and plots the metrics in `plots` in the main scenarios folder.

## Authors

Supervisor: Selene Baez Santamaria

- Student 1: Bas Diender
- Student 2:
- Student 3: Alice X.S. Ye 
- Student 4:
- Student 5:

TO DO:

- check the datasets for unicode characters
- optional - why is not everything good in the hood 
