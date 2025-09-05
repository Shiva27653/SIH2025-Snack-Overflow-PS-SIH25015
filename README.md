# SIH2025-Snack-Overflow-PS-SIH25015
# The Smart Spraying Pod: AI for Precision Agriculture

> ### Where Agriculture Meets Intelligence

## 🌱 Project Overview

For too long, farmers have been trapped in a cycle of **blanket spraying**—wasting chemicals, harming the environment, and still losing crops to disease. Our project, the **Smart Spraying Pod**, is an intelligent, portable system designed to end this inefficiency.

This repository contains the **AI and Machine Learning core** that powers the pod's intelligence.



---
## 🏛️ Solution Architecture

Our solution is a modular, three-stage pipeline that automates the entire process from visual inspection to treatment recommendation.

### **Stage 1: Real-Time Disease Detection**
-   **Technology:** YOLOv8 Object Detection
-   **Function:** The system uses a high-performance model to instantly identify and locate disease symptoms on plants from an image or video feed.

### **Stage 2: Infection Severity Analysis**
-   **Technology:** YOLOv8 Semantic Segmentation
-   **Function:** To provide a quantitative measure of infection, this stage uses a segmentation model to calculate the precise pixel ratio of diseased area to healthy leaf area, generating an **infection severity score**.

### **Stage 3: Automated Dosage Calculation**
-   **Technology:** XGBoost / Regression Models
-   **Function:** The decision-making core of our platform. A machine learning model takes the severity score, crop type, and growth stage as input to calculate the optimal, scientifically-backed pesticide dosage, minimizing chemical usage.

---
## 🚀 Prototype Status & Demonstration

This repository contains the working prototype for **Stage 1: Disease Detection** for which we are still collecting more datasets and find precise methods 

### **Getting Started**

1.  **Download the Dataset:**
    -   Our dataset is hosted on Google Drive. You can download it from the following link:
    -   [**Download Dataset Here**](https://drive.google.com/drive/folders/1BogtnOm1ljRBWuJqJ32nC4DsVWYyDwSn?usp=sharing)
    -   Place the dataset folder in the main directory of this project.

2.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Shiva27653/SIH2025-Snack-Overflow-PS-SIH25015.git](https://github.com/Shiva27653/SIH2025-Snack-Overflow-PS-SIH25015.git)
    cd SIH2025-Snack-Overflow-PS-SIH25015
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
