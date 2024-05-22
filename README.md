Materials Bandgap Prediction using Random Forest Regression
===========================================================

This repository contains code for predicting the bandgap of materials using a Random Forest Regression model. The code is written in Python and utilizes various libraries such as pandas, numpy, scikit-learn, and pymatgen.

Installation
------------

To run this code, you'll need to have Python 3.x installed on your system. You can install the required dependencies using pip:

Copy code

`pip install pandas numpy scikit-learn pymatgen matplotlib seaborn graphviz`

Usage
-----

1.  Clone the repository:

Copy code

`git clone https://github.com/your-username/materials-bandgap-prediction.git`

1.  Navigate to the project directory:

Copy code

`cd materials-bandgap-prediction`

1.  Run the Python script:

Copy code

`python main.py`

This will execute the code and generate the results.

Data
----

The code uses a dataset of materials and their corresponding bandgap values. The dataset is located in the `data` directory and is named `bandgap_data_v2.csv`. The code also generates additional features based on the chemical formulas of the materials, which are stored in the `generated_features` directory.

Features
--------

The code generates various features from the chemical formulas of the materials using the `pymatgen` library. These features include atomic number, atomic radii, atomic volume, atomic weight, and various other properties related to the crystal structures of the materials.

Model
-----

The code uses a Random Forest Regression model from the `scikit-learn` library to predict the bandgap values of materials. The hyperparameters of the model are optimized using a grid search cross-validation strategy.

Results
-------

The code generates parity plots and error metrics (RMSE, MAE, R^2) for both the training and test datasets. It also provides predictions for selected materials such as Si, SiO2, C, Sn, and NaCl.

Contributing
------------

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

Credits
=======

This has been possible under the Skunkworks group of University of Wisconsin Madison.

License
-------

This project is licensed under the GNU General Public License v3.0.
