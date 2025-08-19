# Python Crash Course for MSc Applied Mathematics

This repository contains materials for a **6-hour crash course in Python**, designed for new MSc students in Applied Mathematics (Imperial College London) in 2025.  
The course assumes mixed backgrounds: some students may be completely new to Python, while others already have programming experience. 

The aim is to get everyone comfortable with **core Python** and the **scientific Python ecosystem** (NumPy, SciPy, Pandas, Matplotlib), with direct links to **applied mathematics** problems.

---

## Structure

The course is divided into two 3-hour sessions:

### Session 1 — Core Python & Scientific Basics

- Python syntax, variables, data types
- Control flow, functions, modules
- NumPy arrays, vectorization, linear algebra
- Random number generation & statistics
- Plotting with Matplotlib
- Exercises: factorial, dice simulation, linear systems, random sampling

📄 Notebook: [`PythonCrashCourse_Session1.ipynb`](./PythonCrashCourse_Session1.ipynb)

---

### Session 2 — Python for Applied Mathematics

- Recap quiz
- SciPy: numerical integration, ODE solvers, optimization
- Pandas: tabular data, statistics, plots
- Object-oriented programming (OOP) for structuring solvers and models
- Mini-projects:
  - Monte Carlo estimation of $\pi$
  - 1D Heat equation (finite difference)
- Exercises: Gaussian integral, logistic growth, rolling mean, stability in PDE scheme

📄 Notebook: [`PythonCrashCourse_Session2.ipynb`](./PythonCrashCourse_Session2.ipynb)

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
