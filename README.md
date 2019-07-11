# Statistics-for-Data-Science-using-R
Learn the core statistical concepts, followed by application of these concepts using R Studio with the a nice combination of theory and practice. Learn key statistical concepts and techniques like exploratory data analysis, correlation, regression, and inference.

### Statistics: 
Science of Average and their Estimate

### Data Science: 
Data Science is primarily used to make decisions and predictions.

### Business Intelligence: 
Enable the business to make intelligent, fact-based decision.

# Table of Content
1. Data and its Types
2. Variable and it's Types
3. Sample and Population
4. Sampling Techniques
5. Descriptive Statistics
6. Information Gain and Entropy
7. Probability and it's Uses
8. Baye's Theorem
9. Statistical Inference
10. Hypothesis Testing
11. Testing the Data
12. Data Clustering
13. Regression Modelling

### What is statistics?
Statistics Definition: (Science of Average and their Estimate)
Statistics is the science of collecting, organizing, presenting, analyzing and interpreting data for specific purpose to help in making more effective decision.

#### Why study statistics:
To make more effective decision for the betterment of individual, society, business, nature and so on

#### Statistical Analysis:

Statistical analysis is implemented to manipulate, summarize, and investigate data, so that useful decision making information results are obtained.

Two type of statistics:

a)	Descriptive Statistics (used to describe the basic features of the data)

b)	Inferential statistics (aims at learning characteristics of the population from a sample)


# 1. Data and its Types
#### What is data?
Data is a set of collected or recorded facts of particular subject.

Data in general terms refer to facts and statistics collected together for reference or analysis.

Types of Data:
#### 1. Qualitative Data
#### 2. Quantitative Data 

#### 1. Qualitative Data:
“Data Associated with the quality in different categories”. Data is measurements, each fall into one of several categories. (Hair Color, ethnic groups and other attributes of the population)

##### (a). Nominal Data: “With no inherent order or ranking”
~ Data with no inherent order or ranking such as gender or race, suck kind of data called Nominal Data.

##### (b). Ordinal Data: “with an order series”

#### 2. Quantitative Data: 
“Data associated with Quantity which can be measured”
~ Data measured on a numeric scale (distance travelled to college, the number of children in a family etc.)

##### (a). Discrete Data: “Based on count, finite number of values possible and value cannot be subdivided”
~ Data which can be categorized into classification, data which is based upon counts, there are only a finite number of values possible and values cannot be subdivided meaningfully, such kind of data is called Discrete Data.

##### (b). # Continuous Data: “measured on a continuum or a scale, value which can be subdivided into finer increments”
~ Data which can be measured on a continuum or a scale, data which can be have almost any numeric value and can be subdivided into finer and finer increments, such kind of data is called Continuous Data.


# 2. Variable and it's Types
#### What is variable?
A variable in algebra represents an unknown value or a value that varies.

#### Types of Variables:
##### 1. Categorical Variable:
Variable that can be put into categories. For example, male and female are two categories in a Gender.

##### 2. Control Variable:
A factor in an experiment which must be held constant

##### 3. Confounding Variable:
Extra variables that have a hidden effects on your experimental results

##### 4. Dependent Variable (Output Variable):
The outcome of an experiment

##### 5. Independent Variable (Input Variable):
A variable that is not affected by anything


# 3. Sample and Population
#### Population:
A Population is the set of all possible states of a random variable. The size of the population may be either infinite or finite.

In other words, A collection or set of individual or objects or events whose properties are to be anlysed called population.

#### Sample:
A Sample is a subset of the population; its size is always finite.

A subset of population is called "Sample". A well choosen sample will contain most of the information about a particular population parameter.


# 4. Sampling Techniques

#### 1. Probability Sampling : 
This Sampling technique uses randomization to make sure that every element of the population gets an equal chance to be part of the selected sample. It’s alternatively known as random sampling.

##### (a) Random Sampling : 
Every element has an equal chance of getting selected to be the part sample. It is used when we don’t have any kind of prior information about the target population.

For example: Random selection of 20 students from class of 50 student. Each student has equal chance of getting selected. Here probability of selection is 1/50.

##### (b) Systematic Sampling 

Here the selection of elements is systematic and not random except the first element. Elements of a sample are chosen at regular intervals of population. All the elements are put together in a sequence first where each element has the equal chance of being selected.

For a sample of size n, we divide our population of size N into subgroups of k elements.

We select our first element randomly from the first subgroup of k elements.

To select other elements of sample, perform following:

We know number of elements in each group is k i.e N/n

So if our first element is n1 then

Second element is n1+k i.e n2

Third element n2+k i.e n3 and so on..

Taking an example of N=20, n=5

No of elements in each of the subgroups is N/n i.e 20/5 =4= k

Now, randomly select first element from the first subgroup.

If we select n1= 3

n2 = n1+k = 3+4 = 7

n3 = n2+k = 7+4 = 11


##### (c) Stratified Sampling 
This technique divides the elements of the population into small subgroups (strata) based on the similarity in such a way that the elements within the group are homogeneous and heterogeneous among the other subgroups formed. And then the elements are randomly selected from each of these strata. We need to have prior information about the population to create subgroups.

#### 2. Non-Probability Sampling : 
It does not rely on randomization. This technique is more reliant on the researcher’s ability to select elements for a sample. Outcome of sampling might be biased and makes difficult for all the elements of population to be part of the sample equally. This type of sampling is also known as non-random sampling.

##### (a) Snowball Sampling:
This technique is used in the situations where the population is completely unknown and rare.
Therefore we will take the help from the first element which we select for the population and ask him to recommend other elements who will fit the description of the sample needed.

So this referral technique goes on, increasing the size of population like a snowball.

##### For example: 
It’s used in situations of highly sensitive topics like HIV Aids where people will not openly discuss and participate in surveys to share information about HIV Aids.

Not all the victims will respond to the questions asked so researchers can contact people they know or volunteers to get in touch with the victims and collect information

Helps in situations where we do not have the access to sufficient people with the characteristics we are seeking. It starts with finding people to study.

##### (b) Quota Sampling: 
This type of sampling depends of some pre-set standard. It selects the representative sample from the population. Proportion of characteristics/ trait in sample should be same as population. Elements are selected until exact proportions of certain types of data is obtained or sufficient data in different categories is collected.

##### For example: 
If our population has 45% females and 55% males then our sample should reflect the same percentage of males and females.

##### (c) Judgement sampling 
This is based on the intention or the purpose of study. Only those elements will be selected from the population which suits the best for the purpose of our study.

##### For Example: 
If we want to understand the thought process of the people who are interested in pursuing master’s degree then the selection criteria would be “Are you interested for Masters in..?”

All the people who respond with a “No” will be excluded from our sample.

##### (d) Convenience Sampling
Here the samples are selected based on the availability. This method is used when the availability of sample is rare and also costly. So based on the convenience samples are selected.

##### For example: 
Researchers prefer this during the initial stages of survey research, as it’s quick and easy to deliver results.

# 5. Descriptive Statistics: 
Collecting, Summarizing or Describing and Processing data to transform data into information

Descriptive statistics are used to describe the basic features of the data in a study.
* Descriptive statistics is a data analysis strategy.
* It deals with the representation of numerical facts, or data, in either table or graphic form, and with the methodology of analysis the data.

Example: A student’s grade point average (GPA), provides a good understanding in analysing his overall performance.

