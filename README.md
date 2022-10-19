
# Project Title : Ted Talks View Prediction

# Problem statement:

The main objective is to build a predictive model, which could help in predicting the views of the videos uploaded on the TEDx website.

# About the Data:

We have the data of previous TED talk events , which contains data points such as the length (duration ) of the talk, topics , speaker occupation and textual features such as Transcript , Title , and Description And most importantly , the target variable : the view of the video The Data is available for 4005 TED talks .

# Dataset Info:

* Number of records: 4005
* Number of attributes: 19

# Features Information

The dataset contains features like:

* talk_id: Talk identification number provided by TED
* title: Title of the talk
* speaker_1: First speaker in TED's speaker list
* all_speakers: Speakers in the talk
* occupations: Occupations of the speakers
* about_speakers: Blurb about each speaker
* recorded_date: Date the talk was recorded
* published_date: Date the talk was published to TED.com
* event: Event or medium in which the talk was given
* native_lang: Language the talk was given in
* available_lang: All available languages (lang_code) for a talk
* comments: Count of comments
* duration: Duration in seconds
* topics: Related tags or topics for the talk
* related_talks: Related talks (key='talk_id',value='title')
* url: URL of the talk
* description: Description of the talk
* transcript: Full transcript of the talk

# Target Variable:

* views: Contains count of views of every talk

# Approach Taken:

The task was divided into 2 main parts:
 * 1. Statistical Analysis over the dataset to discover relationships between each feature and the target variable . So that this relationship information can be used by the management in making better Business decisions
 * 2. Creating a Machine Learning Pipeline , that can take in the data of any new video and predict how many views it will generate on a daily basis .It was required to kepp this pipeline modular , such that it can be retrained often when new data is collected

 # Project Work Flow

* 1.  Importing Libraries

* 2.  Loading the dataset

* 3.  Data Cleaning

* 4.  EDA on features

* 5.  Feature selection

* 6.  Fitting the regression models

* 7.  HyperParameter Tuning

* 8.  Evaluation Metrices of the model

* 9.  Final selection of the model

* 10. Conclusion

# Technical Details for ML:

* We used many Algorithms ( Random Forest , XGBoost and CatBoost ) We used RandomSearchCV for HyperParameter Tuning Comparing both R2 Score , we can see that Random Forrest and XGBoost model performs the best

# Technical Insights from exploring the Data:

* For the ML Pipeline , the XGBoost Model performed the best ● For the NLP Pipeline , the Random Forest Model performed the Best ● Feature Engineering and Feature Extraction helped in increasing the model performance

# Conclusions : Insights from exploring the Data :

* opics like Technology , Science , Education , Biology attract the attention of viewers more than other topics . ● Entrepreneurs and Activists are the most engaging speakers

# Python Libraries used

Data wranling:
* Numpy
* Pandas

For Graphing :
* Matplotib
* Seaborn

Machine learning :
* Scikit-Learn
* SK-Opt
* XGBoost
* CatBoost

Miscellaneous :
* Google colab tools


## Contributing Team Members: 

- [Priyesha Solanki](https://www.github.com/PUSol) 
- [Navyaa Kanaujia](https://github.com/navyaa2001) 
- [Prachi Rathod](https://github.com/PSRoth)
- [Priyanshi Zala](https://github.com/2610zala)
## 🔗 Links
[![resume](https://img.shields.io/badge/my_resume-000?style=for-the-badge&logo=ko-fi&logoColor=white)](file:///C:/Users/Lovel/OneDrive/Desktop/Priyesha%20Docs/Priyesha-resume.pdf)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/priyesha-solanki)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/home)

