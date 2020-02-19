[![image](https://sigopt.com/static/img/SigOpt_logo_horiz.png?raw=true)](https://sigopt.com)

# Parallelism

Example using the [SigOpt Python API Client](https://sigopt.com/docs/overview/python) to tune a classifier in parallel. Shows how to create the experiment once on master, then spin up multiple workers to each run an optimization loop. SigOpt acts as the scheduler, making sure each worker gets the right Suggestion at the right time. Learn more from [the docs](https://sigopt.com/docs/overview/parallel).

## Setup
1. Log in to your SigOpt account at [https://app.sigopt.com](https://app.sigopt.com)
2. Find your API Token on the [API tokens page](https://app.sigopt.com/tokens).
3. Install requirements `pip install -r requirements.txt`

## Questions?
Any questions? Drop us a line at [support@sigopt.com](mailto:support@sigopt.com).

## API Reference
To implement SigOpt for your use case, feel free to use or extend the code in this repository. Our [core API](https://sigopt.com/docs) can bolt on top of any complex model or process and guide it to its optimal configuration in as few iterations as possible. 

## About SigOpt

With SigOpt, data scientists and machine learning engineers can build better models with less trial and error.

Machine learning models depend on hyperparameters that trade off bias/variance and other key outcomes. SigOpt provides Bayesian hyperparameter optimization using an ensemble of the latest research.

SigOpt can tune any machine learning model, including popular techniques like gradient boosting, deep neural networks, and support vector machines. SigOpt’s REST API, Python, and R libraries integrate into any existing ML workflow.

SigOpt augments your existing model training pipeline, suggesting parameter configurations to maximize any online or offline objective, such as AUC ROC, model accuracy, or revenue. You only send SigOpt your metadata, not the underlying training data or model.

[Visit our website](https://sigopt.com) to learn more!
