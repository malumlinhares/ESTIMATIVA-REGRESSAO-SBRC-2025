# ESTIMATIVA-REGRESSAO-SBRC-2025
Code and datasets from the study "Network Performance Estimation Based on Regression Techniques Applied to Monitoring Data", presented at SBRC 2025.

This repository provides the code and datasets used in the study "Network Performance Estimation Based on Regression Techniques Applied to Monitoring Data", presented at SBRC 2025. The study explores the use of regression models to estimate network throughput based on monitoring metrics like delay and traceroute.


Repository Content
code/: Contains the Python scripts used for data preprocessing, regression model training, and result evaluation.

    preprocessing.py: Script for processing and merging throughput, delay, and traceroute data.
    model_training.py: Script for training and evaluating regression models.
    evaluation.py: Script for computing performance metrics such as NRMSE and accuracy.
    data/: Contains the datasets used in the study, sourced from the National Education and Research Network (RNP).

    throughput_data.csv: Throughput data collected at 4-hour intervals.
    delay_data.csv: Delay data collected every minute.
    traceroute_data.csv: Traceroute data collected every 10 minutes, including the number of hops and identification of bottleneck links.

results/: Contains the experiment results, including performance metrics and visualizations.
    nrmse_results.csv: Normalized Root Mean Square Error (NRMSE) results for each model and communication point.
    accuracy_results.csv: Accuracy results per range for the selected models.
    plots/: Graphs generated during the model evaluation process.

requirements.txt: List of dependencies required to run the Python scripts.




