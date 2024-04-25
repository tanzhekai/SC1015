# SC1015 Mini-Project: Flight Delay Prediction
Groups Members: 
1. Tan Leong Jun Joseph (U2321339H)
2. Tan Zhe Kai (U2322419A)

## Problem Formulation (Motivation)
- According to the United States Federal Aviation Administration (FAA), an on-time flight is defined as one that arrives or departs in no more than 15 mins after the scheduled time.
- In 2019, the performance of US airlines in terms of timely arrivals was around 80%, with the average length of delay to be 50mins.
- As flight delays are caused by a variety of factors such as the weather, the air traffic congestions and many more, accurate predictions on which factors causes flight delays the most, can not only improve operational efficiency but also contribute to the entire aviation industry and its travellers.

## Problem Goal
- To predict the greatest factors causing flight delays.

## Dataset from Kaggle
Source: [2019 Airline Delays w/ Weather and Airport Detail](https://www.kaggle.com/datasets/threnjen/2019-airline-delays-and-cancellations)

_(Note: Datasets are not included into the Github repository as the file sizes are too large.)_
<br>

![image](https://github.com/tanzhekai/SC1015/assets/160701256/438201ae-79f6-4100-8a72-0043e1274b79)

### Jupyter Notebooks:
- [1.0 Data Cleaning](https://github.com/tanzhekai/SC1015/blob/main/1.0%20Data%20Cleaning.ipynb)
- [2.0 Exploratory Data Analysis & Visualization](https://github.com/tanzhekai/SC1015/blob/main/2.0%20Exploratory%20Data%20Analysis.ipynb)
- [3.0 Classification Models](https://github.com/tanzhekai/SC1015/blob/main/3.0%20Classification%20Models.ipynb)

### Slides:
- [slides](https://github.com/tanzhekai/SC1015/blob/main/slides.pdf)

### Data-driven Insights & Recommendations
Looking from the perspective of the 3 main groups of air travel, we can see that the variables we found can give insights on the best ways to reduce flight delays. 

1. For travellers, as concurrent flights are high during peak holiday seasons, travellers may choose to instead travel during less popular months. <br>
2. For the airlines, since the age of the plane is the most important variable that affects flight delays, the fleet management of airlines should prioritize using newer aircrafts to reduce maintenance time during peak seasons as well. <br>
3. Airports should also interact and work closely with each other to understand and allow efficient flight scheduling to reduce congestion. <br>

Although we are aware that these recommendations are common in air travel, learning how to apply models and predict flight delays by ourselves allow us to fully understand and solve our initial problem formulation in this project.

### Learning outcomes

Data Collection:
  - Proper problem formulation with dataset

Data Preparation:
- Cleaning duplicate entries
- Merging datasets

EDA and Visualistion:
- Identify redundancies and inconsistencies
- Use of visualisation tools

Metrics and Models:
- Deriving the best model by comparing metrics
- Use and difference of multiple models

Data-Driven Insights:
- Interpreting the outcome of models with Feature Importances

<br>

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
