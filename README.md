# 🚗 Dynamic Pricing for Urban Parking

Capstone project for Summer Analytics 2025 by Consulting & Analytics Club, IIT Guwahati.

## 📌 Overview

Urban parking is often underutilized or overcrowded due to static pricing. In this project, we built a real-time dynamic pricing engine for 14 parking lots using historical and live data, built entirely from scratch using Python, Pandas, Numpy, and Pathway.

## 💻 Tech Stack

- Python
- Pandas
- Numpy
- Pathway (Real-time streaming)
- Bokeh (Visualization)
- Google Colab / Kaggle
- GitHub

## 🧠 Architecture Diagram

```mermaid
flowchart TD
    A[dataset.csv] --> B[Pathway Stream Processor]
    B --> C[Feature Extraction]
    C --> D1[Model 1: Linear Pricing]
    C --> D2[Model 2: Demand-based Pricing]
    D1 --> E[Real-time Pricing Output]
    D2 --> E
    E --> F[Bokeh Visualization]
