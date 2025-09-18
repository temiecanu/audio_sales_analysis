# Audio Sales Analysis

## Project Overview

This project involves the analysis of wholesale sales data in the audio equipment industry. The focus is on deriving actionable insights to support strategic business decisions, optimize product offerings, and enhance sales processes.

### Company Context: SoundSphere

SoundSphere is a fictional European distributor of audio equipment. The company collaborates with major retail chains and specialized stores. During this analysis, data was consolidated from multiple backups due to temporary unavailability of the primary storage system.

---

## Repository Structure

```
audio_sales_analysis/
│
├── data/                      
│   ├── orders/                         # Contains dated folders with CSVs for each manager
│   └── products/                       # Product categories with their respective CSVs
│
├── usd_rate.txt                        # USD to EUR exchange rates per day
├── audio_sales_analysis.ipynb          # Full analysis notebook
├── README.md
```

---

## Project Goals

- **Data Consolidation**: Merging scattered data into a unified format.
- **Key Metrics Calculation**: Analyzing sales trends, revenue dynamics, and performance indicators.
- **Actionable Insights**: Identifying high-performing brands and employees while addressing inefficiencies.

---

## Data Description

### Tables
- **Orders (`orders.csv`)**
  - Data about customer orders.
- **Order Status (`order_status.csv`)**
  - Data about order statuses and client details.
- **Products (`products.csv`)**
  - Data about products and pricing.

### File Structure
- **data/orders/**: Contains subfolders organized by date and manager.
  - Example: data/orders/2024-03-01/Maximilian Berger/orders.csv
- **data/products/**: Organized by product categories.
  - Example: data/products/AV-processors/products.csv
- **usd_rate.txt**: Contains the USD to EUR exchange rate for each day.

---

## Key Insights

- **Sales Dynamics**: Analyzed revenue, average receipts, and order counts for trends and anomalies.
- **Brand Analysis**: Identified top-performing brands and those with excess inventory.
- **Manager Performance**: Evaluated contributions to total revenue and orders for recognition and coaching.
- **CRM Analysis**: Investigated repeated orders to address potential system malfunctions.

---

## Project Structure

1. **Data Collection**: Consolidation from backup files.
2. **Trend Analysis**: Revenue and order count patterns.
3. **Key Metrics Calculation**: Revenue, average receipt, and order performance.
4. **Insights Generation**: Identifying brand and employee performance.

---

## How to Run

1. Clone the repository:

```bash
git clone https://gitlab.com/your_username/audio_sales_analysis.git
cd audio_sales_analysis
```
2. Install required libraries:

```bash
pip install -r requirements.txt
```
3. Run the Jupyter notebook or script:

```bash
jupyter notebook audio_sales_analysis.ipynb
```
---

## Visualizations

This project includes advanced visualizations using Plotly and Matplotlib to present trends, revenue breakdowns, and employee performance.

## Author

Artemie Țurcanu - Data Analyst.