<div align="center">

# 📊 MexEE 402: Data Preprocessing Case Study

**MexEE Elective 2: Data Science and Machine Learning**
Batangas State University, Alangilan Campus
*1st Semester, AY 2026-2027*

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

---

## 👥 Members

| Name | Student Number | Section |
|:---|:---:|:---:|
| Bool, Mark Luke | 23-06923 | MEXE-4102 |
| Sulit, Ernest Aucin | 23-05557 | MEXE-4102 |

---

## 📓 Notebook Links

| Chapter | Links |
|:---|:---:|
| **Ch1_2_3** | [🔗 Chapter 1-2-3](https://colab.research.google.com/drive/1peeBkyd9rbNRKR13HfSUg_-tRqWk-gS_?usp=sharing) ·
| **Ch4** | [🔗 Chapter 4](https://colab.research.google.com/drive/1CUnQt6MEy9qhKM9gs0IWIqT60P7T2zXA?usp=sharing) ·
| **Ch5** | [🔗 Chapter 5](https://colab.research.google.com/drive/1NVNU2tOF134GJo0j_dj2OCHRMaYmQ5Or?usp=sharing) ·
| **Ch6** | [🔗 Chapter 6](https://colab.research.google.com/drive/1YcKH7Bqn7eL1iDduXTRPQviPNOg2xjSJ?usp=sharing) ·
| **Ch7** | [🔗 Chapter 7](https://colab.research.google.com/drive/1hltzIcpeIDCSDf6hJ21JOJBAdH8fGOB3?usp=sharing) ·
| **Ch8** | [🔗 Chapter 8](https://colab.research.google.com/drive/1zSOBWXnqi-NDGoXg6gRLVwqPVWF_JRqq?usp=sharing) ·
| **Ch9** | [🔗 Chapter 9](https://colab.research.google.com/drive/1JuOjoUD9VEFdHcLuwbgTQDB2sFXD8jmk?usp=sharing) ·

---

## 💡 What We Learned

<div align="justify">

<details>
<summary><b>Ch1_2_3</b></summary>

  &nbsp;&nbsp;&nbsp;&nbsp;In chapter 1, we’ve learned the basics, the introduction to data processing, what is data processing and why it is essential. This chapter also includes the common issues we will encounter and the techniques in data processing. In chapter 2, we’ve learned about the step-by-step process of understanding and exploring data through Python. It also indicates the proper format and the step-by-step process of understanding the data process. In chapter 3, it’s all about data cleaning. Why it is important to have clean, organized data, how to import, locate and handle data, reduce redundancies and remove irrelevant data. And that's what chapters 1, 2, and 3 are all about.

</details>

<details>
<summary><b>Ch4</b></summary>

&nbsp;&nbsp;&nbsp;&nbsp; In Chapter 4, we learned how data transformation and feature engineering can make data easier to understand and more useful for analysis. We learned about data scaling, binning, creating new features, interaction features, ordinal encoding, and one-hot encoding. We also learned that choosing the correct method is important because different types of data need different ways of transformation.


</details>

<details>
<summary><b>Ch5</b></summary>

&nbsp;&nbsp;&nbsp;&nbsp;From chapter 5, we learned how important is data scaling and normalization in ensuring that a machine-learning model will not favor data sets with larger numerical value. We were really surprised to find out that in some machine learning models, larger numerical values can have great influences in its predictions and thus create an unreliable model. With this knowledge, we realized that scaling is very important in ensuring that every data will have an equal influence in the machine learning model’s calculation and prediction. We also learned that  it’s not always necessary to implore but we do understand that its application depends on the nature of the data and the requirements of the algorithm.

</details>

<details>
<summary><b>Ch6</b></summary>

&nbsp;&nbsp;&nbsp;&nbsp;In chapter 6, we learned that there can be an outlier in some data set. An outlier is a value or data which is significantly far from the majority of the data and doing nothing about it can affect statistical results such as the mean and standard deviation which can lead to misleading interpretations. This chapter also taught us the ways in which we can find an outlier, the Z-score method which surprised me, because I thought it was only used for hypothesis testing and the IQR method, these methods both use threshold values for determining if a value is an outlier. The Z-score method commonly uses the cutoff values of -3 to +3 while the IQR method’s threshold values depend on the lower and upper fence. The main difference between the two methods are the values that are going to be tested because in the Z-score method, we used the computed z-scores of the data but in IQR, we used the value itself. Most importantly, we also learned that we can delete an outlier if it is irrelevant or implore capping/flooring to change the outlier’s value with respect to the nearest boundary of the data set.  


</details>

<details>
<summary><b>Ch7</b></summary>

&nbsp;&nbsp;&nbsp;&nbsp;Chapter 7 taught us how useful feature selection is for creating machine learning models because it can  reduce the number of variables that the model will process, it will also simplify the model by reducing the unnecessary information which can improve the model performance. We also learned about three different methods in which we can choose the best features. First is the filter method which surprised me because it uses correlation coefficients to filter the features, second is the Recursive Feature Elimination with cross validation which repeatedly removes the least important features to identify which inputs are most useful for predicting the target. This method evaluates different numbers of remaining features using 5-fold cross-validation to compare model performance before it selects the number of features that achieves the best cross-validation score. Last is the LassoCV which shrinks coefficients and it handles unimportant features by reducing its coefficients toward zero. Learning about these feature selection methods enables us to understand that not every feature is relevant.

</details>

<details>
<summary><b>Ch8</b></summary>

&nbsp;&nbsp;&nbsp;&nbsp;In this chapter, we learned that a preprocessing pipeline is like a conveyor belt that processes raw data through a series of steps before it is utilized in a machine learning model. It helps make data preparation more automated, efficient, reliable, and reproducible. We also learned that a pipeline can contain multiple steps, such as `SimpleImputer` for filling missing values and `StandardScaler` for standardizing numerical features. Additionally, we also learned that by using `ColumnTransformer`, we can apply preprocessing steps to specific columns, such as Age and Fare in the Titanic dataset. Overall, we realized that preprocessing pipelines help organize data preparation and ensure that data is properly processed before training a machine learning model.

</details>

<details>
<summary><b>Ch9</b></summary>

&nbsp;&nbsp;&nbsp;&nbsp;In Chapter 9, we learned how to apply data preprocessing techniques using the Titanic dataset. We learned that data preprocessing is important because it helps clean and organize data before performing data analysis and machine learning. We handled missing values in the Age, Embarked, and Sex columns and used StandardScaler to scale numerical features such as Age and Fare. We also used OneHotEncoder to convert categorical features, such as Sex, Embarked, and Pclass, into numerical values. Another technique we learned was data discretization, which groups passenger ages into different life stages, such as Child, Adult, and Elderly. These techniques helped us understand how to prepare a dataset for further analysis.

We also learned how to use different visualizations to understand the data and identify patterns. The visualizations in the notebook included histograms for age distribution, count plots for survival count, survival by gender, passenger class, embarkation port, and family size, a box plot for fare and survival, and a heatmap to show the correlations between numerical features. We also used a histogram to compare the age distribution of survivors and non-survivors. These plots helped us understand the possible factors that affected passenger survival and it also allows us to visualize the data for better understanding and interpretations. 

</details>

---

## 🐞 Errors We Found

<div align="justify">
  
| Chapter | Original (wrong) | Correct version | Why |
|:---|:---|:---|:---|
| Ch1_2_3 | `('/content/vgsales.csv')` | `import kagglehub` `path = kagglehub.dataset_download("gregorut/videogamesales")` `('/kaggle/input/videogamesales/vgsales.csv')`| It's not really that much of an error, but if you use the original version and accidentally terminate its session, you will need to upload the vgsales.csv to the content again while in the corrected version, you can still run it without uploading the data despite terminating the session. |
| Ch6 |In the Z-score method, 100 is detected as a clear outlier  |There is no outlier found in the Z-score method |Though the z-score of 100 is higher than other numbers, it still falls inside the cutoff threshold of -3 to +3. Therefore, there is no outlier in the Z-score method. |
| Ch7 | cv=5  | cv=3 | It's not necessarily an error but due to the small dataset, using cv=5 made the calculation unstable. While using cv=3 gives us a more stable result but it doesn't mean that it's more reliable which is why we still retain cv=5  in the notebook. In this chapter, the real problem lies with size of the dataset.|
| Ch7 | `relevant__features = correlations_2[correlations_2 > 0.5]` `print(relevant__features)`  | `relevant__features = correlations_2[correlations_2 > 0.5]` `print(relevant__features)` `relevant__features = relevant__features.drop('Final Grade')`|In the original version, the final grade wasn't drop as a relevant feature but it needs to be dropped because it is the target data and must not belong to relevant features. |


---

## 🤖 Note on AI Tools

&nbsp;&nbsp;&nbsp;&nbsp;We utilize Chatgpt and Claude in answering the chapter questions and also in understanding each codes and concepts that we need to grasp. The following AI tools were also used to verify grammatical errors and also in validation of our answers, if it convey the correct concepts. We also utilized Gemini AI that is available in the Google Colab to explain codes and  fix errors in the code because there are times where we miss some commas, parenthesis, and brackets. 

---

## 📚 References

1. McKinney, W. (2021). *Python for Data Analysis*, 3rd ed. O'Reilly.
2. VanderPlas, J. *Python Data Science Handbook*.

