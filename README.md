# NIFTY Implied Volatility Surface Prediction

## Overview

This project predicts missing implied volatility (IV) values across strike prices and timestamps in NIFTY50 options market data.

The goal is to reconstruct a smooth and financially meaningful implied volatility surface using machine learning techniques.

Developed as part of the Finance Club IIT Roorkee Open Project 2026.

---

## Problem Statement

Implied volatility is a critical component of:

- Option Pricing
- Volatility Trading
- Portfolio Risk Management
- Market Making

The challenge is to estimate missing IV values using observed option market data.

---

## Methodology

### Data Processing

- Option contract parsing
- Strike extraction
- Timestamp processing
- Missing value handling

### Feature Engineering

- Time-to-expiry
- Neighbor strike IV
- ATM volatility
- Put-call volatility spread
- Cross-sectional volatility structure

### Model

- HistGradientBoostingRegressor
- TimeSeriesSplit validation
- Log-transformed target

### Evaluation Metric

- Mean Squared Error (MSE)

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

---

## Repository Structure

