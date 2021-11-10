# Lending Club Case Study using exploratory data analysis(EDA).

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This case study is to apply various exploratory data analysis technique to solve the business problem of *consumer finance company*.Solving this assignment will give an idea about how real business problems are solved using EDA.

### Business Understanding
Lending Club is a consumer finance company which specializes in lending various types of loans. The company receives a loan application, the company must decide for loan approval based on the applicant’s profile. Certain factors of risks are associated while making this decision.
    * Loss of business
        Applicant is likely to pay the loan, and company is not approving the loan.
    * Financial Loss
        Applicant may default on the loan, i.e. not pay.
        
### Business Objective
Improve loan approval process to balance revenue from customer who fully pay their loans and financial loss due to customers defaulting.

### Problem Statemenet
When a person applies for a loan, there are two types of decisions that could be taken by the company:
    *Loan accepted
    *Loan rejected
Lending Club would like for us to do an exploratory data analysis to the past loan applicant’s dataset to understand consumer attributes and loan attributes that *drive loan default behavior & thereby the ability to identify risky loan applicants*.

### Data Set
The dataset *loan.csv* contains previous data for loan applicants with the loan default status.

### Data Understanding
* Loan.csv - the dataset to work on
* Data_Dictonary.xlsx - covers the defination of all attributes of the dataset
* Various consumer and loan attributes(details covered in the notebook) in the data set was considered for data analysis.
    - Annual income,etc.



## Conclusions
* Any loan applicant with annual **income less than 100K** should go through heightened scrutiny.
* It's **risky** to offer loan to applicants with **higher DTI and Loan to income ratio**.
* The higher default rate in **high interest rate category** evidently says it's **risky to offer high interest loan** to customers.
* Any loan applicant who has a **credit age below 5** years should go through heightened scrutiny.
further details in *Recommendation.xlsx* and *Lending Club Case Study.pdf*
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
#### Python libraries
* Pandas.
* numpy.
* matplotlib.
* seaborn.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was created as part of AI & ML program Sept 2021, Upgrad 



## Contact
Created by [@udaykadavi] - feel free to contact me! <br>
Contributor - [@2bibhu]
