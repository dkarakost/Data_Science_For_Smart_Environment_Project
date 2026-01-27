### The background 

Visualizing data with different kinds of plots or figures is a crusial step in data analysis, both for exploration and communicating results. Effective visualizations help identify trends and relationships before applying modeling techniques.

At the beginning of the course, my experience with data visualization was mainly limited to the matplotlib library. While I was able to create basic plots, I lacked familiarity with more advanced visualization tools and spatial analysis libraries. In particular, I had limited experience using Seaborn for statistical visualizations and GeoDa for spatial data exploration.

---

### Methodology and data sourced used 

To achieve this goal, I used python and Jupyter Notebooks as enviroment setup with a focus on Seaborn Library. I also used GeoDA for quick spatial analysis since the dataset includes coordinates. 

The data sources that were two in CSV format: 

- The dataset *report_eng(Beaches)* holds the information about the names of the beaches and the trashes quantities. This dataset was primarily used for early-stage exploration and spatial analysis.

- The dataset *cleaned_data.csv* is the merged dataset which contains information the user ratings, the beaches names, location and trash amount. This dataset was used for the final visual analysis and interpretation.


---


### Details about the implementation 

The implementation is provided in two Jupyter Notebooks: 

 ##### Data_Analysis_beforeMerge.ipynb

- It removes unnecessary columns to simplify data.
- Groups beaches by region and other categories to create summary tables for the visuals.
- Generates plots (bar charts and scatterplots) to compare the distributions across regions regarding the beach pollution.
- Generates lineplots to for highlighting trends across seasons.
- Uses visuals as an exploratory tool before further analysis or merging.

 ##### DataAnalysis_afterMerge.ipynb

- It loads merge data and creates summary tables for visualization. 
- Groups and aggregates the data according to ratings and trash amount per beach.
- Generates scatter plot showing the relationship of trash amount and ratings.
- Generates scatter plot with correlation line between the user ratings and trash amount

---

### Results 

The final output of the analysis consists of multiple plots and figures. These plots provide a quick overview of the datasets and help identify correlations between beach pollution and other variables such as beach length, season and user ratings.

Compared to my initial approach, which relied solely on matplotlib, this project demonstrates use of Seaborn for statistical visualization and GeoDa for spatial data exploration. The plots are more informative, simplified and meaningfull in highlighting the insights.

---

### Conclusion 

The visual analysis and the generated plots represent the findings of the project. They used as exploratory analysis of the dataset. They demonstrate the ditribution of the amount of trash, the correlation between beach pollution and user ratings, overall ratings and beach length.


The learning goal was achieved, as I am now more confident using additional visualization libraries beyond matplotlib, particularly Seaborn and GeoDa, to explore and present both statistical and spatial data. I am able to create meaningful, interpretable visualizations and organize them into a clear analytical pipeline.