# Ad-Click-Prediction
#### Abstract
Advertising has become an essential element of online experience and one of the primary earning sources for the internet industry. Selecting the correct order and the ads to be shown to a user greatly influences the probability that an end-user will click on the ad. This ranking has a significant influence on the revenue the advertisers generate after showing the ads and also helps them to optimize the ad performance. Furthermore, it improves end-user satisfaction if they are shown relevant ads. 

These ads are mostly ranked based on Click-through rates, which helps understand how well the ad is doing and capturing interest. A click-through rate is calculated by dividing the count of users who clicked on the advertisement on a website by the count of ad impressions (displayed). For example, if an ad impression delivered was 1000 and 9 users clicked on the ad, then the CTR, in this case, would be 0.9 percent. Therefore, accurately predicting the CTR for an ad is a key step to increase the revenues; the higher the CTR for an ad, the more successful it creates interest among the target users. 

This paper focuses on ad click prediction. Extracting the important features is the main part of the prediction, and it takes the majority of the time. Given a set of features such as time spent on site, age of the user, ad headline, gender, internet usage, timestamp, clicked on the ad (0/1), the project aims to predict who is possibly going to click on the displayed ad using random forest model.

#### Project Goals and Background 
Over the years the Ads business had drastically changed, until the end of the 20th-century traditional tv ads have dominated the market but with technology advancement, in the 21st century, more focus is on the Online Advertisement. Today, Online advertising is a huge market worth more than $160 billion worldwide. With the increasing usage of online services, marketing companies have a lot of information about users to do targeted advertising which in turn increasing the revenue for the advertisers. The aim of this project is to help advertiser predict ad click, so that they can target and show relevant ads as per the user’s group of interest. This will help many businesses and advertainment company to increase their profit by analyzing their customer’s behavior toward the Ad click. The main goal of this project is to help all kind of businesses to reach their customers by knowing in advance who will click on ads.

Search engines like Google, Bing and Yahoo make use of sponsored search to display ads based on the search keywords. Most of the revenue these companies generate is based on search keywords where Advertisers bids on these keywords also known as bidding keywords to place their ads. Figure 1.1 shows how generic ad server works, when a user visits a website ad request is sent to the ad server which analyzes data about the user and then based on the attributes the highest bidding ad is displayed to the user. Social media companies like Facebook, Reddit, Twitter, Instagram, Snapchat, LinkedIn, Apple News, etc. have a lot of personal data about the user and can easily use those attributes to do target advertising. 

#### Project Deliverables 
In project deliverables, I have delivered step by step work on this project. The first step was data preparation (gather, clean, transform and store the data). Second, explore and visualize the data. Third, check the relationship between variables and choose appropriate feature using random forest model, apply the correlation heat map to distinguish the variables. In the case of random forest many decision trees are aggregated to limit the overfitting of data and avoid bias results. After all these process train and test the model and generate results to predict ad click. At the end summarize the overall work and share the references used in this project.

#### Data Exploration
Data exploration is an essential step that can help us to cut down massive data to manageable groups and it is an initial step of data analysis. There are different methods that we can use for data exploration such as initial reports, data visualization using different graphs and using some matrix strategies like correlation matrix, d-matrix. These methods help us to understand the characteristics and patterns of data. It is necessary to understand the data types of each column in the dataset. Data types are divided into Text type (string), Numeric type (integer, float, complex), Boolean type (bool), Sequence type (list, range, tuple), Set type (set, frozenset), Mapping type (dictionary) and Binary type (bytes, byte array, memory view).

I have used Tableau Prep to explore, clean and prepare the dataset. While cleaning the dataset, removed unwanted columns, null values and to rename the variables and values. Also used Jupyter notebook and python libraries to perform further operations like load or transform the data, examine the variables data types and check duplicate values. If there are any duplicate values, then removed them for better outcomes from the applied model (random forest).

#### Data Sources
I have selected Ad Display/Click Data to predict Ad click rate (Kaggle, n.d.) datasets from the Kaggle website. The overall use of this dataset is to illustrate the advertising system. This dataset contains discrete (countable, distinct data) and continuous (values fall within a particular range) variables. 

#### Resource Requirements

Project management includes resource requirements that we need during the work. Resource requirement has four types discussed below:
##### Data requirements:
The dataset should have all those features that are mandatory. If I want to predict Ad Click or not, then I need a related dataset to predict the results with the labeled data. Dataset for this project has been collected from the Kaggle website. 
##### Software and tools requirements:
The Ad Click Prediction project can implement using Python 3.7. We need different libraries and suitable versions used in python like NumPy (version 1.16.5) to clean and read the data, Pandas (version 1.1.3) useful to build data frame which allow us to manipulate and store data in tabular format, Matplotlib (version 3.1.1) and Seaborn (0.11.0) for data visualization, sklearn to check accuracy classification score and implement DecisionTreeClassifier and Scikit-learn (version 0.21.3). 
The required tools to complete the project are Jupyter notebook, Tableau Prep, Tableau Desktop.
##### Hardware requirements: 
A laptop or computer with 16GB RAM, 64-bit Operating System, Intel Core i7 processor, GPU to accelerate the modeling speed.
##### Software licenses: 
All sources I am using for the Ad Click prediction project are open-source. Therefore, no need for software licenses. 

#### Conclusion
With the growing online advertisement, ad click prediction is going to get a lot more attention, with new and effective models created every year. For effective online Ads system, it is important to get a good initial estimate of click prediction.
In this project I have explained logistic regression, Naïve Bayes, decision tree and random forest machine learning models for the ad click prediction project. The model has trained using Scikit-Learn library. Scikit-Learn supports many concepts like k-neighbors, machine vector, random forest and python numerical operations. The accuracy rate of the random forest model is high as compare to logistic regression and Naïve Bayes algorithm. The accuracy score for logistic regression is 0.9 (90%), whereas the accuracy score for random forest is 0.942 (94.2%).
In the future we can work with the XGBoost algorithm which will help to boost the speed of program. Random forest creates trees in parallel manner that can help make model fast, however XGBoost strengthens the model that predicts the results more efficiently, hence it will make better prediction model. XGBoost resulted in ten times lower error rate that the random forest.

