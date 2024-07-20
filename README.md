# Randomized high order fuzzy cognitive maps as reservoir computing models: A ﬁrst introduction and applications

This repository contains a novel univariate time series (or energy) forecasting technique, which is composed of a group of randomized high order FCM models labeled R-HFCM. The novelty of the proposed R-HFCM model is relevant to merging the concepts of FCM and Echo State Network (ESN) as an efﬁcient and particular family of Reservoir Computing (RC) models, where the least squares algorithm is applied to train the model. From another perspective, the structure of R-HFCM consists of the input layer, reservoir layer, and output layer in which only the output layer is trainable while the weights of each sub-reservoir components are selected ran- domly and kept constant during the training process. As case studies, in this paper we consider solar energy forecasting with public data for Brazilian solar stations, hourly electric load of the power supply company of the city of Johor in Malaysia, solar energy dataset from United States National Renewable Energy Laboratory (NREL), electric load data from the Global Energy Forecasting Competition 2012 (GEFCom 2012), and PJM hourly energy consumption data. The experiments also include the effect of the map size, activation function, the number of order and the size of the reservoir on the accuracy of R-HFCM method. The obtained results conﬁrm the outperformance of the proposed R-HFCM model in comparison to the other methods. This study provides evidence that FCM can be a new way to implement a reservoir of dynamics in time series modeling.

To use R-HFCM model, upload your cleaned and pre-processed dataset. Then run the Jupyter Notebook to see the results. It is necessary to mention that it necessary to install pyFTS library using the following command line code: !pip3 install -U git+https://github.com/PYFTS/pyFTS

## References
Orang, O., de Lima e Silva, P. C., Silva, R., & Guimarães, F. G. (2022). Randomized high order fuzzy cognitive maps as reservoir computing models: A first introduction and applications. Neurocomputing, 512, 153-177, DOI:10.1016/j.neucom.2022.09.030











