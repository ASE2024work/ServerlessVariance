# Exploring the Overlooked Performance Variance in Serverless Computing

Welcome to visit the homepage of our paper entitled "Exploring the Overlooked Performance Variance in Serverless Computing". The homepage contains the collected research papers, serverless functions, their code, and scripts that execute serverless functions.


## Research Papers

* In the file "**Collected research papers and RQ1 results.xlsx**", there is detailed information about 99 research papers that we collected, including
  - CSRankings category
  - conference
  - publication year
  - paper title 
  - the labeled information **regarding RQ1**
    - Category 1: Mean or median values
    - Category 2: Confidence (e.g., confidence intervals) or variability (e.g., standard deviation, coefficient of variance, or percentiles)
    - Category 3: The number of times that an experiment was repeated


## Serverless Functions

* We have also curated and made publicly available a dataset about serverless functions for future performance testing and optimization of serverless computing.
  - In the file "**Serverless functions.xlsx**", there is detailed information about 72 serverless functions, including
    - input payload
    - executed serverless platform
    - programming language
    - timeout time
    - memory allocation size
    - original code link
    - functionality type
    - involved research papers


## Code for Serverless Functions

* In the directory "**ServerlessFunctionCode**", there are deployment packages corresponding to Func1 to Func72. 
  - the code for each serverless function is packaged in a separate folder
  - the short input payload for some serverless functions is recorded in the file "**Executed serverless functions.xlsx**"
  - the long input payload for some serverless functions is stored in the directory "**input**", including the payloads for func20, func29, func54, func56, func57, and func60


## Scripts

* **Invocation scripts**: Invocation scripts used in our study are in the directory "**Invocation scripts**", including the invocation code of AWS Lambda and Google Cloud Functions.
  - "**invokeFunctionScript-run1.py**" and "**invokeFunctionScript-run2.py**" for AWS Lambda
  - "**invokeGoogleFunction.py**" for Google Cloud Functions
