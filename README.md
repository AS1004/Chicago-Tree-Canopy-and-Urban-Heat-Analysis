# Chicago Tree Canopy & Urban Heat Analysis

## Project Overview

  This project investigates the relationship between tree canopy coverage and the heat island effect in Chicago neighborhoods. Using publicly available data, the analysis explores how increased tree coverage may      reduce surface heat and improve local environmental conditions, which can benefit urban ecosystems (including pollinator habitats).

## Data Sources

  1. Tree Canopy Coverage – Morton Arboretum community-level canopy reports
  2. Heat Island Effect – CHIVES surface heat index percentile for each neighborhood (0–100 scale)
  Each dataset was manually compiled and cleaned to ensure consistency for analysis.

## Methodology

  ### Data Cleaning
  
  - Created standardized column names ("Tree_Canopy_Percentage", "Heat_Island_Effect")
  - Verified numerical values and handled missing data
  
  ### Scatter Plot & Linear Trendline
  
  - Visualized tree canopy percentage vs heat island effect
  - Added linear regression to quantify the slope of heat reduction per 1% canopy increase
  - Calculated correlation coefficient (r = –0.4) to measure the strength of the relationship
  
  ### Quartile Analysis
  
  - Divided neighborhoods into four canopy quartiles (Low, Mid-Low, Mid-High, High)
  - Calculated average heat island effect per quartile
  - Created a bar chart to compare neighborhood groups visually

## Key Findings

  - Tree canopy and heat island effect show a moderate negative correlation (r = –0.4), indicating that neighborhoods with more trees generally experience less surface heat.
  - The trendline slope suggests that increasing canopy coverage by 1% corresponds to an average decrease in heat index, showing a measurable environmental benefit.
  - Quartile analysis highlights that neighborhoods in the highest canopy quartile experience significantly lower average heat than those in the lowest quartile, suggesting that targeted tree planting could have     the greatest impact.

## Environmental Implications

  - Urban tree planting can mitigate surface heat, improve local climate resilience, and support pollinator-friendly habitats in Chicago.
  - Actionable insights for urban planning and environmental policy
  - Links quantitative analysis along with tangible insights into environmental sustainability.
  
## Python Skills Demonstrated

  - Data cleaning and preprocessing with pandas
  - Method chaining and grouped aggregation
  - Scatter plotting and regression trendlinse with matplotlib and numpy
  - Quartile-based aggregation & bar chart visualization

## Limitations

  - Tree canopy and heat island metrics do not directly measure pollinator populations or species-level ecological health.
  - The analysis uses a Google Colab–GitHub workflow with a static CSV file, which limits dynamic data updates and automated data ingestion.

## FINAL NOTE

  - Please run through Colab and upload the file linked within the repository, thank you!
  
