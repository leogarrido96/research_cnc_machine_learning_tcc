# Smart Data Collection for Brownfield CNC Milling Machines

  

## 📌 Overview

  
This project is part of a final undergraduate thesis (TCC) for the Mechanical Engineering program at the Federal University of Bahia (UFBA). It provides a benchmark dataset and architecture for real-world machine learning (ML) applications in the context of brownfield CNC milling machines. Data has been collected over two years from three different machines operating in an industrial environment. The system demonstrates how an edge-to-cloud setup can enable scalable, annotated, and reliable data acquisition for predictive maintenance and anomaly detection in manufacturing.


---

  
## 📁 Project Structure


```
smart-cnc-data/
│
├── data/ # 
│ ├── raw/ # Original dataset, sample dataset and notebook with data processing (reduction, verification and saving)
│ ├── processed/ # Cleaned and transformed data 
│
├── notebooks/ # Notebook with EDA
├── models/ machine learning models
│
├── requirements.txt # Python dependencies
│
├── requirements.txt # Python dependencies
│
└── README.md # Project documentation
```


___


## 📊 Dataset Description

  
- **Machines:** M01, M02, M03  
- **Time Period:** October 2018 – August 2021  
- **Tool Operations:** 15 unique operations (e.g., Step Drill, T-Slot Cutter)  
- **Labels:**
  - `0` — Healthy process
  - `1` — Faulty process (e.g., tool breakage, chip jam, misalignment)
  

---


## 🛠️ Installation


```
bash

git clone https://github.com/yourusername/smart-cnc-data.git

cd smart-cnc-data

pip install -r requirements.txt
```  


---


## 📈 Evaluation


Metrics used:
- Accuracy
- Precision / Recall
- F1-Score
- ROC Curve
- Confusion Matrix


---


## 👨‍🔬 Authors

### Dataset
- Mohamed-Ali Tnani, Bosch Rexroth AG  
- Michael Feil, Technical University of Munich  
- Klaus Diepold, Technical University of Munich  

### Machine Learning Project
 - Leonardo Garrido
---