
## Metadata 

* **report_eng(Beaches)**

```This dataset contains the beaches names, location, country and coordinates it can be used to retrieve the beaches from Google Places with naming and location matching ```

---


* **beaches_v2-b**

```The dataset contains the retrieved information from the Google Places API. It has the user ratings and the amount of the overall users as well as the type, the vicinity and the coordinates that the API return.```

---

* **Beaches_corrected_final**

```IMPORTANT this dataset is a manually corrected version of the beaches_v2-b.csv file where it has the correct names, beaches location it will be used for merge with the materials-record file ```

---

* **materials-record**

```The dataset contains generic information per beach in Italy. It can be used to do some quick statistical analysis and follong the steps it will to be merged with the Beaches_corrected_final file ```


--- 


* **merged_dataset_v2**

``` This dataset is the merged dataset that has both the trash, beach, user ratings and overall ratings but with inconsistent coordinates  ```

---


* **Cleaned_data**

```This is a new version of merged_dataset_v2 which has the corrent and consistent coordinates. Later it is used to do Stastical analysis and machine learning ```



## Workflow 

- **Step 1:** Open the GoogleMapData.ipynb file use your Google Api Key in order to have the Beaches_v2-b file 
- **Step 2:** (Optional) open the file Data_Analysis_beforeMerge.ipynb to do a quick statistical analysis to WWF dataset
- **Step 3:** Open the DataPreperation.ipynb file. In the file load the manually corrected file beaches_corrected_final, which all the rows represent the corrected named and located beaches. Otherwise you can use the Beaches_vs-b but contains less beaches. 
- **Step 4:** Open the clean_coords.ipynb to correct the files data from merged dataset 
- **Step 5:** Open the DataAnalysis_afterMerge.ipynb to check the correlation of tourists and trash that has been found at each beach.
- **Step 6:** Open the interactive_heatmap.ipynb to create and download interactive heatmaps regarding the trash distribution.
- **Step 7:** Open Machine_Learning.ipynb to predict the beach amount for each beach for the next season.



## Results 

Inside the results folders there are plots and interactive density maps. Those plots and maps comes from the jupyter notebooks files after executing them successfully.

