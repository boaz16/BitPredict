# BitPredict: Bitcoin Price Prediction

A deep learning project utilizing TensorFlow and time series analysis to forecast the price of Bitcoin based on historical data. 

## Badges
<!-- TODO: Add actual URLs for badges once the repo is hosted/configured -->
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626)

## Overview
**BitPredict** is a component of the TensorFlow Developer Certificate Course. The goal of this project is to provide insights into potential future price movements of Bitcoin using deep learning techniques. It fetches historical Bitcoin price data, processes it using Pandas, and applies various time-series forecasting models using TensorFlow.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Course Details](#course-details)
- [License](#license)
- [Contact](#contact)

## Features
- **Historical Data Retrieval:** Automatically downloads historical BTC/USD data.
- **Data Preprocessing:** Utilizes Pandas for robust time-series data manipulation and visualization.
- **Deep Learning Models:** Builds, trains, and evaluates multiple TensorFlow models designed for time-series forecasting.
- **Performance Evaluation:** Compares model predictions against historical data.

## Tech Stack
- **Python 3**
- **TensorFlow / Keras** (Deep Learning Framework)
- **Pandas & NumPy** (Data Manipulation & Time Series processing)
- **Matplotlib** (Data Visualization)
- **Jupyter Notebook** (Development Environment)

## Getting Started

### Prerequisites
You need Python installed on your system along with Jupyter Notebook and TensorFlow.

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/boaz16/BitPredict.git
   cd BitPredict
   ```

2. **Install dependencies:**
   Since there is no `requirements.txt`, you can install the necessary packages manually:
   ```bash
   pip install tensorflow pandas numpy matplotlib jupyterlab
   ```

3. **Run the Notebook:**
   ```bash
   jupyter notebook project3_bitpredict.ipynb
   ```

## Project Structure
```text
BitPredict/
├── project3_bitpredict.ipynb    # Main Jupyter Notebook containing the data pipeline and models
└── README.md                    # Project documentation
```

## Course Details
This project was built as part of the [TensorFlow Developer Certificate](https://www.udemy.com/share/104ssS3@qr2xIEbG8LOqfGgHfmw-a2Z6r_d_6_olkS5hKSmVWT23wYDJNTbD82qAAoaJss-SKQ==/) course on Udemy.