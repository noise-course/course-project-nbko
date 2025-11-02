# Project Title

## Project Participants

Format the following information in a markdown table:

- Naeun Ko
- nbko
- Individual Project

## Project Description

One paragraph description of your project. Summarize the following:

- Problem statement
- Why it is important problem
- How it relates to the theme of the course (e.g., what is the intersection
  with networking and ML?).
- Any related work you are aware of
- What is the goal? Research? Tech transfer? Reproducing a result?

I am performing a Multi-Class Classification task to automatically identify a device's Operating System (OS) by analyzing its network traffic patterns. I will use two different machine learning models, Random Forest and a Simple Neural Network (MLP), to classify 100-packet samples into one of 13 possible OS labels. My main goal is to reproduce the current best-known result on the nPrint leaderboard, and then slightly improve it through basic hyperparameter tuning.

## Data

What data will you need to complete this project?

- I will use the publicly available, pre-processed network traffic dataset linked on the nPrint benchmarks page for OS Detection.

- Dataset Name: nPrint OS Detection
- Data Source: Google Drive link provided on the nPrint Leaderboard page (https://nprint.github.io/benchmarks/os_detection/nprint_os_detection.html)
- Data State: The data is already converted into the nPrint feature representation, which is ready for machine learning model input. This skips the difficult step of raw packet parsing.
- Size: Under 1 GB, making it manageable for download and quick processing.
- Goal: Use the labeled training and testing data splits provided to train and evaluate our models.

## Deliverables

Detail what you intend to turn in for the final project. (Refer to the
documentation about the project to outline your deliverables.)

Problem Importance:

- OS detection from network traffic is a crucial task in cybersecurity and network management. Knowing a device's OS is the first step in identifying vulnerabilities or enforcing network policy.

Learning Objectives:

- Practical ML Workflow: How to run a complete, end-to-end machine learning pipeline on a real-world dataset.
- Model Comparison: How to implement and compare two different types of classifiers (tree-based vs. simple neural network).
- Network Features: What the nPrint representation is and which specific packet features (like TTL or window size) are most important for OS identification.

Goal:

- Reproduce the existing benchmark of around 77% Balanced Accuracy using a Random Forest model, and then try to achieve a higher score using an optimized model (MLP).

Next Step:

- Download and load the nprint os detection dataset this week to verify file access and start basic data exploration immediately.
