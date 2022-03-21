## FAQs for SC1015 Mini-Project

What is the Grading Scheme for the Mini-Project?
* 10% for coming up with your own problem definition based on a dataset
* 10% for data preparation and cleaning to suit the problem of your choice
* 20% for exploratory data analysis/visualisation to gather relevant insights
* 20% for the use of machine learning techniques to solve a specific problem
* 20% for the presentation of data-driven insights and the recommendations
* 10% for the quality of your final team presentation and overall impressions
* 10% for learning something new and doing something beyond this course

Your individual contribution will be evaluated through peer assessment.

This evaluation will be used as a "scaling factor" for your overall score.

If you are attempting something different, especially something that you think do not fit naturally into the grading scheme, feel free to discuss with your Lab TA directly. They will mentor you and also grade your project.

## Dataset Collection
[About the GTD](https://www.start.umd.edu/gtd/)

Managed by the National Consortium for the Study of Terrorism and Responses to Terrorism (START), the Global Terrorism Database™ includes more than 200,000 terrorist attacks dating back to 1970. Read about the history of the GTD below.

The Global Terrorism Database (GTD)™ is the most comprehensive unclassified database of terrorist attacks in the world. The National Consortium for the Study of Terrorism and Responses to Terrorism (START) makes the GTD available via this site in an effort to improve understanding of terrorist violence, so that it can be more readily studied and defeated. The GTD is produced by a dedicated team of researchers and technical staff.

The GTD is an open-source database, which provides information on domestic and international terrorist attacks around the world since 1970, and now includes more than 200,000 events. For each event, a wide range of information is available, including the date and location of the incident, the weapons used, nature of the target, the number of casualties, and – when identifiable – the group or individual responsible.

Defining Terrorism
The GTD defines terrorism as:
“The threatened or actual use of illegal force and violence by a non-state actor to attain a political, economic, religious, or social goal through fear, coercion, or intimidation.”

The data collection team uses a series of inclusion criteria to systematically identify events for inclusion in the database. More information about the data collection process can be found in the GTD Codebook.

[Some analysis that they have already done](https://www.start.umd.edu/gtd/analysis/) 

## Questions (General Overview of entire database)
Who is most likely to be targeted? (Are you at risk of being targeted)

(Multi-variable Categorisation: Best combination to be targeted)

Country

Victim job

Victim job role

Nationality

Where is most likely to be targeted?

(Categorisation)

Country

Religious places

Populated areas

What makes a successful attack? 

(Classification: Success)

Country data

Attack type

Success rate

Target victim information (Victim’s Background)

Perpetrator background 

Location

Suicidal bombing

What happens after, the consequences? 

(Regression: Fatalities + Injuries = Casualties) 

[https://www.mdpi.com/2071-1050/13/14/7598]

Casualties

Damage

Severity

Property Damage Extent

The number of terrorist attacks that are predicted to take place in the future?

(Regression: # of future terrorist attacks)

Terrorist Attacks from now

Motivations

Summary

## Data Preparation
* Proper representation for your models ith feature engineering and feature selection
* Data pre-processing to fix issues - class imbalance, skewness, scale of variables
* Filling in missing values
* Transform / Enrich data (Perhaps find more data)

## Descriptive Statistics
Central Tendency

Variability

Correlation

Remove / Predict outliers (If the outliers are not useful)

Visualising data

## Machine Learning

(Could produce 3 sets from each algo to compare the different results achieved)

Linear Regreesion / Classification

Splitting data sets

Text Classification

kNN Algorithm (For optimization)

K-means clustering (For optimisation)

## Information Presentation

## Ethical Consideration

Miscellaneous

Visualisation Tools

Plotly - Interactive Maps

Folium - Maps

Kepler - 3D Web Maps

Optimisation Tools

Pickle - Save the model

## References

https://www.start.umd.edu/gtd/analysis/

https://ourworldindata.org/terrorism 

https://realpython.com/python-statistics/ 

Everything on descriptive statistics

https://mv1249.github.io/Task4.html (jupyter notebook using the dataset)

EDA on the dataset, using plotly and folium

https://jovian.ai/zubairsheikh9/global-terrorism#C49 (jupyter notebook using the dataset)

Understanding, Cleaning, and EDA on the dataset, using matplot, seaborn

https://notebooks.githubusercontent.com/view/ipynb?browser=chrome&color_mode=auto&commit=3dab86eb312bfcb432d45639cac6fe6b48648ea2&device=unknown&
enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6d72696e2d323630312f4c474d5649502d2d446174612d536369656e63652f3364616238366562333132626663
62343332643435363339636163366665366234383634386561322f5461736b253230322532302d2532304578706c6f7261746f727925323044617461253230416e616c797369732532306f6e25323044617461
7365742532302d253230546572726f7269736d2e6970796e62&logged_in=false&nwo=mrin-2601%2FLGMVIP--Data-Science&
path=Task+2+-+Exploratory+Data+Analysis+on+Dataset+-+Terrorism.ipynb&platform=android&repository_id=395616175&repository_type=Repository&version=98 

EDA on the dataset using matplot

https://prisma.dcc.uchile.cl/cursoMD/2019-1/Analisis%20de%20Terrorismo%20%20en%20el%20Mundo/ (jupyter notebook using the dataset)

Has EDA, Classification, Clustering and Association Rules (Quite extensive)

http://rstudio-pubs-static.s3.amazonaws.com/336829_1097dfdfc03345c4aeb47081653ac1bb.html
https://medium.com/swlh/global-terrorism-study-exploratory-and-descriptive-data-analysis-4e5a1d8b473d
https://www.kaggle.com/srinidhi14vaddy/global-terrorism-database-study
https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html
