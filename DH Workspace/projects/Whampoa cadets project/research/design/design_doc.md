# Project Design Document

## Project Title 

- Tension Between Ideal and Reality: A Re-examination of Whampoa Military Academy's "Anti-Localism" Based on Geographical Origins and Regional Network Analysis

## Project Files

- [Research Journal]
- [Cleaned Dataset]
- [Interactive Map]

## Background and Context (the W's)

- As Jiang Tao (2024) pointed out in his article "Breaking Localism," the establishment of the Whampoa Military Academy was a key effort by the Nationalist Party to create a revolutionary army that "transcended regionalism." However, does this macro-level institutional goal mean that the social composition of the cadets also achieved "de-regionalization"? This study uses quantitative analysis of the geographical origins and regional networks of the first cohort of cadets to examine the tension between revolutionary ideals and social reality.

## Research Puzzles

- To what extent did the geographical concentration of cadets reflect the Academy’s reliance on pre-existing regional revolutionary networks?
- How did the recruitment practices align with the institutional goal of building a nationalized army?
- How can Social Network Analysis (SNA) clarify the relationship between institutional ideals and social realities in early revolutionary movements?

## Methodology

- Data Collection: Extract cadet names and native places (籍贯) from the official 黄埔军校第一期同学姓名籍贯表（湖南省档案馆校编版）.
- Data Cleaning: Standardize historical place names and split 籍贯 into 省 (province) and 县 (county) fields.
- SNA & Visualization: Use network analysis to model provinces as nodes and cadet numbers as edge weights. Create an interactive HTML map to visualize spatial distribution.
- Historical Contextualization: Compare findings with historical studies on regional revolutionary networks.

## Data and Sources

- Primary Source: 黄埔军校第一期同学姓名籍贯表 (PDF from 黄埔军校同学录——湖南省档案馆校编).
- Secondary Sources: Academic works on Whampoa Academy’s institutional history and regional mobilization (e.g., Jiang Tao’s research on “anti-localism”).
Tools: Python (Pandas for data cleaning, Folium/Plotly for mapping), ChatGPT (for PDF-to-CSV conversion).

## Expected Outputs

- A cleaned and structured dataset of cadets’ geographical origins.
- An interactive map highlighting provincial distribution and density.
- A research journal documenting methodological steps and analytical insights.
- A short report (3–5 pages) summarizing key findings on regional recruitment patterns.

## Working hypotheses

- Cadet origins were highly concentrated in specific provinces (e.g., 湖南, 江西), reflecting reliance on localized recruitment channels.
- The Academy’s recruitment practices prioritized efficiency over ideological consistency during its founding phase.
- SNA will reveal core-periphery patterns in geographical recruitment networks.

## Challenges and Risks

- Data Quality: Historical inconsistencies in place names and administrative boundaries.
- Tool Dependency: AI-assisted data extraction requires manual verification.
- Archival Access Difficulty: The most accessible "primary source" currently available is the name list compiled and organized by archival institutions, which may differ from the original historical records in terms of completeness and accuracy. This introduces potential biases in data representation.

## Action Items

- [ ] Extract and clean cadet data from PDF source.
- [ ] Standardize 省 and 县 fields and validate place names.
- [ ] Develop an interactive map for spatial visualization.
- [ ] Conduct SNA to quantify provincial recruitment networks.
- [ ] Draft the final report and research journal entries.
