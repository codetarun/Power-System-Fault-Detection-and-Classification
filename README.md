# Power-System-Fault-Detection-and-Classification

This project involves building a machine learning model to detect and classify different types of faults in a power distribution system automatically. It uses real-time electrical parameters such as voltage, current, and phasors to distinguish between normal and faulty conditions.

## Problem Statement:
Design a machine learning model to detect and classify different types of faults in a power 
distribution system. Using electrical measurement data (e.g., voltage and current 
phasors), the model should be able to distinguish between normal operating conditions 
and various fault conditions (such as line-to-ground, line-to-line, or three-phase faults). 
The objective is to enable rapid and accurate fault identification, which is crucial for 
maintaining power grid stability and reliability. 

## Dataset
- Source: [Kaggle – Power System Faults Dataset], https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset

## ML Model
- Algorithm: Random Forest Classifier
- Data Preprocessing: Cleaned & structured electrical signals
- Accuracy: Evaluated on multiple fault classes

## Deployment
- Platform: IBM Watson Studio (AutoAI & custom notebook)
- Model hosted via Watson Machine Learning
- Output: Predicted fault type with class probability

## Technologies Used
- IBM Cloud Lite (Watson Studio, ML)

## Objective
Enable accurate and real-time classification of faults in power systems to improve grid monitoring, fault recovery, and operational efficiency.

---

**Note:** This project is part of the "IBM SkillsBuild - Edunet Foundation - AICTE Internship" using IBM Cloud services.
