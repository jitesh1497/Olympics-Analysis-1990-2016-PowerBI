# Olympics Analysis 1990-2016



**Problem Statement :**

### Problem Statement

The Olympics stand as more than just a premier global sporting event; they are a mirror reflecting the broader themes of societal evolution, gender equity, and international rivalry. With a legacy stretching back over a century, the Olympics serve as a stage where the shifting dynamics of sports, shaped by nations and gender, play out in real-time. However, gaining a deep understanding of these dynamics—especially in terms of gender representation, national dominance, and the comparative success of athletes across different Olympic seasons—remains a complex endeavor.

In this Power BI project, I undertake a comprehensive analysis of the Olympics dataset spanning from 1990 to 2016. The analysis delves into critical areas such as the distribution of medals across genders, the evolving ratio of male and female athletes over the years, and the standout performances of countries and individual athletes. Additionally, the project explores the participation trends of nations, the diversity of sports featured in both the Winter and Summer Games, and a comparative assessment of athletic achievements across these two distinct Olympic seasons.

The ultimate goal of this analysis is to illuminate the evolving landscape of international sports, shedding light on both the advancements made and the areas where further progress is required. By highlighting trends in gender equality and global representation within the Olympics, this project aims to contribute to a deeper understanding of how the Games continue to shape and reflect broader societal changes.

## Snapshot of Dashboard

![Screenshot 2024-08-14 164846](https://github.com/user-attachments/assets/3b5e44c5-43e8-43a6-bf96-c928910566bd)

#  Steps Followed

1) Extract the CSV File:

Began by extracting the Olympics dataset in CSV format.

2) Data Transformation:

i)Delete Irrelevant Columns: Removed columns like Height and Games that were not relevant to the analysis.

ii)Make First Row as Header: Converted the first row into the header to ensure proper column naming.

iii)Remove Notes Column: Deleted the first column as it contained unnecessary notes.

3) Data Cleaning:


i) Rename Columns: Renamed the country_definition.noc column to Country for clarity and consistency.

ii) Standardize Gender Labels: Replaced 'M' and 'F' in the Gender column with 'Male' and 'Female' to enhance readability.

iii) Check for Null Values: Identified and handled null values found in the Country column to ensure data integrity.

4) Data Integration:

Join Tables: Performed a full outer join on two tables with the common column NOC to consolidate the data.

5) Upload Data to Power BI:

Imported the cleaned and transformed dataset into Power BI for further analysis.

6) Data Modeling:

Established relationships between tables and ensured data consistency.

7)Visualization Creation:

i) create Charts: Developed various visualizations, including gender-wise medal distribution, male-to-female ratio by year, top 10 countries by total medals, and more.

ii) Compare Olympic Seasons: Analyzed the differences in medal counts between Summer and Winter Olympics.

iii) Identify Top Athletes: Highlighted top Olympic medalists based on total medals won.



# Specific Analysis:

**1. Pie Chart - Medals Won by Gender**

- **Male:** 196.3k Medals (72.53%)
- **Female:** 74.39k Medals (27.47%)

**Insight:**  
The data reveals a significant gender disparity in the distribution of Olympic medals, with male athletes winning nearly three times as many medals as female athletes. This disparity reflects the historical gender imbalance in sports participation and opportunities, although the gap has been narrowing over recent decades. The increase in female participation over time has begun to shift these proportions, indicating progress toward gender equality in sports.

---

**2. Stacked Column Chart - Count of Individual Medals**

- **Top Athlete:** Michael Fred Phelps, II

**Insight:**  
Michael Phelps stands out as the most decorated Olympian of all time, with an unparalleled count of individual medals. His dominance in swimming is evident, underscoring his status as a global sports icon and a testament to the power of dedication, training, and athletic prowess.

---

**3. Stacked Area Chart - Athlete Participation by Year and Gender**

- **Insight:**  
This chart illustrates the trend of athlete participation over the years, segmented by gender. The gradual increase in female participation reflects the broader societal shifts toward inclusivity and the breaking down of barriers in sports. The data highlights significant milestones where female representation saw marked increases, correlating with global movements toward gender equality and the introduction of more women's events in the Olympics.

---

**4. Stacked Bar Chart - Medals by Country in Summer and Winter Olympics**

- **Insight:**  
The analysis reveals that some countries excel predominantly in the Summer Olympics, while others show strength in the Winter Games. Countries like the USA and Russia dominate in both seasons, indicating a well-rounded sports development program. In contrast, nations like Norway and Canada show particular strength in winter sports, reflecting their geographical and climatic advantages.

---

**5. Matrix - Total Medals Won by Country (Alphabetical Order)**

- **Insight:**  
This matrix provides a comprehensive view of each country's total medal tally, listed alphabetically. It offers an organized way to assess the performance of nations across the Olympics, allowing for easy comparison and highlighting the achievements of countries that might otherwise be overlooked in the overall rankings.

---

**6. Cards - Key Metrics**

- **Total Medals Given Till Date:** 39.77k
- **Count of Sports:** 67
- **Count of Countries That Won Medals:** 148
- **Count of Events:** 766

**Insight:**  
These key metrics offer a quick, at-a-glance overview of the scale and diversity of the Olympic Games. The large number of medals awarded and the wide variety of sports and events underscore the global and inclusive nature of the Olympics. The participation of 148 countries in winning medals highlights the universal appeal and reach of the Games, with nations from every corner of the globe achieving success.



