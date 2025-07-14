# Bachelor Thesis 

This repository contains the official implementation of the Bachelor Thesis submitted by **Klaudia Tamburi** to the **Faculty of Architecture and Engineering at Epoka University** supervised by **Prof. Dr. Bekir Karlik**.

**Thesis Title**:  
**Artificial Intelligence Based Logistics Optimization Model to Increase Branch-Based Sales and Stock Harmony**

**Submitted**: June 2025  
**University**: Epoka University

---

> **Note**: This version reflects the initial implementation submitted as part of the thesis defense. Ongoing improvements and refinements are planned for future versions.

---

## Abstract

Traditional supply chain management faces significant challenges including inaccurate
demand forecasting, inefficient stock distribution, and high transportation costs, leading
to costly outcomes such as overstocking, stockouts, and increased operational expenses.
This study presents an integrated artificial intelligence-driven approach for optimizing
logistics operations to maximize branch-based sales and achieve stock harmony across
multi-location retail networks.
The methodology employs a comprehensive four-stage framework combining advanced
machine learning techniques with mathematical optimization. The main task of this
study was using a Long Short-Term Memory (LSTM) neural network to forecast
regional demand for 33 product families using historical sales data from Corporación
Favorita, Ecuador. The second important step was to focus on the optimization layer
which is divided in two parts: Firstly, Mixed Integer Linear Programming (MILP) for
optimizing product distribution considering capacity constraints and differentiated
3delivery frequencies based on product perishability and secondly, Google OR-Tools for
solving the Vehicle Routing Problem to minimize transportation costs while ensuring
efficient delivery routes. And finally, comprehensive sales performance analysis was
conducted to evaluate key performance indicators (KPIs) including sales volatility,
growth patterns, and store-level efficiency metrics to validate forecasting accuracy and
identify operational improvement opportunities.
This integrated approach demonstrates the potential of AI-powered supply chain
optimization to address complex logistics challenges while providing actionable insights
for strategic decision-making in retail operations.
 
### For more details you can read the full thesis documentaion [Artificial Intelligence Based Logistics Optimization Model to Increase Branch-Based Sales and Stock Harmony] (./Thesis_Klaudia_Tamburi_SWEIIIB.pdf)

---

## Repository Structure

├── [Codes] (./Codes) : folder with all available Jupyter notebooks with the codes for this project.
├── [Original Dataset] (./Original%20Dataset) : folder with the file link to download the original dataset.
├── [Processed Dataset] (./Processed%20Dataset) : folder with the processed/modified dataset output from the codes.
├── [Interactive_Maps_Optimization_Layer_Output] (./Interactive_Maps_Optimization_Layer_Output) : folder with the interactive maps with the product distribution plans.
└── [Thesis_Klaudia_Tamburi_SWEIIIB.pdf] (./Thesis_Klaudia_Tamburi_SWEIIIB.pdf) : graduation project documentation.

---

## How to Run the Project

### Step 1: Download the Dataset
You can find the link of the original dataset in [here](./Original%20Dataset/link_to_original_dataset.txt).

### Step 2: Upload Dataset and Jupyter Notebooks to Google Colab or Azure Machine Learning
This project supports running the notebooks on either Google Colab or Azure Machine Learning platforms since both platforms were utilized during this project. You can upload the dataset and notebooks to either service to run the code in the cloud. Alternatively, you may run the notebooks locally on your machine—just ensure all required libraries are properly installed and your CPU and GPU can handle the data processing and models running.

### Step 3: Run The Codes
Make sure to run the notebooks in order as numbered.
