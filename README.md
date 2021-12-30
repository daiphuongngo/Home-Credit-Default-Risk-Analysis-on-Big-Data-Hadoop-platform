## Home Credit Default Risk Analysis on Big Data (Hadoop, SQL), Tableau, Power BI

## Category: 

- Banking

- Credit

- Finance

- Financial Institute

## Dataset: Home Credit Default Risk

Original: https://www.kaggle.com/c/home-credit-default-risk

Customized datasets:

- application.csv: (Application dataset)

| prev_id	| curr_id	| contract | amount | credit | down_payment | start_day | purpose | contract_status | payment_type | reject_reason | client | product_type | channel | yield_group | 
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|


- p_application.csv: (Previous Application dataset)

| curr_id	| contract | sex | car | income | credit | income_type | education | family_status | house | start_day | organization | 
|-|-|-|-|-|-|-|-|-|-|-|-|

Original datasets:

![home_credit](https://user-images.githubusercontent.com/70437668/147731951-9f81a423-c763-438c-8743-fb625f49aed8.png)

## Business Case:

"Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders. Home Credit Group strives to broand fiancial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.

While Home Credit is currently using various statistical and machine learning methods to make these predictions, they're challenging Kagglers to help them unlock the full potential of their data. Doing so will ensure that clients capable of repayment are not rejected and that loans are given with a principal, maturity, and repayment calendar that will empower their clients to be successful."

## Targets:

Conducting a basic Explanatory Data Analysis on their customized datasets as attached on the Big Data platform to analyze the loan applicants' background and help Home Credit Group expanding their financial services to those who are unable to access financial service. 

## Languages & Tools: 

- Python 

- SQL

- Scala 

+ Hadoop

+ Hive

+ HDFS

+ Zeppelin

+ Tableau

+ Power BI

## Business Questions: 

- Family status of the loan applicants?

- Occupation of the loan applicant?

- Education of the loan applicant?

- How capable would each applicant be of repaying a loan? 

## Final Conclusion:

Most significant background check of applicants who got the most loan approvals:

- Working Income Type

- Married Family Status

- Secondary/Special Secondary Education Type

Home Credit should:

- Focus on Working income type, Married couples, Secondary/High school education background of applicants as the first priority and the main customer target

- Secondary customer target should be Commercial Associates, Single/Not Married customers, High School

## Visualizing charts:

### Living Background of Loan Applicants by Gender

![Living Background of Loan Applicants by Gender](https://user-images.githubusercontent.com/70437668/138408668-5839b767-c253-4a87-82b6-a42df5cdcf1c.jpg)

![Living Background of Loan Applicants by Gender](https://user-images.githubusercontent.com/70437668/140484418-f6c9110a-6d4a-42a6-ad6b-902468625552.jpg)

### Loan applications by family status

![Loan applications by family status](https://user-images.githubusercontent.com/70437668/138408685-c430d66f-4182-4076-91e0-90955be465b6.jpg)

![Loan applications by family status](https://user-images.githubusercontent.com/70437668/140484455-8d67093e-6b2e-4306-a7dd-1b6f1483e86f.jpg)

### Percentage of loan applications by family status 

![Percentage of loan applications by family status ](https://user-images.githubusercontent.com/70437668/138408705-77485972-7369-415a-a32e-6c7c4116874b.jpg)

![Percentage of loan applications by family status](https://user-images.githubusercontent.com/70437668/140484469-9973d556-4778-4a69-95fe-c3abb1e79678.jpg)

### Contract Status by Income Type

![Contract Status by Income Type](https://user-images.githubusercontent.com/70437668/138408514-01b4dc82-bf5f-49da-96ea-de562a40b4f4.jpg)

![Contract Status by Income Type](https://user-images.githubusercontent.com/70437668/140484484-699abc75-4449-4812-a244-2c673583a2bd.jpg)

### Education type of applicants who got the most loan approvals

![Education type of applicants who got the most loan approvals](https://user-images.githubusercontent.com/70437668/138408564-c312b289-2db8-46ba-b34f-4406b875715f.jpg)

![Education type of applicants who got the most loan approvals](https://user-images.githubusercontent.com/70437668/140484503-84ec3124-da24-4599-9ddf-337f95121f85.jpg)

### Income Sources of Loan Applicants

![Income Sources of Loan Applicants](https://user-images.githubusercontent.com/70437668/138408604-69600898-47aa-4b6c-aba2-548cd4a4f63f.jpg)

![Income Sources of Loan Applicants](https://user-images.githubusercontent.com/70437668/140484514-5dca47af-c41b-4bfe-a33d-a719c5b9eafa.jpg)

### Income type of applications who got the most loan rejection

![Income type of applications who got the most loan rejection](https://user-images.githubusercontent.com/70437668/138408628-2bb8d7c0-b2bf-4f83-a2d4-703787f6a05d.jpg)

![Income type of applications who got the most loan rejection](https://user-images.githubusercontent.com/70437668/140484524-5cd7fb2c-e73b-40c7-beb9-5bf3e1f944a5.jpg)

### Average Income by Income Type

![Average Income by Income Type](https://user-images.githubusercontent.com/70437668/138408493-42a014a1-1a22-4c47-a50a-b4712937a300.jpg)

![Average Income by Income Type](https://user-images.githubusercontent.com/70437668/140484541-c6aeaaae-5729-4b41-8092-fcf1bd85e228.jpg)

### Credit Amount by Income Sources of Loan Applicants

![Credit Amount by Income Sources of Loan Applicants](https://user-images.githubusercontent.com/70437668/138408538-8329ea1b-93cc-48c0-aa15-b2bcafa3e33b.jpg)

![Credit Amount by Income Sources of Loan Applicants](https://user-images.githubusercontent.com/70437668/140484552-dd90ef33-6daf-4319-9a09-3fa80ac1302b.jpg)

## Dashboards:

### Dashboard - Income type, Family Status, Education, Credit Amount

![Dashboard - Income type, Family Status, Education, Credit Amount](https://user-images.githubusercontent.com/70437668/138408987-1c864496-ef72-406b-99d3-a0e29dc9213b.jpg)

### Dashboard - Income Type and Average

![Dashboard - Income Type and Average](https://user-images.githubusercontent.com/70437668/138409002-ed5f0e0d-98e5-4c70-a0e2-6b1ca70ea55d.jpg)

### Dashboard - Approved applicants by family, contract status, income type

![Dashboard - Approved applicants by family, contract status, income type](https://user-images.githubusercontent.com/70437668/138409033-7816863a-fc6f-492c-b84e-fadeaff9da8c.jpg)




