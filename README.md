# Project 2: Inventory and Sales Data Simulation

## Overview
This Python project simulates inventory management, customer behavior, and sales data for a corporation. It generates products, customer orders, and store sales, producing detailed analytics and visualizations.

## Features
- **Product Generation**: Randomized inventory of up to 200,000 items.
- **Sales Simulation**: Tracks customer purchases and generates sales data across 20 stores.
- **Data Insights**:
  - Most purchased products.
  - Large-basket buyer analysis (5+ items per order).
  - Top-performing stores for large-basket buyers.
  - Product category trends in large-basket orders.

## Key Results
- **Top Products**: Music Player, Stairmaster, and Gym Equipment dominate sales.
- **Large Baskets**: 308 large-basket orders identified across all stores.
- **Top Store**: Store 17 had the highest frequency of large-basket buyers.
- **Category Makeup**:
  - **Smart**: 20.4%
  - **Touchscreen**: 14.6%
  - **High-Speed**: 14.3%

## Visualizations
- **Store Performance**: Bar chart ranking stores by large-basket orders.
- **Category Makeup**: Pie and bar charts showing product description distribution.

## Setup
1. Install dependencies: `pandas`, `matplotlib`.
2. Run the script:  
   ```bash
   python project2.py
