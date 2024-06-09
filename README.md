
The aim of this project is to construct a Neural Collaborative Filtering recommendation system and train it on Yelp's dataset to generate personalized restaurant recommendations.

#### **Key Features**

- **Data Preprocessing:** Comprehensive data handling to organize and split the data effectively for training, validation, and testing purposes.
- **Hybrid Recommendation Model:** An ensemble approach combining Generalized Matrix Factorization (GMF) and Multi-Layer Perceptron (MLP) components to create a robust model capable of understanding complex user-item interactions through both linear and non-linear computations.
- **Hyperparameter Tuning with Ray Tune:** Employing Ray Tune for adaptive hyperparameter optimization, enhancing model performance through Population-Based Training (PBT).
- **Evaluation and Inference:** Evaluation of the model's performance on unseen data using RMSE, followed by a practical application scenario demonstrating the system's utility.

#### **References**

- The dataset utilized in this project is sourced from Kaggle: [Yelp Dataset](https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset). Note that the data files are too large to be included directly in the repository, so you will need to download them separately as described below.
- The ensemble approach of the recommendation system developed in this project is largely based on the insights and methodologies presented in the paper [Neural Collaborative Filtering](https://arxiv.org/pdf/1708.05031v2.pdf) by He, Liao, Zhang, Nie, Hu, and Chua (2017).

#### **Getting Started**

To dive into this project, clone the repository to your local machine or environment where you have Python (3.8 or newer) and the necessary hardware support (preferably a GPU). The project is contained within a Jupyter notebook, offering an interactive platform to explore and extend the work presented.

**Installation**
1. Clone the repository to your local machine or development environment.
2. Download the Yelp Dataset from Kaggle. Ensure you place the folder named `yelp-dataset` within your project directory, containing `yelp_academic_dataset_business.json` and `yelp_academic_dataset_review.json`.
3. Install the required dependencies using `pip install -r requirements.txt`.
4. Launch the Jupyter notebook to walk through the project from data processing to making recommendations.
