# LearnData :scientist: :computer: :books:
Useful resources I used to learn data engineering, data analysis and data science. The list is updated on a regular basis.

## Data Engineering
### 1. Data Warehousing

- **[Kimball's Data Warehouse Guide](https://drive.google.com/file/d/1N-1gvleB9G-csHTTwjeQ5Ac_-P3Wr2Cd/view?usp=sharing)**

Toolkit of dimensional design principles and techniques. This book contains many examples that serve as a framework to discuss the patterns that
emerge in dimensional modeling. It is mainly used as a reference when designing **Data Warehouses** and understanding their purpose in the world of business intelligence and analytics.

- **[Data Warehouse Fundamentals Udemy Course](https://www.udemy.com/course/data-warehouse-fundamentals-for-beginners/?ranMID=39197&ranEAID=GjbDpcHcs4w&ranSiteID=GjbDpcHcs4w-Z4loChyTwoEeSbWrJLz3Jw&utm_source=aff-campaign&LSNPUBID=GjbDpcHcs4w&utm_medium=udemyads) (TODO)**

A Udemy course I have completed to get a solid grasp of Data Warehousing fundamentals.

- **The Big Table Design**

### 2. Data modeling

"Data modeling is the process of creating a visual representation of either a whole information system or parts of it to communicate connections between data points and structures. The goal is to illustrate the types of data used and stored within the system, the relationships among these data types, the ways the data can be grouped and organized and its formats and attributes." (IBM)

Here's an [article](https://www.ibm.com/cloud/learn/data-modeling) discussing the process of data modeling and the types of data modeling (such as dimensional data models, relational data models, ...)

- **[Role-playing dimensions in Power BI](https://towardsdatascience.com/role-playing-dimensions-in-power-bi-185dc58f90f1)**

- **[Slowly changing dimension](https://en.wikipedia.org/wiki/Slowly_changing_dimension)**

### 3. ETL and ELT
### 4. Big Data
 * **Hadoop**
     * **[What is MapReduce](https://www.guru99.com/introduction-to-mapreduce.html)**
### 5. SQL

* **[Basic SQL commands](https://www.w3schools.com/sql/sql_syntax.asp)**

All basic data query language statements (SELECT, WHERE, DISTINCT, ORDER BY, GROUP BY, ...)

* **[DDL, DQL, DML and DCL](https://www.geeksforgeeks.org/sql-ddl-dql-dml-dcl-tcl-commands/)**: Four categories of SQL commands

  * **DDL: Data Definition Language:** SQL commands that can be used to define the database schema

  * **DQL: Data Query Language:** Used for performing queries on the data within schema objects

  * **DML: Data Manipulation Language:** Commands that deals with the manipulation of data present in the database

  * **DCL: Data Control Language:** includes commands such as GRANT and REVOKE which mainly deal with the rights, permissions, and other controls of the database system

* **[Aggregate Functions and Window Functions](https://learnsql.com/blog/window-functions-vs-aggregate-functions/)**
* **[How to solve complex SQL questions](https://www.youtube.com/watch?v=vLjAG9eXkcU&list=PLLqIliLAYMUcoMQzpGbibNDHOWez_uAJF&index=48)**

A methodology used to approach more complex problems that involve more business rules and logical steps. 
* **[CTEs and Temp Tables in SQL Server](https://www.dotnettricks.com/learn/sqlserver/difference-between-cte-and-temp-table-and-table-variable#:~:text=Temp%20Tables%20are%20physically%20created,the%20scope%20of%20a%20statement.)**
*  **[Triggers](https://www.youtube.com/watch?v=WBmE4Utu6P4)**
* **[Indexes](https://www.tutorialspoint.com/sql/sql-indexes.htm)**

Speeding up data retrieval in a database



- **Query optimization**
### 6. APIs 

### 7. Python 

## Data Analysis / Data Science

### 1. Types of data analysis
A list of popular types of data analysis
- **[Diagnostic Analysis](https://www.sisense.com/glossary/diagnostic-analytics/)**
- **[Churn analytics](https://mixpanel.com/blog/churn-analytics/#:~:text=Churn%20analytics%20is%20the%20process,larger%20margins%2C%20and%20higher%20profits.)**
The process of measuring the rate at which customers qui the rate, product/site/or service (Marks Simborg, 2022)

### 2. Statistics

- **Descriptive Statistics**
- **Confidence Interval and Sampling Strategies**
- **[Hypothesis testing and the Null Hypothesis](https://www.youtube.com/watch?v=0oc49DyA3hU)**

    Some information on [t-tests](http://www.sthda.com/english/wiki/paired-samples-t-test-in-r)

### 3. Data visualization tips
- **[10 Rules For Better Dashboard Design](https://uxplanet.org/10-rules-for-better-dashboard-design-ef68189d734c)**

### 4. Power BI
- **[Power BI DAX Exercices](https://www.wiseowl.co.uk/power-bi/exercises/)**

A list of exercices on Wise Owl's Website to practice the DAX langugage

- **[Data modeling for Power BI](https://www.youtube.com/watch?v=MrLnibFTtbA)**

The main topics that are discussed in the video include: Data modeling (more specifically, dimensional modeling), the attributes of a good data model (what makes a good data model), the advantages of a good data model, star schemas, Fact (the representation of a business event, for example a sale transaction, a student enrolling in a course, ...) and Dimension (contains descriptive attributes that define how a fact should roll up, for example, rol it up to the country, to the category, ...) tables, the granurality of data, ...

The video also includes a demo.

### 5. [Supervised and unsupervised Learning](https://www.ibm.com/cloud/blog/supervised-vs-unsupervised-learning)
## Projects

**1. Etsy shop scrape data and load it in database, analyze competitors sales history** TODO

**2. [Predict the outcome of a League of Legends match using Riot Games's API](https://github.com/Abddab/Predicting_League_of_Legends_match_outcome)** In progress

**3. [Building a Data Warehouse from a transactional database](https://github.com/Abddab/Data-Warehousing-demo/blob/main/README.md)**

Using [AdventureWorks's OLTP database](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms), create a Data Warehouse using SSIS as an ETL tool. The dimensional models will be imported into Power BI to generate useful reports.

## Toolbox
## Markdown
**1. [Markdown Language Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)**

**2. [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)**

**3. [A good README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2#file-readme-template-md)**


