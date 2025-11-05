# Readmission Prediction Project

## Project Description
This is a **Machine Learning project** aimed at predicting whether a patient will be readmitted to the hospital within 30 days of a previous encounter. Accurate predictions can help optimize healthcare resources and improve patient outcomes.

The project workflow is divided into the following steps:

1. **Data Load** – Load patient data from available sources.  
2. **Data Preprocessing** – Clean and prepare the data for modeling.  
3. **Data Evaluation** – Explore and analyze data to identify patterns and issues.  
4. **Data Splitting** – Split data into training and testing sets.  
5. **Model Training** – Train models using four different machine learning algorithms.  
6. **Model Evaluation** – Evaluate model performance using relevant metrics.

The project is implemented in Python using popular libraries such as `pandas`, `numpy`, `scikit-learn`, `matplotlib`, and `seaborn`.

---

## How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/Alany10/Readmission.git
cd Readmission
```


### 2. Create and Activate the Conda Environment

If you already have the environment `readmission_env`, activate it:

```bash
conda activate readmission_env
```

If you need to create it from scratch:

```bash
conda create -n readmission_env python=3.9
conda activate readmission_env
```


### 3. Install Required Packages

Install the necessary Python libraries:

**Using Conda:**
```bash
conda install numpy=2.0.2 pandas=2.2.3 matplotlib=3.9.2 seaborn=0.13.2 scikit-learn=1.6.1 jupyter notebook ipykernel
```


**Using pip:**

```bash
pip install numpy==2.0.2 pandas==2.2.3 matplotlib==3.9.2 seaborn==0.13.2 scikit-learn==1.6.1 jupyter ipykernel
```

**Note:** The versions match the ones used in the environment for full compatibility.

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

This will open Jupyter in your default web browser. Navigate to the `.ipynb` file and open it.

### 5. Run the Notebook

Execute the notebook cells sequentially from top to bottom.  
The notebook covers the full workflow from data loading to model evaluation.

---

### Running in VSCode

1. Install the **Python extension** and the **Jupyter extension** in VSCode.  
2. Set the Python interpreter to the `readmission_env` environment.  
3. Open the `.ipynb` file and run cells directly in VSCode.

---

### Environment Details

- **Python:** 3.9.21  
- **Key Packages:**  
  - numpy 2.0.2  
  - pandas 2.2.3  
  - matplotlib 3.9.2  
  - seaborn 0.13.2  
  - scikit-learn 1.6.1  
  - jupyter 1.1.1  

> For a full list of packages and versions, see the output of `conda list` in `readmission_env`.

---

### Notes

- Make sure the environment is activated before running the notebook.  
- Run the notebook sequentially to ensure all data transformations and model evaluations execute correctly.



For more documentation of the initial data, visit this link:  
https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008
