## A Transformer-Based Framework for Geomagnetic Activity Prediction<br>
[![DOI](https://github.com/ccsc-tools/zenodo_icons/blob/main/icons/kp.svg)](https://zenodo.org/record/7514451#.Y7xGhRXMLrl)


## Authors
Yasser Abduallah, Jason T. L. Wang, Chunhui Xu, and Haimin Wang

## Abstract

Geomagnetic activities have a crucial impact on Earth, which can affect spacecraft and electrical power grids.
Geospace scientists use a geomagnetic index,
called the Kp index,
to describe the overall level of geomagnetic activity.
This index is an important indicator of disturbances in the Earth's magnetic field 
and is used by the U.S. Space Weather Prediction Center as an alert and warning service
for users who may be affected by the disturbances.
Early and accurate prediction of the Kp index is essential for 
preparedness and disaster risk management. 
In this paper, we present a novel deep learning method, named KpNet, 
to perform short-term, 1-9 hour ahead, forecasting of the Kp index 
based on the solar wind parameters taken from the NASA Space Science Data Coordinated Archive. 
KpNet combines transformer encoder blocks with Bayesian inference, 
which is capable of quantifying both aleatoric uncertainty (data uncertainty) and 
epistemic uncertainty (model uncertainty)
when making Kp predictions. 
Experimental results show that KpNet outperforms closely related machine learning methods 
in terms of the root mean square error and R-squared score. 
Furthermore, KpNet can provide both data and model uncertainty quantification results, which the existing methods cannot offer.
To our knowledge, this is the first time that
Bayesian transformers have been used for Kp prediction.

## Binder

This notebook is Binder enabled and can be run on [mybinder.org](https://mybinder.org/) by using the link below.


### ccsc_solarflare.ipynb (Jupyter Notebook for Kp-prediction)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zhangsgithub04/Kp-prediction/HEAD?labpath=YA_01_ATransformerBasedFrameworkForGeomagneticActivity.ipynb)

Please note that starting Binder might take some time to create and start the image.

Please also note that the execution time in Binder varies based on the availability of resources. The average time to run the notebook is 15-20 minutes, but it could be more.

For the latest updates of the tool refer to https://github.com/deepsuncode/Kp-prediction



## Installation on local machine
To install TensorFlow with pip refer to https://www.tensorflow.org/install/pip

Tested on Python 3.9.16 and the following version of libraries
|Library | Version   | Description  |
|---|---|---|
|keras| 2.10.0 | Deep learning API|
|numpy| 1.24.2| Array manipulation|
|scikit-learn| 1.2.1| Machine learning|
|matplotlib| 3.6.3| Visualization tool|
| pandas|1.5.3| Data loading and manipulation|
| seaborn | 0.12.2| Visualization tool|
| scipy | 1.10.0| Provides algorithms for optimization and statistics|
| tensorflow| 2.10.1| Comprehensive, flexible ecosystem of tools and libraries for machine learning |
|tensorflow-probability | 0.17.0| For probabilistic models|
