# Machine Learning based Flood Mapping

The repository contains code base for automatic classification for flood water using remote sensing and utilizing capabilities of Google Earth Engine integrated with Tensorflow model.

* The key steps in the classification procedure include:

  1. Exporting training/testing data from Earth Engine in TFRecord format - Four flood events in US.
  2. Preparing the data for use in a TensorFlow model.
  3. Training and validating a Sequential model in TensorFlow.
  4. Making predictions on image data exported from Earth Engine in TFRecord format.
  5. Ingesting classified image data to Earth Engine in TFRecord format.

* Needs Cloud Storage credits to which files will be written/imported from.

* The code has been modified  from [TF_demo1_keras.ipynb](https://github.com/google/earthengine-api/blob/master/python/examples/ipynb/TF_demo1_keras.ipynb)

* For any questions/comments, please contact skahmad@uw.edu
