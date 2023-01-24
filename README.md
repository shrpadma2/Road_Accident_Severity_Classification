# Road-Traffic-Severity-Classification-Project
This multiclass classification effort divides the seriousness of traffic incidents into three groups. The dataset used for this study is heavily skewed and is based on real-world data. Learn more about the specifics of the description and the issue with the activities completed.

**Description:** For a master's thesis, the police departments in the Addis Ababa Sub-city, Ethiopia, provided this data collection. The data set was created using manual records of the year 2017–20's traffic accidents. During data encoding, all sensitive information was eliminated, leaving 32 characteristics and 12316 instances of the accident. Following preprocessing, it is examined using various machine learning classification techniques in order to determine the main reasons of the accident.

**Source of dataset:** [Link to the dataset](https://www.narcis.nl/dataset/RecordID/oai%3Aeasy.dans.knaw.nl%3Aeasy-dataset%3A191591)

**Problem Statement:**The multi-class variable Accident severity is the feature that is being targeted. By working through each day's job, the goal is to categorize this variable based on the other 31 qualities step-by-step. Your performance will be measured using the f1-score.


### Tasks and methods employed:

Analyzing exploratory data is step one.
- Dabl is used to analyze data.
- Exploratory data analysis with Seaborn and Matplotlib.

2. Data pre-processing and preparation
- Lack of Values Fillna-method treatment
- One Hot utilizing pandas get_dummies encoding
- Feature selection using the SelectKBest method and the "chi2" statistic
- Using PCA to lower dimensionality
- Data imbalance treatment using the "SMOTENC" method

3. Using the Sci-Kit Learn Library for modeling
- Baseline model using the default method of "RandomForest"
- Hyperparameters that have been tuned using the n estimators and max depth parameters

4. Assessment
- The 'f1 score' evaluation measure was weighted.
"fl score = 61%" for the baseline model; "f1 score = 88%" for the final model evaluation.

### Acknowledgement: [TMLC Academy](https://www.themlco.com/Academy/index.html)

