# Normalisation
Normalisation, also known as min-max scaling, is a scaling technique whereby the values in a column are shifted so that they are bounded between a fixed range of 0 and 1.

MinMaxScaler is the Scikit-learn function for normalisation.

# Standardisation
On the other hand, standardisation or Z-score normalisation is another scaling technique whereby the values in a column are rescaled so that they demonstrate the properties of a standard Gaussian distribution, that is mean = 0 and variance = 1.

StandardScaler is the Scikit-learn function for standardisation.

Unlike StandardScaler, RobustScaler scales features using statistics that are robust to outliers. More specifically, RobustScaler removes the median and scales the data according to the interquartile range, thus making it less susceptible to outliers in the data.

# [Normalisation vs standardisation](https://www.geeksforgeeks.org/normalization-vs-standardization/)
Here comes the million-dollar question — when should we use normalisation and when should we use standardisation?

As much as I hate the response I’m about to give, *it depends*.

The choice between normalisation and standardisation really comes down to the application.

Standardisation is generally preferred over normalisation in most machine learning context as it is especially important when comparing the similarities between features based on certain distance measures. This is most prominent in Principal Component Analysis (PCA), a dimensionality reduction algorithm, where we are interested in the components that maximise the variance in the data.

Normalisation, on the other hand, also offers many practical applications particularly in computer vision and image processing where pixel intensities have to be normalised in order to fit within the RGB colour range between 0 and 255. Moreover, neural network algorithms typically require data to be normalised to a 0 to 1 scale before model training.

At the end of the day, there is no definitive answer as to whether you should normalise or standardise your data. One can always apply both techniques and compare the model performance under each approach for the best result.
