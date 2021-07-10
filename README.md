# ICORT
## File Descriptions
#### Classification
###### contains files for classifying the correct resizing factor
- `UCR_RF_Classification.ipynb :` Implementation of proposed method for classification of resizing factor into 1 of 10 candidate factors
- `bayar(2016).ipynb :` Contains pipeline for benchmarking against bayar's method of constrained convolution
- `classification_bayar.hdf5 :` Saved weights for model trained in bayar(2016).ipynb
- `model.hdf5 :` Saved weights for proposed model for classification
#### Detection
###### Contains files for detecting presence of resizing in an image
- `bayar(2016)_detection.ipynb :` Bayar's method for detection of resizing
- `UCR.ipynb :` Implementation of propsed method for detection of resizing in an image
- `final.hdf5 :` Saved weights for proposed model for detection
- `detection.hdf5 :` Saved weights for bayar's method employed for resizing detection

