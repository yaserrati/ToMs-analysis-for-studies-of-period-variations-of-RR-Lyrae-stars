# Hands-On Analysis of Period Variations in RR Lyrae Stars  

This repository contains a comprehensive analysis of period variations in RR Lyrae stars using data from the [GEOS RR Lyrae database](http://rr-lyr.irap.omp.eu/dbrr/). The project is aimed at exploring and analyzing period changes, creating custom models, and visualizing data to understand these fascinating variable stars.

---

## **Features**
- Manipulation of the GEOS RR Lyrae web interface.
- Analysis of period variations for stars like SW Aqr, RR Lyr, UU Boo, and TU UMa.
- Python scripts for:
  - Linear fitting of O-C diagrams.
  - Quadratic fitting of period variations.
  - Visualization of period evolution over time.
  - Modeling binary star systems using light-time effect equations.
- Data cleaning techniques for extracting meaningful insights from downloaded datasets.

---

## **Getting Started**

### **Prerequisites**
- Python 3.6 or higher
- Libraries: `numpy`, `matplotlib`, `scipy`
- A Linux or compatible operating system for using `awk` and command-line tools.

---

### **Setup Instructions**
1. Clone this repository:
   ```bash
   https://github.com/yaserrati/ToMs-analysis-for-studies-of-period-variations-of-RR-Lyrae-stars
   ```
2. Navigate to the project directory:
   ```bash
   cd rr-lyrae-analysis
   ```
3. Install the required Python libraries:
   ```bash
   pip install pandas numpy matplotlib
   ```

---

## **Project Structure**

- **`SW_Aqr-period.ipynb`**: Script for linear fitting and deducing new elements for SW Aqr.
- **`fit_RR_Lyr.ipynb`**: Script for fitting RR Lyr period changes year by year.
- **`fit2.py`**: Script for quadratic fitting of O-C diagrams.
- **`pltPer.py`**: Script for plotting period variations over time.
- **`data/`**: Directory containing cleaned datasets.
- **`notebooks/`**: Jupyter notebooks for interactive analysis.

---

## **How to Use**
### **1. Analyze SW Aqr**
- Use the `SW_Aqr-period.py` script to analyze period variations of SW Aqr.
- Edit the script to match your input data file.
- Run the script:
  ```bash
  python SW_Aqr-period.py
  ```

### **2. Analyze RR Lyr**
- Use `fit_RR_Lyr.py` to analyze year-by-year period changes for RR Lyr.
- Extract the data for each year and run the script for each file.

### **3. Quadratic Fitting**
- Use `fit2.py` to fit quadratic elements for stars like UU Boo or AA Aql.

### **4. Modeling TU UMa**
- Run the custom Python script for modeling the O-C diagram and time delays for TU UMa as a binary system.

---

## **Contributing**
Contributions are welcome! Feel free to fork the repository and submit a pull request.  

---

## **Acknowledgments**
- GEOS RR Lyrae database for providing data and tools for analysis.
- "Le Borgne et al., 2014, MNRAS, 441, 1435" for foundational methodologies.
```

