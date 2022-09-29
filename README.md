# Python-SDV-SyntheticData-ML
## Evaluate the performance of 9 machine learning models when trained on SDV generated synthetic data and testing it on the original data.
*From the book Hands-on machine learning with Scikit-Learn, Keras & TensorFlow by O'Reilly.*

### Context
The [Synthetic Data Vault](https://sdv.dev/SDV/getting_started/index.html) created an API that allows its users to generate synthetic data with python. The goal of this github repo is to evaluate how well machine learning models that are trained on synthetic data evalute when tested on the test set of the original data. Three different synthetic data synthesizers are evaluated: FastML, Gaussian and CTGAN to which 9 different regressive machine learning are applied. Results are then compared between the machine learning models trained on the synthetic set and machine learning models trained on the original set when tested on the test set of the original dataset.

### Files you'll find 
* README.md file 
* 211015_notebook_code.ipynb -> jupyter notebook
* 220614_Hackathon_Task1_Gaussion.ipynb -> Gaussian code
* 220616_Hackathon_Task1_CTGAN .ipynb -> CTGAN code
* 220614_Hackathon_Task1_FastML.ipynb -> FastML code
* data_with_missing.csv -> dataset


