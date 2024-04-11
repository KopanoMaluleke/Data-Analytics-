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
