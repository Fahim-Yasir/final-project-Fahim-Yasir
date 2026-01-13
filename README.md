# Machine Learning Solution for Network Security

This project applies various Machine Learning (ML) techniques to design an effective Threat Detection system for network security.

## Problem Statement

The increase in computer network usage has heightened the need for robust network security systems. Traditional security measures often fall short against sophisticated cyber threats. This project aims to develop an ML-based solution that can accurately and efficiently detect cyber-attacks by analyzing patterns in network traffic.

## Dataset

The dataset originates from the 1998 DARPA Intrusion Detection Evaluation Program by MIT Lincoln Labs, designed to simulate a typical U.S. Air Force LAN environment. It comprises 125,972 records and 41 features per record, processed from seven weeks of network traffic. This refined dataset eliminates redundancies, ensuring a comprehensive set of data for training the models.

## Result

The best model, an ensemble technique, achieved an AUROC of 0.96 on the test set, indicating high accuracy in distinguishing between normal connections and attacks. The dataset included unique attack types in the test set to evaluate the model’s performance under realistic conditions, demonstrating its effectiveness in identifying new and unseen threat patterns.

## Repository Contents

- Data Folder: Contains the training and testing datasets used in the models.
- Jupyter Notebook: Includes all the code for analysis and model development.
- Project Report: A detailed report that outlines the motivations, methods, results, and conclusions of the project.
- requirements.txt: Lists all the Python packages and their versions that are required to run the project notebook.
