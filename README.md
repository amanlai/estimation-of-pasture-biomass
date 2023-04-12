# Estimation of Pasture Biomass
_by Enkhmanlai Amarsaikhan, Nyamjargal Erdenebaatar, Damdinsuren Amarsaikhan, Munkhdulam Otgonbayar and Batbileg Bayaraa_

Mongolian pasture plays an essential role in the national economy. Reliable pasture biomass estimation is indispensable to support the agricultural sector and also sustainable livelihood in the country. The aim of this study is to determine an appropriate method to estimate and map pasture biomass in a forest-steppe area of Mongolia. 

For this purpose, machine learning methods such as random forest (RF), support vector machine (SVM), and partial least squares regression (PLSR) were compared. As data sources, spectral indices derived from Sentinel-2B image of 2019 and field-measured biomass sample datasets were used. To determine the optimal spectral predictor variables, initially, 20 spectral indices were evaluated using the PLSR. Of these, five indices (i.e. ATSAVI2, EVI, GRVI, IPVI and MSR) with the highest correlation coefficients ($r\ge 0.94$) were considered for further analysis. These indices were also examined and validated by a variable importance analysis. Then, the RF, SVM, and PLSR models were applied to predict and map pasture biomass using the selected five indices. 

The PLSR method demonstrated the highest accuracy with coefficient of determination ($R^2$)=0.899 and root mean square error (RMSE)=10.560 g/m2. The SVM technique showed the second highest accuracy with $R^2$=0.837 and RMSE=12.881 g/m2. The RF model gave the lowest accuracy with $R^2$=0.823 and RMSE=13.430g/m2. Our research showed that different machine learning models might be applied (because in all cases $R^2>0.82$) for a pasture biomass estimation and mapping in the selected test site, but the best result could be achieved by the use of the PLSR.
