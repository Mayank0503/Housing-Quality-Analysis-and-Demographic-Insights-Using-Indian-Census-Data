# Housing-Quality-Analysis-and-Demographic-Insights-Using-Indian-Census-Data
Analyzed housing quality and demographic patterns across Indian districts using Census datasets. Built a Housing Quality Index (HQI), performed exploratory data analysis, clustering, hypothesis testing, and visualized findings through static, interactive, and spatial maps in R.


# Project Synopsis

## Title  
**Housing Quality Analysis and Demographic Insights Using Indian Census Data**

## 1. Introduction  
This project focuses on analyzing housing quality and demographic conditions across Indian districts using 2011 Census datasets. A Housing Quality Index (HQI) was developed to quantify and compare housing standards. Advanced data analysis techniques such as clustering, correlation analysis, hypothesis testing, and spatial visualization were applied to derive meaningful insights into regional disparities.

## 2. Feasibility Study  
- **Technical Feasibility:** The project was implemented using R programming, leveraging packages like `tidyverse`, `ggplot2`, `sf`, `leaflet`, and `cluster`. All tools used are open-source and freely available.  
- **Operational Feasibility:** The project workflow from data cleaning to visualization was streamlined and successfully executed, making it operationally feasible.  
- **Economic Feasibility:** No additional investment was required apart from computational resources and open datasets.

## 3. Literature Survey  
Prior studies on housing conditions and demographic inequality were referenced to design the HQI framework. Methods like k-means clustering and linear regression were used based on standard practices in socio-economic data analysis. Spatial analysis and interactive mapping approaches were inspired by best practices from geographic information system (GIS) research.

## 4. Methodology  
- **Data Collection:** Two datasets were used — detailed housing condition data and district-level demographic statistics from the 2011 Indian Census.  
- **Data Preparation:** Datasets were filtered, cleaned, and merged by district codes. New features like population density and gender literacy gap were engineered.  
- **Exploratory Data Analysis:** Distributions, top/bottom rankings, and correlation matrices were generated to understand patterns.  
- **Clustering Analysis:** K-Means clustering grouped districts based on HQI and demographic features.  
- **Hypothesis Testing:** A linear regression model tested the relationship between SC/ST percentages and female literacy rates.  
- **Visualization:** Generated static plots, interactive dashboards, and spatial maps of HQI across districts.  
- **Tools Used:** R, ggplot2, corrplot, sf, leaflet, cluster, factoextra, fuzzyjoin.

## 5. Facilities Required  
- **Software:**  
  - R Programming Language  
  - RStudio IDE  
  - Required R packages (tidyverse, ggplot2, sf, leaflet, cluster, etc.)  
- **Hardware:**  
  - Standard personal computer or laptop with at least 8GB RAM  
- **Data Resources:**  
  - Indian Census Housing Condition Dataset  
  - Indian Districts Demographic Dataset  
  - India District Boundary Shapefile (2011)

## 6. Bibliography  
- Government of India, Census 2011 Data  
- R Documentation (ggplot2, sf, leaflet, cluster)  
- Academic papers and online resources on Housing Quality Indices, Clustering in socio-economic studies, and GIS mapping.

## 7. References  
- Census of India official website: [https://censusindia.gov.in](https://censusindia.gov.in)  
- CRAN R Project: [https://cran.r-project.org/](https://cran.r-project.org/)  

## 8. Appendix  
- Snapshots of final visualizations (Top/Bottom HQI districts, Correlation Plots, Spatial Maps)  
- Summary tables (State-wise HQI Summary, Cluster-wise Analysis, Regression Model Outputs)

