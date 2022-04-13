# Introducing our SC1015 Mini-Project

## About
---
This is our mini-project for SC1015 (Intro to Data Science and Artificial Intelligence).

### Contributors (SC7 Group 10)
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

Maintained by researchers headquartered at the University of Maryland. The dataset consits of information on more than <b>200,000</b> global terrorist attacks.

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

## Lessons Learnt
---
- We used all the rows initially for dataset cleaning, which resulted in us dropping too many points. Instead we first picked out the relevant columns, then cleaned those values. Resulting in us obtaining a fuller dataset.
- Dataset had an imbalance in number of failed and successful columns. Resulting in us having to use weights for rebalancing.
- Library versioning could've been affecting the results obtained on different OS (Mac/Windows). Therefore, this required us to check the requirement.txt, tried to shift to a Windows device, and make use of Google Collab.
- Initially, we had all of our codes in a file, which resulted in our neural network not having enough memory to run (and the kernel failing). Hence we split up the code files into different Jupyter Notebook files.
- Split the Neural Network Model into another notebook

## References
---
https://www.start.umd.edu/gtd/analysis/<br>
https://ourworldindata.org/terrorism <br>
https://realpython.com/python-statistics/<br>
https://machinelearningmastery.com/metrics-evaluate-machine-learning-algorithms-python/</br>
