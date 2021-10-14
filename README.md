# Classification of Wine

### Table of Contents
---

I.   [Project Overview             ](#i-project-overview)
1.   [Description                  ](#1-description)
2.   [Deliverables                 ](#2-deliverables)

II.  [Executive Summary  ](#ii-executive-summary)
1.   [Goals:                        ](#1-goals)
2.   [Key Findings:                 ](#2-key-findings)
3.   [Recommendations:              ](#1-recommendations)

III. [Project                      ](#iii-project)
1.   [Questions                    ](#1-questions)
2.   [Findings                     ](#2-findings)

IV. [Data Context                 ](#iv-data-context)
1.   [Data Dictionary              ](#1-data-dictionary)

V.  [Process                      ](#v-process)
1.   [Project Planning             ](#1-project-planning)
2.   [Data Acquisition             ](#2-data-acquisition)
3.   [Data Preparation             ](#3-data-preparation)
4.   [Data Exploration             ](#4-data-exploration)
5.   [Modeling & Evaluation        ](#5-modeling--evaluation)
6.   [Product Delivery             ](#6-product-delivery)

VI.   [Modules                      ](#vi-modules)

VII.  [Project Reproduction         ](#vii-project-reproduction)

<br>

<br>

### I. Project Overview
---
#### Abstract: Using chemical analysis to determine the origin of wines

#### 1. Description

Individual Projects

Codeup students will work on individual data science projects that touch the full DS pipeline.
This time is meant to address feedback that Codeup alumni's portfolios tend to look similar and re-enforce skills in time management and completing end to end data science projects.


#### 2. Deliverables

- Github Repo w/ Final Notebook and README
- Sections indicated with markdown headings in my final notebook with a good title and the documentation is sufficiently explanatory and of high quality
- Project summary and writeup


### II. Executive Summary
---

#### 1. Goals:

- With this project I am striving to create machine learning model/s to predict the origin of wines using chemical analysis. 
This dataset was acquired through UCI's Machine Learning Repository and be found at https://archive-beta.ics.uci.edu/ml/datasets/wine

- Thoroughly document each step
- Make sure project is reproduceable

#### 2. Key findings:

- Clean dataset
- No data dictionary, had to search all the feature meanings.


#### 3. Recommendations:

- Better documentation of what the type/class of wine represent of which growers.
- Have the column names in the data set.
---

### III. Project

#### 1. Questions 

- Can the chemical makeup of wine be used to determine the cultivator/s?

### 2. Findings
#### My findings are:
- The logistic regression model performed the best.

### IV. Data Context
---

#### 1. Data Dictionary

Following acquisition and preparation of the initial data frame from the UCI Machine Learning webpage,  the data frame used in this project contain the following variables, which I had to look up myself. Contained values are defined along with their respective data types.

| Variable                     | Definition                                         | Data Type  |
|:----------------------------:|:--------------------------------------------------:|:----------:|     
| type *                       | type of wine, from three different cultivators     | int64    |
| alcohol                      | measured in % vol or ABV(Alcohol by volume)        | float64    |
| mailic_acid                  | acidity of grapes                                  | float64    |
| ash                          | inorganic matter remaining after evaporation       | float64    |
| alkalinity_of_ash            | a parameter strongly influenced by water balance   | floar64    |
| magneisum                    | a mineral                                          | int64      |
| total_phenols                | important plant consituents with redox properties  | float64    |
| flavanoids                   | type of antioxidant                                | float64    |
| nonflavanoid_phenols         | phenolic compounds with variable structures        | float64    |
| proanthocyanins              | condensed tannins that srongly influence the       |            |
|                              | perceived astringency                              | float64    |
| color_intensity              | is an amount of color                              | float64    |
| hue                          | indicates the development of a color towards orange| float64    |
| od280_od315_of_dilutedwines  | a method for determining the protein concentration | float64    |
| proline                      | an amino acid                                      | int64      |

* Target variable

### V. Process
---
- See my Trello board [Wine Project](https://trello.com/b/UnrjJ2wG/wine-project)

#### 1. Project Planning
✓ 🟢 **Plan** ➜ ☐ _Acquire_ ➜ ☐ _Prepare_ ➜ ☐ _Explore_ ➜ ☐ _Model_ ➜ ☐ _Deliver_

- [x] Build this README containing:
    - Project overview
    - Initial thoughts
    - Project summary
    - Instructions to reproduce
- [x] Plan stages of project and consider needs versus desires

#### 2. Data Acquisition
✓ _Plan_ ➜ 🟢 **Acquire** ➜ ☐ _Prepare_ ➜ ☐ _Explore_ ➜ ☐ _Model_ ➜ ☐ _Deliver_

- [x] Obtain initial data and understand its structure
    - Obtain data from UCI Machine Learning website, downloading a csv file.
- [x] Remedy any inconsistencies, duplicates, or structural problems within data
- [x] Perform data summation

#### 3. Data Preparation
✓ _Plan_ ➜ ✓ _Acquire_ ➜ 🟢 **Prepare** ➜ ☐ _Explore_ ➜ ☐ _Model_ ➜ ☐ _Deliver_

- [x] Address missing or inappropriate values, including outliers
- [x] Plot distributions of variables
- [x] Consider and create new features as needed
- [x] Split data into `train`, `validate`, and `test`

#### 4. Data Exploration
✓ _Plan_ ➜ ✓ _Acquire_ ➜ ✓ _Prepare_ ➜ 🟢 **Explore** ➜ ☐ _Model_ ➜ ☐ _Deliver_

- [x] Visualize relationships of variables
- [x] Decide upon features and models to be used

#### 5. Modeling & Evaluation
✓ _Plan_ ➜ ✓ _Acquire_ ➜ ✓ _Prepare_ ➜ ✓ _Explore_ ➜ 🟢 **Model** ➜ ☐ _Deliver_

- [x] Create, fit, and predict with models
- [x] Evaluate models with out-of-sample data
- [x] Utilize best performing model on `test` data
- [x] Summarize findings

#### 6. Product Delivery
✓ _Plan_ ➜ ✓ _Acquire_ ➜ ✓ _Prepare_ ➜ ✓ _Explore_ ➜ ✓ _Model_ ➜ 🟢 **Deliver**
- [x] Prepare Jupyter Notebook of project details through data science pipeline
    - Python code clearly commented when necessary
    - Sufficiently utilize markdown
    - Appropriately title notebook and sections
- [x] With additional time, continue with exploration beyond MVP
- [x] Proof read and complete README and project repository

### VI. Modules
---

- I did not use any modules in this project

### VII. Project Reproduction
---

To recreate and reproduce results of this project, you will need to download the ataset through UCI's Machine Learning Repository  at https://archive-beta.ics.uci.edu/ml/datasets/wine

then copy the repo and run it.

[[Return to Top]](#classification of wine)

