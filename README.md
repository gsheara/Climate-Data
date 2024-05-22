# Climate-Data
Changes in overall climate, such as global warming, have the capacity to impact all aspects of the planet from weather patterns and storm intensity to individual ecosystems and habitats. Being able to observe, analyze, and predict the trends of the changes is crucial in addressing and preventing future damage from being done. The purpose of this notebook is to compare the average sea surface temperature of the southern and arctic oceans and forecast change in average temperature into the future.

# Description
The datasets used come from the ERA5, which observes hourly global climate measurements. This project focuses on the southern and arctic oceans. Using a moving average analysis of sea surface temperatures and a Prophet model prediction, it seems that the southern ocean changes sea surface temperature in cycles and is warming more gradually, compared to the Arctic ocean whose sea surface tempearture is more steeply increasing.

# Requirements
This project utilizes free and open source materials such as the Python libraries used for analysis and visualization (matplotlib, numpy, pandas, scipy) and datasets which can be found in this repository. 

# Data
The data used for this project includes two dataframes, one containing measurements on the Southern Ocean and one on the Arctic Ocean. This project focuses on the sea surface temperature observed in each ocean. 

Southern ocean dataset: https://github.com/gsheara/Climate-Data/blob/0fa908aa0de88fbe7457d8b925c8cfe6356c8c41/southern.csv

Arctic ocean dataset: https://github.com/gsheara/Climate-Data/blob/0fa908aa0de88fbe7457d8b925c8cfe6356c8c41/arctic.csv

# Data processing
The data was analyzed and visualized using a moving average of the daily signal of the sea surface temperatures and the Prophet model for prediction. A Colab notebook used to perform analysis can also be found in this repository.

Analysis Notebook link: https://github.com/gsheara/Climate-Data/blob/f7d3898bc52710fed766e7476a4e60968665e7aa/Climate_Analysis_Notebook.ipynb

# Authors
This project and corresponding repository was created by Genny Sheara for an assignment in DATA 3320: Data Methodologies at Seattle University. LinkedIn: https://www.linkedin.com/in/genny-sheara/

# License
All data and tools utilized for this project are open source and reproducible by anyone.
