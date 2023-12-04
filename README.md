# Low-Surface-Brightness-Galaxy
Candidates_LSBG.csv: Catalog of Low Surface Brightness Galaxy includes 37,536 LSB galaxy candidates.

TrainSample_LSBG.csv & ValSample_LSBG.csv: Catalog of Low Surface Brightness Galaxy in train set and val set.

**Please Note:**

The columns in the catalog represent：

***Flag***:  indicates source of the coordinates. '1' indicates that the R.A. and Dec. coordinates were provided by SDSS, while '0' indicates that the R.A. and Dec. coordinates were predicted by the GalCenterNet model.

***Confidence score***: The confidence score assigned by the GalCenterNet. It provides a measure of how reliable the model believes its predictions are. The confidence score vary between 0 and 1, where a higher value indicates a higher confidence level in the prediction.

***Anomaly score***: The anomaly score provided by Deep-SVDD anomaly detection model. A higher anomaly score indicates that the LSB galaxy is considered more deviating from the norm.
