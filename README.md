# Economic-and-Financial-Analysis-of-Efficient-Buildings-in-Mozambique-and-Kyrgyzstan
# README

# Economic and Financial Analysis (EFA) and Monte Carlo Risk Analysis for Energy-Efficient Buildings

Prepared by: Siddika Bhuiyan Mishu

---

# Project Overview

This repository contains Economic and Financial Analysis (EFA) models, supporting Python code, Monte Carlo simulation tools, and analytical reports developed for energy-efficient building interventions in:

1. Mozambique – Low-Income Cooling-Efficient Buildings
2. Kyrgyzstan – Low-Income Heating-Efficient Buildings

The purpose of the analysis is to evaluate the economic viability, financial sustainability, and risk profile of selected building-efficiency interventions designed to improve thermal comfort, reduce household energy expenditures, and strengthen climate resilience among low-income households.

The analysis follows a World Bank-style EFA framework and incorporates both deterministic and probabilistic (Monte Carlo) approaches to assess project performance under uncertainty.

---

# Country 1: Mozambique

## Project Objective

The Mozambique analysis focuses on cooling-efficiency measures suitable for low-income households living in hot climates where cooling demand contributes significantly to household energy expenditure and thermal discomfort.

## Intervention Package

The cooling intervention package includes:

* Cool Reflective Roof Coating
* Ceiling Installation and Roof Insulation
* Cross Ventilation Improvements
* External Shading (Awnings, Overhangs, Trees)
* Efficient Fans (DC and Energy-Efficient Fans)

## Analytical Framework

The analysis includes:

* Capital expenditure (CAPEX) assessment
* Operating expenditure (OPEX) assessment
* Economic Cost-Benefit Analysis
* Financial Cost-Benefit Analysis
* Sensitivity Analysis
* Monte Carlo Risk Analysis

## Key Baseline Results

| Indicator | Value             |
| --------- | ----------------- |
| ENPV      | 33.28 million MZN |
| FNPV      | 39.11 million MZN |
| EIRR      | 13.95%            |
| FIRR      | 15.94%            |

## Sensitivity Analysis

The model evaluates project performance under:

* 10% decrease in revenue/energy savings
* 10% increase in investment cost
* Two-year delay in benefits

## Monte Carlo Risk Analysis

The Monte Carlo simulation evaluates uncertainty in:

* Investment costs
* Energy savings
* Benefit realization
* Project implementation delays

Key findings include:

* Probability ENPV > 0: 100%
* Probability FNPV > 0: 100%
* Probability EIRR > 10%: 81.86%
* Probability FIRR > 10%: 94.44%

The simulation suggests that the intervention package remains economically and financially viable under most uncertainty scenarios.

---

# Country 2: Kyrgyzstan

## Project Objective

The Kyrgyzstan analysis focuses on heating-efficiency interventions suitable for low-income households living in cold-climate environments where winter heating costs represent a major burden on household budgets.

The analysis examines how building envelope improvements and efficient heating technologies can reduce heat losses, improve thermal comfort, lower energy consumption, and enhance resilience to cold weather conditions.

## Intervention Package

The heating intervention package includes:

* Roof and Ceiling Insulation
* Wall Insulation Retrofit
* Efficient Windows (Double/Triple Glazing)
* Efficient Heating Systems
* Air Sealing and Draft Proofing

## Analytical Framework

The analysis includes:

* Capital expenditure (CAPEX) assessment
* Operating expenditure (OPEX) assessment
* Economic Cost-Benefit Analysis
* Financial Cost-Benefit Analysis
* Sensitivity Analysis
* Monte Carlo Risk Analysis

## Key Baseline Results

| Indicator | Value     |
| --------- | --------- |
| ENPV      | US$48,000 |
| FNPV      | US$53,000 |
| EIRR      | 19.06%    |
| FIRR      | 14.97%    |

## Sensitivity Analysis

The model evaluates:

* 10% reduction in benefits
* 10% increase in investment cost
* Two-year implementation delay

The intervention package remains above the viability threshold under most scenarios.

## Monte Carlo Risk Analysis

The Monte Carlo simulation incorporates uncertainty related to:

* Investment costs
* Heating energy savings
* Benefit realization
* Project implementation timing

Key findings include:

* Probability ENPV > 0: 100%
* Probability FNPV > 0: 100%
* Probability EIRR > 10%: 89.7%
* Probability FIRR > 10%: 84.5%

The results indicate that the intervention package remains relatively robust under a broad range of uncertainty scenarios.

---

# Python and Monte Carlo Simulation Framework

The repository includes Python and Google Colab notebooks used to:

* Process EFA outputs
* Generate investment and performance visualizations
* Perform sensitivity analysis
* Conduct Monte Carlo simulations
* Generate ENPV, FNPV, EIRR, and FIRR probability distributions
* Visualize risk zones and viability thresholds

Monte Carlo simulations use 10,000 iterations and incorporate uncertainty in:

* CAPEX
* Energy savings
* Revenue streams
* Project delays

Risk visualizations classify outcomes into:

* Red Zone – High-risk scenarios below viability threshold
* Orange Zone – Moderate-return scenarios
* Green Zone – Strong-return scenarios

---

# Disclaimer

The analyses presented in this repository are illustrative and intended to support policy discussions and investment planning related to energy-efficient buildings. Results are highly dependent on the underlying assumptions regarding costs, energy prices, savings, discount rates, and implementation arrangements.

Further validation of technical assumptions, energy savings estimates, and cost data is recommended before applying these results to actual investment decisions.

---

# Repository Contents

1. Economic and Financial Analysis (EFA) Excel Models
2. Monte Carlo Simulation Reports
3. Python / Google Colab Notebooks
4. Visualization Outputs
5. Sensitivity Analysis Results
6. Supporting Documentation

---

# Contact

Siddika Bhuiyan Mishu

World Bank Group Consultant

Energy Access, Productive Use of Energy, Sustainable Cooling, and Energy-Efficient Buildings

Washington, DC, USA
