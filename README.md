# OpenBMI_EEG_Analysis
An ongoing project exploring EEG data for a P300-based brain-computer interface.

## Overview

This notebook loads and visualises OpenBMI ERP/P300 speller data. It compares average target and non-target responses at the Cz and Oz electrode channels using subject 1, session 1.

## Work completed

- Downloaded the dataset file and checked its SHA-256 checksum.
- Loaded the MATLAB data using SciPy.
- Inspected the data structure and array dimensions.
- Plotted average target and non-target ERP responses at Cz and Oz.

## Current status

This repository contains the initial data inspection and visualisation stage. Classification and model evaluation are not included in the current notebook.

## Running the notebook

Open open_BMI_file_check.ipynb in Google Colab and run the cells in order. The data download is included in the notebook, so an internet connection is required.

## Dataset

OpenBMI dataset, available through GigaDB:
https://gigadb.org/dataset/100542
