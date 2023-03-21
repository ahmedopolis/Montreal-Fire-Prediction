# High Fire-Risk Areas in Montreal :fire: :city_sunrise: :fire_engine:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
</br>

## Summary

The herein repository host the necessary assets for the data exploration, cleaning, integration, feature engineering and modelling for predicting fire-risk levels for the greater city of Montreal. Various datasets have been leveraged comprised of fire incidents, crimes, property assessments, demographics, weather conditions and districts all pertaining to the greater city of Montreal and its affiliated cities. Besides the weather and population datasets, Ville de Montréal publishes the datasets. The city of Montreal and its affiliated cities were split through square tesselation via a custom Python solution using geoPandas and Shapely. Each grid were rank by fire-risk for every month between 2015 and 2023. Decision tree models were used for data modelling where both random forest and XGBoost models performed well in accurately classifying high and low fire-risk areas, but XGBoost model was able to identify high-risk areas more efficiently.

## Tools

A variety of tools and techniques were used in different steps of the project. Exploratory analysis was conducted using Python, Excel (pivot table), and Alteryx. Data cleaning, pre-processing, model development, and visualizations were primarily accomplished using Python (Jupyter notebook and libraries) and Tableau.

## License

This codebase is a public domain, so feel free to use this repo for what you want.
