# Data-Analytics-

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/47b3cc62-54bf-42ab-91cc-f690560c675b/bbe296c3-4019-4024-bba7-ccaf8c741eb0/Untitled.png)

Skills: 

- Data visualization
- Descriptive analytics
- Predictive modelling

# Week 1 - Data Analytics

Content covered in week one:

**Module 1: The Basics of Data**

- Chapter 1: The Data Analyst
- Chapter 2: Understanding Data

Data analytics can be branched into two primary components: conceptual understanding of data (theoretical aspect) and hands-on manipulation of data (practical aspect).

## **Module 1: The Basics of Data**

1. What the role of a Data Analyst is and the scope of data analytics.
2. The process of data analytics.
3. The techniques of data analytics.
4. The role of data governance.

**What the role of a Data Analyst is and the scope of data analytics.**

- The ultimate role of a data analyst is to transform raw data into actionable insights that guide decision-making processes within an organization.

***key responsibilities and skills:***

1. Data Collection and Preparation

2. Data Analysis

3. Data Visualization and Storytelling

4. Decision Support

5. Collaboration and Communication

6. Continuous Learning and Adaptation

 The goal is to contribute to the organization's success by turning data into a valuable asset that informs and drives decision-making.

Article about data analytics in more depth:  

[YouTube](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbWR0RUNtYnlLS3ZEaHRtZVdoLVpZcjRxdnRVZ3xBQ3Jtc0trRlpJUHpvdjBxQUVfM0RiY0l4MTdqMEk4N2xNZk9tbWpvRkc5ZnEtdzFsUnVTMklCVjVEc3BHY3NoTC1USnhvbjU2SGlEUTF6U0Z5d01IVnI1cnpPd1JTVHZDejhMUmx1Q2JUOFJsS3Q0ang0aS12cw&q=https://bit.ly/47LEBk3&v=yZvFH7B6gKI)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/47b3cc62-54bf-42ab-91cc-f690560c675b/dfb1e44b-e3b5-4e9d-a40e-355b8a4d5f8d/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/47b3cc62-54bf-42ab-91cc-f690560c675b/5c2d150a-5fb2-49e6-a09f-2cadaa37a54e/Untitled.png)

Artificial intelligence (AI) includes any type of technique where you are attempting to get a computer system to imitate human behavior. 

Exam Tip: 

**You will not need to know the details of machine learning, artificial intelligence, or deep learning techniques when you take the CompTIA Data+ exam. It is, however, important that data analysts understand these techniques, but they are beyond the scope of the test.**

---

Chapter 2 

In this chapter, you will:

- Understand Domain 1.0: Data Concepts and Environments
- Compare and contrast different data types
- Compare and contrast common data structures and file formats

- ---

Chapter 2 

In this chapter, you will:

- Understand Domain 1.0: Data Concepts and Environments
- Compare and contrast different data types
- Compare and contrast common data structures and file formats

Data elements and data types in Data Science 

- A **data element** is an attribute about a person, place, or thing containing data within a range of values.
- A **data type** limits the values a data element can have.

Structured data is tabular in nature and organized into rows and columns.

**Alphanumeric** is the most widely used data type for storing character-based data.  alphanumeric is appropriate when a data element consists of both numbers and letters. An example is with an Address both the letter and numbers are required. 

- Alphanumeric data type is ideal for storing product stock-keeping units (SKUs). Common in the retail clothing space to have a unique SKU for each item available for sale.
- If you sell jeans, you may stock products from Armani Jeans, Diesel, Lee Jeans, Levi's, and Wrangler. To keep track of all the manufacturer, size, color, and fit combinations in your inventory, you might use an SKU

**Character Sets**
11/04/2024

**Character Sets**

The ASCII encoding standard is based on the U.S. English alphabet. ASCII accommodates both the upper and lowercase English alphabet and numbers, mathematical operators, and symbols.

Exam Tip: ***As you prepare for the Data+ exam, you should recognize the difference between storing a data type and formatting it to facilitate human interpretation. Take care not to automatically infer a data type based on formatting.***

***Strong And Weak Typing***

- A database column defined as numeric only accepts numerical values. You will get an error if you attempt to enter characters into a numeric column.

## *Unstructured Data Types*

 Unstructured data is any type of data that does not fit neatly into the tabular model. 

Examples of unstructured data include:

- digital images
- audio recordings
- video recordings
- open-ended survey responses

To capture and analyze unstructured data, we make use of data types designed explicitly for that purpose.

Problem Statement: Suppose the veterinary office wants to augment its records to include digital images of the animals. To accommodate that requirement, we need to make use of an unstructured data type. 

- Binary data types are one of the most common data types for storing unstructured data.  When considering which binary data type to use, file size tends to be the limiting factor.

Exam Tip: ***As you prepare for the Data+ exam, you should be familiar with the different types of structured and unstructured data that you might encounter. Be prepared to evaluate a situation and select the most appropriate data type to store a piece of data.***

## *Semi-structured*

Semi-structured data represents the space between structured spreadsheets and unstructured videos.

- Quantitative or Qualitative: Quantitative data answers questions like “How many?” and “How much?” Qualitative data consists of frequent text values. Data elements whose values describe characteristics, traits, and attitudes are all qualitative
- Discrete vs. Continuous Data: Qualitative data is discrete, but quantitative data can be either discrete or continuous data. For example, age is a continuous variable, but you may treat a person's age in years as discrete. A good rule of thumb is that discrete applies when counting while continuous applies when measuring.

Exam tip: 

***As you prepare for the Data+ exam, make sure you can distinguish between qualitative and quantitative data, as well as discrete and continuous data.***

***Categorical Data***

- Text data with a known, finite number of categories is categorical.

***Dimensional Data***

- Dimensional modeling is an approach to arranging data to facilitate analysis.

**Structured Data vs Unstructured Data vs Semi-Structured Data**

- Tabular data is structured data, with values stored in a consistent, defined manner, organized into columns and rows.
- Unstructured data is qualitative, describing the characteristics of an event or an object. Images, phrases, audio or video recordings, and descriptive text are all examples of unstructured data.
- Semi-structured data is data that has structure and that is not tabular. Email is a well-known example of semi-structured data.

### *Text Files*

Text files are one of the most commonly used data file formats. As the name implies, they consist of plain text and are limited in scope to alphanumeric data.

- Text files are also commonly referred to as flat files.
- Widely adopted is their ability to be opened regardless of platform or operating system without needing a proprietary piece of software. Whether you are using a Microsoft Windows desktop, an Apple MacBook, or a Linux server.
- When a file is comma-delimited, it is known as a **comma-separated values (CSV)** file.
- When a file is tab-delimited, it is called a **tab-separated values (TSV)** file.

***Fixed-Width Files***

Before it was common to use delimited files with variable-length columns, flat files were fixed-width

***JavaScript Object Notation***

*JavaScript Object Notation (JSON)* is an open standard file format, designed to add structure to a text file without incurring significant overhead. Easily readable by people and easily parsed by modern programming languages.

***Extensible Markup Language (XML)***

*Extensible Markup Language (XML)* is a markup language that facilitates structuring data in a text file. While conceptually similar to JSON, XML incurs more overhead because it makes extensive use of tags. Tags describe a data element and enclose each value for each data element. While these tags help readability, they add a significant amount of overhead.

***HyperText Markup Language (HTML)***

HyperText Markup Language (HTML) is a markup language for documents designed to be displayed in a web browser.




---

16/04/2024

**Databases and Data Acquisition**

Databases make it easy to summarize a lot of data. 

- Example: For example, a financial analyst wants to understand why some retail outlets are more profitable than others. The analyst might look at the individual records for each store, but that's difficult to do if there are thousands of items and hundreds of stores. Answering the business questions here requires summarizing the data for each store.

# Relational vs Nonrelational

### Relational Database

- The oldest and most mature databases is the relational database.  Relational databases excel at storing and processing structured data. Tabular data is highly structured.
- Entity Relationship Diagram:  ER diagrams **provide a graphical interface for designing databases**.
- The power of the relational model is that it also allows us to describe how entities connect or relate, to each other.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/47b3cc62-54bf-42ab-91cc-f690560c675b/1c924693-2ec9-41ae-b4a1-6a464f414471/Untitled.png)

Unary - A unary relationship is when an entity has a connection with itself.  

- A binary relationship connects two entities
- A ternary relationship connects three entities. For example, you might use a ticket entity to connect a venue, a performing artist, and a price.

Binary relationships are the most common and easy to explore, whereas unary and ternary are comparatively complex and rare.

ERD 

- Entity relationship diagram also serves as a relational database's blueprint.
- Ability to read ERDs helps you understand the structure of a relational database.
- Useful when formulating how to retrieve information from the database that is spread across multiple tables

## Relational Databases

— Are pieces of software that let you make an operational system out of an ERD.


# Relational vs Nonrelational

---

19/04/2024

### Relational Database

- The oldest and most mature databases is the relational database.  Relational databases excel at storing and processing structured data. Tabular data is highly structured.
- Entity Relationship Diagram:  ER diagrams **provide a graphical interface for designing databases**.
- The power of the relational model is that it also allows us to describe how entities connect or relate, to each other.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/47b3cc62-54bf-42ab-91cc-f690560c675b/1c924693-2ec9-41ae-b4a1-6a464f414471/Untitled.png)

Unary - A unary relationship is when an entity has a connection with itself.  

- A binary relationship connects two entities
- A ternary relationship connects three entities. For example, you might use a ticket entity to connect a venue, a performing artist, and a price.

Binary relationships are the most common and easy to explore, whereas unary and ternary are comparatively complex and rare.

ERD 

- Entity relationship diagram also serves as a relational database's blueprint.
- Ability to read ERDs helps you understand the structure of a relational database.
- Useful when formulating how to retrieve information from the database that is spread across multiple tables

## Relational Databases

— Are pieces of software that let you make an operational system out of an ERD. 

---

## Nonrelational Databases

- A nonrelational database does not have a predefined structure based on tabular data. Data validation happens in code, as opposed to being done in the database.

Examples of nonrelational databases include 

- key-value
- document
- column family, and
- Graph

### Database Use Cases

Databases stores data

Databases tend to support two major categories of data processing:

- Online Transactional Processing (OLTP) and
- Online Analytical Processing (OLAP).

# **Online Transactional Processing**

- OLTP systems handle the transactions( booking a flight reservation) we encounter every day. OLTP systems balance the ability to write and read data efficiently.

**Normalization**

Normalization is the process to eliminate data redundancy and enhance data integrity in the table. Normalization also helps to organize the data in the database. It is a multi-step process that sets the data into tabular form and removes the duplicated data from the relational tables.

First normal form (1NF) is when every row in a table is unique and every column contains a unique value.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/47b3cc62-54bf-42ab-91cc-f690560c675b/e8dcec2e-8d8b-417e-8ede-86a01b23c29c/Untitled.png)

# **1st Normal Form (1NF)**

- A table is referred to as being in its First Normal Form if atomicity of the table is 1.
- Here, atomicity states that a single cell cannot hold multiple values. It must hold only a single-valued attribute.
- The First normal form disallows the multi-valued attribute, composite attribute, and their combinations.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/47b3cc62-54bf-42ab-91cc-f690560c675b/7df52764-dabd-48c2-ba3f-29869d476e9d/Untitled.png)

# **Candidate Key**

A candidate key is a set of one or more columns that can identify a record uniquely in a table, and YOU can use each candidate key as a [Primary Key.](https://www.simplilearn.com/tutorials/sql-tutorial/primary-key-in-sql)

- Primary Key: Putting it simply, it is a column that accepts unique values for each row.
- 

# **Super Key**

Super key is a set of over one key that can identify a record uniquely in a table, and the Primary Key is a subset of Super Key.

# **2NF (Second Normal Form):**

 Builds on 1NF by We need to remove redundant data from a table that is being applied to multiple rows. and placing them in separate tables. It requires all non-key attributes to be fully functional on the primary key.

# **3NF (Third Normal Form):**

Extends 2NF by ensuring that all non-key attributes are not only fully functional on the primary key but also independent of each other. This eliminates transitive dependency.

# **Online Analytical Processing**

OLAP systems focus on the ability of organizations to analyze data.

- OLAP systems have a denormalized design. Instead of having data distributed across multiple tables, denormalization results in wider tables than those found in an OLTP database.

# **Schema Concepts**

- A data warehouse is a database that aggregates data from many transactional systems for analytical purposes.

# **Dimensionality**

- Dimensionality refers to the number of attributes a table has. The greater the number of attributes, the higher the dimensionality.

## **Handling Dimensionality**

- An understanding of this method is required to write a query to retrieve the current price. Another method extends the snowflake approach to modelling dimensions. You have a product dimension for the current price and a product history table for maintaining price history.

---

# **Data Acquisition Concepts**

## **Integration**

- Data from transactional systems flow into data warehouses and data marts for analysis.
1. **Extract:** Phase 1 -  extract data from the source system and place it in a staging area. The goal of the extract phase is to move data from a relational database into a flat file as quickly as possible.
2. **Transform:** Phase 2 transforms the data. The goal is to reformat the data from its transactional structure to the data warehouse's analytical design.
3. **Load:** The purpose of the load phase is to ensure data gets into the analytical system as quickly as possible.

**ETL Vendors**

- A delta load only moves changes between systems

**Data Collection Methods**

- Augmenting data from your transactional systems with external data is an excellent way to improve the analytical capabilities of your organization.

# NB: I need to go back to chapter 3 module 2

Chapter 4 

## Data Quality

**Duplicate Data**

Duplicate data occurs when data representing the same transaction is accidentally duplicated within a system.

- Example: Unintentionally, you double-click the purchase button. Instead of purchasing one ticket for your upcoming travels, you create two. The first is intentional, whereas the second is a duplicate.

The best way to resolve duplicate data is to prevent its creation in the first place. A common way to stop duplicate data before it gets into a system is a visual warning to alert users. 

 Duplicate resolution process

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/47b3cc62-54bf-42ab-91cc-f690560c675b/f944144b-b680-46c8-888a-31d0fb8e8388/Untitled.png)

## **Redundant Data**

Data redundancy is a function of integrating multiple systems.

- Transactional databases are often in third normal form

## **Missing Values**

Missing values occur when you expect an attribute to contain data but nothing is there.  Missing values are also known as null values. 

- To handle missing values, you first have to check for their existence. SQL offers functions to check for null and functions that can replace a null with a user-specified value. There are similar functions in both Python and R.

## **Invalid Data**

- Invalid data are values outside the valid range for a given attribute.

Example: All of the values in Figure 4.8 belong to their respective data type. Historically, temperatures on Earth are between –140 and 140 degrees Fahrenheit. With this context, it becomes clear that –99,999 is an unrealistic value for temperature. The value is clearly invalid despite being numeric.

### **Nonparametric Data**

Nonparametric data is data collected from categorical variables. Sometimes the categories indicate differentiation, and sometimes they have a rank order associated with them. In this latter case, the rank order of the values is of significance, not the individual values themselves.

- For example, suppose a person has abdominal pain and seeks medical attention. The doctor asks the person to rate their pain on a scale of 0 to 10. Since individuals experience pain differently, the scale in Figure 4.9 helps people put their discomfort in context.

### **Data Outliers**

A data outlier is a value that differs significantly from other observations in a dataset.

- Example: Consider the real estate sale price example in Figure 4.10. All of the properties are on the same street, city, and state. Most of the properties have a sale price between $128,000 and $153,000. However, the property at 130 Main Street has a sale price of $26,496,400. That is a dramatic difference from the rest of the sales prices.

### **Specification Mismatch**

A specification describes the target value for a component. A specification mismatch occurs when an individual component's characteristics are beyond the range of acceptable values. 

- For example, suppose you want to add a room to a house and you buy 15 wooden studs. Looking at the blueprint for the addition, you need wooden studs with a rectangular cross-section measuring 2 inches by 4 inches (2×4). When purchasing the studs, you want to ensure that all 15 have a consistent cross-section.

In manufacturing, a specification mismatch causes a component to fail post-production quality checks. 

Data Invalid vs Specification Mismatch 

- When data is invalid, it has values that fall outside a given range.
- Specification mismatch occurs when data does not conform to its destination data type.

 For example, you might be loading data from a file into a database. If the destination column is numeric and you have text data, you'll end up with a specification mismatch. To resolve this mismatch, you must validate that the inbound data consistently maps to its target data type.

### **Data Type Validation**

Refers to **checking whether or not an entry matches the field**. For example, you might try entering text in the age field, which should only allow numerical data types. If the user inputs a text in a numerical type field, the algorithm we use may crash or the results will be faulty.

### **Recoding Data**

Recoding data is a technique you can use to map original values for a variable into new values to facilitate analysis. Recoding groups data into multiple categories, creating a categorical variable. A categorical variable is either nominal or ordinal. 

- For example, T-shirt size is an example of an ordinal variable, as sizes come in small, medium, large, and extra-large. Variable values fit into a fixed number of categories, similar to how lookup tables work in Chapter 3. Recoding is helpful when you have numeric data you want to analyze by category.

### **Derived Variables**

- A derived variable is a new variable resulting from a calculation on an existing variable.

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/47b3cc62-54bf-42ab-91cc-f690560c675b/b062b631-6805-4090-8cdd-5b1b5267a143/Untitled.png)

### **Data Merge**

A data merge uses a common variable to combine multiple datasets with different structures into a single dataset.

Example: Since a data merge adds columns to a dataset, merging gives you additional data about a specific observation. Imagine you want to get an overall picture of a person's health. To get the data, you obtain records from the person's primary care physician and other medical specialists.

Example 2:  Consider the systems that support a university. When a person applies, the university stores data, including admissions essays, high school transcripts, letters of recommendation, and standardized test scores. Upon becoming a student, a person generates academic data, including course enrollment and grades. Some students have work-study jobs, which create payroll data, including hours worked and hourly rate.

veral data manipulation tools are available that cater to various data analysis and transformation needs. Here are some widely used tools:

Microsoft Excel: A versatile spreadsheet tool for basic data manipulation and analysis.
Python: The Pandas library in Python is popular for data manipulation, offering powerful data structures and tools.
R: R is a statistical programming language with packages like dplyr and tidyr that excel in data manipulation.
SQL: Structured Query Language manages and manipulates data in relational databases.
OpenRefine: A tool for cleaning and transforming messy data, handy for data cleaning.
Apache Spark: An extensive data processing framework that supports data manipulation for large datasets.
Tableau Prep: A data preparation tool for cleaning, shaping, and enriching data before analysis in Tableau.

## Data Manipulation

Several data manipulation tools are available that cater to various data analysis and transformation needs. Here are some widely used tools:

1. **Microsoft Excel**: A versatile spreadsheet tool for basic data manipulation and analysis.
2. **Python**: The Pandas library in Python is popular for data manipulation, offering powerful data structures and tools.
3. **R**: R is a statistical programming language with packages like dplyr and tidyr that excel in data manipulation.
4. **SQL**: Structured Query Language manages and manipulates data in relational databases.
5. **OpenRefine**: A tool for cleaning and transforming messy data, handy for data cleaning.
6. **Apache Spark**: An extensive data processing framework that supports data manipulation for large datasets.
7. **Tableau Prep**: A data preparation tool for cleaning, shaping, and enriching data before analysis in Tableau.

