# Wareef: AI-Driven Smart Greenhouse System

Wareef is an intelligent greenhouse management system that integrates Artificial Intelligence (AI) and Internet of Things (IoT) technologies to enable data-driven, efficient, and sustainable agriculture. The system is designed for precision strawberry cultivation in controlled greenhouse environments, with a focus on arid regions such as Saudi Arabia.

The platform combines real-time environmental sensing with machine learning models to support automated decision-making across irrigation, climate control, plant growth monitoring, and disease detection.

## System Overview

Wareef is designed as a modular system composed of multiple AI-driven components. Each module addresses a specific greenhouse function and can operate independently while contributing to the overall system.

Core functionalities include:
- Environmental monitoring using IoT sensors (temperature, humidity, soil moisture)
- Irrigation prediction and control based on environmental conditions
- Growth stage classification for plant development tracking
- Disease detection using image-based deep learning models
- Environmental control through ventilation and fog system regulation

## Repository Structure

The repository follows a modular design to support scalability and maintainability:

- modules/: Implementation of core AI components for greenhouse operations
- eda/: Data exploration, preprocessing, and baseline modeling
- models/: Trained models and model artifacts
- datasets/: Dataset descriptions and external data access instructions
- notebooks/: Experimental workflows and prototyping


## Methodology

The system follows a data-driven and modular approach:
- Sensor data is collected from greenhouse environments and preprocessed
- Exploratory data analysis is conducted to understand patterns and relationships
- Machine learning and deep learning models are developed for prediction and classification tasks
- Each module is validated independently and prepared for integration into a unified system

This approach moves beyond traditional threshold-based control by incorporating predictive models and adaptive decision-making.

## System Architecture

The Wareef system follows a layered architecture that integrates IoT data acquisition with AI-based decision-making:

1. Data Acquisition Layer  
   Environmental data is collected in real time using IoT sensors, including temperature, humidity, soil moisture, and light intensity. Actuator states (e.g., fog system, irrigation pumps) are also recorded.

2. Data Processing Layer  
   Raw sensor data is cleaned, structured, and transformed into meaningful features suitable for analysis and modeling.

3. AI Modeling Layer  
   Machine learning and deep learning models are applied to perform:
   - Irrigation prediction  
   - Growth stage classification  
   - Disease detection  
   - Environmental control decision support  

4. Application and Control Layer  
   Model outputs are used to support decision-making and control greenhouse actuators such as irrigation systems, ventilation, and fogging. A centralized dashboard enables monitoring and visualization.

## Datasets

The project utilizes multiple datasets:
- Strawberry Greenhouse Environmental Control Dataset (Zenodo)
- Strawberry Disease Detection Dataset (Kaggle)
- Strawberry Growth Stage Dataset (Kaggle)

Datasets are not redistributed in this repository and must be obtained from their original sources in accordance with their licenses.

## Results

The developed models demonstrate strong performance across tasks:
- Growth stage classification achieved up to 98% accuracy
- Disease detection achieved approximately 90.85% accuracy
- Predictive models improved decision-making for irrigation and environmental control

## Project Context

This project is developed as a senior graduation project and is aligned with sustainable agriculture initiatives and Saudi Arabia’s Vision 2030. It aims to provide a scalable and resource-efficient solution for greenhouse management in water-scarce environments.

## Notes

This repository contains research, experimentation, and system components developed during the project lifecycle. Some components are presented as prototypes and may require further optimization for full-scale deployment.
