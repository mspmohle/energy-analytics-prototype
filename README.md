Energy Analytics Prototype

This project demonstrates a real-world data analysis workflow using publicly available U.S. electric grid outage data.
It explores outage trends across NERC regions, identifies high-impact areas, and builds the foundation for predictive analytics and reliability forecasting.

Overview

This notebook simulates a proof-of-concept energy analytics pipeline for identifying grid reliability patterns and outage hotspots.
It demonstrates the full workflow—from data ingestion to visualization—as would be used in an energy or utilities data-science environment.

Key Features

Automated dataset ingestion from Kaggle (U.S. Electric Grid Outages dataset).
Data cleaning, transformation, and storage using DuckDB for reproducibility.
Exploratory data analysis of outage events by region, demand loss, and customer impact.
Visual analytics for outage frequency, duration, and load loss.
All results exported for easy integration into dashboards or BI systems.

Repository Structure
```text
energy-analytics-prototype/
│
├── notebooks/
│   ├── 01_data_ingest_and_cleaning.ipynb   # Main analysis notebook
│   ├── data/                               # Raw and cleaned outage data
│   └── figures/                            # Visualizations generated from analysis
│
├── sql/                                    # SQL summary queries (DuckDB)
├── README.md                               # Project documentation
├── requirements.txt                        # Python dependencies
└── .gitignore                              # Environment and temp file exclusions

Tools and Libraries

Python (Pandas, NumPy, Matplotlib, Seaborn)
DuckDB for analytical storage
Kaggle API for data sourcing
Jupyter Notebook for reproducible analysis
Matplotlib and Seaborn for visualization

Data Source

U.S. Electric Grid Outages Dataset (2023)
https://www.kaggle.com/datasets/willianoliveiragibin/us-electric-grid-outages

License: CC0 (Public Domain)

Purpose
This prototype demonstrates the analytical approach and technical rigor suitable for roles such as Data Analyst, Energy Data Scientist, or Analytics Engineer, showing how to manage and visualize grid reliability data for operational insights.

Author
Michael S. Mohle

License
This project is licensed under the MIT License — you are free to use, modify, and distribute this work for any purpose, provided that proper credit is given.
