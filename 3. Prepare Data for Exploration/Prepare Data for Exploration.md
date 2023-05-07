- Understanding the different types of data and data structures.
- What type of data is right for the question you're answering
- Practical skills about how to extract, use, organize, and protect your data.

Course will cover:
- How data is generated
- Different formats, types, and structures of data
- Analyze data for bias and credibility
- What "Clean data" means
- Databases
- Extract your own data using spreadsheets and SQL
- The basics of data organization
- The process of protecting your data

## Data types and data structures
### Generating data
Every piece of information is data. All that data is usually generated as a result of our activity in the world.

#### How data is collected?
- Interviews
- Observations
(Observation is the method of data-collection most often used by scientists.)
- Forms
- Questionnaires
- Surverys
- Cookies
(cookies are most effective to track people's online activities and interests,)

### Data collection considerations
- How the data will be collected
Decide if you will collect the data using your own resources or receive (and possibly purchase it) from another party. Data that you collect yourself is called first-party data.
- Choose data sources
If you don’t collect the data using your own resources, you might get data from second-party or third-party data providers.
- Decide what data to use
Datasets could show a lot of interesting information. But be sure to choose the data that actually helps solve your problem question.
- How much data to collect/use
If you are collecting your own data, make reasonable decisions about sample size. Random sample or more strategic to focus on certain criteria.
- Select the right data type
For example, if you are analyzing trends over time, make sure you use time series data. In other words, data that includes dates.
- Determine the time frame
If you are collecting your own data, decide how long you will need to collect the data, especially if you are tracking trends over a long period of time. If you need an immediate answer, you might not have time to collect new data. In this case, you would need to use historical data that already exists.


**First-party data**: Data collected by an individual or group using their own resources.

**Second-party data**: Data collected by a group directly from its audience and then sold.

**Third-party data**: Data collected from outside sources who did not collected it directly.
(It might not be as reliable, but that doesn't mean it can't be useful. You'll just want to make sure you check it for accuracy, bias, and credibility.)

**Population**: All possible data values in a certain dataset.
(In data analyze)

**Sample**: A part of a population that is representative of the population.
(In instances when collecting data from an entire population is challenging, data analysts may choose to use a sample.)

![](attachments/5TyGAFZrRi28hgBWa-Ytcg_a723a1a4d78b42e1bcb6ddd2178adc42_Screen-Shot-2020-12-14-at-2.19.22-PM.png)



### Differentiate between data structures

#### All data structures
**Qualitative and Quatitative**
Qualitative data is usually listed as a name, category, or description.

Quantitative data can be measured or counted and then expressed as a number, with a certain quantity, amount, or range.
Quantitative data can be broken down into discrete or continuous data.

**Discrete data**: Data that is counted and has a limited number of values.

**Continuous data**: Data that is measured and can have almost any numeric value.
(its value can be shown as a decimal with several places)

**Nominal data**: A type of qualitative data that is categorized without a set order.

**Ordinal data**: A type of qulitative data with a set order or scale.
(Rank from 1 to 5)

**Internal data**: Data that lives within a company's own systems.

**External data**: Data that lives and is generated outside of an organization.
(External data is particularly valuable when an analysis depends on as many sources as possible.)

**Structured data**: Data organized in a certain format such as rows and columns.
(Table, Spreadsheets, Relational databases.
Structured data that is grouped together to form relations enables analysts to more easily store, search, and analyze the data.)

**Unstructured data**: Data that is not organized in any easily identifiable manner.
(Audio files, video files, email, photos, social media.
Unstructured data is not organized, although it may have an internal structure.)

#### Data formats in practice
##### Primary vs. Secondary
| Data Format Classification | Definition                                        | Examples                                                                                                                                                              |
|:-------------------------- |:------------------------------------------------- |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Primary data               | Collected by a researcher from first-hand sources | - Data from an interview you conducted <br>- Data from a survey returned from 20 participants <br>- Data from questionnaires you got back from a group of workers             |
| Secondary data             | Gathered by other people or from other research   | - Data you bought from a local data analytics firm’s customer profiles <br>- Demographic data collected by a university  <br>- Census data gathered by the federal government |

##### Internal vs. External
| Data Format Classification | Definition                                           | Examples                                                                                                                                                  |
|:-------------------------- |:---------------------------------------------------- |:--------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Internal data              | Data that lives inside a company’s own systems       | - Wages of employees across different business units tracked by HR <br>- Sales data by store location  <br>- Product inventory levels across distribution centers |
| External data              | Data that lives outside of a company or organization | - National average wages for the various positions throughout your organization <br>- Credit reports for customers of an auto dealership                      |


##### Continuous vs. Discrete
| Data Format Classification | Definition                                                  | Examples                                                                                                                                     |
|:-------------------------- |:----------------------------------------------------------- |:-------------------------------------------------------------------------------------------------------------------------------------------- |
| Continuous data            | Data that is measured and can have almost any numeric value | - Height of kids in third grade classes (52.5 inches, 65.7 inches) <br>- Runtime markers in a video <br>- Temperature                                |
| Discrete data              | Data that is counted and has a limited number of values     | - Number of people who visit a hospital on a daily basis (10, 20, 200) <br>- Room’s maximum capacity allowed <br>- Tickets sold in the current month |




##### Qualitative vs. Quantitative
| Data Format Classification | Definition                                                           | Examples                                                                                                                        |
|:-------------------------- |:-------------------------------------------------------------------- |:------------------------------------------------------------------------------------------------------------------------------- |
| Qualitative                | Subjective and explanatory measures of qualities and characteristics | - Exercise activity most enjoyed <br>- Favorite brands of most loyal customers <br>- Fashion preferences of young adults        |
| Quantitative               | Specific and objective measures of numerical facts                   | - Percentage of board certified doctors who are women <br>- Population of elephants in Africa <br>- Distance from Earth to Mars |


##### Nominal vs. Ordinal
| Data Format Classification | Definition                                                         | Examples                                                                                                                                                                          |
|:-------------------------- |:------------------------------------------------------------------ |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Nominal                    | A type of qualitative data that isn’t categorized with a set order | - First time customer, returning customer, regular customer <br>- New job applicant, existing applicant, internal applicant <br>- New listing, reduced price listing, foreclosure |
| Ordinal                    | A type of qualitative data with a set order or scale               | - Movie ratings (number of stars: 1 star, 2 stars, 3 stars) <br>- Ranked-choice voting selections (1st, 2nd, 3rd) <br>- Income level (low income, middle income, high income)     |


##### Structured vs. Unstructured
| Data Format Classification | Definition                                                  | Examples                                                  |
|:-------------------------- |:----------------------------------------------------------- |:--------------------------------------------------------- |
| Structured data            | Data organized in a certain format, like rows and columns   | - Expense reports <br>- Tax returns <br>- Store inventory |
| Unstructured data          | Data that isn’t organized in any easily identifiable manner | - Social media posts <br>- Emails <br>- Videos            | 



#### The structure of data
Data is everywhere and it can be stored in lots of ways. Two general categories of data are: 
-   **Structured data:** Organized in a certain format, like rows and columns.
-   **Unstructured data:** Not organized in any easy to identify way.

![](attachments/bG2cUYmWTg6tnFGJli4OAQ_29c5e99b864645df8cb1f3c5900b3c3e_DA_C3M1L3R2.png)

##### Structured data
**Structured data** is organized in a certain format, like rows and columns.
Structured data is typically stored in spreadsheets and/or databases.  If the data is exported, the structure goes along with the data.

##### Unstructured data
**Unstructured data** can’t be organized in any easily identifiable manner.
There is much more unstructured than structured data in the world. Video and audio files, text files, social media content, satellite imagery, presentations, PDF files, open-ended survey responses, and websites all qualify as types of unstructured data.




#### Data modeling
**Data modeling** is the process of creating diagrams that visually represent how data is organized and structured.  These visual representations are called **data models**.

Structured data works nicely with a data model.
**Data model**: A model that is used for organizing data elements and how they relate to one another.

**Data elements**: Pieces of information, such as people's names, account numbers, and address.

Data models help to keep data consistent and provide a map of how data is organized.
Data modeling can help you explore the high-level details of your data and how it is related across the organization’s information systems.


##### Levels of data modeling
![](attachments/CFnznQrXRhaZ850K1_YW7w_32345423f15a4115961a22948e080610_Screen-Shot-2021-01-08-at-2.28.52-PM.png)
1.  **Conceptual data modeling** gives you a high-level view of your data structure, such as how you want data to interact across an organization.
2.  **Logical data modeling** focuses on the technical details of the model such as relationships, attributes, and entities.
3.  **Physical data modeling** should actually depict how the database was built. By this stage, you are laying out how each database will be put in place and how the databases, applications, and features will interact in specific detail.


##### Data modeling techniques
Read more about ERD, UML, and data dictionaries in this [data modeling techniques article](https://dataedo.com/blog/basic-data-modeling-techniques "data modeling techniques article").
###### ERDs
**Entity Relationship Diagrams**, also referred to as **ER diagrams** or **ERDs**.
1.  **Entities** representing objects (or tables in relational database),
2.  **Attributes** of entities including **data type**,
3.  **Relationships** between entities/objects (or foreign keys in a database).

![](attachments/dataedo_sample_erd.png)
ERDs work well if you want to design a relational (classic) database, Excel databases or CSV files. Basically, any kind of tabular data.

###### UMLs
UML (Unified Modeling Language) comprises of several different diagrams representing different aspect of the system, and one of them being a **Class Diagram** that can be used for data modeling.

In class diagrams architects define:
1.  **Classes** (equivalent of entity in relational world),
2.  **Attributes** of a class (same as in an ERD) including **data type**,
3.  **Methods** associated to specific class, representing its behavior (in relational world those would be stored procedures),
4.  **Relationships** grouped into two categories:
    -   **Relationships between objects** (instances of Classes) differentiated into Dependency, Association, Aggregation and Composition (equivalent to relationships in an ERD),
    -   **Relationships between classes** of two kinds Generalization/Inheritance and Realization/Implementation (this has no equivalent in relational world).

![](attachments/uml_class_diagram.png)

###### Data Dictionary
Data dictionaries are a tabular definition/representation of data assets.
![](attachments/sample_data_dictionary.png)



### Explore data types, fields, and values
**Data type**: A specific kind of data attribute that tells what kind of value the data is.

**Data type in spreadsheets**:
- Number
- Text or string
A sequence of characters and punctuation that contains textual information.
- Boolean
A data type with only two possible values, such as TRUE or FALSE.

**Data table components**
Rows--> Records,  Column --> Fields

#### Wide and long data
Wide data subjects can have data in multiple columns. Long data subjects can have multiple rows that hold the values of subject attributes.

In wide data, each column contains a unique data variable. In long data, separate columns contain the values and the context for the values, respectively.

**Wide data**: Data in which every data subject has a single row with multiple columns to hold the values of various attributes of the subject.

**Long data**: Data in which each row is one time point per subject, so each subject will have data in multiple rows.
(Long data is a great format for storing and organizing data when there's multiple variables for each subject at each time point that we want to observe.)


##### Data transformation
Data transformation enables data analysts to change the structure of data.

Data transformation usually involves these tasks:
-   Adding, copying, or replicating data 
-   Deleting fields or records 
-   Standardizing the names of variables
-   Renaming, moving, or combining columns in a database
-   Joining one set of data with another
-   Saving a file in a different format. For example, saving a spreadsheet as a comma separated values (CSV) file.

**Goals** for data transformation:
-   Data **organization**: better organized data is easier to use
-   Data **compatibility**: different applications or systems can then use the same data
-   Data **migration**: data with matching formats can be moved from one system to another
-   Data **merging**: data with the same organization can be merged together
-   Data **enhancement**: data can be displayed with more detailed fields 
-   Data **comparison**: apples-to-apples comparisons of the data can then be made


| **Wide data is preferred when**                                    | **Long data is preferred when**                                                                            |
|:------------------------------------------------------------------ |:---------------------------------------------------------------------------------------------------------- |
| Creating tables and charts with a few variables about each subject | Storing a lot of variables about each subject. For example, 60 years worth of interest rates for each bank |
| Comparing straightforward line graphs                              | Performing advanced statistical analysis or graphing                                                       |
(typically, transform long data to wide data more often than they transform wide data to long data because wide data is easier to read and understand)

---

##  Bias, credibility, privacy, ethics, and access
### Unbiased and objective data
**Bias**: A preference in favor of or against a person, group of people, or thing.

**Data bias**: A type of error that systematically skews results in a certain direction.
The way you collect can also create bias.

**Unbiased sampling**: A sample that's representative of the population being measured.
Using random sampling during data collection helps ensure unbiased sampling.
Using visualization to identify sampling bias.
But bias can help narrow your focus, like only taking the last year's income data.

**Four type of data bias:**
- **Sampling bias**
A sample that isn't representative of the population as a whole.
i.e., doing research on commuters, and only survey people walking by in the sidewalk, you'll miss out on input from people who ride bicycles, drive, or take the subway.
- **Observer bias**
(experimenter bias/research bias) The tendency for different people to observe things differently.
- **Interpretation bias**
The tendency to always interpret ambiguous situations in a positive or negative way.
Interpretation bias, can lead to two people seeing or hearing the exact same thing, and interpreting it in a variety of different ways, because they have different backgrounds, and experiences.
- **Confirmation bias**
The tendency to search for or interpret information in a way that confirms pre-existing beliefs.
People see what they want to see.

### Data credibility
The more high quality data we have, the more confidence we can have in our decisions.

#### Identifying good data: ROCCC
- **R**eliable
With reliable data you can trust that you're getting accurate, complete and unbiased information
- **O**riginal
be sure to validate it with the original source
- **C**omprehensive
The best data sources contain all critical information needed to answer the question or find the solution.
i.e. research every aspect of the organization instead of one great online review
- **C**urrent
The best data sources are current and relevant to the task at hand.
(i.e. you can always trust Data.gov, which is home to the U.S. government's open data.)
In general, the usefulness of data decreases as time passes. The best data sources are current and relevant.
- **C**ited
Citing makes the information you're providing more credible.
"Who created the data set?", "Is it part of a credible organization?", "When was the data last refreshed?" are questions that can help you determine if a data source is cited.

Vetted public datasets, academic papers, financial data, and governmental agency data are usually good data sources.
If you need a great reliable data source, check out the U.S. Census Bureau, which regularly updates their information.

#### Bad data
Bad data are not ROCCC.

**Not reliable:**
Bad data can't be trusted because it's inaccurate, incomplete, or biased.
Or it could be data visualizations and graphs that are just misleading.
**Not original:**
If you can't locate the original data source and you're just relying on second or third party information, that can signal you may need to be extra careful in understanding your data.
**Not comprehensive:**
Bad data sources are missing important information needed to answer the question or find the solution or contain human error.
**Not current:**
Bad data sources are out of date and irrelevant.
**Not cited:**
If your source hasn't been cited or vetted, it's a no-go.

A bad data source is not cited or vetted, is out of date or irrelevant, or solely relies on third-party information.
Every good solution is found by avoiding bad data.



### Data Ethics and privacy
**Ethics**: Well-founded standards of right and wrong that prescribe what humans ought to do, usually in terms of rights, obligations, benefits to society, fairness or specific virtues.

**Data ethics**: Well-founded standards of right and wrong that dictate how data is collected, shared, and used.

The importance of data privacy has been recognized by governments worldwide and they started creating data protection legislation to help protect people and their data. like:
GDPR(Genenral Data Protection Regulation of the European Union)

#### Aspects of data ethics
- **Ownership**
Individuals who own the raw data they provide, and they have primary control over its usage, how it's processed, and how it's shared.
- **Transaction transparency**
All data processing activities and algorithms should be completely explainable and understood by the individual who provides their data.
To avoid biased outcomes, it's helpful to provide transparent analysis especially to the people who share their data.
- **Consent**
Individual's right to know explicit details about how and why their data will be used before agreeing to provide it.
They should know answers to questions like why is the data being collected? How will it be used? How long will it be stored?
But with so much activity happening online these days, consent usually just looks like a terms and conditions checkbox with links to more details.
- **Currency**
Individuals should be aware of financial transactions resulting from the use of their personal data and the scale of these transactions.
- **Privacy**
See details below
- **Openness**
Free access, usage, and sharing of data.
See details below

**Steps for ethic data use:**
Self-reflect and understand what it is that you are doing and the impact that it has.
Think about not just those that sit laterally next to you, but also think about those that are represented in this dataset and those that aren't represented in this dataset.
And then also, think about the various harms and risks associated with the work that you're doing.
Also understanding what's the concept process like

#### Data privacy
Privacy is personal.

**Privacy**: Preserving a data subject's information and activity any time a data transaction occurs.
Sometimes called information privacy or data protection.

It can include:
- Protection from unauthorized access to our private data
- Freedom from inappropriate use of our data
- The right to inspect, update, or correct our data
- Ability to give consent to use our data
- Legal right to access our data.

For companies, it means putting privacy measures in place to protect the individuals' data.


#### Data anonymization
Data anonymization is the process of protecting people's private or sensitive data by eliminating PII information.

**Personally identifiable information** (or **PII**): Information that can be used by itself or with other data to track down a person's identity.

Typically, data anonymization involves blanking, hashing, or masking personal information, often by using fixed-length codes to represent data columns, or hiding data with altered values.

**What types of data should be anonymized?**
Healthcare and financial data are two of the most sensitive types of data. Data in these two industries usually goes through **de-identification**, which is **a process used to wipe data clean of all personally identifying information**.

Here is a list of data that is often anonymized:
-   Telephone numbers
-   Names
-   License plates and license numbers
-   Social security numbers
-   IP addresses
-   Medical records
-   Email addresses
-   Photographs
-   Account numbers

Data anonymization is one of the ways we can keep data private and secure.


#### Open data
In data analytics, **open data** is part of **data ethics,** which has to do with using data ethically.
**Openness(or open data)** :Free access, usage, and sharing of data.
Means we can access, use, and share that data if it meets these high standards.



Three standards:
- **Availability and access**
Open data must be available as a whole, preferably by downloading over the internet in a convenient and modifiable form.
Data.gov is a great example of this.
- **Re-use and redistribution**
Open data must be provided under terms that allow reuse and redistribution, including the ability to use it with other data sets.
- **Universal participation**
**Everyone** must be able to use, re-use and redistribute the data.
There shouldn't be any discrimination against fields, persons, or groups. No one can place restrictions on the data, like making it only available for use in a specific industry.

Data can only be considered open when it meets all three of these standards.

Benefit of open data: Credible databases can be used more widely.
Basically, this means that all of that good data can be leveraged, shared, and combined with other data.

Interoperability is key to open data's success.
Companies have to cooperate and work together to make data useful.

##### Sources of open data
Luckily for data analysts, there are lots of trustworthy sites and resources available for open data. It is important to remember that even reputable data needs to be constantly evaluated, but these websites are a useful starting point:
1.  [**U.S. government data site**](https://www.data.gov/ "U.S. government data site"): Data.gov is one of the most comprehensive data sources in the US. This resource gives users the data and tools that they need to do research, and even helps them develop web and mobile applications and design data visualizations. 
2.  [**U.S. Census Bureau**](https://www.census.gov/data.html "U.S. Census Bureau"): This open data source offers demographic information from federal, state, and local governments, and commercial entities in the U.S. too. 
3.  [**Open Data Network**](https://www.opendatanetwork.com/ "Open Data Network"): This data source has a really powerful search engine and advanced filters. Here, you can find data on topics like finance, public safety, infrastructure, and housing and development.
4.  [**Google Cloud Public Datasets**](https://cloud.google.com/public-datasets "Google Cloud Public Datasets"): There are a selection of public datasets available through the Google Cloud Public Dataset Program that you can find already loaded into BigQuery.  
5.  [**Dataset Search**](https://datasetsearch.research.google.com/ "Dataset Search")**:** The Dataset Search is a search engine designed specifically for data sets; you can use this to search for specific data sets.
6.  [**Kaggle**](https://www.kaggle.com/datasets?utm_medium=paid&utm_source=google.com+search&utm_campaign=datasets&gclid=CjwKCAiAt9z-BRBCEiwA_bWv-L6PpACh6RzmrJjQjmNGCCE7kky1FCtc6Jf1qld-4NwDMYL0WsUyxBoCdwAQAvD_BwE "This link takes you to the Kaggle Datasets page where you can explore, analyze, and share data.") has an Open Data search function that can help you find datasets to practice with.
7.  [**BigQuery**](https://cloud.google.com/bigquery/public-data "This link takes you to the BigQuery public datasets documentation.") hosts 150+ public datasets you can access and use.

##### Difference Between Open Data and Public Data
*What is open data?*
Generally speaking, “ [open data](https://portal0.cf.opendata.inter.sandbox-toronto.ca/) “ is the information that has been published on government-sanctioned portals. In the best case, this data is structured, machine-readable, open-licensed, and well maintained.
*What is public data?*
[Public data](https://www.google.com/publicdata/directory) is the data that exists everywhere else. This is information that’s freely available (but not really accessible) on the web. It is frequently unstructured and unruly, and its usage requirements are often vague.
**_“Only 10% of government data is published as open data”_**

##### Examples of public datasets
There are a lot of great public datasets that you can use to practice your analysis skills and explore everything from climate change to health data:

###### Public health datasets

1.  [Global Health Observatory data](https://www.who.int/data/collections "This link takes you to the World Health Organization's data collections site."): You can search for datasets from this page or explore featured data collections from the World Health Organization.  
2.  [The Cancer Imaging Archive (TCIA) dataset](https://cloud.google.com/healthcare/docs/resources/public-datasets/tcia "This link takes you to the Google Cloud Cancer Imaging Archive (TCIA) overview page."): Just like the earlier dataset, this data is hosted by the Google Cloud Public Datasets and can be uploaded to BigQuery.
3.  [1000 Genomes](https://cloud.google.com/life-sciences/docs/resources/public-datasets/1000-genomes "This link takes you to the Google Cloud Life Sciences 1000 Genomes project page."): This is another dataset from the Google Cloud Public resources that can be uploaded to BigQuery. 

###### Public climate datasets
1.  [National Climatic Data Center](https://www.ncdc.noaa.gov/data-access/quick-links "This link takes you to the NOAA data access page with quick access to climate and weather datasests."): The NCDC Quick Links page has a selection of datasets you can explore. 
2.  [NOAA Public Dataset Gallery](https://www.climate.gov/maps-data/datasets "This link takes you to a NOAA dataset gallery from climate.gov."): The NOAA Public Dataset Gallery contains a searchable collection of public datasets.

###### Public social-political datasets
1.  [UNICEF State of the World’s Children](https://data.unicef.org/resources/dataset/sowc-2019-statistical-tables/ "This link takes you to statistical tables for children's health published by Unicef."): This dataset from UNICEF includes a collection of tables that can be downloaded.
2.  [CPS Labor Force Statistics](https://www.bls.gov/cps/tables.htm "This link takes you to the U.S. Bureau of Labor Statistics page."): This page contains links to several available datasets that you can explore.
3.  [The Stanford Open Policing Project](https://openpolicing.stanford.edu/ "This link takes you to the Stanford open policing project page and datasets."): This dataset can be downloaded as a .CSV file for your own use.


---

### BigQuery
[BigQuery](https://console.cloud.google.com/bigquery) is a fully-managed petabyte-scale [enterprise data warehouse](https://cloud.google.com/solutions/bigquery-data-warehouse) that runs on the Google Cloud.  It can solve problems by enabling super-fast SQL queries using the processing power of Google's infrastructure.

You can access BigQuery through the Cloud Console, the [command-line tool](https://cloud.google.com/bigquery/docs/cli_tool), or by making calls to the [BigQuery REST API](https://cloud.google.com/bigquery/docs/reference/v2) using a variety of [client libraries](https://cloud.google.com/bigquery/docs/reference/libraries) such as Java, .NET, or Python.

BigQuery [quickstart guide](https://cloud.google.com/bigquery/docs/quickstarts/quickstart-web-ui) to learn how to start performing data analysis on Google Cloud.

#### Query a public dataset
1.  In the middle pane, click **ADD DATA** \> **Explore public datasets**.
2. In the searchbox, type "USA Names" then enter.
3. Click on the **USA Names** tile you see in the search results.
4. Click VIEW DATASET.

#### Query the USA Name dataset
To compose a new query, click on **COMPOSE NEW QUERY**. Enter the following query into the **Query editor** test area:
```SQL
SELECT
  name,
  gender,
  SUM(number) AS total
FROM
  `bigquery-public-data.usa_names.usa_1910_2013`
GROUP BY
  name,
  gender
ORDER BY
  total DESC
LIMIT
```

In the upper right of the window, view the query validator. BigQuery displays a green check mark icon if the query is valid. When the query is valid, the validator also shows the amount of data the query processes when you run it.

#### Create a dataset
1. Back in the console, in the middle pane, in the **Explorer** section, click your Project ID (it will start with qwiklabs), click Actions icon (three vertical dots on the right), then open.
2. On the right side in the project section, click **CREATE DATASET**.
3. On the **Create dataset** page:
-   For **Dataset ID**, enter `babynames`.
-   For **Data location**, choose **United States (US)**.
-   For **Default table expiration**, leave the default value.
4. Click **Create dataset** at the bottom of the panel.

**Load the data into a new table**
- Click on the **babynames** dataset (found in the middle pane in the **Explorer** section) and then click **Create table** in the right console.
-  For **Source**, choose **Upload** from the dropdown menu.
-  For **Select file**, click **Browse**, navigate to the `yob2014.txt` file and click **Open**.
-  For **File format**, choose **CSV** from the dropdown menu.
-  For **Table name**, enter `names_2014`.
-  In the **Schema** section, click the **Edit as text** toggle and paste the following schema definition in the text box.
`name:string,gender:string,count:integer`
- Click **Create table**

**Query the table**
```SQL
SELECT
  name,
  count
FROM
  `babynames.names_2014`
WHERE
  gender = 'M'
ORDER BY
  count DESC
LIMIT
  5
```

For more information about BigQuery, see [BigQuery Documentation](https://cloud.google.com/bigquery/docs/) and [BigQuery Public Datasets](https://cloud.google.com/bigquery/public-data/).


#### Another example
**ADD DATA** --> **Explore public datasets** --> "“Cloud-to-Ground Lightning Strikes"

In the bottom-right window, review the description of the dataset, as well as some basic information.

|            |                                      |
| ---------- | ------------------------------------ |
| Dataset ID | bigquery-public-data:noaa\_lightning |

In this case, the database connection is “bigquery-public-data” and the Dataset ID is “noaa\_lightning”.

**Total number of strikes:**
```SQL
SELECT SUM(number_of_strikes) FROM `bigquery-public-data.noaa_lightning.lightning_2019`
```

**Grouped by date and sorted by sum:**
```SQL
SELECT date,SUM(number_of_strikes) as total
FROM `bigquery-public-data.noaa_lightning.lightning_2019`
GROUP BY date
ORDER BY total DESC
LIMIT 1000
```

#### Getting started resources for other databases

If you are connecting to and performing SQL queries on other database platforms, here are similar getting started resources:

-   [Getting started with MySQL](https://dev.mysql.com/doc/mysql-getting-started/en/ "This link takes you to Getting Started with MySQL documentation."): This is a guide to setting up and using MySQL.
-   [Getting started with Microsoft SQL Server](https://docs.microsoft.com/en-us/sql/relational-databases/tutorial-getting-started-with-the-database-engine?view=sql-server-ver15 "This link takes you to the Getting Started with the Database Engine tutorial from Microsoft."): This is a tutorial to get started using SQL Server.
-   [Getting started with PostgreSQL](https://www.postgresql.org/docs/10/tutorial-start.html "This link takes you to the Getting Started tutorial from postgresql.org."): This is a tutorial to get started using PostgreSQL.
-   [Getting started with SQLite](https://www.sqlite.org/quickstart.html "Getting started with SQLite"): This is a quick start guide for using SQLite.


#### SQL
A Database is essentially a _collection of one or more tables_.
SQL allows you to get information from "structured datasets".
An example of _unstructured data_ would be an image file. Unstructured data is inoperable with SQL and cannot be stored in BigQuery datasets or tables (at least natively.) To work with image data (for instance), you would use a service like [Cloud Vision](https://google.qwiklabs.com/catalog_lab/1112), perhaps through its [API](https://google.qwiklabs.com/catalog_lab/1241) directly.

##### Capitalization
With SQL, capitalization usually doesn’t matter. But it can maek you write SQL queries like a pro.

|                 | cap           | e.g.                      |
| --------------- | ------------- | ------------------------- |
| clause starters | ALL CAPS      | SELECT, FROM, WHERE, etc. |
| Functions       | ALL CAPS      | SUM()                     |
| Column names    | all lowercase | column_name               |
| Table names     | CamelCase     | TableName                 |

**when inside quotes:**
Most, like MySQL, PostgreSQL, and SQL Server, aren’t case sensitive.
e.g. searched for country_code = ‘us’ --> return 'us', 'uS', 'Us', and 'US'.
Some **SQL dialects** are case sensitive like BigQuery
e.g. searched for country_code = ‘us’ --> return 'us'

##### Single or double quotes
Single or double quotes: `''` or `" "`
When referring to strings, it doesn't matter but recommend to use single quotes.
(e.g., `country_code = 'US'`)
Except your string has quotes inside it.  (e.g. `Food = "Shepherd’s pie"`)

##### Comments
It is best to use `--` and be consistent with it. (Some SQL also recognize `#`)
The database query engine will ignore everything in the same line after `--`. It will continue to process the query starting on the next line.

**Multi-line comments**
Use `/*` to start the comment and `*/` to close the comment more than two lines.
The `/*` and ` */` method for multi-line comments usually looks cleaner and helps separate the comments from the query.

##### Snake_case names for columns
When you create a new column, the new column will receive a generic default name. (SQL defaults to f0, f1, f2, f3) So it is always good to give your columns useful names, especially when using functions.

When naming your new column, names should never have spaces in them.
The best practice is to use snake_case. (e.g. `total_tickets`)

##### CamelCas names for tables
Use CamelCase capitalization when naming your table.
CamelCase(or PascalCase) capitalization means that you capitalize the start of each word, like a two-humped (Bactrian) camel. (e.g. `TicketsByOccasion`)
(P.S. The capitalization of the first word in CamelCase is optional; e.g. camelCase.  Also called reserving camelCase)

Using snake_case to write table names is also acceptable.

When writing a query, the name of the dataset can either be inside two backticks, or not, and the query will still run properly.

##### Indentation
Indentation doesn’t matter in SQL, but, as a general rule, you want to keep the length of each line in a query <= 100 characters. It makes your queries easy to read.
![](attachments/VCypOGHsR9msqThh7NfZVw_6aa3b0dd87a44412bd8cbf3602f99f0b_Screen-Shot-2020-12-18-at-16.56.02.png)





---

## Kaggle

### notebooks
On the Code home page, you’ll notice links to notebooks created by other Kagglers.

For example, type **Beginner** in the search bar to show notebooks tagged as beginner-friendly. Or, click on the **Filter** icon, the triangle shape on the right side of the search bar. You can filter results by tags, programming language, output, and other options. Filter to **Datasets** to show notebooks that use one of the tens of thousands of public datasets available on Kaggle.

Suggested notebooks:
-   [gganimate](https://www.kaggle.com/mrisdal/gganimate) [](https://www.kaggle.com/mrisdal/space-is-the-place) by Meg Risdal
-   [Getting staRted in R](https://www.kaggle.com/rtatman/getting-started-in-r-first-steps) by Rachael Tatman
-   [Writing Hamilton Lyrics with TensorFlow/R](https://www.kaggle.com/anasofiauzsoy/writing-hamilton-lyrics-with-tensorflow-r) by Ana Sofia Uzsoy
-   [Dive into dplyr (tutorial #1)](https://www.kaggle.com/jessemostipak/dive-into-dplyr-tutorial-1) by Jesse Mostipak

#### Edit a notebook
1. Click on the link to open up the notebook. It contains the dataset you’ll work with later on.

2. Click on the **Copy and Edit** button at the top-right to make a copy of the notebook in your account. Now, the notebook appears in **Edit** mode. Edit mode lets you make changes to the notebook if you want.
This notebook is private. If you want to share your work, you can choose to make it public. When you copy and edit another Kaggler’s work, always make meaningful changes to the notebook before publishing it. That way, you’re not misrepresenting someone else’s work as your own.

#### Working with datasets in notebooks
In this notebook, you’ll find the data in a box labeled **Data** at the top-right of your screen. In the box, there’s an input folder with the title: **palmer-archipelago-antarctica-penguin-data**. Follow these instructions to explore the datasets and learn more about the data within them:

1. Click on this title. Two .csv files appear: **penguins\_lter.csv** and **penguins\_size.csv**. Click on one of them. At the bottom of the notebook, you’ll now find an interactive data table with all the information from the dataset.
2. Click on the other .csv file. This opens a second tab with the second dataset. 
3. Take a moment to check out each dataset. 
4. Sort the data in each column by clicking on the **horizontal bars** to the right of each column name.
5. Click on the button that says **10 of 17 columns** to change the columns that are visible in the table.

#### Creating a notebook
> Note: Kaggle supports both R and Python. Changing the programming language by clicking the option under **Settings** on the right side of the notebook.

- Click on the notebook title at the top of the interface to edit it directly.
- Click on the **+** symbol to add code cells, which are represented by light grey blocks.
- Click on the Single Play arrow `▷` (**Shift** + **Enter** (Windows) or **Shift** + **Return** (Mac)) to "run" whichever code cell your cursor is in, or click on the Double Play arrows `▷▷` (with the text Run All next to them) to run your entire notebook.
- Use your mouse to hover over the white space between code cells you’ll see two buttons pop up. The `+code` and `+Markdown` buttons will create a new code cell and a new Markdown cell respectively.
- When you want to start a new line of text in Markdown, you need to add two blank spaces to the end of the line.

### Datasets
Click on the **Data** icon in the **Navigation** bar on the left. This takes you to the **Datasets** home page. From here, you can create a new dataset or search for datasets created by other Kagglers.

Check out a specific dataset. like **Animal Crossing New Horizons Catalog.**

##### Landing page
**Header:** The header at the top of the page contains the following information about the dataset:
-   Its title 
-   A brief description of its contents
-   The name of its creator 
-   When it was last updated
-   Its current version 

**Badge:**  In the top-right corner of the header, you’ll find three more items: 
-   A badge in the shape of a circle 
-   An icon in the shape of a caret symbol ( ^ )
-   A number
**Upvotes:** Clicking on the caret lets you “upvote” the dataset. The number shows the number of times this dataset has been upvoted by the Kaggle community.

##### Tabs
**Tabs:** Beneath the header is a bar with six tabs: Data, Tasks, Notebooks, Discussion, Activity, and Metadata.

Move down the page. You’ll find a box that contains three terms: Usability, License, and Tags:
**Usability** shows how complete the dataset _webpage_ is (and not the dataset itself). Kaggle encourages the community to add information to the dataset webpage to make the dataset itself easier to understand. For example, a brief description or a column header. Hover your cursor over the **Usability score** to discover what the dataset page contains. 

**Licenses** govern how a dataset can be used. Click on the **license name** to learn more about that specific license. 

**Tags** refer to different themes or categories. For example, if you click on the **video games** tag, you’ll go to a page that shows you everything related to video games on Kaggle. This includes competitions, notebooks, and datasets!

##### data explorer
Try clicking on **umbrellas.csv** to check it out. In the Detail tab:
The description at the top of the Detail tab shows that the umbrellas.csv file contains data on all the umbrellas in the video game.

Let’s check out the columns. Each column header has three items: 
-   A small icon on the left that shows the data type
-   The name of the column
-   An icon with three bars that lets you sort the data if you click on it
Below each column header is a box that contains a summary of the data. This lets you quickly get an idea of what’s in the dataset.

Create a Kaggle notebook: To use code to create a Kaggle notebook, you click on the **New Notebook** button in the dataset header.
To download a copy of the dataset to your computer, click on the **Download** button in the dataset header at the top of the page. Or you can only download one sheet.

##### Privacy, Collaboration and Version control
**Privacy**
You have the option to upload your own datasets and keep them private. You also have the option to add collaborators to your dataset, whom you can add as viewers or editors. Viewers are able to see your private dataset and editors are able to make changes to your private dataset.
You can share the link to your private dataset so anyone with the link is able to view it. If you don’t want this feature [you can disable it in the Settings tab of your dataset.](https://www.kaggle.com/product-feedback/120243)

It’s important to note that if you have a private dataset on Kaggle and you choose to make it public, **you will not be able to make the dataset private again**. The only option you would have is to delete the dataset from Kaggle completely.

**Collaboration**
Any notebooks that you create on Kaggle are currently private by default. Like in datasets, you can add collaborators as viewers or editors. You can also make your notebook public, which will share it with the entire Kaggle community. 

If you add collaborators to your Kaggle notebook, they can make changes to your notebook. You’ll want to make sure you’re communicating and coordinating with your collaborators because the last person who saves the notebook will overwrite all of the previous work. If you’d like more fine-grained control of changes to your code, a system like GitHub provides more version control.

**Version control**
Speaking of version control, Kaggle has its own style of letting you keep records of your progress. You can read all of the details [in this post](https://www.kaggle.com/product-feedback/139884), but think back to when you’ve done some work in a Kaggle notebook and clicked on the Save Version button.
When you clicked this button then clicked Save, you did it without changing anything. But you also have the option to add a short descriptive note about what changes you’ve made.
This can be helpful when you’ve made changes to your notebook but want to go back to an earlier version. To do this, go to Edit mode and click on the number next to the Save Version text at the top of your notebook.
This will open a navigation bar on the right side of the screen and list out all of the versions of your notebook. When you click on different versions of your notebook, the left side of the screen will populate with the code and text from that version. 

From this screen you can also open the version in **Viewer** mode, pin a version as the default, or even change the version name. Pinning a version as the default can be helpful when you have a working version of your notebook available to the Kaggle community, but want to go in and make changes and updates that might not work the first time you implement them. This allows you to safely make changes “behind the scenes” while showing the Kaggle community the most recent working version of your notebook. Pretty handy, right?

### Dataset formats on Kaggle
**CSV, JSON, SQLite, and BigQuery datasets**
-   CSV: Check out this [Credit card customers](https://www.kaggle.com/sakshigoyal7/credit-card-customers "This link takes you to a Kaggle dataset with anonymized credit card data. ") dataset, which has information from 10,000 customers including age, salary, marital status, credit card limit, credit card category, etc. (CC0: Public Domain, Sakshi Goyal).
-   JSON: Check out this JSON dataset for [trending YouTube videos](https://www.kaggle.com/datasnaek/youtube-new "This link takes you to a Kaggle dataset for trending YouTube videos.") (CC0: Public Domain, Mitchell J).
-   SQLite: Check out this SQLite dataset for 24 years worth of [U.S. wildfire data](https://www.kaggle.com/rtatman/188-million-us-wildfires "This link takes you to a Kaggle dataset for U.S. wildfires.") (CC0: Public Domain, Rachael Tatman).
-   BigQuery: Check out this [Google Analytics 360](https://www.kaggle.com/bigquery/google-analytics-sample "This link takes you to a sample Google Analytics dataset in Kaggle.") sample dataset from the Google Merchandise Store (CC0 Public Domain, Google BigQuery).

Refer to the Kaggle [documentation for datasets](https://www.kaggle.com/docs/datasets "This link takes you to the Kaggle documentation for datasets.") for more information and search for and explore datasets on your own at [kaggle.com/datasets](https://www.kaggle.com/datasets "This link takes you to the main Kaggle datasets page.").

As with all other kinds of datasets, be on the lookout for ‘Null’ and duplicate data in open datasets from databases. Keep in mind that Null can mean that the value is unassigned, or it can be the value of 0. It is important to make sure you know which is intended before you use a dataset with Null data.

### Getting social on Kaggle
Like linkedIn to GitHub to Medium, you can also build an online presence on Kaggle!
With the [Kaggle Progression System](https://www.kaggle.com/progression/) you can not only track your progress and growth within the community, but also demonstrate your data skills and savvy to employers and colleagues.
Your Kaggle profile page is a collection of all of your work and accomplishments on Kaggle. Take a look at the profile page for [Heads or Tails](https://www.kaggle.com/headsortails) to learn a little more.

Know how the Kaggle community operates by reading through the [Community Guidelines](https://www.kaggle.com/community-guidelines) and checking out the [Getting Started on Kaggle YouTube playlist](https://www.youtube.com/playlist?list=PLqFaTIg4myu8gbDh6oBl7XRYNBlthpDEW).

---

## Database
A database is a collection of data stored in a computer system.

### Relational database
Databases store an organized data, making it much easier for data analysts to manage and access information.

**Relational database**: A database that contains a series of tables that can be connected to form relationships.
Basically, they allow data analysts to organize and link data based on what the data has in common.
Tables in a relational database are connected by the fields they have in common.

![](attachments/Pasted_image_20210507120827.png)

If a field exists within both tables, we can use it to connect the tables together. Certain fields may also be referred to as a primary key.

**Primary key**: An identifier that references a column in which each value is unique.
i.e. Branch ID, VIN, Part ID

**Foreign key**: A field within a table that is primary key in another table.
i.e. VIN in table "Repair parts"
A table can only have one primary key, but it can have multiple foreign keys.
![](attachments/syB_f3KVRrOgf39ylaaznA_45b04edc1ba243d8b5b6d869c61a21f1_Screenshot-2021-04-29-5.11.22-PM.png)

*A type of relational databases*
**Normalized database**: A database in which only related data is stored in each table.

**Normalizing** a database is a technique to reduce data redundancy.
The main idea behind database normalization is that a table should be about a specific topic and only includes supporting related data. (minimizes redundancies)
A key benefit of working with normalized databases is that they help lower data redundancy. In this way, data analysts are less likely to experience data integrity issues.

**Redundancy**: When the same piece of data is stored in two or more separate places.

### Schema
**Schema**: A way of describing how something is organized.

A **database schema** represents any kind of structure that is applied to the database.
(you can think about data schemas like blueprints of how the database is constructed)
Useful when you're learning about a new data set or designing a relational database.

 Two commonly used schemas are **star** schemas and **snowflake** schemas. Refer to this [Star and Snowflake Schema in Data Warehouse with Examples](https://www.guru99.com/star-snowflake-data-warehousing.html "Star and Snowflake Schema in Data Warehouse with Examples") article for more information.

**3 chief types of multidimensional schemas:**
#### Star Schema
The center of the star can have one fact table and a number of associated dimension tables:
![](attachments/022218_0758_StarandSnow1.png)
 
#### Snowflake Schema
A Snowflake Schema is an extension of a Star Schema, and it adds additional dimensions.
![](attachments/022218_0758_StarandSnow2.png)
  
#### Galaxy Schema
Contains two fact table that share dimension tables between them.
![](attachments/022218_0758_StarandSnow3.png)
The schema is viewed as a collection of stars hence the name Galaxy Schema.
   
   
### Metadata
**Meta**: something referencing back to itself or being completely self aware.
i.e. A character in a book knows she's in a book; Making a documentary about making documentaries; Analyze how to analyze data.

**Metadata**: Data about data.
Think of it as an analyze guide. Metadata tells you where the data comes from, when and how it was created, and what it's all about.
i.e. The "Get info" of a picture, like pixels, date taken and size.
i.e. In an email, the meta includes: subjects, From, To, Created at, how quick it was delivered.

Metadata helps data analysts identify the type of data, if it is clean and reliable, and how it can be combined with another dataset.

Metadata is used in database management to help data analysts interpret the contents of the data within the database.


#### 3 common types of metadata
- **Descriptive**
Metadata that describes a piece of data and can be used to identify it at a later point in time.
i.e. ISBN(International Standard Book Number) in the book spine, offer, title.
- **Structural**
Metadata that indicates how a piece of data is organized and whether it's part of one or more than one data collection.
i.e. catalog
- **Administrative**
Metadata is metadata that indicates the technical source of a digital asset.
i.e. Photos' "Get info"


#### Using metadata as an analyst
Putting data into context is probably the most valuable thing that metadata does.

Metadata creates a single source of truth by keeping things consistent and uniform.

Metadata also makes data more reliable by making sure it's accurate, precise, relevant, and timely.

**Metadata repository**: A database specifically created to store metadata.

A data analyst uses a metadata repository to access metadata quickly, maintain the metadata’s structure, and store metadata in a database.

Metadata repositories make it easier and faster to bring together multiple sources for data analysis. They do this by:
- Describe the state and location of the metadata
- Describe the structure of the tables inside
- Describe how data flows through the repository
- Keep track of who accesses the metadata and when.

For example, when working with external data:
Examine the metadata of the external data to confirm that the data is clean, accurate, relevant, and timely;
Confirming that we're allowed to use it. Reach out to the owner to make sure we can access or purchase it.

#### Metadata management
So many organizations struggle to find the right data at the right moment.
On the other hand, metadata is stored in a single, central location and it gives the company standardized information about all of its data.
**This is done in two ways**:
- First, metadata includes information about where each system is located and where the data sets are located within those systems.
- Second, the metadata describes how all of the data is connected between the various systems.

Another important aspect of metadata is something called data governance.
**Data governance**: A process to ensure the formal management of a company’s data assets.

Metadata analysts are great team players because they're passionate about making data accessible by sharing with colleagues and other stakeholders.

### Working with more data sources
Internal data is data that lives within a company's own systems. It's typically also generated from within the company;
External data is data that lives and is generated outside an organization, 
sometimes called secondary data.

Open data helps:
- make government activities more transparent
- educate citizens about voting and local issues
- improves public service by giving people ways to be a part of public planning or provide feedback to the government
- leads to innovation and economic growth by helping people and companies better understand their markets.


### Importing data from spreadsheets and databases
**Importing online data using a URL in Google Sheets**:
Input the **\=IMPORTDATA** function and paste the URL into the parentheses. Remember to put the URL in quotes!
`=IMPORTDATA("https://..../abc.csv")`

Import a certain range of data from an online source using the **IMPORTRANGE** function:
`=IMPORTRANGE("https://..../abc.csv", "World Cup!A1:D21")`

A data source: **[World Health Organization's data repository](https://www.who.int/data/gho/)**


### CSV
**CSV (Comma-seperated values)**
A CSV file saves data in a table format.

CSV files use plain text and they're delineated by characters. So each column or field is clearly distinct from another when importing. (delimiter)

A .CSV file makes it easier for data analysts to examine a small part of a large dataset, import data to a new spreadsheet, and distinguish values from one another.

### Sorting and filtering
#### Sorting
**Sorting data**: Arranging data into a meaningful order to make it easier to understand, analyze, and visualize.

p.s. The last sorted column being the primary sort criteria. i.e. first sort by cities then by states, it will show first sort by states then by cities.

**Freeze head row**: select head row --> View --> Freeze --> 1 row. This lock the head row in place.

**Multiple criteria sorting**:
- select the whole dataset (by click the left upper corner)
- Menu --> Data --> Sort range
- Highlight (check) that "Data has header row"
- Add needed sort column

#### Filtering
**Filtering**: Showing only the data that meets a specific criteria while hiding the rest.
Steps:
- Data --> Create a filter
- Choose the column we need and click the filter icon at the corner of the header
(Bottom shows the unique values, you can select or deselect to filter values)

To turn off the filter, click the activated(green) filter button in the tool bar.


---

## Example: Inspecting a Dataset
-  In Google Sheets, create a new blank sheet
-  Upload the first data in your local as "Replace spreadsheet" and all the followings as "Inset new sheet(s)" to create tabs.
(Datasets larger than 20MB might be slow to import, open, and analyze in Google Sheets.)

**Asking the right questions**
For this ice cream company, you probably want to know:
-   What is the most popular flavor?
-   What is the cost of selling as a percent of the revenue generated?
-   Does temperature affect sales?
-   What percentage of sales come from new customers?
-   Are sales on the weekends/holidays greater than other days?

**Check how many columns/rows:** A quick way to check number of columns is to select the row labeled 1. The status bar at the bottom should say **Count: x**.
Similiar way to check number of rows by selecting the column A and see **Count: x**. (If another statistic is shown, click the down arrow next to the number and select the **Count**)


## Organize and protect your data
### Organize Data
**Benefits of organizing data:**
- Makes it easier to find and use
- Helps you avoid making mistakes during your analysis
- Helps to protect your data.

**Best practices when organizing data:**
- Naming conventions
Consistent guidelines that describe the content, date, or version of a file in its name.
Basically, this means you want to use logical and descriptive names for your files to make them easier to find and use.
- Foldering
organize your files into folders; Break folders down into subfolders
- Archiving older files
Move old projects to a separate location to create an archive and cut down on clutter.
To separate current from past work and reduce clutter, data analysts create archives.
- Align your naming and storage practices with your team
- Develop metadata practices

It's a good idea to take time early on in a project to consider what the best organization methods will be for you and your team to stick to.


#### Naming conventions
**File naming conventions**: Consistent guidelines that describe the content, date, or version of a file in its name.

**File naming DO's:**
- Work out your conventions early
To avoid having to spend time redoing it later
- Align your file naming with your team
- Make sure your file names are meaningful
- Keep your file name short and sweet
- Format dates yyyymmdd:  i.e. SaleReport20201125
- Lead revision numbers with 0: SaleReport20201125v02
so that if you run into double digits of revisions, it's already built into your conventions.
- Use hyphens, underscores, or capitalized letters instead of using spaces: SaleReport_2020_11_25_v02
- Create a text file that lays out all your naming conventions on a project.
This is really helpful if someone new joins your team, or if you just need a quick reminder while you're working on something.
![](attachments/Pasted_image_20210510175705.png)



![](attachments/bTVGrSgBRcm1Rq0oAYXJgw_91587a0c9da643779f8dc57752d68e6b_Screen-Shot-2021-01-08-at-2.09.00-PM.png)
**(guidelines)Best practices for file naming conventions:**
- Work out conventions to use early on to avoid having to rename files again and again.
- Align your file naming with your team or company's existing file-naming conventions.
- Make sure that your file name is meaningful; include information like project name, date created, revision version, and anything else that will help you quickly identify (and use) your file.
- Include the date and version of the file in the name; common formats for this include YYYYMMDD for dates and v## for versions.
- Create a text file with a breakdown of the file naming conventions you've decided to use.
- Avoid spaces and special characters i.e. #, \$, @, etc. Instead, use hyphens, underscores, or capital letters. Special characters or spaces can create errors in some programs.

To align file naming and storage practices, it’s useful to develop metadata practices with your data analytics team.

#### Foldering
Data analysts use foldering to keep project-related files together and organize them into subfolders.

![](attachments/qlYjEh9SSNuWIxIfUtjbxQ_988a11443b8c41908e9178b9e74d9a23_Screen-Shot-2021-01-08-at-2.09.13-PM.png)
**(guidelines)Best practices for keeping your files organized:**
- Create folders and subfolders hierarchically so that related files are stored together.
- Separate ongoing and completed work so that your current project files are easy to find. You can archive older project files in a separate folder location or an external hard drive.
Data analysts use archiving to separate current from past work. This involves moving files from completed projects to a separate location.
- Backup your files often to avoid losing any important work.


### Securing data
Security features can be designed to keep unauthorized users from viewing certain files, or just lock your worksheets so that you don't accidentally break your formulas.

**Data security**: Protecting data from unauthorized access or corruption by adopting safety measures.
Usually the purpose of data security is to keep unauthorized users from accessing or viewing sensitive data.

**Google sheets and Excel secure features:**
- Protect spreadsheets from being edited
- Access control features (like password protection and user permissions)

Excel: encrypted by password then email
Google sheets:
"Share" menu control who can see or edit
Tabs can he hidden (but still accessible)

When using data security measures, analysts can choose between protecting an entire spreadsheet or protecting certain cells within the spreadsheet. Data security can be used to protect an entire spreadsheet, specific parts of a spreadsheet, or even just a single cell.

#### Balancing security and analytics
We want to keep our data safe and secure, but we also want to use it as soon as possible so that we can make meaningful and timely observations. This can be tricky.
**Measures that can help companies do just that:**
- **Encryption** uses a unique algorithm to alter data and make it unusable by users and applications that don’t know the algorithm.
This algorithm is saved as a "key" which can be used to reverse the encryption; so if you have the key, you can still use the data in its original form.
- **Tokenization** replaces the data elements you want to protect with randomly generated data referred to as a "token." The original data is stored in a separate location and mapped to the tokens. To access the complete original data, the user or application needs to have permission to use the tokenized data and the token mapping. This means that even if the tokenized data is hacked, the original data is still safe and secure in a separate location.
- Some others like using authentication devices for AI technology, etc.



## Online Presence
A professional online presence can:
- Help potential employers find you
- Make connections with other analysts
- Learn and share data findings
- Participate in community events

Linkedin: Make connections, Follow industry trends, Find job opportunities
Github: Share insights and resources, Read forums and wikis, Manage team projects, Hosts community events

### Build data analytics network
**Networking**: Professional relationship building.
Networking can involve meeting with someone in person or online, as well as participating in an online forum.

Search for public meetups in your area. Like [Meetup](https://www.meetup.com/)
Follow interesting companies or thought leaders on: LinkedIn, twitter, facebook, instagram

Networking is the most effective way to connect with fellow data analysts. When you’re networking, you can meet other professionals and participate in industry-related groups.

Great data podcasts to follow, like Partially Derivative and the O'Reilly Data Show.

Blogs and online communities, like O'Reilly, Kaggle, KDnuggets, GitHub and Medium, that can help you connect with peers and experts.

#### Online connections
Knowing where to look is key. Here are some suggestions on where to start online:

-   **Subscriptions** to newsletters like [Data Elixir](https://dataelixir.com/ "This link takes you to the Data Elixir newsletter home page."). Not only will this give you a treasure trove of useful information on a regular basis, but you will also learn the names of data science experts who you can follow, or possibly even connect with if you have good reason to. 
-   **Hackathons** (competitions) like those sponsored by [Kaggle](https://www.kaggle.com/ "This link takes you to the Kaggle home page."), one of the largest data science and machine learning communities in the world. Participating in a hackathon might not be for everyone. But after joining a community, you typically have access to forums where you can chat and connect with other data analysts. 
-   **Meetups**, or online meetings that are usually local to your geography. Enter a search for ‘data science meetups near me’ to see what results you get. There is usually a posted schedule for upcoming meetings so you can attend virtually to meet other data analysts. Find out more information about [meetups happening around the world](https://www.meetup.com/topics/data-analytics/ "This link takes you to the worldwide Data Analytics Meetup page."). 
-   **Platforms** like LinkedIn and Twitter. Use a search on either platform to find data science or data analysis hashtags to follow. You can also post your own questions or articles to generate responses and build connections that way. At the time of this writing, the LinkedIn `#dataanalyst` hashtag had 11,842 followers, the `#dataanalytics` hashtag had 98,412 followers, and the `#datascience` hashtag had 746,945 followers. Many of the same hashtags work on Twitter and even on Instagram.
-   **Webinars** may showcase a panel of speakers and are usually recorded for convenient access and playback. You can see who is on a webinar panel and follow them too. Plus, a lot of webinars are free. One interesting pick is the [Tableau on Tableau webinar series](https://www.tableau.com/learn/series/how-we-do-data "This link takes you to Tableau's on-demand webinars about how they use Tableau themselves."). Find out how Tableau has used Tableau in its internal departments.

#### In-person (offline) gatherings
In-person gatherings are super valuable in a digitized world. They are a great way to meet people. A lot of online relationships start from in-person gatherings and are carried on after people return home. Many organizations that sponsor annual gatherings also offer virtual meetings and resources during the rest of the year.

Here are a few suggestions to find in-person gatherings in your area:

-   **Conferences** usually present innovative ideas and topics. The cost of conferences vary, and some are pricey. But lots of conferences offer discounts to students and some conferences like [Women in Analytics](https://womeninanalytics.com/about/ "This link takes you to the Women in Analytics home page.") aim to increase the number of under-represented groups in the field. Leading research and advisory companies such as [Gartner](https://emtemp.gcom.cloud/ngw/eventassets/common/conference-calendar/gartner-conference-calendar.pdf "This link takes you to the Gartner conferences page.") also sponsor conferences for data and analytics. The [KDNuggets list of meetings and online events](https://www.kdnuggets.com/meetings/index.html "This link takes you to the KDNuggets list of meetings and online events for data analytics.") for AI, analytics, big data, data science, and machine learning is useful.

-   **Associations** or **societies** gather members to promote a field like data science. Many memberships are free. The [Digital Analytics Association](https://www.digitalanalyticsassociation.org/ "This link takes you to the Digital Analytics Association home page.") is one example. The [KDNuggets list of societies and groups](https://www.kdnuggets.com/websites/societies.html "This link takes you to a KDNuggets list of data analytics societies and groups.") for analytics, data mining, data science, and knowledge discovery is useful.

-   **User communities** and **summits** offer events for users of data analysis tools; this is a chance to learn from the best. Have you seen the [Tableau community](https://community.tableau.com/s/ "This link takes you to the Tableau online community.")?

-   **Non-profit organizations** that promote the ethical use of data science and might offer events for the professional advancement of their members. The [Data Science Association](https://www.datascienceassn.org/ "This link takes you to the Data Science Association's home page.") is one example.


### Benefits of mentorship
**Mentor**: A professional who shares their knowledge, skills, and experience to help you develop and grow.

If there's no one you can connect with in your current work environment, you can find mentors anywhere from a social media platform, networking event or mentor matching program. For instance, 
- Score.org
- MicroMentor.org
- Mentorship (an app)

Allow you to look for specific credentials that match your needs.

The more authentic and honest you are about it, the better it will go. For example, it's always a good idea to share your gratitude for their time and effort.

**Sponsor**: A professional advocate who's committed to moving a sponsee's career forward with an organization.

A mentor helps you skill up
A sponsor helps you move up.

Well, unlike mentors, you don't get to choose the sponsor. The sponsor almost always chooses you.

First, build and nurture your LinkedIn presence.
Next, look at your current social media presence and make sure it's helping you put your best foot forward.
Finally, always be open to connecting with peers and colleagues.
