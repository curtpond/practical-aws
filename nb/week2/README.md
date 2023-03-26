# Build, Train, and Deploy ML Pipelines Using BERT

## Week 1:
[C2_W1_Assignment](https://github.com/curtpond/practical-aws/blob/main/nb/week2/C2_W1_Assignment.ipynb)

[Slides for Week 1](./slides/C2_W1.pdf)
### Objectives
- Apply feature engineering to prepare datasets for training.
- Select feautures and labels, balance the dataset, split the dataset, transform the data.
- Configure, store, and share features using Amazon SageMaker Feature Store.
- Build a multi-class text classification for sentiment analysis BERT model of product reviews.

## Week 2:
[C2_W2_Assignment](https://github.com/curtpond/practical-aws/blob/main/nb/week2/C2_W2_Assignment.ipynb)

[Slides for Week 2](./slides/C2_W2.pdf)
### Objectives
- Train a text classifier using a variant of BERT called RoBERTa.
- Train a custom model with Amazon SageMaker (Bring Your Own Script)
- Configure dataset & evaluation metrics
- Configure hyperparameters
- Providing training script
- Fit the model
- Debug and profile models

## Week 3:
[C2_W3_Assignment](https://github.com/curtpond/practical-aws/blob/main/nb/week2/C2_W3_Assignment.ipynb)

[Slides for Week 3](./slides/C2_W3.pdf)
### Objectives
- Define and run a pipeline using a directed acyclic graph (DAG) with specific pipeline parameters and model hyper-parameters
- Define a processing step that cleans, balances, transforms, and splits our dataset into train, validation, and test dataset
- Define a training step that trains a model using the train and validation datasets
- Define a processing step that evaluates the trained model's performance on the test dataset
- Define a register model step that creates a model package from the trained model
- Define a conditional step that checks the model's performance and conditionally registers the model for deployment
- Pipelines: build a directed acyclic graph (DAG) of steps and conditions to orchestrate SageMaker jobs and resource creation
- Processing job steps: build a simplified, managed experience on SageMaker to run data processing workloads, such as feature engineering, data validation, model evaluation, and model explainability
- Training job steps: build an iterative process that teaches a model to make predictions on new data by presenting examples from a training dataset
- Conditional step execution: provide conditional execution of branches in a pipeline
- Registering models: register a model in a model registry to create a deployable models in Amazon SageMaker
- Parameterized pipeline executions: allows pipeline executions to vary by supplied parameters
- Model endpoint: host the model as a REST endpoint to serve predictions from new data


