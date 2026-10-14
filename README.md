# Machine Learning e-Portfolio – Activity Code and Reports

Code and written evidence for the e-Portfolio activities of **Machine Learning (ML_PCOM7E), University of Essex Online**.
Each activity has its own folder containing the Jupyter notebook(s) with saved outputs and a separate written report (`.docx`).

| Unit | Activity | Code | Written document |
|------|----------|------|------------------|
| 3 | Correlation and regression – Ex 1 | `unit03_correlation_regression/covariance_pearson_correlation.ipynb` | `Unit03_Ex1_Covariance_Pearson_Report.docx` |
| 3 | Correlation and regression – Ex 2 | `unit03_correlation_regression/linear_regression.ipynb` | `Unit03_Ex2_Linear_Regression_Report.docx` |
| 3 | Correlation and regression – Ex 3 | `unit03_correlation_regression/multiple_linear_regression.ipynb` | `Unit03_Ex3_Multiple_Linear_Regression_Report.docx` |
| 3 | Correlation and regression – Ex 4 | `unit03_correlation_regression/polynomial_regression.ipynb` | `Unit03_Ex4_Polynomial_Regression_Report.docx` |
| 5 | Wiki activity: clustering | `unit05_clustering_wiki/kmeans_animation_replication.ipynb` | `Unit05_Wiki_Clustering_Post.docx` |
| 5 | Jaccard distance / dissimilarity | `unit05_jaccard_distance/jaccard_distance.ipynb` | `Unit05_Jaccard_Distance_Report.docx` |
| 7 | Perceptron – Ex 1 (simple perceptron) | `unit07_perceptron/simple_perceptron.ipynb` | `Unit07_Ex1_Simple_Perceptron_Report.docx` |
| 7 | Perceptron – Ex 2 (AND operator) | `unit07_perceptron/perceptron_AND_operator.ipynb` | `Unit07_Ex2_Perceptron_AND_Report.docx` |
| 7 | Perceptron – Ex 3 (multi-layer, sigmoid) | `unit07_perceptron/multi_layer_perceptron.ipynb` | `Unit07_Ex3_Multi_Layer_Perceptron_Report.docx` |
| 8 | Gradient cost function | `unit08_gradient_descent/gradient_descent_cost_function.ipynb` | `Unit08_Gradient_Descent_Report.docx` |
| 9 | CNN model activity | `unit09_cnn/cnn_object_recognition.ipynb` | `Unit09_CNN_Report_and_Ethics.docx` |
| 11 | Model performance measurement | `unit11_model_performance/model_performance_measurement.ipynb` | `Unit11_Model_Performance_Report.docx` |

## Running the notebooks
```bash
pip install -r requirements.txt
jupyter notebook
```
Or upload any notebook to Google Colab. All random seeds are fixed, so results are reproducible.

## Notes
* The notebooks are original implementations written for these activities; the module’s own starter notebooks are on the Essex Software Hub.
* `unit09_cnn/cnn_object_recognition.ipynb` tries to load **CIFAR-10** and falls back to scikit-learn’s bundled 8×8 digits dataset if the download is not possible. The dataset used is printed at the top of the output. The saved outputs in this repository come from the digits fallback; re-run the notebook on Colab to regenerate them on CIFAR-10.
* The Unit 5 wiki document includes draft peer replies in square brackets, to be adapted after reading peers’ posts.
