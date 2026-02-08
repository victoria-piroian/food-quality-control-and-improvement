# Controlling Pretzel Quality – Statistical Quality Control Project

## Overview
This project focuses on statistical quality control and process improvement in food manufacturing using real-world production data from pretzel rod samples. The project applies classical quality engineering, statistical process control (SPC), and Six Sigma methodologies to evaluate manufacturing stability, detect defects, and assess process capability. The workflow includes:

- Data collection: Measurement of pretzel length, defects, chips, and breakage attributes.
- Data visualization: Histograms, stem-and-leaf plots, boxplots, cumulative frequency plots, and time series plots.
- Statistical analysis: Distribution fitting, confidence intervals, hypothesis testing, and normality testing.
- Variable control charts: X̄-R, X̄-S, X̄-S², and I-MR charts.
- Attribute control charts: p, np, c, and u charts.
- Advanced SPC methods: CUSUM and EWMA charts for small-shift detection.
- Process capability analysis: Cp, Cpk, Cpm, process fallout, and Six Pack analysis.
- Model validation: Phase I/Phase II simulation using training/testing data splits.

---

## Key Features

### Data Collection & Preprocessing
- Manual measurement protocol with dual-observer validation
- Subgroup sampling structure (bag-based sampling)
- Continuous variables: Pretzel length
- Attribute variables: Breakage (binary), chip/crack counts
- Structured subgroup labeling for SPC analysis

### Statistical Analysis
- Distribution fitting and goodness-of-fit testing
- Normality testing (Anderson-Darling)
- Confidence interval estimation
- Hypothesis testing on manufacturing target mean
- Descriptive statistics and exploratory analysis

### Control Charts – Variables
- X̄-R Charts (mean and range monitoring)
- X̄-S Charts (mean and standard deviation monitoring)
- X̄-S² Charts (mean and variance monitoring)
- I-MR Charts (individual values and moving range)
- Phase I / Phase II process simulations
- Average Run Length (ARL) analysis

### Control Charts – Attributes
- p-charts (fraction nonconforming)
- p-charts with varying sample size (variable control limits)
- np-charts (number nonconforming)
- c-charts (number of nonconformities)
- u-charts (average nonconformities per unit)
- Operating Characteristic (OC) curves

### Advanced SPC Methods
- CUSUM charts for mean and variance monitoring
- Standardized and tabular CUSUM methods
- Fast Initial Response (FIR) CUSUM
- EWMA charts for small-shift detection
- EWMS and EWRMS charts for variance monitoring

### Process Capability Analysis
- Cp, Cpk, Cpm calculation
- Process centering analysis
- Bias detection relative to target
- Process fallout estimation (PPM)
- Six Pack capability visualization
- Manufacturing efficiency evaluation

---

## Usage
Clone the repository:
```bash
git clone <repo-url>
```

Install dependencies:

```
pip install numpy pandas matplotlib scipy scikit-learn

```

### Run notebooks/scripts to:
- Load pretzel measurement datasets
- Perform statistical analysis
- Generate SPC control charts
- Simulate Phase I and Phase II processes
- Build attribute and variable charts
- Run CUSUM and EWMA monitoring
- Compute process capability metrics
- Generate Six Pack and capability reports

### View outputs such as:
- Control charts
- SPC diagnostics
- Process capability reports
- OC curves
- CUSUM/EWMA charts
- Defect detection results

---

## Goals
- Apply real-world statistical process control methods
- Model manufacturing quality using SPC frameworks
- Detect process instability and quality shifts
- Compare classical control charts with advanced monitoring methods
- Evaluate manufacturing capability using Six Sigma metrics
- Demonstrate industrial quality engineering methodology
- Support data-driven manufacturing optimization

---

## Author

Victoria Piroian

University of Toronto

Faculty of Applied Science & Engineering, 2023
