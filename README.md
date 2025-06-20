# PPMT Automated Pressuremeter Load–Settlement Analysis (Briaud, 2007)

This repository provides a fully automated Python-based framework for predicting the load–settlement behavior of shallow foundations using PENCEL pressuremeter test data, following Briaud (2007).

---

## Overview

This tool processes in-situ pressuremeter data to:

- Identify the wall contact point using two-line intersection logic  
- Shift and normalize strain–pressure curves  
- Apply Lemée-type extrapolation to reach strain = 0.414  
- Extract pressures at specified strain levels  
- Calculate strain influence areas (based on Schmertmann-style framework)  
- Compute weighted average pressures  
- Apply footing correction factors (rigidity, eccentricity, slope, etc.)  
- Generate final load–settlement curves  

---

## Repository Structure

PPMT-Automated-pressuremeter-load-settlement/
│
├── Code/ # Python or Jupyter notebook source code
├── Data/ # Raw pressuremeter test data (Excel)
├── Outputs/ # Plots and tables (load–settlement, pressure–strain, etc.)
├── LICENSE # MIT License
└── README.md # This file

---

## How to Run

1. Clone or download the repository  
2. Open the script or notebook in Jupyter or VSCode  
3. Provide the following inputs when prompted:
   - Footing geometry  
   - Applied load  
   - Soil unit weight  
   - Path to Excel data file  
4. Run the code to generate:
   - Load–settlement curves  
   - Weighted average pressure tables  
   - High-resolution figures and Excel exports  

---

## Example Outputs

- Pressure vs. strain curves (with wall point and extrapolation)  
- Strain influence profile vs. depth  
- Pressuremeter to foundation pressure ratio (Γ vs. strain)  
- Final Load–Settlement plot  

All outputs are saved in the `Outputs/` directory.

---

## Citation

If you use this tool or data in your research, please cite:

> Ygzaw, B. W. (2025). *Automated Settlement Prediction from Pressuremeter Data Using Briaud’s Method: A Python-Based Framework*. GitHub Repository.

---

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code with attribution.

---

## Contact

**Brhane W. Ygzaw**  
Doctoral Researcher, Florida Institute of Technology  
Email: brhane.ygzaw@mu.edu.et  
GitHub: [github.com/BrhaneWYgzaw](https://github.com/BrhaneWYgzaw)

---

## Coming Soon

- CPT and DMT settlement modules  
- Streamlit-based GUI  
- DOI via Zenodo or ResearchGate
