# Hyper-parameter optimization system
The code runs in Python3.7

### Required modules:
* NumPy
* Pandas
* Matplotlib
* liac-arff
* joblib
* scikit-learn
* h2o (& its dependencies see: http://docs.h2o.ai/h2o/latest-stable/h2o-docs/downloading.html)
* TensorFlow
* keras

### Execution instructions
1. Create the following folder tree:\
![alt text](https://github.com/Dimiexe/automl/blob/master/exapmle_system.png?raw=true)
2. The contents of the "final_models" and "regularization" dirs must be the same with the ones in this repo.
3. Place your new dataset in the "test_dataset" dir.
4. Set your preferences in the 4th cell of the "Process new dataset.ipynb" file.
    * path to the "example_system" dir
    * prefered algorithm (GLM, RF, XGboost)
    * Print runtime info (yes, no)
    * H2O cluster options (memory, threads)
5. Run the application by executing all cells in the "Process new dataset.ipynb" file.
6. The resulting base-learning model is saved in "final_results_base_learning", along with a rutime report in csv form and a .jar file.
