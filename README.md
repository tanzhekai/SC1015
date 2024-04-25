# SC1015 Mini-Project: Flight Delay Prediction
Groups Members: 
1. Tan Leong Jun Joseph (U2321339H)
2. Tan Zhe Kai (U2322419A)

## Problem Formulation (Motivation)
- According to the United States Federal Aviation Administration (FAA), an on-time flight is defined as one that arrives or departs no more than 15 minutes after the scheduled time.
- In 2019, the performance of US airlines in terms of timely arrivals was around 80%, with the average length of delay being 50mins.
- As flight delays are caused by a variety of factors, such as the weather, air traffic congestion and many more, accurate predictions on which factors cause flight delays the most, can not only improve operational efficiency but also contribute to the entire aviation industry and its travellers.

## Problem Goal
- The goal is to predict whether a flight will be delayed and understand the greatest factors that cause flight delays.

## Dataset from Kaggle
Source: [2019 Airline Delays w/ Weather and Airport Detail](https://www.kaggle.com/datasets/threnjen/2019-airline-delays-and-cancellations)

_(Note: Datasets are not included into the Github repository as the file sizes are too large. To view the datasets, go to the Kaggle link above.)_
<br>

![image](https://github.com/tanzhekai/SC1015/assets/160701256/438201ae-79f6-4100-8a72-0043e1274b79)

## Attached Files:
**Jupyter Notebooks**:
- [1.0 Data Cleaning](https://github.com/tanzhekai/SC1015/blob/main/1.0%20Data%20Cleaning.ipynb)
- [2.0 Exploratory Data Analysis & Visualization](https://github.com/tanzhekai/SC1015/blob/main/2.0%20Exploratory%20Data%20Analysis.ipynb)
- [3.0 Classification Models](https://github.com/tanzhekai/SC1015/blob/main/3.0%20Classification%20Models.ipynb)

**Data Dictionary:**
- [Documentation of variables](https://github.com/tanzhekai/SC1015/blob/main/train_sets_documentation.txt)

**Slide Deck**:
- [Presentation Slides](https://github.com/tanzhekai/SC1015/blob/main/slides.pdf)

---
## Project Outline

### [1.0 Data Preparation & Cleaning](https://github.com/tanzhekai/SC1015/blob/main/1.0%20Data%20Cleaning.ipynb)
- Handling of `NaN` values (e.g. dropping them or filling them with mean value)
- Removing irrelevant column variables (not useful for solving problem)
- Feature engineering: transforming existing data into new data
- Changing variable data types: to reduce memory usage
- Label encoding of categorical variables

### [2.0 Exploratory Data Analysis & Visualizations](https://github.com/tanzhekai/SC1015/blob/main/2.0%20Exploratory%20Data%20Analysis.ipynb)
- Exploring each column variable, understanding the data and creating meaning.
- Number of delayed flights per airline/airport
- Airline/airport with the most flight delays
- Most/least popular airlines
- Busiest airport
- Correlation of each variable

### [3.0 Classification Models](https://github.com/tanzhekai/SC1015/blob/main/3.0%20Classification%20Models.ipynb)
**Classification Models:**
1. Decision Tree
2. Random Forest
3. AdaBoost
4. XGBoost
5. Naive Bayes

**Metrics & Evaluation**
- `Accuracy`, `Precision`, `Recall` and `F1-Score`
- Hyperparameter Tuning using GridSearchCV
- K-folds cross-validation
- Feature Importance

<br>

## 4.0 Data-driven Insights & Recommendations
Looking from the perspective of the 3 main groups of air travel, we can see that the variables we found can give insights into the best ways to reduce flight delays. 

1. For travellers, as concurrent flights are high during peak holiday seasons, travellers may choose to instead travel during less popular months. <br>
2. For the airlines, since the age of the plane is the most important variable that affects flight delays, the fleet management of airlines should prioritize using newer aircraft to reduce maintenance time during peak seasons as well. <br>
3. Airports should also interact and work closely with each other to understand and allow efficient flight scheduling to reduce congestion. <br>

Although we are aware that these recommendations are common in air travel, learning how to apply models and predict flight delays by ourselves allows us to fully understand and solve our initial problem formulation in this project.

<br>

## Learning outcomes

**Data Collection:**
  - Proper problem formulation with the dataset

**Data Preparation:**
- Cleaning duplicate entries
- Merging datasets

**EDA and Visualistion:**
- Identify redundancies and inconsistencies
- Use of visualisation tools
- Generating meaning from visualizations

**Metrics and Models:**
- Deriving the best model by comparing metrics
- Explore other machine learning algorithms and building of models (e.g. XGBoost and AdaBoost)

**Data-Driven Insights:**
- Interpreting the outcome of models with Feature Importance
- Determining the factors that impact flight delays the most

---

## Contributions
**Data Collection:** `Joseph` and `Zhe Kai`<br>
**Data Preparation (Cleaning and Merging):** `Zhe Kai`<br>
**EDA and Visualisation:** `Joseph` and `Zhe Kai`<br>
**Metrics and Models:** `Zhe Kai`<br>
**Data-Driven Insights:** `Joseph` and `Zhe Kai`<br>
**Presentation Script:** `Joseph` and `Zhe Kai`<br>
**Presentation Slides:** `Joseph`<br>
**Presentation Video:** `Joseph` and `Zhe Kai`<br>
**README:** `Joseph` and `Zhe Kai`<br>

## References
- Slotnick, D. (2020, February 19). Why Your Airplane (Still) Might Be Delayed. The New York Times. Retrieved from https://www.nytimes.com/2020/02/19/business/air-travel-delays-airlines.html
- A general architecture of XGBoost. (n.d.). In ResearchGate. Retrieved from https://www.researchgate.net/figure/A-general-architecture-of-XGBoost_fig3_335483097
- Naive Bayes. (n.d.). In scikit-learn: Machine Learning in Python. Retrieved from https://scikit-learn.org/stable/modules/naive_bayes.html
- Dancerworld60. (n.d.). Demystifying Naïve Bayes—Simple Yet Powerful for Text Classification. Medium. Retrieved from https://medium.com/@dancerworld60/demystifying-na%C3%AFve-bayes-simple-yet-powerful-for-text-classification-ad92b14a5c7
