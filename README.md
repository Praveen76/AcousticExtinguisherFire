# Acoustic Extinguisher Fire

**Data:**: The dataset has 6 input features called SIZE, FUEL,	DISTANCE,	DESIBEL,	AIRFLOW,	FREQUENCY, and one output feature called STATUS. This is a binary classification problem.
You can import dataset from the [following link](https://www.kaggle.com/datasets/muratkokludataset/acoustic-extinguisher-fire-dataset) to replicate the same results and follow along the experiement.

![Acoustic Extinguisher Fire Dataset](https://github.com/Praveen76/AcousticExtinguisherFire/blob/main/dataset-cover.jpeg)

# Instructions for Installation:

**Dependencies:** : You'll need to install below dependencies to run this project.

* json: 2.0.9
* pandas: 1.0.1
* numpy: 1.18.1
* matplotlib: 3.5.3
* seaborn: 0.10.0
* sklearn: 0.22.1

The code has been tested on Windows system. It should work well on other distributions but has not yet been tested.

In case of any issue with installation or otherwise, please contact me on [Linkedin](https://www.linkedin.com/in/praveen-kumar-anwla-49169266/)

# **Important learnings:**
    1. How to mount Google Drive, or G-Drive in Google Colab
    2.How to unizip a file using Python
    3. How to import dataset from Kaggle
    4. How to encode Ordinal Variables
    5. How to apply Sklearn pipeline
    6. How to apply GridSearchCV
    7. Understand different scaling techniques such as StandardScaler(), MinMaxScaler(), Normalizer(), MaxAbsScaler()
    8. How to find best hyper parameters


# **Scikit-learn Pipeline benefits**: 
Scikit-learn Pipeline is a powerful tool for simplifying and streamlining the machine learning workflow. It offers several benefits that make it a valuable component of the scikit-learn library. Here are some of the key advantages of using a scikit-learn pipeline:
 
1. Clean and Readable Code: Pipelines provide a clean and organized way to structure your machine learning code. Each step in the pipeline is easily identifiable, making your code more readable and maintainable.
2. Easy Preprocessing: Pipelines seamlessly integrate data preprocessing steps (e.g., data scaling, encoding, imputation) with the model training process. This ensures that the same preprocessing steps are applied to both the training and testing data, reducing the risk of data leakage.
3. Prevent Data Leakage: Pipelines automatically apply transformations and modeling in the right order, preventing data leakage. This is crucial for tasks like cross-validation, where you want to ensure that preprocessing is applied separately to each fold of the data.
4. Hyperparameter Tuning: Pipelines can be used in conjunction with tools like GridSearchCV or RandomizedSearchCV for hyperparameter tuning. This allows you to search for the best hyperparameters for both the preprocessing and modeling steps simultaneously.
5. Efficient Model Selection: Pipelines make it easier to experiment with different models and model combinations. You can switch out the estimator component of the pipeline without changing the preprocessing steps, which can save a lot of time and effort.
6. Code Reusability: Once you've defined a pipeline, you can reuse it for different datasets or projects with minimal changes. This promotes code reusability and consistency in your machine learning workflows.
7. Simplified Deployment: You can export a trained pipeline as a single entity, making it easy to deploy models in production. This is especially useful when you need to package preprocessing steps along with the model.
8. Better Error Handling: Pipelines can help with error handling and debugging. Since each step is well-organized, it's easier to pinpoint issues and resolve them.
9. Improved Collaboration: Pipelines make it easier for teams to collaborate on machine learning projects. Everyone can follow a consistent structure, and it's easier to share and understand code.
10. Streamlined Workflow: By encapsulating all the necessary steps in one pipeline, you can create a streamlined and automated workflow for your machine learning projects, from data preprocessing to model training and evaluation.
11. Easier Interpretability: Pipelines can be used in conjunction with tools for model interpretability and feature importance analysis. This makes it easier to understand and explain the decisions made by your models.

In summary, scikit-learn pipelines offer a structured, efficient, and maintainable way to build and deploy machine learning models. They promote best practices, help prevent common errors, and make it easier to work with machine learning in a systematic and organized manner.



# **About Me:**
I’ve been working as a Data Scientist for a very long time now. I've worked on various NLP, Machine learning & cutting edge deep learning frameworks to solve business problems. Please feel free to check out my personal wesbsite [TowardsMachineLearning.Org](https://towardsmachinelearning.org/) , where I cover an array of topics from Machine learning, NLP, Deep Learning, etc.

