# Introducing our SC1015 Mini-Project

## About
---
This is our mini-project for SC1015 (Intro to Data Science and Artificial Intelligence).

### Contributors (SC7 Group 10)
---
@nghochi123<br>
@Mel-NLY

## Understanding our project
---
Here's the sequence of files that we'd recommend for you to look through:<br>
1. [Data analysis](Data_analysis.ipynb)
2. [What determines a successful terrorist attack?](What_determines_a_successful_terrorist_attack_.ipynb)
3. [What do terrorists really want?](What_do_terrorists_really_want_.ipynb)

## Dataset
---
The dataset is called the Global Terrorism Database, obtained from the National Consortium for the Study of Terrorim and Responses to Terrorism ([START](https://www.start.umd.edu/gtd/)).

Maintained by researchers headquartered at the University of Maryland. 

## Problem Definition + Motivation
---
Using this dataset, we are trying to find the answer to the following categorical questions:
- What determines a successful terrorist attack?
- What are terrorists really after?

We realized that wanting to determine <u><b>what makes or breaks a successful terrorist attack</b></u> was important, so that we could focus on the important combination of features. Coming up with solutions that target the more important features to prevent the attacks from succeeding and hurting many others in the process.

Following the same methodology, being able to pick out the <u><b>motives</b></u> that are the most harmful and common would also serve to reduce the number of successful terror attacks.


## Models Used
---
- Random Forest Classifier<br>
- Logistic Regression<br>
- K-Nearest Neighbours Classifier<br>
- Support Vector Classification (SVC)<br>
- Neural Networks<br>
- Stochastic Gradient Descent Classifier<br>
- Kernel SVM<br>
- Decision Tree Classifier<br>
- AdaBoost<br>
- Gradient Boosting<br>

## What We Discovered
---
- What determines a successful terrorist attack?<br>
These was the best combination of features found that could predict the successful-ness of a terrorist attack.
    - Number of Kills
    - Timestamp
    - AttackType
    - Number of Wounded
    - WeaponType
    - Month<br>

- What are terrorists really after?<br>
Retaliation was found to be the most common of motives among the terrorists.



## Tools Used
---
[Folium](https://python-visualization.github.io/folium/) - Interactive Leaflet Map<br>
[Keplergl](https://kepler.gl/) - Geospatial Analytic Visualizations<br>
[Plotly](https://plotly.com/) - Interactive Web-based Visualizations<br>
[Pickle](https://docs.python.org/3/library/pickle.html) - Serializing and deserializing object structures

## Challenges that we faced + Solutions tri
- Top features that we select (clean them only) instead of cleaning the entire dataset at once (Dropping too many points)
- Work our way up from the most important feature (1,2,3...5)
- Rebalancing the dataset (re-evaluating the number of success and failures)
    - Weighted for reimbalancing
- Double check the library versioning
    - requirement.txt (Issue comes because of different OS)
    - Ill use Windows + env
- Split the Neural Network Model into another notebook
    - Prevent kernel from failing

## References
---
https://www.start.umd.edu/gtd/analysis/
https://ourworldindata.org/terrorism 
https://realpython.com/python-statistics/<br>
