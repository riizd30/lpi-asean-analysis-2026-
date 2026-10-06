# LPI-ASEAN-Logistics-Performance-Analysis
### Table of Contents
1.  Introduction
2.  Methodology
    - Define Project Goal & Scope
    - Collect & Prepare the Data
    - Analyze the Data with Python
3.  Key Insights
4.  Impact & Outcome
5.  Business Recommendations
6.  Conclusion
7.  Disclaimer

### Introduction
This project focuses on a public Logistics Performance Index (LPI) dataset sourced from 【entity-World Bank¦canonical_name=World Bank】 Open Data (2007-2022). Analysis was performed primarily using Python to explore logistics performance trends across World, BRICS, and ASEAN. The goal is to understand why Indonesia's LPI stuck at 3.00 (-0.01) while ASEAN average grew to 3.34 (+0.30) and identify opportunities for improving customs, infrastructure, and port clustering decisions.

### Methodology
#### 1. Define Project Goal & Scope
- Identify why Indonesia LPI is one of only 2 negative countries in ASEAN (-0.01) vs Vietnam +0.41 overtake in 2014
- Analyze LPI performance by 6 components (Customs, Infra, Shipments, Competence, Tracking, Timeliness) over time
- Determine divergence patterns across ASEAN 4 (ID, MY, TH, VN, SG 4.30)
- Identify strengths and weaknesses in LPI components across ASEAN countries
- Examine business impact of +0.1 LPI improvement

#### 2. Collect & Prepare the Data
- Imported raw 【entity-World Bank¦canonical_name=World Bank】 LPI CSV (2007, 2010, 2012, 2014, 2016, 2018, 2022, 2023)
- Corrected data types for year and score fields, created data_long format
- Selected relevant columns for time, country, region, and 6 components
- Cleaned country names and extracted ASEAN 4 + BRICS vs World
- Removed records with no LPI score and handled 2020 missing (COVID)
- Prepared dataset for heatmap, dumbbell, and THE CLOSER diagnosis chart

#### 3. Analyze the Data with Python
- Compared ASEAN Avg vs BRICS vs World to identify Indonesia stagnation
- Evaluated component trends by country (Customs 2.80, Infra 2.90, Timeliness 3.35)
- Reviewed divergence pattern Vietnam 2.89→3.30 (+0.41) vs ID 3.01→3.00 (-0.01) from 2007-2022
- Examined heatmap evolution ASEAN 4 across 2007-2022
- Categorized components by strengths (Timeliness) and weaknesses (Customs, Infra, Tracking)
- Built THE CLOSER chart: Indonesia Archipelago Paradox with 73% gap explained

### Key Insights
Analysis revealed that over half of ASEAN growth came from Vietnam and Thailand, while Indonesia showed -0.01 stagnation. Timeliness 3.35 (+0.01 above ASEAN 3.34) consistently drove performance, while Customs 2.80 (-0.50 vs SG, clearance 2.5 days vs 0.5) and Infrastructure 2.90 fluctuated due to fragmented ports. Gap to Singapore 4.30 is 1.30 and 73% explained by Customs + Infra + Tracking.

### Impact & Outcome
This analysis provides a framework to prioritize high-impact reforms and address underperforming components. It helps quantify Rp80T saving per +0.1 LPI, reduce logistics cost (Bappenas 23.8% GDP), and align infrastructure with actual demand.

### Business Recommendations
Customs efforts should focus on Digital Single Window (target 0.5 day from 1.2), infrastructure should favor 4-hub clustering to cut -15% inter-island cost, and low-performing tracking systems should be upgraded. Roadmap 2025-2030: Turning 3.00 into 3.50 (Base) / 3.80 (Stretch).

### Conclusion
Customs and infrastructure performance must be evaluated together with timeliness. Examining component scores rather than total LPI highlights which components actively drive gap to SG 4.30 and which tie up Rp80T. The findings provide a practical basis for better logistics management. Archipelago Paradox is not destiny, it's design.

### Disclaimer
This project demonstrates Python-based analysis. The dataset is publicly available from 【entity-World Bank¦canonical_name=World Bank】 LPI. Insights are for learning and portfolio purposes only.

**Link Dataset & Code**
https://github.com/rizz30/LPI-ASEAN-Logistics-Performance-Analysis
