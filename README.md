# Fatigue and Depression Predictive Analysis

![Project Banner](https://via.placeholder.com/1200x300.png?text=Fatigue+and+Depression+Analysis)

## Overview

This project focuses on predictive analysis of fatigue and depression using a dataset that includes various health-related features such as sleep quality, brain fog level, physical pain score, and depression PHQ-9 scores. The goal is to build a machine learning model to predict the **Fatigue Severity Scale Score** and gain insights into the relationships between these features and fatigue/depression diagnoses.

The project is implemented in Python using a Jupyter Notebook, leveraging libraries like `pandas`, `scikit-learn`, `seaborn`, `matplotlib`, and `plotly` for data processing, visualization, and modeling.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset (`me_cfs_vs_depression_dataset.csv`) contains 1000 records with 16 features, including:
- **Numerical Features**: `age`, `sleep_quality_index`, `brain_fog_level`, `physical_pain_score`, `stress_level`, `depression_phq9_score`, `fatigue_severity_scale_score`, `pem_duration_hours`, `hours_of_sleep_per_night`
- **Categorical Features**: `gender`, `pem_present`, `work_status`, `social_activity_level`, `exercise_frequency`, `meditation_or_mindfulness`, `diagnosis`

The target variable is `fatigue_severity_scale_score`, which we aim to predict using a Random Forest Regressor.

## Installation

To run this project, ensure you have Python 3.12+ installed. Follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/sahil007707/fatigue-depression-analysis.git
   cd fatigue-depression-analysis
