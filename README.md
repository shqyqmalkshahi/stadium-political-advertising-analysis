# stadium-political-advertising-analysis

Developed a data-driven model to evaluate political advertising opportunities in sports stadiums using a custom Opportunity Score combining reach, engagement, and cost efficiency.

# Stadium & Live Event Political Advertising Analysis

## Overview
This project analyzes political advertising opportunities within sports stadiums and live-event environments. The goal is to identify which venues, placements, and geographic regions provide the highest advertising value based on audience reach, engagement, and cost efficiency.

Sports venues offer a unique advertising environment due to high attendance, long exposure duration, and strong audience engagement, making them ideal for targeted campaign messaging.

---

## Problem Statement
Political campaigns invest heavily in advertising, but determining which stadiums and placements provide the best return on investment is challenging.

This project addresses how to optimize advertising decisions by evaluating:

- Audience reach  
- Engagement potential  
- Cost efficiency  

---

## Objective
To build a data-driven framework that identifies the most effective advertising opportunities across:

- Stadiums  
- Sports leagues  
- Placement types  
- Geographic regions  

---

## Dataset
- 120 advertising observations across multiple venues  
- Sports included:
  - NFL  
  - MLB  
  - NBA  
  - NHL  
  - College Football  

### Features:
- Stadium name  
- Sport type  
- State  
- Stadium capacity  
- Average attendance  
- Ad type (scoreboard, LED, concourse, etc.)  
- Placement (field-level, upper deck, etc.)  
- Estimated reach  
- Engagement score  
- Cost  

---

## Methodology

### Data Preparation
- Cleaned and validated dataset (no missing values)  
- Verified data consistency across all variables  

---

### Custom Metric: Opportunity Score

To evaluate advertising effectiveness, a custom metric was developed:

Opportunity Score = (Estimated Reach × Engagement Score) ÷ Cost  

This metric combines:
- Exposure (reach)  
- Audience interaction (engagement)  
- Financial efficiency (cost)  

---

### Analysis Performed

- Aggregated opportunity scores by:
  - Stadium  
  - Sport  
  - State  
  - Placement  

- Evaluated relationships between:
  - Attendance and reach  
  - Cost and advertising efficiency  
  - Placement and engagement  

- Identified top-performing venues and placements  

---

## Key Insights

- Large stadiums (especially college football) provide the highest advertising value  
- Attendance strongly drives estimated reach  
- Field-level and concourse placements generate the highest engagement  
- Upper deck placements show lower performance  
- Some lower-cost placements provide strong reach, indicating cost-efficient opportunities  
- States with large venues (e.g., Texas, Michigan, Pennsylvania) offer the highest value  

---

## Business Value

This project transforms advertising strategy from intuition-based to data-driven by:

- Identifying high-impact advertising opportunities  
- Optimizing budget allocation  
- Improving campaign reach and engagement  
- Supporting strategic decision-making for political campaigns  

---

## Target Audience

- Political campaign strategists  
- Media planners  
- Advertising analysts  
- Marketing decision-makers  

---

## Limitations

- Dataset is simulated and may not reflect all real-world conditions  
- Engagement scores are estimated  
- Does not include audience demographics  

---

## Future Improvements

- Incorporate real-time audience data  
- Add demographic targeting features  
- Include digital advertising integration  
- Expand dataset across more events and seasons  

---

## Project Structure

- `.ipynb` → full analysis and model  
- `.pdf` → project report  
- `.csv` → dataset  

---

## Tools Used

- Python  
- pandas  
- matplotlib  
- Jupyter Notebook  

---

## Author
Shaghayegh Malekshahi  
Data Science & Analytics Intern  
Master’s in Data Science  
