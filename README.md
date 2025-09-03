# 📊 Modelling Volatility Dynamics Between Commodity ETFs and Their Net Asset Value using BVAR and HAR Models

<p align="center">
  <img src="https://img.shields.io/badge/PhD-Dissertation-blue?style=for-the-badge&logo=graduationcap" alt="PhD Dissertation"/>
  <img src="https://img.shields.io/badge/Chapter-2-green?style=for-the-badge" alt="Chapter 2"/>
  <img src="https://img.shields.io/badge/Status-In_Progress-warning?style=for-the-badge" alt="Status"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-LaTeX-008080?style=flat-square&logo=latex" alt="LaTeX"/>
  <img src="https://img.shields.io/badge/Data_Period-2010--2023-orange?style=flat-square&logo=calendar" alt="Data Period"/>
  <img src="https://img.shields.io/badge/ETFs-4_Commodities-purple?style=flat-square&logo=trending-up" alt="ETFs"/>
  <img src="https://img.shields.io/badge/Analysis-High_Frequency-red?style=flat-square&logo=chart-line" alt="High Frequency"/>
</p>

<div align="center">

**👨‍🎓 Author:** Simon-Pierre Boucher  
**🏛️ Institution:** Université Laval, Quebec City, Canada  

</div>  

## Abstract

We examine volatility transmission between commodity ETFs and their underlying assets using high-frequency realized variance data across multiple sampling frequencies. Analyzing crude oil, gold, silver, and natural gas ETFs with HAR-X models and Bayesian VAR, we document systematic heterogeneity in volatility spillovers. Precious metals exhibit strong unidirectional transmission from underlying assets to ETFs, with gold coefficients reaching 0.632 at 1-minute frequency and negligible reverse effects. Energy commodities show bidirectional transmission with asymmetries favoring underlying-to-ETF spillovers. Sampling frequency critically affects transmission measurement: 1-minute data reveals effects up to three times larger than 30-minute estimates. Jump components dominate continuous volatility transmission, particularly for precious metals. Our Bayesian analysis confirms that underlying volatility often rivals ETF self-persistence in predicting ETF dynamics. These findings challenge symmetric arbitrage assumptions and demonstrate that transmission efficiency varies with underlying market microstructure.

## 🔬 Research Overview

### 🎯 Key Research Questions
- 📈 How do volatility spillovers operate between commodity ETFs and their underlying assets?
- 💡 Do transmission patterns differ systematically across commodity types (precious metals vs. energy)?
- ⚖️ How does sampling frequency affect our understanding of volatility transmission mechanisms?
- 🔄 Are continuous and jump volatility components transmitted differently across markets?

### 📊 Methodology

<p align="center">
  <img src="https://img.shields.io/badge/Time_Period-13_Years-blue?style=flat&logo=clock" alt="Time Period"/>
  <img src="https://img.shields.io/badge/Start_Date-Jan_2010-green?style=flat&logo=calendar" alt="Start Date"/>
  <img src="https://img.shields.io/badge/End_Date-Jan_2023-red?style=flat&logo=calendar" alt="End Date"/>
</p>

- **📅 Data Period:** January 1st, 2010 to January 1st, 2023
- **🔍 Approach:** High-frequency realized variance construction with multiple sampling frequencies (1, 5, 30-minute)
- **📦 ETFs:** Four major commodity ETFs (GLD, SLV, USO, UNG)
- **📏 Models:** HAR-X models and Bayesian Vector Autoregression with jump decomposition

### ✅ Key Findings
1. **💫 Asymmetric Transmission:** Precious metals show strong unidirectional NAV-to-ETF spillovers, while energy commodities exhibit bidirectional patterns
2. **📉 Frequency Effects:** High-frequency sampling reveals transmission effects up to 3x larger than lower frequencies
3. **🔄 Jump Dominance:** Jump components universally exhibit stronger transmission than continuous volatility
4. **⚡ Market Structure:** Transmission efficiency varies systematically with underlying market microstructure

## 📁 Repository Structure

<p align="center">
  <img src="https://img.shields.io/badge/Files-15+-brightgreen?style=flat&logo=files" alt="Files"/>
  <img src="https://img.shields.io/badge/Sections-6-blue?style=flat&logo=list" alt="Sections"/>
  <img src="https://img.shields.io/badge/Tables-Multiple-orange?style=flat&logo=table" alt="Tables"/>
  <img src="https://img.shields.io/badge/Figures-8+-purple?style=flat&logo=image" alt="Figures"/>
</p>

### 📄 Main Files
- 📝 `chapitre2.tex` - Main LaTeX document
- 📚 `master.bib` - Bibliography file  
- 📊 `chapitre2.pdf` - Compiled PDF output (when available)

### 📋 Content Sections
- 🎯 `sections/01_introduction.tex` - Introduction and research questions
- 📖 `sections/02_literature_review.tex` - Comprehensive literature review
- 📊 `sections/03_data.tex` - Data construction and iNAV methodology
- 🔬 `sections/04_methods.tex` - HAR and BVAR econometric frameworks
- 📈 `sections/05_results.tex` - Empirical results and analysis
- 🎯 `sections/06_conclusion.tex` - Conclusions and implications

### 🛠️ Supporting Materials
- 📋 `tables.tex` - All statistical tables and results
- 🖼️ `figures.tex` - Figure references and time series plots

### 📊 Key Analysis Components
- 📈 **Realized Variance Construction** - Multiple sampling frequency analysis
- 📉 **Jump Detection** - Bipower variation methodology
- 🌊 **HAR-X Models** - Cross-market volatility transmission
- 🎨 **BVAR Analysis** - Impulse response and variance decomposition

## 🛠️ Compilation Instructions

<p align="center">
  <img src="https://img.shields.io/badge/LaTeX-Required-red?style=flat&logo=latex" alt="LaTeX Required"/>
  <img src="https://img.shields.io/badge/BibTeX-Enabled-green?style=flat&logo=book" alt="BibTeX"/>
  <img src="https://img.shields.io/badge/Steps-4-blue?style=flat&logo=list-ol" alt="Steps"/>
</p>

### 📋 Prerequisites
- 📦 **LaTeX distribution:** TeX Live, MiKTeX, or MacTeX
- 🔧 **Required packages:** See preamble in `chapitre2.tex`

### ⚡ Compilation Steps
```bash
# Step 1: Initial compilation
pdflatex chapitre2.tex

# Step 2: Process bibliography
bibtex chapitre2

# Step 3: Second compilation (resolve citations)
pdflatex chapitre2.tex

# Step 4: Final compilation (resolve cross-references)
pdflatex chapitre2.tex
```

### 📤 Output
- 📊 **Final document:** `chapitre2.pdf`

## 🏆 Research Contributions

<p align="center">
  <img src="https://img.shields.io/badge/Innovation-5_Areas-gold?style=flat&logo=lightbulb" alt="Innovation"/>
  <img src="https://img.shields.io/badge/Methodology-Novel-success?style=flat&logo=search" alt="Methodology"/>
  <img src="https://img.shields.io/badge/Data-High_Frequency-info?style=flat&logo=database" alt="Data"/>
</p>

1. **🔬 Methodological Innovation:** First systematic construction of high-frequency iNAV series for commodity ETFs
2. **📊 Frequency Analysis:** Comprehensive examination of sampling frequency effects on volatility transmission measurement
3. **🔍 Cross-Sectional Analysis:** Systematic comparison across commodity types revealing market structure differences
4. **⏱️ Jump Decomposition:** Separate analysis of continuous vs. discontinuous volatility transmission mechanisms
5. **🎯 Dual Framework:** Combined HAR and BVAR approaches providing multiple perspectives on transmission dynamics

## 🏷️ Keywords

<div align="center">

![ETF](https://img.shields.io/badge/ETF_Volatility-wheat?style=flat&logo=trending-up&logoColor=white)
![Commodity](https://img.shields.io/badge/Commodity_Markets-yellow?style=flat&logo=leaf&logoColor=black)
![Realized](https://img.shields.io/badge/Realized_Variance-orange?style=flat&logo=chart-bar&logoColor=white)
![HAR](https://img.shields.io/badge/HAR_Models-blue?style=flat&logo=timeline&logoColor=white)
![Microstructure](https://img.shields.io/badge/Market_Microstructure-green?style=flat&logo=microscope&logoColor=white)
![High Frequency](https://img.shields.io/badge/High_Frequency-red?style=flat&logo=activity&logoColor=white)
![BVAR](https://img.shields.io/badge/Bayesian_VAR-purple?style=flat&logo=share&logoColor=white)
![Spillovers](https://img.shields.io/badge/Volatility_Spillovers-darkred?style=flat&logo=shuffle&logoColor=white)
![Arbitrage](https://img.shields.io/badge/Arbitrage_Mechanisms-teal?style=flat&logo=balance-scale&logoColor=white)
![Transmission](https://img.shields.io/badge/Volatility_Transmission-pink?style=flat&logo=broadcast-tower&logoColor=white)

</div>

## 🎓 Academic Context

<p align="center">
  <img src="https://img.shields.io/badge/Literature-5_Areas-academic?style=flat&logo=book-open" alt="Literature"/>
  <img src="https://img.shields.io/badge/Finance-Core-blue?style=flat&logo=university" alt="Finance"/>
  <img src="https://img.shields.io/badge/Econometrics-Advanced-green?style=flat&logo=calculator" alt="Econometrics"/>
</p>

This research contributes to several academic literatures:
- 📈 **ETF Market Efficiency:** Understanding arbitrage mechanisms and pricing dynamics in ETF markets
- 🔬 **Volatility Modeling:** High-frequency realized variance estimation and jump detection methodologies
- 💡 **Market Microstructure:** Cross-market volatility transmission and price discovery mechanisms
- 🌱 **Commodity Finance:** Structural differences between precious metals and energy commodity markets
- 📊 **Applied Econometrics:** HAR modeling and Bayesian VAR techniques for financial time series

## 📋 Data and Methodology Details

### 🏦 ETFs Analyzed
- **🥇 SPDR Gold Trust (GLD)** - Physically-backed gold ETF
- **🥈 iShares Silver Trust (SLV)** - Physically-backed silver ETF  
- **🛢️ United States Oil Fund (USO)** - Futures-based crude oil ETF
- **⛽ United States Natural Gas Fund (UNG)** - Futures-based natural gas ETF

### 📈 Key Variables
- **Realized Variance (RV)** - Sum of squared intraday returns
- **Bipower Variation (BV)** - Jump-robust volatility estimator
- **Jump Component (J)** - Discrete price movement contribution
- **Continuous Component (C)** - Smooth price evolution contribution

### 🔬 Econometric Methods
- **HAR-X Models** - Cross-market volatility spillovers at daily, weekly, monthly horizons
- **HAR-CJ-X Models** - Separate continuous and jump component transmission
- **Bayesian VAR** - Impulse response analysis and variance decomposition
- **Multiple Frequencies** - 1-minute, 5-minute, and 30-minute sampling

## 👥 Author Information

<div align="center">

### 👨‍🎓 Principal Author
**Simon-Pierre Boucher**  
PhD Candidate in Finance  
🏛️ Université Laval, Quebec City, QC, Canada  
📧 simon-pierre.boucher.1@ulaval.ca

<p align="center">
  <img src="https://img.shields.io/badge/Status-PhD_Candidate-blue?style=flat&logo=graduation-cap" alt="PhD Candidate"/>
  <img src="https://img.shields.io/badge/Field-Finance-green?style=flat&logo=chart-line" alt="Finance"/>
  <img src="https://img.shields.io/badge/Location-Quebec_City-red?style=flat&logo=map-pin" alt="Location"/>
</p>

### 🤝 Co-authors
- 👩‍🏫 **Marie-Hélène Gagnon** (Professor of Finance and Research Fellow, CRREP, Université Laval)
- 👨‍🏫 **Gabriel J. Power** (IG Wealth Management Chairholder, Professor of Finance and Research Fellow, CRREP and CRIB, Université Laval)

</div>

## 📊 JEL Classification

<p align="center">
  <img src="https://img.shields.io/badge/G12-Asset_Pricing-blue?style=flat" alt="G12"/>
  <img src="https://img.shields.io/badge/G13-Contingent_Pricing-green?style=flat" alt="G13"/>
  <img src="https://img.shields.io/badge/G14-Information_&_Market_Efficiency-orange?style=flat" alt="G14"/>
  <img src="https://img.shields.io/badge/C32-Time_Series_Models-purple?style=flat" alt="C32"/>
</p>

## 📄 License

<p align="center">
  <img src="https://img.shields.io/badge/License-Academic_Use-lightgrey?style=flat&logo=creative-commons" alt="Academic Use"/>
  <img src="https://img.shields.io/badge/Purpose-Educational_Research-blue?style=flat&logo=book" alt="Educational Research"/>
</p>

This academic work is part of a PhD dissertation and is intended for educational and research purposes. Please cite appropriately if using any content from this repository.

---

<div align="center">
  
**📊 Research Excellence in Finance**

<img src="https://img.shields.io/badge/Last_Updated-September_2025-brightgreen?style=flat&logo=calendar" alt="Last Updated"/>
<img src="https://img.shields.io/badge/Made_with-❤️-red?style=flat" alt="Made with Love"/>

*Advancing understanding in ETF volatility dynamics and market microstructure*

</div>