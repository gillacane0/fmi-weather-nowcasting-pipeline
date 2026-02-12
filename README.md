# FMI Weather Data Pipeline & ML Nowcasting

This repository contains an end-to-end technical study conducted for the **FMI ML Trainee** position. It focuses on the Helsinki Kumpula station, integrating historical analysis with real-time API ingestion.

## Key Features
- **Real-time Ingestion:** Custom pipeline using the FMI WFS API (`fmiopendata`) to fetch MultipointCoverage data.
- **Advanced EDA:** Wind Rose analysis and thermodynamic profiling for atmospheric stability assessment.
- **Predictive Modeling:** Linear Regression baselines for Short-term Nowcasting, comparing 10-min, 1-hour, and 24-hour lag performance to evaluate synoptic advection effects.
- **Scalability:** Discussion on integrating local station data with **Vision Transformers (ViT)** for multi-modal climate forecasting.

## Quick Preview
![Wind Rose](wind_rose_fmi.png)
*Dominant wind directions and speed distribution at Kumpula station.*

## Tech Stack
`Python`, `Pandas`, `Scikit-Learn`, `Windrose`, `FMI-API`, `Matplotlib/Seaborn`
