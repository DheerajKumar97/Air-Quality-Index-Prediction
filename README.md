# Air-Quality-Index-Prediction

# Data Summary

Air pollution is one of the most widespread problem in India today. Breathing bad quality air has robbed the country with its significant opportunity to grow, and has costed huge human and economic losses. Monitoring and forecasting the status and trends of ambient air quality to ascertain air quality standards is one of the important step to address this issue.

This report presents results of forecasting the Air Quality Index for the City of Mumbai for the month of January 2017 using time series analysis. 

The report highlights performance of various time series models built to forecast the AQI based on four major pollutants – PM10, PM2.5, SO2 and NO2 and using these results forecast the overall quality of air for Mumbai. 

The models are built using data driven and regression based techniques to obtain most accurate results. The performance evaluations of the adopted models are carried out on the basis of MAPE and RMSE. The results indicate that the models provide satisfactory predictions for the air quality parameters and can be used for practical assessment.

# Features of Data

**T**       Averrage Temperature.

**TM**      Maximum Temperature.

**Tm**      mininmum Temperature.

**SLP**     Atmopheric pressure at sea level.

**H**       Averrage relative humidity.

**PP**      Total Rainfall.

**VV**      Averrage Visibility.

**V**       Averrage Wind Speed.

**T**       Averrage Temperature.

**PM 2.5**  Atmopheric pressurePM 2.5.

# Model Accuracy 

 #                       # R2_Score	          RMSE	          MSE	              MAE
# Model				
# Desicion Tree	           0.648079	          50.485125	         2548.747819	       24.255094
# Cross_Validated_DTree    0.569868	          55.813792	         3115.179380	       40.505720
# Random Forest	           0.762237	          41.496613	         1721.968918	       29.188837
# Cross_Validated_RF	     0.819211	          36.184870	         1309.344807	       22.567863
# XGboost	                 0.762237	          41.496613	         1721.968918	       29.188837
# Cross_Validated_Xgb	     0.836624	          34.398088	         1721.968918	       29.188837
