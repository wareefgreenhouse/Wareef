# Wareef Modules

This directory contains the core functional modules of the Wareef system. Each module is designed to handle a specific task within the smart greenhouse pipeline, combining AI models with sensor-driven inputs to support automated decision-making.

The modules are developed as independent components to ensure modularity, scalability, and ease of integration into the overall system.

## Modules Overview

- disease-detection: Deep learning models for identifying and classifying strawberry diseases from image data.
- irrigation-prediction: Predictive models for optimizing irrigation based on environmental and soil conditions.
- growth-classification: Models for classifying plant growth stages to support monitoring and planning.
- environment-control: Decision models for controlling greenhouse actuators such as ventilation, fogging, and lighting.

## Design Principles

- Modularity: Each module can be developed, tested, and deployed independently.
- Scalability: Modules are structured to support future expansion and additional functionalities.
- Integration: All modules are designed to interface with IoT sensor data and a centralized system dashboard.
- Data-driven: Decisions are based on real-time inputs and trained machine learning models.

## Purpose

The modules collectively enable intelligent monitoring, analysis, and control within the Wareef smart greenhouse system, supporting efficient and sustainable agricultural practices.
