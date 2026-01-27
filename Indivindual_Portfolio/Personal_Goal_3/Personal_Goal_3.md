### The background 

Visualizations and representations of results often fail to reach a general audience. Depending on the goal, the interpretation of results can be difficult for readers with limited knowledge of the subject. This can lead to important data findings being overlooked due to their abstract nature.


At the begging of this course, I was able to create plots and maps to support my analyses, however these visualizations often required a technical background of the reader in order to be unstandable. This learning goal focuses on improving my ability to transform the insights of the results into a contenxt understoundable into a broader audience.

---

### Methodology and data sourced used 

To achieve this goal, I reused the cleaned and merged beach dataset developed in previous stages of the project. This allowed me to focus less on data processing and more on how results are communicated. From the jupyter notebooks i could integrate the plots into the story map and from merged dataset i could create interactive density maps as feature layers inside the ArcGIS storymap environment.

The data sources were: 

- All the generated plots from the reusable Jupyter Notebooks by using Python, Matplotlib and Seaborn.
- The cleaned_data.csv dataset that contains the coordinates for each beach along with the trash amount.
- The story map format to present resuts also as density maps and a intepretable development of the project.
 

---


### Details about the implementation 

The implementation is provided in an ArcGIS storymap and a jupyter notebook file.

The jupyter notebook file: 

**DataAnalysis_afterMerge.ipynb**

- It loads merge data and creates summary tables for visualization. 
- Groups and aggregates the data according to ratings and trash amount per beach.
- Generates scatter plot showing the relationship of trash amount and ratings.
- Generates scatter plot with correlation line between the user ratings and trash amount


The link for the story map:

https://storymaps.arcgis.com/stories/c11ea261c3e04dc18d68c065b9c520c4

The StoryMap demonstrates the project’s goals, methodology, and results in a coherent sequence, with integrated visualizations.



---

### Results 


The visual analysis shows that higher user ratings or tourist presence do not necessarily correspond to cleaner beaches except the seasonal Trend. This insight represents that there can be other variables that affect beach pollution such as the location, or events like concepts. Regarding seasonal variation, there was slight decrease in trash levels was observed each spring. To extent the results more I used machine learning to predict the amount of trash for the next season per beach. Altough the pipeline for the machine learning is working the prediction accuracy is very low.

The audience can easily understand: 

- How pollution levels accross locations.
- The user ratings and tourism presence don't strongly correlate with pollution.
- Which beaches exhibit the highest pollution levels through interactive exploration of density maps.

---

### Conclusion 

By focusing on simplified visuals and explanatory observations, the results become accessible to a broader audience. The story map format is less technical related and represents the path of the project devopment and findings. In this way, the audience is guided through the analysis in a more socially meaningful structure, allowing viewers to understand the insights without specialized knowledge.


The learning goal achieved. I am now able to communicate analytical results clearly and effectively to non-technical audiences by simplifying concepts, using intuitive visual explanations but there is always room for improvement. Additionally, the use of interactive maps enhances the reader’s geospatial awareness of beach locations and pollution patterns.
