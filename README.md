## Exploratory Data Analysis & Modeling (EDA)

This folder contains exploratory data analysis (EDA) and preliminary modeling notebooks
developed as part of the senior project on **AI-driven smart greenhouse systems for strawberry cultivation**.

The notebooks cover multiple, complementary aspects of smart agriculture, including
environmental control, irrigation, plant growth stages, and plant disease detection.
Each notebook is self-contained and documents the dataset, analysis steps, and modeling
approach used.

---

## Notebook Overview

### 1. `Fog_Modeling.ipynb`
**Dataset:**  
- Strawberry Greenhouse Environmental Control Dataset (Zenodo)

**Description:**  
This notebook focuses on exploratory analysis and modeling of **fog system control**
within a greenhouse environment. It analyzes environmental sensor data (e.g., temperature,
humidity, illumination) and actuator states to understand fog activation patterns and
their relationship to greenhouse climate conditions.

**Purpose:**  
- Analyze fog actuator behavior  
- Identify environmental conditions associated with fog activation  
- Establish a baseline for data-driven fog control modeling  

---

### 2. `Irrigation_EDA_and_Modeling.ipynb`
**Dataset:**  
- Strawberry Greenhouse Environmental Control Dataset (Zenodo)

**Description:**  
This notebook performs EDA and modeling related to **irrigation and ground-level control**,
including pumps and valves. It examines temporal patterns, sensor–actuator relationships,
and control-relevant variables such as solution temperature, conductivity, and acidity.

**Purpose:**  
- Understand irrigation control dynamics  
- Analyze actuator usage patterns (pumps, valves, ground systems)  
- Support the development of data-driven irrigation control models  

---

### 3. `Growth_Stages_EDA_and_Modeling.ipynb`
**Dataset:**  
- Strawberry Growth Stage Dataset (Kaggle)

**Description:**  
This notebook explores strawberry plant **growth stages** using visual and/or tabular data.
It includes dataset inspection, class distribution analysis, and preliminary modeling to
identify or classify different growth stages.

**Purpose:**  
- Analyze growth-stage data characteristics  
- Support growth-aware decision-making in smart farming systems  
- Provide contextual plant-state information complementary to environmental control  

---

### 4. `Plant_Disease_EDA_and_Modeling.ipynb`
**Dataset:**  
- Strawberry Disease Detection Dataset (Kaggle)

**Description:**  
This notebook focuses on **plant disease analysis and detection**, performing EDA on
image-based strawberry disease data and developing baseline models for disease
classification.

**Purpose:**  
- Analyze class balance and visual characteristics of strawberry diseases  
- Establish baseline disease detection models  
- Support integration of plant health monitoring into the smart greenhouse pipeline  

---

## Notes on Data Availability

- The **Zenodo greenhouse dataset** is used for fog and irrigation analyses and includes
  environmental sensor readings and actuator control signals.
- The **Kaggle datasets** used for growth stages and disease detection are not redistributed
  in this repository and must be downloaded separately in accordance with their respective
  licenses.
- Where applicable, notebooks include instructions or references for obtaining the datasets.

---

## Role in the Overall Project

These EDA notebooks provide:
- Data integrity verification and domain-aware exploratory analysis  
- Justification for modeling choices used in later stages of the project  
- Foundational insights supporting the development of intelligent, data-driven
  greenhouse control and monitoring systems  

The analyses here directly inform subsequent modeling, evaluation, and deployment phases
of the senior project.
