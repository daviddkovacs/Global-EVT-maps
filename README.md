
Hello!

We present the workflow for the retrieval of global maps in Google Earth Engine (GEE) of 4 Essential Vegetation Traits (EVTs): 

(1) fraction of absorbed photosynthetically active radiation (FAPAR)
(2) leaf area index (LAI)
(4) fractional vegetation cover (FVC)
(3) leaf chlorophyll content (LCC)


Sentinel-3 (S3) top-of-atmosphere (TOA) OLCI data is used with hybrid retrieval models to infer globally four essential vegetation traits (EVTs):
The models are based on Gaussian process regression (GPR) algorithms trained on SCOPE-6SV model simulations, and so applicable to process TOA OLCI data.
This workflow is the global extension of the regional study: https://github.com/psreyes/S3_TOA_GPR_1
Within the GEE folder, you will find the scripts used to visualize these products in the GEE environment. Furthermore, the Whittaker smoother temporal reconstruction method is implemented in the GEE JavaScript code, that will allow for spatiotemporal reconstruction to obtain gap-free maps.


![12124r1](https://user-images.githubusercontent.com/123364246/219020011-22517ec1-2cf6-4b91-8334-fdd813aac119.png)


You can use the Colab file (Main Python script.ipynb) containing a Python script with comments and descriptions to retrieve the maps in your own GEE environment.
