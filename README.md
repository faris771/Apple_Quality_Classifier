# Machine Learning Project - Apple Quality Classification

## Introduction
**ENCS5341** Machine Learning And Datascience project, aims to perform a predictive task on a real-world problem using
machine learning models. We chose a classification task and picked a dataset from
Kaggle. As a baseline model, we evaluated a nearest neighbor baseline using a distance
of our choice and reported the performance of this baseline using both k=1 and k=3. We
then tried to achieve better performance by evaluating two additional models on the task,
namely SVC and ExtraTreeClassifier. We discussed and motivated our model selection
and commented on why the performance has improved. We tuned at least one hyper-
parameter for each model by testing at least 4 different values. Finally, we analyzed the
performance of our best model from examining instances in the test set where our model
exhibits errors

## Files
- **main.ipynb:** Jupyter Notebook containing the complete code.
- **apple_quality.csv:** Dataset used for training and testing the models.
- **README.md:** Project overview and instructions (you are reading it).

## How to Run the Code
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/faris771/apple_quality_classifier.git
    cd apple_quality_classifier
    ```

2. **Install Dependencies:**
    Ensure you have the necessary Python packages installed. You can use the provided `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook:**
    Open and run the `main.ipynb` notebook using Jupyter. This can be done using Anaconda or any other Jupyter environment.
    ```bash
    jupyter notebook main.ipynb
    ```

4. **Explore the Code:**
    - The notebook contains sections for data exploration, preprocessing, model training, and analysis.
    - Each cell is documented with comments explaining the code and its purpose.

5. **Experiment and Modify:**
    - Feel free to experiment with different hyperparameters, models, or dataset modifications.
    - Adjust parameters within the code and observe the impact on model performance.

6. **Contribute:**
    - If you find any issues or have suggestions for improvements, feel free to contribute by opening an issue or creating a pull request.

## Dataset
- The "Apple Quality" dataset (apple_quality.csv) is included for convenience.
- The dataset has been preprocessed for the purpose of this project.

## Acknowledgments
This project is part of the **ENCS5341** Machine Learning and Data Science course.

**Contributors:**
*  [Faris Abu Farha](https://github.com/faris771)
*  [Omar Masalmah](https://github.com/Omarmasalmah)
  

**Instructor:**
Dr. Yazan Abu Farha


