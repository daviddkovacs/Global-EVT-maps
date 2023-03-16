This folder contains the JavaScript codes that are for the processing of the S3-TOA-GPR-1.0 vegetation maps in GEE. These scripts allows you to visualize and investigate time series of different locations of your interest. Additionally, the Whittaker smoother is implemented into the code and thus allows for the spatiotemporal reconstruction of the maps.

![image](https://user-images.githubusercontent.com/123364246/219391936-898085ea-9b5b-4a14-b8f8-5efbf0130be3.png)


The code features the S3-TOA-GPR-1.0 maps, the Whittaker smoother temporal reconstruction and the Gaussian Process Regression's Uncertainties too. The code is written in a way that you can change the temporal domain of your interest. Keep in mind that the visualization of the data on the global map is the mean pixel value of the images within your set temporal domain.



FAPAR:
https://code.earthengine.google.com/?scriptPath=users%2Fdkvcsdvd%2FGlobal_EVT_maps%3AFAPAR

LAI:
https://code.earthengine.google.com/?scriptPath=users%2Fdkvcsdvd%2FGlobal_EVT_maps%3ALAI

FVC:
https://code.earthengine.google.com/089dde7496257bd0aab5d7e6b6603fec

LCC:
https://code.earthengine.google.com/5908670f83306cf99ffe02ed26a8d2ed
