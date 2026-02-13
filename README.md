
## FEMA National Risk Index in California

### Purpose
This repository houses the scripts necessary to produce a visualization comparing National Risk Index scores between US States - and a visualization comparing racial distributions among NRI scores in California counties.

### Research Questions
"How do FEMA National Risk Index scores for counties in California compare to those in other states?"

"How does climate hazard risk exposure vary across racial / ethnic groups in California?"

### Visualizations
![US States with Highest Proportion of High-Risk Counties](FEMA_NRI_data_viz_files/figure-html/unnamed-chunk-4-1.png)

-

![Population Distribution Across Climate Risk Levels](HW3_files/figure-html/unnamed-chunk-6-1.png)

### Repository Structure
```
├── data/                           # Data directory (empty - see Data Access)
├── FEMA_NRI_data_viz.qmd           # NRI Analysis script
├── HW3.qmd                         # NRI/ACS Analysis script
├── FEMA_NRI_data_viz.html          # Rendered output of NRI visualization
├── HW3.html                        # Rendered output of NRI/ACS visualization
└── README.md                       # This file
```

### Data Access
FEMA's NRI data is available through the Resilience Analysis and Planning Tool (RAPT):

1. Navigate to [FEMA RAPT](https://www.fema.gov/emergency-managers/practitioners/resilience-analysis-and-planning-tool)
2. Click on the **NRI** button in the top menu
3. Find the **National Risk Index Counties** layer
4. Click on the three dots → **Export to CSV**
5. Create a `data/` folder in this repository
6. Save the CSV file as `National_Risk_Index_Counties_807384124455672111.csv` in the `data/` folder

US Census's ACS data is remotely accessed by the script in the `HW3.qmd`

### Usage
After downloading and placing the data file, render `FEMA_NRI_data_viz.qmd` to reproduce the analysis.

### Author
Henry Oliver

## References

https://www.fema.gov/flood-maps/products-tools/national-risk-index

https://eds-240-data-viz.github.io/course-materials/assignments/HW2.html