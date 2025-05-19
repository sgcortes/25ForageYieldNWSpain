# 🌽 25ForageYieldNWSpain
Data and code for article: "A machine learning approach for estimating forage maize yield and quality in NW Spain".

## Code: Jupyter Notebooks for forage maize yields (Dry Matter, Crude Protein and UFL)

* 📙 [Dry Matter forage maize yield predcitions using Machine Learning ensemble methods for NW of Spain](https://github.com/sgcortes/25ForageYieldNWSpain/blob/main/V7_DM_RFR_LGBM_XGB_OPTUNA_SHAP_PERMU_kgDM_RAD_Dia_Export.ipynb)
* 📙 [UFL(Plant Lactation Total Energy) forage maize yield predcitions using Machine Learning ensemble methods for NW of Spain](https://github.com/sgcortes/25ForageYieldNWSpain/blob/main/V7_UFL_RFR_LGBM_XGB_OPTUNA_SHAP_PERMU_kgDM_RAD_Dia_Export.ipynb)
* 📙 [Crude Protein forage maize yield predcitions using Machine Learning ensemble methods for NW of Spain](https://github.com/sgcortes/25ForageYieldNWSpain/blob/main/V7_CP_RFR_LGBM_XGB_OPTUNA_SHAP_PERMU_kgDM_RAD_Dia_Export.ipynb)
* 📙 [Dry Matter forage maize yield predcitions using Machine Learning ensemble methods and Bootstrapping for NW of Spain](https://github.com/sgcortes/25ForageYieldNWSpain/blob/main/V8_BoostrappingRFR_LGBM_XGB_OPTUNA_SHAP_PERMU_kgDM_RAD_Dia_Export.ipynb)

## Dataset:

📅 [Dataset (MS Excel file)](https://github.com/sgcortes/25ForageYieldNWSpain/blob/6cec3334f8163dfc43892384b56c27ee7168ea92/260324_ENG_MaizeForageSpainNWwtYearRadDay.xlsx)

The data file contains 1449 data for forage maize production covering 23 years from 2000 to 2022 and corresponds to 7 locations in NW of Spain (Grado, Barcia and Villaviciosa) in Asturias and (Ordes, Ribadeo, Sarria and Deza) in Galicia region. 
The production variables are: 
  * kg DM/ha, kilograms of Dry Matter by hectar 
  * UFL / ha, Unit of Forage milk by hectar
  * kg CP / ha, kilograms of Crude Protein by hectar

The input variables are 14:
|   	|   	|   	|   	|
|---- |----|-----	|----- |
|Location   	| Year  	| Cultivar 	| Sowing date(Julian day) |Growing Season (days)|
| Elevation (m)  	|WHC(mm)   	|C(%)    	| pH  	|
| Tmax(ºC)  	| Tmin(ºC)  	| Radiation(MJ/m2 day)  	|Precipitation(mm)   	|
|Anthesis date(Julian day) |Harvest date(Julian day) |---- |---  | 
