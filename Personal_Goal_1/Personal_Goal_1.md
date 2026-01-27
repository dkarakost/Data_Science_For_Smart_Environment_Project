### The background 

Data acquisition, preperation and wrangling are fundamental steps in any data science project.
Poorly structured or inconsistent data can significantly increase the data preperation and analysis time, leading to a downgrade in the quality of the results.

At the begging of the course, I had basic knowledge of data acquisition and preprocessing, as I was familiar working only with cleaned datasets that can be downloaded directly from browser and required less preparation. I lacked the knowledge of getting a dataset in different format such as JSON and doing efficient data preperation.

---

### Methodology and data sourced used 

To achieve this goal I used Python and Jupyter Notebooks in order to structure a reusable pipeline for data acquisition, preperation and wrangling. In the Jupyter Notebook I successfully accessed Google Places API to acquire the data into JSON format and by using pandas I saved the data into CSV format. For data preparation and wrangling, Pandas was used to load, clean, and transform the data into appropriate data types, ensuring consistency and supporting further analysis.

The data sources used include publicly available datasets (e.g., CSV and JSON files). In the project can be found as: 

- **report_eng(Beaches)** The dataset contains the name and the location of the beaches(WWF Dataset).
- **materials-record.csv** The dataset contains generic information per beach in Italy (WWF Dataset).
- **beaches_corrected_final** The dataset that was created after quering the user reviews from the Google Places API. 

The complete workflow is documented in two Jupyter notebooks that demonstrate a data acquisition and preprocessing pipeline.


---


### Details about the implementation 

The implementation is provided in two Jupyter Notebooks: 

##### GoogleMapData.ipynb

- Set up the enviroments such as requests, pandas and time.
- Configure the Google Places API key which is needed to fetch location dta from Google Maps.
- Loads a file *report_eng(Beaches)* which contains the name and the location of the beaches.
- Query Google Places API where it sends requests to the Google Places API to retrieve additional information such as coordinates and ratings.
- The collected results from the API which was in JSON format, is organized into a pandas dataframe and saved as a CSV for futher analysis.


##### DataPreperation.ipynb

- It loads multiple datasets such as the WWF dataset and the reviews dataset from Google Places.
- Cleans and standardize the beach names to be consistent in both datasets. 
- Merge the datasets into one table and then drops unnecessary or irrelevant columns. 
- Handles the missing values and apply data wrangling by converting text values to numeric.
- Exports a csv file ready for data analysis.


---

### Results 

The final output of the pipeline is a clean and consistent dataset that can be directly used for exploratory analysis or modeling.

Compared to my initial approach, the structured pipeline reduced
data preparation time and improved code readability and reusability.
Summary statistics included in the notebook demonstrate the quality of the processed data.

---

### Conclusion 

The results show that selection the data source, either from a website or from a service by using API key can play a big role in data acquisition, preperation and wrangling. It can improve or degrade the overall efficiency and data quality.

This learning goal was acchieved as, I am able now to collect data from different sources. Clean and transform the retrieved data in order to be ready for further analysis. Finally to wrap all the above in reusable and organized pipelines.