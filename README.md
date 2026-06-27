# ML-Micromilling-UI

Machine learning–guided user interface for predicting surface roughness, friction factor, and pressure drop in micromilled PMMA microfluidics.

---

## ✨ Features
- Predicts **surface roughness (Ra)** from CNC micromilling parameters.  
- Estimates **friction factor** using polynomial regression and empirical models.  
- Calculates **pressure drop** via Darcy–Weisbach formulation.  
- Interactive **Dash web application** for easy user input and results visualisation.  

---

## 📂 Repository Structure
```

ML-Micromilling-UI/
│
├── LICENSE                  # MIT license
├── README.md                # Project documentation
├── requirements.txt         # Dependencies
├── MLmicromilling\_User\_interface\_for\_Github.ipynb  # Notebook version of the UI


````

---

## 🔧 Installation
Clone the repository:
```bash
git clone https://github.com/realalinorouzi/ML-Micromilling-UI.git
cd ML-Micromilling-UI
````

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the Dash user interface:

```bash
python src/app.py
```

Or open the notebook directly:

```bash
jupyter notebook MLmicromilling_User_interface_for_Github.ipynb
```

---

## 📊 Data & Models

* **Surface roughness dataset**: 264 instances with 8 milling parameters.
* **Friction factor dataset**: 84 instances digitized from literature.
* Pre-trained ML models include **Linear Regression, SVR, GBR, and Polynomial Regression** (see manuscript for details and data).

---

## 📖 Citation

If you use this repository, please cite our manuscript:

> Norouzi, A., et al.
> *Machine Learning-Assisted Optimization of CNC-Micromilled PMMA Microchannels for Predictable Hydraulic Performance and Low Protein Fouling Resistance*. (2026).
DOI: https://doi.org/10.1016/j.biosx.2026.100781
---

## 📜 License

This project is licensed under the **MIT License**.

