# Antibiotic Resistance Surveillance Analysis (AMR Project)

## Overview
This project conducts a comprehensive meta-analysis of antimicrobial resistance (AMR) trends and estimates the economic burden across major provinces. The analysis includes data preprocessing, time series modeling, spatial analysis, machine learning predictions, economic impact estimation, and policy recommendation generation.

## Project Goals
- Analyze trends in antibiotic resistance from 2015 to 2024.
- Detect change points and forecast future resistance rates.
- Investigate geographic variance and clustering of resistance.
- Build predictive machine learning models for high resistance risk.
- Estimate provincial and national economic burden of AMR.
- Provide actionable policy recommendations to guide interventions.

## Data
- Simulated AMR surveillance dataset including yearly resistance rates for key pathogens and antibiotics across 5 provinces.
- Variables include year, province, pathogen, antibiotic, sample counts, resistance counts, population, GDP, and healthcare expenditure.
- Replace simulated data with real surveillance data by updating the data loading section.

## Code Structure
- **scripts/** Contains R analysis scripts implementing data cleaning, modeling, visualization, and reporting.
- **data/** Raw and processed datasets.
- **figures/** Plots illustrating trends, heatmaps, and economic impact.
- **results/** Model outputs, summary statistics, and saved objects.
- **reports/** Final summary reports and policy briefs.

## Key Results
- Increasing overall AMR trends for major pathogens.
- Identification of critical pathogen-antibiotic combinations with highest resistance.
- Geographic hotspots highlighting priority provinces for intervention.
- Random Forest model achieved robust accuracy predicting high resistance cases.
- Economic burden estimated in millions USD, projecting increasing costs annually.
- Strategic policy recommendations formulated for targeted surveillance and control efforts.

## How to Run
1. Clone this repository.
2. Open the project in RStudio.
3. Install required packages (listed in the main script).
4. Update `data` folder with real data or use the simulated data.
5. Run the main R script (`amr_analysis.R`) to perform the complete analysis.
6. Outputs including plots, results, and reports will be saved to respective folders.

## Future Work
- Integrate genomic data for deeper AMR mechanism insights.
- Enhance spatial models with finer geographic resolution.
- Expand economic models to factor in indirect costs and interventions impact.
- Develop interactive dashboards for real-time monitoring and reporting.
## License
MIT License
