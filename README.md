# R-Modeling-for-Enhanced-Pharmacokinetics
This project, driven by R modeling, dissects drug metabolism dynamics to refine delivery strategies. It unveils the intricate relationship between administration methods and metabolic pathways, offering concise insights for tailored treatments and patient safety
# Drugs in the Body

## Project 2

**MATH 3MB3 - Introduction to Modelling**  
**Anum Amin**,
**Ahraz Kibria**,
**Avan Mamende**
**April 19, 2024**

---

### Table of Contents

1. [Introduction](#introduction)
2. [Model](#model)
   - [Base Model](#base-model)
   - [Analysis of Base Model](#analysis-of-base-model)
   - [Model Extension](#model-extension)
3. [Results](#results)
4. [Discussion](#discussion)
5. [References](#references)
6. [Appendix A: R Code](#appendix-a--r-code)

---

### 1. Introduction <a name="introduction"></a>

The administration and metabolism of drugs within the human body plays a vital role in the medical and pharmacological domain, emphasizing the importance of patient well-being. This report delves into the intricate interplay between drug delivery techniques and metabolic processes, aiming to understand their combined effects on a patient's dosage routine over time. By exploring these dynamics, we seek to provide insights that can enhance pharmacology research and personalized medicine.

### 2. Model <a name="model"></a>

#### 2.1 Base Model <a name="base-model"></a>

Two base models are considered: intravenous administration and oral pill administration. The models involve differential equations describing the rate of change of drug concentration in the body over time. These equations are characterized by dosing rates, processing rates, and clearance rates, with specific assumptions for each administration method.

#### 2.2 Analysis of Base Model <a name="analysis-of-base-model"></a>

The equilibria of the base models indicate that the drug concentration in the body eventually approaches zero due to continuous clearance. Simulations demonstrate the dynamics of drug concentration over time for different dosing rates and administration methods, revealing insights into peak concentration and clearance rates.

#### 2.3 Model Extension <a name="model-extension"></a>

An extension to the base model considers logistic drug metabolism, introducing a carrying capacity parameter. This modification reflects the finite capacity of the body to metabolize drugs and provides a more realistic representation of drug clearance dynamics.

### 3. Results <a name="results"></a>

The extension model demonstrates how the carrying capacity parameter influences drug metabolism dynamics, affecting peak concentration and clearance rates. Insights from simulations highlight the importance of realistic modeling approaches in pharmacokinetics.

### 4. Discussion <a name="discussion"></a>

The findings underscore the significance of considering realistic factors, such as carrying capacity, in pharmacokinetic models. While the models provide valuable insights, they have limitations and opportunities for improvement, such as incorporating genetic information and exploring alternative dosing strategies.

### 5. References <a name="references"></a>

Korzekwa, K. & Nagar, S. (2023, January 9). Process and System Clearances in Pharmacokinetic Models: Our Basic Clearance Concepts Are Correct. Drug Metab Dispos 51, 4. https://doi.org/10.1124/dmd.122.001060

Le, J. (2022, June 22). Drug administration - drugs. Merck Manual Consumer Version. https://www.merckmanuals.com/en-ca/home/drugs/administration-and-kinetics-of-drugs/drug-administration 

Mohsin, N. ul A., Farrukh, M., Shahzadi, S., & Irfan, M. (2024, February 14). Drug metabolism: Phase 
I and phase II metabolic pathways. IntechOpen. https://www.intechopen.com/chapters/88053 
Smith, R.L., O’Connell, K., Athanasiu, L. et al. (2020, June 19). Identification of a novel polymorphism associated with reduced clozapine concentration in schizophrenia patients—a genome-wide association study adjusting for smoking habits. Transl Psychiatry 10, 198. https://doi.org/10.1038/s41398-020-00888-1
]

### 6. Appendix A: R Code <a name="appendix-a--r-code"></a>
Images and code provided in file




--- 

This README provides an overview of the project, including its objectives, methodologies, results, and implications. For further details, refer to the main project report and accompanying appendices.

