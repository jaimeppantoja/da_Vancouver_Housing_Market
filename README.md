# Exploring Vancouver's Real Estate Market: Data Analysis and Visual Insights with Python

## Introduction
This Jupyter Notebook analyzes a dataset of 800 observations sourced from Zillow, filtered from an initial pool of over 4,000 property listings. The study employs a diverse range of data analytic techniques, powered by Python, to generate graphs and visualizations that reveal patterns and insights not immediately evident in the raw data.

The process begins with rigorous data cleaning and preparation, including the resolution of inconsistent formats and handling of missing values, ensuring that the dataset is both accurate and reliable. These foundational steps set the stage for meaningful analysis and interpretation. The final report, accessible via [https://jaimeppantoja.github.io/project_web_real_estate/index.html], presents the findings in an engaging and visually intuitive format.

Key visualizations generated in this study include:
- Heatmaps
- Scatter plots
- Distribution graphs

These visualizations uncover trends and relationships in the data, providing actionable insights for stakeholders. The primary Python libraries utilized in this analysis include:
- **`pandas`** for data manipulation and transformation
- **`matplotlib`** and **`seaborn`** for creating detailed and aesthetic visualizations
- **`folium`** for interactive geographic data representation

By integrating these tools, the report demonstrates a comprehensive workflow—from meticulous data preparation to actionable insights—highlighting both technical proficiency and real-world relevance.

---

## Main Areas of Focus
- Descriptive analytics of housing prices by property type
- Market distribution by property type
- Heatmaps by property type (geospatial analysis)
- Clustering algorithms grouping properties by price and location

---

## Summary of Insights

### Housing Prices Distribution:
- The histograms reveal a skewed distribution across different property types, resembling a market with a presence of luxury properties.
- Condos represent the most accessible option among the various property alternatives.

### Distribution of Property Types:
- 78% of the properties in the study are houses and condos.
- Condos constitute the highest share, representing 44% of the properties in the dataset.

### Geospatial Analysis:
- **Heatmaps:** The spatial distribution analysis reveals that condos are predominantly located near the downtown area, while other property classes tend to be situated on the outskirts. This visualization highlights key geographic trends in the real estate market.
- **Clustering:** By leveraging machine learning algorithms like K-Means clustering, relationships between property prices and their locations were identified. The analysis shows that properties closer to the downtown area are generally associated with higher prices, emphasizing the value of proximity to the city center.

---

## Recommendations

### Market Context and Applications:
This study provides a foundational understanding of the Vancouver housing market, offering meaningful insights into current pricing trends and market conditions. The findings can:
- Help real estate agencies educate their agents about the market.
- Assist individuals or organizations interested in investing in the real estate sector by identifying opportunities.

### Clustering Analysis and Investment Opportunities:
The clustering algorithm highlights distinct zones based on property prices, illustrating areas of varying valuation. Notably:
- Regions near the edges of high-value zones may present opportunities to acquire properties with prime locations at discounted prices.
- This insight is especially valuable for investors or developers seeking strategic entry points into the market.

---

## Tools and Libraries
- **Python**: Primary programming language used.
- **Key Libraries**:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `folium`

---

