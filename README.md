# **Car Insurance Claims:**


![ReadMe Image](https://github.com/FoxEW/Car-Insurance-Claims/blob/main/Car_Insurance.jpg?raw=true)

**Author:** Eric


**Business Problem & Scope:**

- Analyse the available data set and identify potential Client segments with high claim risks and provide further insights and recommendations to the Stakeholder. 


**Stakeholders:**

- Insurance Company with potential underwriting and marketing professionals.


**Data Source:**

- Car Insurance data set - from Kaggle
- https://www.kaggle.com/datasets/sagnik1511/car-insurance-data


**Data Description:**

The Stakeholder - a **Car Insurance Company** - has a need to derive more value from available insurance & claims related data.

- The data set consists of 10,000 rows of data - detailing 19 features re. Client & Insurance related events.
- Granularity of data: On a record level - each row provides details of a client's insurance related activities.
- **"Outcome"** = Provides the claim status (activities) of the Client (1 = Claimed, 0 = Not Claimed).


**Exploratory Data Analysis - Insight & Analytics:**

![ReadMe Image](https://github.com/FoxEW/Car-Insurance-Claims/blob/main/Insurance%20Claims%20by%20Driving%20Experience.png?raw=true)

- Claims are reduced by Clients with more ```Years of Driving Experience```; e.g. 20-29 year & 30+ year groups. 
- Claims are more likely to occur in the group where Clients have ```0-9 years of Driving Experience```.

![ReadMe Image](https://github.com/FoxEW/Car-Insurance-Claims/blob/main/Insurance%20Claims%20by%20Age%20Group.png?raw=true)

- ```Insurance Claims``` are the highest in the ```Age Group``` 16-25 year and much lower in the 65+ year group.


**Model preference & supporting metrics:**

The **recommended model** is the - **Logistic Regression Model - using Principal Component Analysis (PCA)**.

This model can assist the Stakeholder to identify and understand metrics that contributes to higher claim activities from Client segments; e.g. :

- Client Driver Experience (years)
- Client Age Category (age group)
- etc, ...


**Specific recommendations to the Stakeholders - as per model findings:**

- Management of claims & costing of insurance products (premiums) can be optimized by taking note of events that increase claim (accident) incidents; e.g. :

  - Speeding drive styles by Clients 
  - Clients with limited years of Driving Experience
  - Clients that fall in younger age groups
  - Client with lower income levels
  - etc, ...
 
- The Insurance Company can also potentially increase profits (reduce claims) by expanding the below segments of their current Client base:
  
  - Clients with 20+ years driving experience
  - Clients of 40+ years of age
  - etc, ...
