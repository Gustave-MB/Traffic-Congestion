# Predicting Traffic Congestion with Machine Learning

## Overview

This repository contains the code and report for a project focused on "Predicting Traffic Congestion with Machine Learning." The project utilizes historical traffic data from Chicago to forecast congestion, employing time series models such as Auto-ARIMA and VAR.

## Authors
- Gustave Munezero Bwirayesu
- Yves Marie Ishimwe Kirunga
- Deo Uwimpuhwe

## Abstract

The project's objective is to gain insights into traffic congestion patterns by leveraging machine learning models on data sourced from 29 regional roads in Chicago. The selected models, Auto-ARIMA and VAR, were compared, with VAR demonstrating superior performance in congestion forecasting. The findings indicate potential applications for optimizing road usage and decision-making, particularly in the context of Rwanda.

## Usage

The project relies on the [Chicago Traffic Tracker Congestion Estimates](https://data.cityofchicago.org/Transportation/Chicago-Traffic-Tracker-Congestion-Estimates-by-Re/t2qc-9pjd) dataset. This repository includes the necessary notebooks, and the complete report.

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/Gustave-MB/Traffic-Congestion.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Traffic-Congestion
   ```

## Results

The study compares Auto-ARIMA and VAR models for speed forecasting, with VAR demonstrating superior performance. The rolling method was applied for model updates, revealing increased forecasting error for distant future predictions. EdgeWater Uptown region exhibited the smallest RMSE among all roads.

## Recommendations

The implementation of a traffic congestion forecasting system is recommended to optimize existing transport infrastructure. The project suggests adopting the developed system in Rwanda to enhance road usage efficiency and decision-making.

## License

This project is licensed under the [MIT License](LICENSE).
