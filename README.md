# Python Crash Course for MSc Applied Mathematics

This repository contains materials for a **3-hour crash course in Python**, designed for new MSc students in Applied Mathematics (Imperial College London) in 2025.  
The course assumes mixed backgrounds: some students may be completely new to Python, while others already have programming experience. 

The goal is to get everyone comfortable with **core Python** and the **scientific Python ecosystem** (NumPy, Matplotlib), with direct links to applied mathematics problems. 
Additional notebooks on **SciPy**, **Pandas**, and further practice exercises are provided for self-study.

---

## Structure

The course is divided into two 3-hour sessions:

### Live Session (3h) — Core Python & Scientific Basics

- Python syntax, variables, data types  
- Control flow, functions, modules  
- NumPy arrays, vectorization, linear algebra  
- Random number generation & statistics  
- Plotting with Matplotlib  
- Exercises: factorial, dice simulation, linear systems, random sampling, histogram plotting  

📄 Notebook: [`PythonCrashCourse_Session.ipynb`](./PythonCrashCourse_Session.ipynb)

---

### Additional Materials — Self-Study

These notes expand on the live session, covering tools you will need throughout the MSc:

- SciPy: numerical integration, ODE solvers, optimisation  
- Pandas: tabular data, statistics, plots  
- Mini-projects:  
  - Monte Carlo estimation of $\pi$  
  - 1D Heat equation (finite difference)  

📄 Notebook: [`Additional_Materials.ipynb`](./Additional_Materials.ipynb)

---

### Extra Exercises — Optional Practice

For students who want to **go further** and explore additional Python features, an extra notebook is provided.  
These exercises are not required but strongly recommended to build fluency.

- List, dict, and set comprehensions  
- Handling and normalizing strings  
- Sets and membership performance  
- Using `enumerate` and `zip`  
- Generator expressions vs list comprehensions  
- f-strings vs `.format()`  
- Bonus `while` loop simulation  

📄 Notebook: [`Extra_Exercises.ipynb`](./Extra_Exercises.ipynb)

---

## 🛠️ Setup

You can run the notebooks in two ways:

1. **Google Colab (recommended for beginners)**  
   - Upload `.ipynb` file to [Google Colab](https://colab.research.google.com/)  
   - No installation required

2. **Local Jupyter installation**  
   ```bash
   pip install jupyter numpy scipy pandas matplotlib
   jupyter notebook
   ```

## 📚 References & Further Reading

* [Python Tutorial](https://docs.python.org/3/tutorial/)
* [NumPy Documentation](https://numpy.org/doc/stable/)
* [SciPy Reference](https://docs.scipy.org/doc/scipy/)
* [Pandas Documentation](https://pandas.pydata.org/docs/)
* [Matplotlib Gallery](https://matplotlib.org/stable/gallery/)
* [SciPy Lecture Notes](https://scipy-lectures.org/)

## ✨ Credits

Developed for the MSc Applied Mathematics induction at **Imperial College London**.
Inspired by [sarabicego/PyCrashCourse2024](https://github.com/sarabicego/PyCrashCourse2024).
