# Taking Steps Towards Reduce Traffic Collisions- A Case Study of London, UK

This repository includes all the files required to carry out the analysis for the CASA0010 Dissertation, which seeks to address the following research question:

**Research Question:**  
*How can ML methods be effectively applied to predict the severity of road collisions and identify spatial variations in the factors influencing different collision hotspots?*

## Project Structure

### Files and Execution Order
To replicate the analysis, please execute the following files in the specified order. Important: Do not clear the Python environment between each step!

- *'dataProcess.ipynb'* is the file containing data cleaning, data visualization, data analysis, and plotting.
- *'hotspot analysis.ipynb'* is the file used for analyzing different road collision hotspots, which helps to derive the spatial differences in influencing factors between these hotspots through comparison.

### Data and Plots

- **Data(csv):**
- *'dft-road-casualty-statistics-casualty-last-5-years.csv'*,
  * 'dft-road-casualty-statistics-collision-last-5-years.csv'*,
  * 'dft-road-casualty-statistics-vehicle-last-5-years.csv'* are the initial data sets.
- *'london_vehicle_collision_casualty.csv'* is the merged dataset.
- *'data_cleaning.csv'* is the dataset after data cleaning and preprocessing.
- *'road_collision_clusters_secondary_no_noise.csv'* is the dataset after clustering.
- *'Different hotspot influencing factors.xlsx'* is used to generate spatial difference charts for different road collision hotspot influencing factors.
- **Plots Folder（image）:**  
  Includes the figures generated during the analysis.
