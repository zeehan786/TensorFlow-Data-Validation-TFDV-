# TensorFlow-Data-Validation-TFDV- (Coursera Assignment)
TensorFlow Data Validation is an open source library to analyze, validate, and monitor machine learning data at scale.

TFDV generates a schema from the training set to evaluate various requirements for future serving dataset. It detects and visualizes the presence of anomalies (e.g.: missing features, out of range or null values, training skew).

Moreover, TFDV uses tools such as Facet to provid interactive visuals to display various stats for the data. With these visuals, users can easily comprehend data and spot for any unpredicted features.

With such useful features, TFX components (StatisticsGen, ExampleValidator and SchemaGen) use TensorFlow Data Validation under the hood to work with large data scales.
