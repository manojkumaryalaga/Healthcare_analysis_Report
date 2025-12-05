# Healthcare Analysis Power BI Dashboard

## Project Overview

This project contains an interactive Power BI dashboard built using a healthcare screening dataset. The dashboard provides insights into member eligibility, screening completion, and demographic trends across language, race, ethnicity, and region. Users can explore patterns using filters and visualizations to gain a deeper understanding of screening performance and population distribution.

## Dataset

The dataset used contains anonymized member screening records and demographic attributes.

### Key Fields

- Member ID Encrypted: Unique encrypted member identifier.  
- EBM Numerator: Indicates if the member received screening.  
- EBM Denominator: Indicates if the member is eligible for screening.  
- ORIG_PREFERRED_LANGUAGE: Member’s preferred language.  
- SRC_LANGUAGE: Source system–recorded language.  
- ORIG_RACE: Member-reported race.  
- SRC_RACE: Source system–recorded race.  
- Original Member Ethnicity: Member-reported ethnicity.  
- SRC_ETHNICITY: Source system–recorded ethnicity.  
- Zip (5-digit): Member ZIP code.  

### Healthcare Analysis Dashboard

- Displays total eligible members, screened members, and unscreened members.  
- Shows demographic breakdowns by ethnicity, region, language, and race.  
- Includes filter options for metric, region, ethnicity, and race.  

### Original Member Ethnicity Tooltip

- Summarizes KPIs for the selected ethnicity group.  

### Region Tooltip

- Provides screening metrics for selected regions.  

### Original Preferred Language Tooltip

- Shows KPI details for different preferred languages.  

### Original Race Tooltip

- Shows race-based KPI summaries for deeper drill-down.  

## Dashboard Screenshot

![Healthcare Analysis Dashboard](path/to/your-dashboard-screenshot.png)  
*Replace `path/to/your-dashboard-screenshot.png` with the actual path to your screenshot in the repository.*

## Insights

Some patterns identified from the dashboards include:

- A total of 6,597 members are eligible for screening.  
- 4,184 members (63%) received screening, while 2,413 members (37%) did not.  
- English is the most common preferred language, followed by Russian, Korean, and Spanish.  
- The majority of members fall under "Not Hispanic or Latino."  
- The USCA region accounts for the highest proportion of eligible members.  
- Screening completion varies significantly across race, ethnicity, and language groups.  

## How to Use

1. Download the `.pbix` Power BI report from this repository.  
2. Open the report using Power BI Desktop.  
3. Interact with the filters to explore insights by demographic categories.  
4. Hover over charts to view tooltip dashboards for detailed summaries.  

## Future Enhancements

- Add time-series analysis to track screening trends over time.  
- Include geographic heat-map visuals using ZIP-code-level data.  
- Add predictive analytics to identify underserved or high-risk groups.  
- Expand drill-down dashboards to include provider or facility comparisons.  
