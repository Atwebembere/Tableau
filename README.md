# Tableau
Trends in suicide rates over time comparing different WHO regions.
# Age-Standardized Suicide Rates Dashboard

## Overview
This repository presents an interactive Tableau dashboard analyzing age-standardized suicide rates across regions and sexes, alongside supporting data and project documentation.

The main components include:
- **`data/Age_standardized.xlsx`**: WHO age-standardized suicide rates dataset (per 100,000 population) with confidence intervals.
- **`workbook/Final_Project.twbx`**: Packaged Tableau workbook containing:
  - Africa Countries by Sex
  - Geographical Region Trends
  - Pie Chart – Regions
  - Suicide Rates – Lesotho
  - Trend of Suicide Rates Over Time
- **`docs/Project_Plan.docx`**: Project plan outlining objectives, methodology, and deliverables.

## Repository Structure
```
├── README.md                # Project overview and instructions
├── data/
│   └── Age_standardized.xlsx  # Raw data file
├── docs/
│   └── Project_Plan.docx      # Detailed project plan
└── workbook/
    └── Final_Project.twbx     # Tableau dashboard
```

## Prerequisites
- **Tableau Desktop** or **Tableau Reader** to open and interact with the `.twbx` workbook.
- **Microsoft Excel** (or compatible) to view the raw data spreadsheet.

## Getting Started
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/age-standardized-suicide-dashboard.git
   cd age-standardized-suicide-dashboard
   ```
2. **Open the data file** in `data/Age_standardized.xlsx` to review the dataset structure.
3. **Launch Tableau** and open `workbook/Final_Project.twbx` to explore the interactive visualizations.

## Usage
- **Filter by Region/Sex**: Use the dropdown filters in the dashboard to isolate specific regions or sexes.
- **Time-Series Analysis**: Slide the year filter in "Trend of Suicide Rates Over Time" to examine temporal patterns.
- **Export Data**: From any worksheet, click `Worksheet -> Export -> Data` to save filtered subsets as CSV.

## Future Enhancements
- Add Python/R scripts for preprocessing and extended statistical analysis under a `scripts/` or `notebooks/` folder.
- Automate data refresh by connecting directly to the WHO API or database.
- Deploy an online version of the dashboard using Tableau Public.

## Contributing
Contributions are welcome! Please:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m "Add feature"`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request
