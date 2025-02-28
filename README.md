# Energy Meter Machine Learning Project

## 📌 Project Overview
This project focuses on training and evaluating various Machine Learning models for predicting energy consumption using an energy meter dataset. The repository contains scripts and notebooks for data preprocessing, model training, evaluation, and final model saving.

## 📂 Directory Structure
```
├── sami-codeai-energy_meter/
    ├── Energy Meter.csv                        # Dataset containing energy meter readings
    ├── EvaluatingVariousMLModelforEnergyMeter.ipynb  # Notebook for evaluating ML models
    ├── EvaluatingVariousMLModelforEnergyMeter.py     # Script for evaluating ML models
    ├── Training&TestingMLAlgorithmForEnergyMeter.ipynb # Notebook for training and testing ML models
    ├── Training&TestingMLAlgorithmForEnergyMeter.py    # Script for training and testing ML models
    ├── Untitled.ipynb                           # Unnamed notebook (may need review)
    ├── finalized_model.pkl                      # Finalized trained model
    ├── model.pkl                                # Intermediate trained model
```

## 🚀 Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/SAMI-CODEAI/sami-codeai-energy_meter.git
   ```
2. Navigate to the project directory:
   ```bash
   cd sami-codeai-energy_meter
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 📊 Dataset
The dataset (`Energy Meter.csv`) consists of energy consumption readings, which are used to train and evaluate various ML models.

## 🛠 Usage
### Training and Testing Models
- Use `Training&TestingMLAlgorithmForEnergyMeter.ipynb` or `Training&TestingMLAlgorithmForEnergyMeter.py` to train and test machine learning models.

### Evaluating Models
- Use `EvaluatingVariousMLModelforEnergyMeter.ipynb` or `EvaluatingVariousMLModelforEnergyMeter.py` to compare different models and analyze their performance.

### Loading a Trained Model
- The `finalized_model.pkl` file contains the trained model, which can be loaded using:
   ```python
   import pickle
   with open('finalized_model.pkl', 'rb') as file:
       model = pickle.load(file)
   ```



