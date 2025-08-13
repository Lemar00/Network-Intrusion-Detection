# Network Intrusion Detection

## Context

Computer networks are exposed to numerous threats such as intrusion attacks, which can compromise data security and confidentiality. Rapid and reliable detection of these intrusions is crucial to protect infrastructures and users.

## Problem Statement

Continuous monitoring of network traffic generates large volumes of data. Analyzing all this data in real time to detect attacks is challenging because it requires significant computational resources. Therefore, it is essential to develop methods capable of efficiently identifying suspicious behaviors without overloading monitoring systems.

## Our Approach

We propose a machine learning-based method to automatically detect intrusions in network traffic. We use the UNSW-NB15 dataset, which contains examples of both normal and malicious traffic, to train a supervised model.

The chosen model is a **Random Forest**, known for its classification efficiency. This model learns to distinguish normal traffic from attack traffic by analyzing multiple features of the network flows.

This approach allows for quick alerts on abnormal behaviors, facilitating security decision-making while optimizing resource usage.

## Features

- Data loading and preprocessing  
- Training of a Random Forest model  
- Performance evaluation with detailed metrics (classification report, ROC curve)  
- Analysis of the most influential variables for detection  

## Usage

To use this project, simply run the provided Jupyter notebook which guides you through all analysis steps.
