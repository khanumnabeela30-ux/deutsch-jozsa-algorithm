# 📌 Deutsch–Jozsa Quantum Algorithm (Qiskit Project)

This repository contains the implementation of the **Deutsch–Jozsa quantum algorithm** using **Qiskit**.  
It includes:

- Quantum circuit construction  
- Balanced-oracle implementation  
- Simulation on AerSimulator  
- Measurement results  
- Histogram matching the output used in the internship report  

---

## 🧠 About the Algorithm

The Deutsch–Jozsa algorithm determines whether a function is:

- **Constant** → always outputs the same value  
- **Balanced** → outputs 0 for half the inputs and 1 for the other half  

A classical computer may need multiple evaluations to determine this.  
A quantum computer solves it with **one single evaluation**, showing exponential speedup.

---

## ⚙️ Technologies Used

- Python 3.10  
- Qiskit (Latest 1.x compatible version)  
- Qiskit AerSimulator  
- Jupyter Notebook  
- Matplotlib (for circuit + histogram visualization)

---

## 🚀 How to Run This Project

### 1. Create a Python environment:
```bash
conda create -n qiskit_env python=3.10
conda activate qiskit_env
pip install qiskit qiskit-aer notebook matplotlib
jupyter notebook
deutsch_jozsa.ipynb
---

## 📊 Output Included in This Project

The notebook displays:

- ✔ The Deutsch–Jozsa quantum circuit
- ✔ The measured output for 1024 shots
- ✔ A histogram that matches the results used in the internship report
- ✔ Correct balanced-oracle behavior with quantum interference

---

## 📂 Project Structure

deutsch-jozsa-algorithm/
│
├── circuit.png                     
├── Histogram.png                   
├── histogram balanced.png          
│
├── deutsch_jozsa.ipynb             
├── README.md                       
└── requirements.txt

## 👩‍💻 Author

**Nabeela Khanum**  
Quantum Computing Internship Project  
Implemented using Qiskit (Python 3.7/3.10)

