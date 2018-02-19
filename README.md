This project provides 1D Convolutional neural network (CNN) application for the recognition of chemical volatiles.
We use three datasets obtained with e-nose detection systems in realistic environments.

The first data set is UMA. In this data set, there are 69 samples belonging to seven different substances. For full dataset please visit: http://mapir.uma.es/mapirwebsite/index.php/people/109-javier-gonzalez-monroy

And you can find some articles about this dataset:
F.M. Schleif, B. Hammer, J.G. Monroy, J.G. Jimenez, J.L. Blanco-Claraco, M. Biehl, N. Petkov, Odor recognition in robotics applications by discriminative time-series modeling, Pattern Anal. Appl. 19 (2016) 207–220. doi:10.1007/s10044-014-0442-2.

Four different classes were considered for this dataset. Commercial alcohols (Negrita Rum, Larios and Gordon Gin, and Cointreau) were considered as a single class, and the other classes were acetone, butane, and ethanol. Four sensor outputs (TGS-2600, TGS-2602, TGS-2611 and TGS-2620) were used for the odor data of each substance in the data set for the study. 

We organized this dataset as UMAX.csv (time-series) and UMAY.csv (labels). 
UMAX.csv contains 69 (samples) x 1042 (time steps) x 4 (feature) 

