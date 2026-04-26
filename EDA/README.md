# Exploratory Data Analysis and Preliminary Modeling

This directory contains exploratory data analysis (EDA) and initial modeling notebooks developed as part of the Wareef smart greenhouse project. The notebooks investigate multiple components of AI-driven greenhouse systems for strawberry cultivation, including environmental control, irrigation, plant growth, and disease detection.

Each notebook is self-contained and documents the dataset, preprocessing steps, exploratory analysis, and baseline modeling approach.

## Notebook Overview

### 1. Fog_Modeling.ipynb
**Dataset:** Strawberry Greenhouse Environmental Control Dataset (Zenodo)

Focuses on analyzing fog system activation in relation to environmental conditions such as temperature, humidity, and illumination.

**Key Objectives:**
- Examine fog actuator behavior
- Identify environmental triggers for activation
- Establish a baseline for data-driven fog control

---

### 2. Irrigation_EDA_and_Modeling.ipynb
**Dataset:** Strawberry Greenhouse Environmental Control Dataset (Zenodo)

Analyzes irrigation-related components including pumps, valves, and ground systems using time-series sensor data.

**Key Objectives:**
- Explore irrigation control dynamics
- Analyze actuator usage patterns
- Support development of predictive irrigation models

---

### 3. Growth_Stages_EDA_and_Modeling.ipynb
**Dataset:** Strawberry Growth Stage Dataset (Kaggle)

Explores plant growth stages through dataset inspection, class distribution analysis, and preliminary classification modeling.

**Key Objectives:**
- Analyze growth stage distributions
- Support growth-aware monitoring
- Provide contextual plant-state insights

---

### 4. Plant_Disease_EDA_and_Modeling.ipynb
**Dataset:** Strawberry Disease Detection Dataset (Kaggle)

Performs EDA on image-based disease data and develops baseline models for classification.

**Key Objectives:**
- Analyze class balance and visual features
- Build baseline disease detection models
- Support plant health monitoring integration

---

## Data Availability
- The Zenodo dataset is used for environmental control and irrigation analysis.
- Kaggle datasets (growth stages and disease detection) must be downloaded separately in accordance with their licenses.
- Instructions for dataset access are provided within the notebooks.

## Role in the Project

These notebooks serve as the foundation for:
- Data validation and understanding
- Feature and pattern discovery
- Justification of modeling approaches

The insights derived here directly inform subsequent model development and system integration within the Wareef platform.
