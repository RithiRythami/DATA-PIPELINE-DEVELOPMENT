# DATA-PIPELINE-DEVELOPMENT

COMPANY: CODTECH IT SOLUTIONS

NAME: RITHI RYTHAMI S

INTERN ID: CT08KFD

DOMAIN: DATA SCIENCE

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION: This model employs a machine learning pipeline in Python with the scikit-learn library. A pipeline chains preprocessing steps together with a model into a single object, so consistency and efficiency are assured. Here are two pipelines constructed: feature scaling using StandardScaler and classification using LogisticRegression for both of the major classification situations.

Feature scaling scales the data to a mean of 0 and standard deviation of 1. That is an important thing for many algorithms, particularly logistic regression algorithms, that are sensitive to the magnitudes of features.

Using the Pipeline class, a pipeline is constructed to define steps sequentially. In this first step, data gets standardized with StandardScaler and in the second step, a logistic regression model gets trained. The structure of the pipeline can be further visualized by using the command set_config(display="diagram"), which will create a diagram to illustrate the components present in the pipeline.

We create a synthetic binary classification dataset using the function make_classification with 1,000 samples and 20 features. The entire dataset is split into a training set and a test set at percentages of 67% and 33% using the train_test_split function in scikit-learn, respectively. This training data is passed to the method fit() of the pipeline for scaling purposes before training the logistic regression model. The predictions are then created against the test set (X_test) using the predict() method.

Tools like Jupyter Notebook create an interactive environment where code can be run, and scikit-learn creates robust libraries for preprocessing, modeling, and pipelines in a streamlined manner. This pipeline creates one object that combines preprocessing and model training in order to create a streamlined, repeatable, and modular approach to building machine learning workflows

OUTPUT:

![Image](https://github.com/user-attachments/assets/e000935c-4d58-425a-b59a-0cb1e4d05247)
