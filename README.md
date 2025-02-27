# **LHE File Analysis**  

This repository contains a set of Jupyter notebooks for analyzing collision data at the parton level using `.LHE` files. The analysis focuses on the process:  

\[
pp \to t j a, \quad a \to \gamma \gamma
\]  

where **\( a \)** represents the axion, a hypothetical particle often considered in extensions of the Standard Model.  

## **Contents**  

The repository includes the following notebooks, each serving a specific purpose in the analysis pipeline:  

1. **`Parton.ipynb`**  
   - This notebook is designed for reading and analyzing `.LHE` (Les Houches Event) files.  
   - It extracts relevant kinematic information from collision events at the parton level.  
   - The data is processed for further analysis, such as invariant mass calculations, transverse momenta distributions, and angular correlations.  

2. **`Smearing.ipynb`**  
   - Implements a **jet smearing algorithm** to simulate detector resolution effects.  
   - Smearing accounts for experimental uncertainties in jet energy measurements.  
   - It refines the parton-level results to be more realistic in the context of detector simulations.  

3. **`root.ipynb`**  
   - Converts and analyzes data using **ROOT**, a high-energy physics data analysis framework.  
   - The notebook processes `.root` files generated from `.LHE` event data.  
   - It allows for visualization of histograms, distributions, and statistical analysis.  

4. **`Root_Analysis.ipynb`**  
   - A dedicated script for extracting and interpreting data from `root.ipynb`.  
   - Includes further post-processing of ROOT-generated datasets.  
   - Enables advanced data visualization and statistical fitting of the extracted results.  

## **Usage**  

- Ensure you have **Python 3**, `numpy`, `matplotlib`, and **ROOT** installed.  
- Open the notebooks in **Jupyter Notebook** or **Jupyter Lab** and execute them in sequence.  
- Modify parameters as needed to adapt the analysis to different datasets or conditions.  

## **Purpose**  

This analysis is useful for studying axion-like particles in high-energy proton-proton collisions, particularly in the context of beyond-Standard Model physics searches at colliders such as the **LHC**.  

