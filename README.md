# Data-Mining

Businesses collect and store an unimaginable amount of data, but how do they turn all that data into insights that help them build a better business? Data mining, the process of sifting through massive amounts of data to identify hidden business trends or patterns, makes these transformational business insights possible.

Data mining is not a new technology. Its roots have been traced to the 1930s, according to Hacker Bits, but the term became more widely used in the 1990s as businesses attempted to grapple with the ever-increasing amount of data our society was producing to derive value from it.

The advent of modern computers and application of data mining techniques meant businesses could finally analyze exponential amounts of data and extract non-intuitive, valuable insights; forecasting likely business outcomes, mitigating risks, and taking advantage of newly identified opportunities. 

Due to its usefulness across many industries, and its critical role in business success, data mining is a promising career path. Companies need data scientists skilled in mining techniques who can present their findings in understandable ways. According to the U.S. Bureau of Labor Statistics, employment for computer and information research scientists is expected to climb by 15 percent through 2029.

# Data Mining Techniques

## 1. Clustering

Clustering refers to the process of grouping a series of different data points based on their characteristics. By doing so, data miners can seamlessly divide the data into subsets, allowing for more informed decisions in terms of broad demographics (such as consumers or users) and their respective behaviors. 

### Methods for Data Clustering

  - **Partitioning method**: This involves dividing a data set into a group of specific clusters  for evaluation based on the criteria of each individual cluster. In this method, data points belong to just one group or cluster.
  - **Hierarchical method**: With the hierarchical method, data points are a single cluster, which are grouped based on similarities. These newly created clusters can then       be analyzed separately from each other. 
  - **Density-based method**: A machine learning method where data points plotted together are further analyzed, but data points by themselves are labeled “noise” and           discarded.
  - **Grid-based method**: This involves dividing data into cells on a grid, which then can be clustered by individual cells rather than by the entire database. As a result,     grid-based clustering hase a fast processing time.
  - **Model-based method**: In this method, models are created for each data cluster to locate the best data to fit that particular model.
  
### Examples of Clustering in Business

Clustering helps businesses manage their data more effectively. For example, retailers can use clustering models to determine which customers buy particular products, on which days, and with what frequency. This can help retailers target products and services to customers in a specific demographic or region.

Clustering can help grocery stores group products by a variety of characteristics (brand, size, cost, flavor, etc.) and better understand their sales tendencies. It can also help car insurance companies that want to identify a set of customers who typically have high annual claims in order to price policies more effectively. In addition, banks and financial institutions might use clustering to better understand how customers use in-person versus virtual services to better plan branch hours and staffing.

## 2. Association

Data miners use association to discover unique or interesting relationships between variables in databases. Association is often employed to help companies determine marketing research and strategy.

### Methods for Data Mining Association

  - **Single-dimensional association**: This involves looking for one repeating instance of a data point or attribute. For instance, a retailer might search its database for the instances a particular product was purchased. 
  - **Multi-dimensional association**: This involves looking for more than one data point in a data set. That same retailer might want to know more information than what a customer purchased — such as their age, method of purchase (cash or credit card), or age.

### Examples of Association in Business
The analysis of impromptu shopping behavior is an example of association — that is, retailers notice in data studies that parents shopping for childcare supplies are more likely to purchase specialty food or beverage items for themselves during the same trip. These purchases can be analyzed through statistical association.

Association analysis carries many other uses in business. For retailers, it’s particularly helpful in making purchasing suggestions. For example, if a customer buys a smartphone, tablet, or video game device, association analysis can recommend related items like cables, applicable software, and protective cases. 

Additionally, association is used by the government to employ census data and plan for public services; it is also used by doctors to diagnose various illnesses and conditions more effectively.

## 3. Classification
In data mining, classification is considered to be a form of clustering — that is, it is useful for extracting comparable points of data for comparative analysis. Classification is also used to designate broad groups within a demographic, target audience, or user base through which businesses can gain stronger insights. 

### Methods for Data Mining Classification

  - **Logistic regression**: This algorithm attempts to show the probability of a specific outcome within two possible results. For example, an email service can use logistic regression to predict whether or not an email is spam.
  - **Decision trees**: Once data is classified, follow-up questions can be asked, and the results diagrammed into a chart called a decision tree. For example, if a computer company wants to predict the likelihood of laptop purchases, it may ask, Is the potential buyer a student? The data is classified into “Yes” and “No” decision trees, with other questions to be asked afterward in a similar fashion. 
  - **K-nearest neighbors (KNN)**: This is an algorithm that tries to identify an unknown object by comparing it to others. For instance, grocery chains might use the K-nearest neighbors algorithm to decide whether to include a sushi or hot meals station in their new store layout based on consumer habits in the local marketplace.
  - **Naive Bayes**: Based on the Bayes Theorem of Probability, this algorithm uses historical data to predict whether similar events will occur based on a different set of data.
  - **Support Vector Machine (SVM)**: This machine learning algorithm is often used to define the line that best divides a data set into two classes. An SVM can help classify images and is used in facial and handwriting recognition software.
  
### Examples of Classification in Business

Financial institutions classify consumers based on many variables to market new loans or project credit card risks. Meanwhile, weather apps classify data to project snowfall totals and other similar figures. Grocery stores also use classification to group products by the consumers who buy them, helping forecast buying patterns.

## 4. Outlier Detection

While other data mining methods seek to identify patterns and trends, outlier detection looks for the unique: the data point or points that differ from the rest or diverge from the overall sample. Outlier detection finds errors, such as data that was input incorrectly or extracted from the wrong sample. Natural data deviations can be instructive as well.

### Methods for Outlier Detection

  - **Numeric outlier**: Outliers are detected based on the Interquartile Range, or the middle 50 percent of values. Data points outside that range are considered outliers. 
  - **Z-score**: The Z-Score denotes how many standard deviations a data point is from the sample’s mean. This is also known as extreme value analysis.
  - **DBSCAN**: This stands for “density-based spatial clustering of applications with noise” and is a method that defines data as core points, border points, and noise points, which are the outliers.
  - **Isolation forest**: This method isolates anomalies in large sets of data (the forest) with an algorithm that searches for those anomalies instead of profiling normal data points.
  
### Examples of Outlier Detection in Business

Almost every business can benefit from understanding anomalies in their production or distribution lines and how to fix them. Retailers can use outlier detection to learn why their stores witness an odd increase in purchases, such as snow shovels being bought in the summer, and how to respond to such findings. 

Generally, outlier detection is employed to enhance logistics, instill a culture of preemptive damage control, and create a smoother environment for customers, users, and other key groups. 

## 5. Prediction
Predictive modeling seeks to turn data into a projection of future action or behavior. These models examine data sets to find patterns and trends, then calculate the probabilities of a future outcome.

Predictive modeling is among the most common uses of data mining and works best with large data sets that represent a broad sample size.

### Methods for Prediction

  - **Forecast modeling**: This is a common technique in which the computer answers a question (for instance, How much milk should a store have in stock on Monday?) by analyzing historical data.
  - **Classification modeling**: Classification places data into groups where it can be used to answer direct questions. 
  - **Cluster modeling**: By clustering data into groups with shared characteristics, a predictive model can be used to study those data sets and make decisions.
  - **Time series modeling**: This model analyzes data based on when the data was input. A study of sales trends over a year is an example of time series modeling.

### Examples of Prediction in Business

Predictive modeling is a business imperative that impacts nearly every corner of the public and private sectors. According to MicroStrategy, 52 percent of global businesses consider advanced and predictive modeling their top priority in analytics.

Predictive models can be built to determine sales projections and predict consumer buying habits. They help manufacturers forecast distribution needs and determine maintenance schedules. Government agencies use census data to map population trends and project spending needs while baseball teams use predictive models to determine contracts and build rosters.
