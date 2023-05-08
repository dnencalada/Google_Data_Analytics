Data integrity, Sample size, Random sampling, Testing data, Clean data, Data cleaning techniques, Data cleaning in spreadsheets and databases, Verify and report your cleaning results.

In this course, you will learn to make sure your data is clean by checking it for completeness and correctness.
You will review a variety of approaches to clean data in spreadsheets and databases.
You will also learn how to verify that your data is clean and
how to create reports to communicate that information to others.
Ensuring the accuracy and reliability of data is a critical part of a data analyst’s job.

## The importance of integrity
### Data integrity and analytics objectives
A strong analysis depends on the integrity of the data.
No matter where your data comes from, always be sure to check that it is valid, complete, and clean before you begin any analysis.

**Data integrity**: The accuracy, completeness, consistency, and trustworthiness of data throughout its lifecycle.

When data integrity is low, it can cause anything from the loss of a single pixel in an image to an incorrect medical decision.

#### Threats to data integrity
Data integrity can be compromised every time it's replicated, transferred, or manipulated.

**Data replication**: The process of storing data in multiple locations.
If you're replicating data at different times in different places, there's a chance your data will be out of sync. This data lacks integrity because different people might not be using the same data for their findings, which can compromise integrity and cause inconsistencies.

**Data transfer**: The process of copying data from a storage device to memory, or from one computer to another.
If your data transfer is interrupted, you might end up with an incomplete data set.

**Data manipulation**: The process of changing data to make it more organized and easier to read.
Data manipulation is meant to make the data analysis process more efficient, but an error during the process can compromise the efficiency.

**Humman error**
**Viruses**
**Malware**
**Hacking**
**System failures**

(Duplicate data is a limitation because it will lead to faulty analysis.)
...


#### Balancing objectives with data integrity
It's important to check that the data you use aligns with the business objective.

Clean data + alignment to business objective
Alignment to business objective + additional data cleaning
Alignment to business objective + newly discovered variables + constraints
        = accurate conclusions

**Key takeaways**:
-   When there is clean data and good alignment, you can get accurate insights and make conclusions the data supports.
-   If there is good alignment but the data needs to be cleaned, clean the data before you perform your analysis. 
-   If the data only partially aligns with an objective, think about how you could modify the objective, or use data constraints to make sure that the subset of data better aligns with the business objective. (newly discovered variables)


### Dealing with insufficient data
Once you know your business objective, you'll be able to recognize whether you have enough data. And if you don't, you'll be able to deal with it before you start your analysis.
#### Types of insufficient data
- **Data from only one source**
(e.g. only use data from one booking site to find out the most popular travel plan.)
(solve: stop and go back to your stakeholders to figure out a plan)
- **Data that keeps updating**
(data still incoming and may not complete. e.g. determine trends for a brand new tourist attraction.)
(solve: wait a month to gather data; or check in with the stakeholders and ask about adjusting the objective, like limit the time span)
- **Outdated data**
(e.g. Outdated data about customer satisfaction won't include the most recent responses.)
(solve: find a new dataset to work with)
- **Geographically-limited data**
(e.g. data limited to travel in just one country whereas your company is global)

#### Ways to address insufficient data
When you are getting ready for data analysis, you might realize you don’t have the data you need or you don’t have enough of it. In some cases, you can use what is known as **proxy data** in place of the real data. Think of it like substituting oil for butter in a recipe when you don’t have butter. In other cases, there is no reasonable substitute and your only option is to collect more data.

- Identify trends with the available data
- Wait for more data if time allows
- Talk with stakeholders and adjust your objective
- Look for a new dataset


##### Proxy data examples
Sometimes the data to support a business objective isn’t readily available. This is when proxy data is useful. Take a look at the following scenarios and where proxy data comes in for each example:

| **Business scenario**                                        | **How proxy data can be used**                               |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| A new car model was just launched a few days ago and the auto dealership can’t wait until the end of the month for sales data to come in. They want sales projections now. | The analyst proxies the number of clicks to the car specifications on the dealership’s website as an estimate of potential sales at the dealership. |
| A brand new plant-based meat product was only recently stocked in grocery stores and the supplier needs to estimate the demand over the next four years. | The analyst proxies the sales data for a turkey substitute made out of tofu that has been on the market for several years. |
| The Chamber of Commerce wants to know how a tourism campaign is going to impact travel to their city, but the results from the campaign aren’t publicly available yet. | The analyst proxies the historical data for airline bookings to the city one to three months after a similar campaign was run six months earlier. |


#### Data issues and suggestions
##### Data issue 1: no data

| Possible Solutions                                           | Examples                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| Gather the data on a small scale to perform a preliminary analysis and then request additional time to complete the analysis after you have collected more data. | If you are surveying employees about what they think about a new performance and bonus plan, use a sample for a preliminary analysis. Then, ask for another 3 weeks to collect the data from all employees. |
| If there isn’t time to collect data, perform the analysis using proxy data from other datasets. *This is the most common workaround.* | If you are analyzing peak travel times for commuters but don’t have the data for a particular city, use the data from another city with a similar size and demographic. |

##### Data issue 2: too little data

| Possible Solutions                                           | Examples                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| Do the analysis using proxy data along with actual data.     | If you are analyzing trends for owners of golden retrievers, make your dataset larger by including the data from owners of labradors. |
| Adjust your analysis to align with the data you already have. | If you are missing data for 18- to 24-year-olds, do the analysis but note the following limitation in your report: *this conclusion applies to adults 25 years and older* *only*. |

##### Data issue 3: wrong data, including data with errors*

| Possible Solutions                                           | Examples                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| If you have the wrong data because requirements were misunderstood, communicate the requirements again. | If you need the data for female voters and received the data for male voters, restate your needs. |
| Identify errors in the data and, if possible, correct them at the source by looking for a pattern in the errors. | If your data is in a spreadsheet and there is a conditional statement or boolean causing calculations to be wrong, change the conditional statement instead of just fixing the calculated values. |
| If you can’t correct data errors yourself, you can ignore the wrong data and go ahead with the analysis if your sample size is still large enough and ignoring the data won’t cause systematic bias. | If your dataset was translated from a different language and some of the translations don’t make sense, ignore the data with bad translation and go ahead with the analysis of the other data. |

> _* Important note: sometimes data with errors can be a warning sign that the data isn’t reliable. Use your best judgment._


##### Decision tree
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image36.png)


### Sample and sample size
The goal of using a sample is to get enough information from a small group within a population to make predictions or conclusions about the whole population.

**Population**: All possible data values in a certain dataset.
It's too time-consuming or expensive to use the whole dataset. Using a sample for analysis is more cost-effective and takes less time.

**Sample**: A part of a population that is representative of the population.
The sample size helps ensure the degree to which you can be confident that your conclusions accurately represent the population.

Downsides of using a sample: 
Small sample of population can lead to uncertainty.
You can't really be 100 percent sure that your statistics are a complete and accurate representation of the population. (lead to sampling bias)

**Sampling bias**: A sample isn't representative of the population as a whole.
(This means some members of the population are being overrepresented or underrepresented.)
Using random sampling can help address some of those issues with sampling bias.

**Random sampling**: A way of selecting a sample from a population so that every possible type of the sample(population?) has an equal chance of being chosen.


##### Calculating sample size
Companies usually create sample sizes before data analysis so analysts know that the resulting dataset is representative of a population.

Terms and definitions:

| **Terminology**              | **Definitions**                                                                                            | **Descriptions**                                                                                                                                                                                                                                                                                                                                                                                                           |
|:---------------------------- | ---------------------------------------------------------------------------------------------------------- |:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Population**               | This is the total number you hope to pull your sample from.                                                | The entire group that you are interested in for your study. For example, if you are surveying people in your company, the population would be all the employees in your company.                                                                                                                                                                                                                                           |
| **Sample**                   | A part of a population that is representative of the population.                                           | A subset of your population. Just like a food sample, it is called a sample because it is only a taste. So if your company is too large to survey every individual, you can survey a representative sample of your population.                                                                                                                                                                                             |
| **Margin of error**          | The maximum amount that the sample results are expected to differ from those of the actual population.     | Since a sample is used to represent a population, the sample’s results are expected to differ from what the result would have been if you had surveyed the entire population. This difference is called the margin of error. The smaller the margin of error, the closer the results of the sample are to what the result would have been if you had surveyed the entire population.                                       |
| **Confidence level**         | The probability that your sample size accurately reflects the greater population.                          | The probability that your sample size accurately reflects the greater population. How confident you are in the survey results. For example, a 95% confidence level means that if you were to run the same survey 100 times, you would get similar results 95 of those 100 times. Confidence level is targeted before you start your study because it will affect how big your margin of error is at the end of your study. |
| **Confidence interval**      | The range of possible values that the population’s result would be (at the confidence level of the study). | This range is the sample result +/- the margin of error.<br> Having a 99\% confidence level is ideal, but most industries hope for at least a $90 \%$ or $95 \%$ percent confidence level.                                                                                                                                                                                                                                     |
| **Statistical significance** |                                                                                                            | The determination of whether your result could be due to random chance or not. The greater the significance, the less due to chance.                                                                                                                                                                                                                                                                                       |
| **Estimated response rate**  |                                                                                                            | If you are running a survey of individuals, this is the percentage of people you expect will complete your survey out of those who received the survey.                                                                                                                                                                                                                                                                    |

**Things to remember when determining the size of your sample:**
- Don’t use a sample size less than 30.
- The confidence level most commonly used is 95%, but 90% can work in some cases.
- Increase the sample size to meet specific needs of your project:
    -   For a **higher** confidence level, use a larger sample size
    -   To **decrease** the margin of error, use a larger sample size
    -   For **greater** statistical significance, use a larger sample size


- Sample sizes vary by business problem.
Given a same 200 sample size out of a 180,000 population, you could probably accept a larger margin of error surveying how residents feel about the new library versus surveying residents about how they would vote to fund it. For that reason, you would most likely use a larger sample size for the voter survey.

- Larger sample sizes have a higher cost.
For drug safety, the benefits outweigh the cost of using a larger sample size. But for consumer preferences, a smaller sample size at a lower cost could provide good enough results.

- Knowing the basics
Knowing the basics will help you make the right choices when it comes to sample size. A sample size calculator is also a great tool for this.

##### Sample size calculator 
A **sample size calculator** tells you how many people you need to interview (or things you need to test) to get results that represent the target population.

Some terms you will come across:
-   **Confidence level**: The probability that your sample size accurately reflects the greater population.
-   **Margin of error**: The maximum amount that the sample results are expected to differ from those of the actual population.
-   **Population**: This is the total number you hope to pull your sample from.
-   (↑ Above three are parameters needed for calculation)
-   **Sample**: A part of a population that is representative of the population.
-   **Estimated response rate**: If you are running a survey of individuals, this is the percentage of people you expect will complete your survey out of those who received the survey.

Sample size calculators let you enter a desired ***confidence level*** and ***margin of error*** for a given ***population size***. They then calculate the sample size needed to statistically achieve those results.


Online calculator:
-   [Sample size calculator by surveymonkey.com](https://www.surveymonkey.com/mp/sample-size-calculator/ "This link takes you to a sample size calculator created by SurveyMonkey.")
-   [Sample size calculator by raosoft.com](http://www.raosoft.com/samplesize.html "This liink takes you to a sample size calculator created by Raosoft. ")

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image37.png)


$$
\text { Sample size }=\frac{\frac{z^{2} \times p(1-p)}{e^{2}}}{1+\left(\frac{z^{2} \times p(1-p)}{e^{2} N}\right)}
$$
N: population size
e: Margin of error (percentage in decimal form)
z: z-score
p: standard of deviation #?
The z-score is the number of standard deviations a given proportion is away from the mean. To find the right z-score to use, refer to the table below:

| **Desired confidence level** | **z-score** |
| ---------------------------- | ----------- |
| 80%                          | 1.28        |
| 85%                          | 1.44        |
| 90%                          | 1.65        |
| 95%                          | 1.96        |
| 99%                          | 2.58        |

[A more detailed z-socre table](https://www.calculator.net/sample-size-calculator.html)
> p.s. the confidence level and margin of error don't have to add up to 100 percent. They are independent of each other.

**Sample size for known population**
![sample size calculation known population](https://blog.remesh.ai/hs-fs/hubfs/samplesize1.png?width=400&name=samplesize1.png)
**Sample size for unknown population**
![sample size calculation unknown population](https://blog.remesh.ai/hs-fs/hubfs/samplesize2.png?width=400&name=samplesize2.png)

##### What to do with the results
Keep in mind, the calculated sample size is the **minimum** number to achieve what you input for confidence level and margin of error. If you are working with a survey, you will also need to think about the estimated response rate to figure out how many surveys you will need to send out.
i.e. If you need a sample size of 100 individuals and your estimated response rate is 10%, you will need to send your survey to 1,000 individuals to get the 100 responses you need for your analysis.


##### Margin of error
**Margin of error**: The maximum amount that the sample results are expected to differ from those of the actual population.

If you already know the sample size, like when you're given survey results to analyze, you can calculate the margin of error yourself. The resulting margin of error will tell us how different the results might be compared to the results if we had surveyed the entire population.
The closer to zero the margin of error, the closer your results from your sample would match results from the overall population.

i.e. your survey tells you that 60% prefer a four-day workweek. The margin of error was 10%, which tells us that between 50 and 70% like the idea.
If you set up a 95% confidence level for your survey, there'll be a 95% chance that the entire population's responses will fall between 50 and 70% saying, yes, they want a four-day workweek.
(The survery is inconclusive because the margin of error overlaps with that 50% mark)

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image38.png)

###### Calculate
To calculate margin of error you need:
- Population size
- Sample size
- Confidence level

Review these terms:
-   **Confidence level**:The probability that your sample accurately reflects the greater population 
-   **Population**: The total number you pull your sample from
-   **Sample**: A part of a population that is representative of the population
-   **Margin of error**: The maximum amount that the sample results are expected to differ from those of the actual population

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image39.png)

-   [Margin of error calculator by G​ood Calculators (free online calculators)](https://goodcalculators.com/margin-of-error-calculator/ "This link takes you to a free margin of error calculator by Good Calculators.")
-   [Margin of error calculator by CheckMarket](https://www.checkmarket.com/sample-size-calculator/#sample-size-margin-of-error-calculator "This link takes you to a margin of error calculator by CheckMarket.")

$$
\mathrm{MOE}=z^{*} \sqrt{p^{*}(1-p)} / \sqrt{n}
$$
MOE: the margin of error,
z: the z-score associated with a level of confidence,
p: the sample proportion, expressed as a decimal,
n: the sample size.



### Summary
**How to prepare for data analysis?**

Pre-cleaning activities before begin analysis of the data:
-   **Step 1:** Determine data integrity. Assess the overall accuracy, consistency, and completeness of the data.
-   **Step 2:** Connect objectives to data. Understand how your business objectives can be served by an investigation into the data.
-   **Step 3:** Know when to stop collecting data.

**Insufficient data?**

### Using statistical power
**Statistical power**: The probability of getting meaningful results from a test.
Usually, the larger the sample size, the greater the chance you'll have statistically significant results with your test. And that's statistical power.

**Hypothesis testing**: A way to see if a survey or experiment has meaningful results.

Statistical power is usually shown as a value out of one. So if your statistical power is 0.6, that's the same thing as saying 60%. In the milk shake ad test, if you found a statistical power of 60%, that means there's a 60% chance of you getting a statistically significant result on the ad's effectiveness.
If a test is statistically significant, it means the results of the test are real and not an error caused by random chance, which requires the statistical power surpass a specific pre-set threshold.
Usually, you need a statistical power of at least **0.8** or $80 \%$ to consider your results statistically significant.

> *The effects from other factors*
> 
> i.e. Determine how many restaurant locations you'd have to use to be confident in your results about if the buzz around the new flavor shakemilk bring in more customers?
> First, you'd have to think about what might prevent you from getting statistically significant results. (Like other promotions, new-item-obsessed customer, constructions, )
> To get a higher statistical power, you'd have to consider all of these factors before you decide how many locations to include in your sample size for your study. You want to make sure any effect is most likely due to the new milkshake flavor, not another factor.
> The measurable effects would be an increase in sales or the number of customers at the locations in your sample size.



---
---


## Sparkling-clean data
### Dirty data
(The number one cause of poor-quality data is actually human error.)

**Dirty data**: Data that is incomplete, incorrect, or irrelevant to the problem you're trying to solve.
**Clean data**: Data that is complete, correct, and relevant to the problem you're trying to solve.

In some cases, you won't have to do a lot of work to clean data. For example, when you use internal data that's been verified and cared for by your company's data engineers and data warehouse team, it's more likely to be clean.
But remember, no dataset is perfect. It's always a good idea to examine and clean data before beginning analysis.

**Data engineers**: Transform data into a useful format for analysis, give it a reliable infrastructure, and develop, maintain, and test systems.

**Data warehousing specialists**: Develop processes and procedures to effectively store and organize data.
(Data warehousing specialists are responsible for ensuring data is available, secure, and backed up to prevent loss.)

**Null**: An indication that a value does not exist in a dataset.
(Don't equal to zero. A null indicates that a value does not exist. A zero is a numerical response.)


##### Types of dirty data
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image40.png)
- **Duplicate data**

| Description                                  | Possible causes                                          | Potential harm to businesses                                 |
| :------------------------------------------- | :------------------------------------------------------- | :----------------------------------------------------------- |
| Any data record that shows up more than once | Manual data entry, batch data imports, or data migration | Skewed metrics or analyses, inflated or inaccurate counts or predictions, or confusion during data retrieval |

- **Outdated data**

| Description                                                  | Possible causes                                              | Potential harm to businesses                        |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :-------------------------------------------------- |
| Any data that has been superseded by newer and more accurate information | People changing roles or companies, or software and systems becoming obsolete | Inaccurate insights, decision-making, and analytics |

- **Incomplete data**

| Description                               | Possible causes                                  | Potential harm to businesses                                 |
| :---------------------------------------- | :----------------------------------------------- | :----------------------------------------------------------- |
| Any data that is missing important fields | Improper data collection or incorrect data entry | Decreased productivity, inaccurate insights, or inability to complete essential services |

- **Incorrect/inaccurate data**

| Description                              | Possible causes                                              | Potential harm to businesses                                 |
| :--------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| Any data that is complete but inaccurate | Human error inserted during data input, fake information, or mock data | Inaccurate insights or decision-making based on bad information resulting in revenue loss |

- **Inconsistent data**

| Description                                                  | Possible causes                                              | Potential harm to businesses                                 |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| Any data that uses different formats to represent the same thing | Data stored incorrectly or errors inserted during data transfer | Contradictory data points leading to confusion or inability to classify or segment customers |

##### Defining dirty data
Misspellings, spelling variations, mixed up letters, inconsistent punctuation and typos in general happen when someone types in a piece of data incorrectly.

As a data analyst, you'll also deal with different currencies. For example, one dataset could be in US dollars and another in euros, and you don't want to get them mixed up.

some other types of dirty data:
- incorrectly labeling
- inconsistent field length

**Field**: A single piece of information from a row or column of a spreadsheet
**Field length**: A tool for determining how many characters can be keyed into a field

**Data validation**: A tool for checking the accuracy and quality of data before adding or importing it.
(Data validation is a form of data cleansing)


##### Business impact of dirty data
-   **Banking**: Inaccuracies cost companies between 15% and 25% of revenue ([source](https://sloanreview.mit.edu/article/seizing-opportunity-in-data-quality/ "This link takes you to an MIT Sloan Management Review article.")).

-   **Digital commerce:** Up to 25% of B2B database contacts contain inaccuracies ([source](https://www.demandgen.com/dirty-data-what-is-it-costing-you/ "This link takes you to a DemandGen blog article. ")).

-   **Marketing and sales**: 8 out of 10 companies have said that dirty data hinders sales campaigns ([source](https://www.dqglobal.com/2011/05/04/obsolete-or-dirty-data/ "This link takes you to a DQ Global blog article.")).

-   **Healthcare**: Duplicate records can be 10% and even up to 20% of a hospital’s electronic health records ([source](https://searchhealthit.techtarget.com/feature/Hospitals-battle-duplicate-medical-records-with-technology "This link takes you to a TechTarget article for health IT.")).


### Data-cleaning tools and techniques
Before removing unwanted data, it's always a good practice to make a copy of the data set.

**Things need to be cleaned:**
- Duplicates
- Irrelevant data  (e.g. Current member vs past member/prospective member)
- Removing extra spaces and blanks
- Fixing misspellings  (fix manunlly or using spreadsheet tools, such as spellcheck, autocorrect, and conditional formatting)
- Inconsistent capitalization
- Incorrect punctuation and other typos
- Removing formatting (using spreadsheet clear formatting tool)


### Cleaning data from multiple sources
Cleaning data that comes from two or more sources is very common for data analysts, but it does come with some interesting challenges.
A good example is a merger.

**Merger**: An agreement that unites two organizations into a single new one.

**Data merging**: The process of combining two or more datasets into a single dataset.
(Challenging because information is almost guaranteed to be inconsistent and misaligned.)

**Compatibility**: How well two or more datasets are able to work together.

**Key questions to ask to avoid redundancy and to confirm that the datasets are compatible when merging datasets:**
- Do I have all the data I need?
- Does the data I need exist within these datasets?
- Does the data need to be cleaned, or are they ready for me to use?
- Are the datasets cleaned to the same standard?

### Common data-cleaning pitfalls
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image41.png)

-   **Not checking for spelling errors**: Misspellings can be as simple as typing or input errors. Most of the time the wrong spelling or common grammatical errors can be detected, but it gets harder with things like names or addresses. For example, if you are working with a spreadsheet table of customer data, you might come across a customer named “John” whose name has been input incorrectly as “Jon” in some places. The spreadsheet’s spellcheck probably won’t flag this, so if you don’t double-check for spelling errors and catch this, your analysis will have mistakes in it. 
-   **Forgetting to document errors**: Documenting your errors can be a big time saver, as it helps you avoid those errors in the future by showing you how you resolved them. For example, let’s say you find an error in a formula in your spreadsheet. You discover that some of the dates in one of your columns haven’t been formatted correctly. If you make a note of this fix, you can reference it the next time your formula is broken, and get a head start on troubleshooting. Documenting your errors also helps you keep track of changes in your work, so that you can backtrack if a fix didn’t work. 
-   **Not checking for misfielded values**: A misfielded value happens when the values are entered into the wrong field. These values might still be formatted correctly, which makes them harder to catch if you aren’t careful. For example, you might have a dataset with columns for cities and countries. These are the same type of data, so they are easy to mix up. But if you were trying to find all of the instances of Spain in the country column, and Spain had mistakenly been entered into the city column, you would miss key data points. Making sure your data has been entered correctly is key to accurate, complete analysis. 
-   **Overlooking missing values**: Missing values in your dataset can create errors and give you inaccurate conclusions. For example, if you were trying to get the total number of sales from the last three months, but a week of transactions were missing, your calculations would be inaccurate.  As a best practice, try to keep your data as clean as possible by maintaining completeness and consistency.
-   **Only looking at a subset of the data**: It is important to think about all of the relevant data when you are cleaning. This helps make sure you understand the whole story the data is telling, and that you are paying attention to all possible errors. For example, if you are working with data about bird migration patterns from different sources, but you only clean one source, you might not realize that some of the data is being repeated. This will cause problems in your analysis later on. If you want to avoid common errors like duplicates, each field of your data requires equal attention.
-   **Losing track of business objectives**: When you are cleaning data, you might make new and interesting discoveries about your dataset-- but you don’t want those discoveries to distract you from the task at hand. For example, if you were working with weather data to find the average number of rainy days in your city, you might notice some interesting patterns about snowfall, too. That is really interesting, but it isn’t related to the question you are trying to answer right now. Being curious is great! But try not to let it distract you from the task at hand.  
-   **Not fixing the source of the error:** Fixing the error itself is important. But if that error is actually part of a bigger problem, you need to find the source of the issue. Otherwise, you will have to keep fixing that same error over and over again. For example, imagine you have a team spreadsheet that tracks everyone’s progress. The table keeps breaking because different people are entering different values. You can keep fixing all of these problems one by one, or you can set up your table to streamline data entry so everyone is on the same page. Addressing the source of the errors in your data will save you a lot of time in the long run. 
-   **Not analyzing the system prior to data cleaning:** If we want to clean our data and avoid future errors, we need to understand the root cause of your dirty data. Imagine you are an auto mechanic. You would find the cause of the problem before you started fixing the car, right? The same goes for data. First, you figure out where the errors come from. Maybe it is from a data entry error, not setting up a spell check, lack of formats, or from duplicates. Then, once you understand where bad data comes from, you can control it and keep your data clean.
-   **Not backing up your data prior to data cleaning**: It is always good to be proactive and create your data backup before you start your data clean-up. If your program crashes, or if your changes cause a problem in your dataset, you can always go back to the saved version and restore it. The simple procedure of backing up your data can save you hours of work-- and most importantly, a headache. 
-   **Not accounting for data cleaning in your deadlines/process**: All good things take time, and that includes data cleaning. It is important to keep that in mind when going through your process and looking at your deadlines. When you set aside time for data cleaning, it helps you get a more accurate estimate for ETAs for stakeholders, and can help you know when to request an adjusted ETA.

### Hands-On Activity
#### Eliminate rows with blank cells
1. Select all columns you want to filter, or just select all; "Data-->Create a filter"
2. In one column, cilck the green triangle icon next to the column title; "Filter by condition --> Is empty --> OK"
3. Delete all the rows showed by selecting them and "Delete selected rows"
4. Turn the filter into none: "Filter by condition --> None --> OK"
5. Repeat this to on other columns (whf?!)

#### Transpose the data
**Transposing**: Convert the data from the long format (more rows than columns) to the wide format (more columns than rows).
1. Selecting and copy the data that you want to transpose including the column labels.
2. Right-click on the cell you want the transposed data to start (e.g. cell I1)
3. "Paste Special --> Paste transposed"
4. (Optional: Delete the previous long data)

#### Get rid of extra spaces in cells with string data
1. Highlight the data in the spreadsheet.
2. Click on the **Data** tab and select the **Trim whitespace** option.

#### Change Text Lower/Uppercase/Proper Case
- **Microsoft Excel**
 [This documentation](https://support.microsoft.com/en-us/office/change-the-case-of-text-in-excel-adc65f5b-958f-46a2-4d23-ab4d5faf48a8) explains how to use a formula to change the case of a text string.
    1.  To change column A to Title Case, select cell B2. Type **=PROPER(A2)**, and press Enter. Tip: Use the formula **=UPPER(A1)** for all UPPERCASE; **=LOWER(A1)** for all lowercase.
    2. Now fill down the formula through column B.
 - **Google sheets**
Use an Add-On to do this.
    1. "Add-Ons --> Get add-ons --> ChangeCase --> Install"
    2. Select the cells you want to manage, "Add-Ons --> ChangeCase --> xxx"


#### Delete all formatting
1. Select the data for which you want to delete the formatting
2. "Format --> Clear Formatting"


### Data-cleaning features in spreadsheets
#### Conditional formatting
**Conditional formatting**: A spreadsheet tool that changes how cells appear when values meet specific conditions.

**Steps(Google sheets):**
1. Select the columns you want to be conditional formatted
2. "Format --> Conditional formatting"
3. At right, change format tules to xxx (like 'Is empty' to highlight empty cells)
4. At right, choose desired formatting style
5. Click "Done"

#### Remove duplicates
**Remove duplicates**: A tool that automatically searches for and eliminates duplicate entries from a spreadsheet.

**Steps(Google sheets):**
1. "Data --> Remove duplicates"
2. (Optional: Choose "Data has a header row")
3. Select desired columns or all to inspect
4. Click "Remove duplicates"


**Make data consistent**:
1. Select the column which contains inconsistant data
2. "Data --> Number --> xxx (like Date to transform into same date formatting)"

#### Text manipulation

**Text string**: A group of characters within a cell, commonly composed of letters, numbers, or both.

**Split**: A tool that divides text around a specified character and puts each fragment into a new, separate cell.

> Specified text separator = delimiter  (e.g. comma)
> A delimiter is a character that indicates the beginning or end of a data item.

**Split text into columns:**
1. Select a column
2. "Data --> Split text to columns"
3. (Optional: Choose the right Seprator hoving on the column (Default: Detect automatically))
(Comma ,  Semicolon ;  Period .  Space )

Another usage: transform string type text into numbers.
e.g. A number row contains a wrong formatted cell, string "707". After splitting text to columns, "707" is transformed into number 707.



#### functions
**Function**: A set of instructions that performs a specific calculation using the data in a spreadsheet.

Every function has a certain syntax that needs to be followed for it to work.
**Syntax**: A predetermined structure that includes all required information and its proper placement.

##### COUNTIF
**COUNTIF**: A function that returns the number of cells that match a specified value.
Syntax: `=COUNTIF(range, "value")`
e.g. `=COUNTIF(I2:I72,"<100")`

##### LEN
**LEN**: A function that tells you the length of a text string by counting the number of characters it contains.
Syntax: `=LEN(cell_reference / string)`
e.g. `=LEN(E2)    =LEN("Google sheet")`

##### Conditional formatting
**Conditional formatting**: A spreadsheet tool that changes how cells appear when values meet specific conditions.
1. Select all cells in a column except for the header
2. "Format --> Conditional formatting"
3. Select formatting rule like "Not equal to"

##### LEFT / RIGHT
**LEFT**: A function that gives you a set number of characters from the left side of a text string.
**RIGHT**: A function that gives you a set number of characters from the right side of a text string.
Syntax: `=LEFT(cell_reference / string, number of characters)`
e.g. `=LEFT(A2,5)`

##### MID
**MID**: A function that gives you a segment from the middle of a text string.
Syntax: `=MID(cell_reference / string, reference starting point,number of middle characters)`
e.g. `=MID(D2,4,2)`
> p.s. the first character in stirng has index 1

##### CONCATENATE
**Concatenate**: A function that joins multiple text strings into a single string.
Syntax: `=CONCATENATE(item1,[item2...])`
e.g. `=CONCATENATE(H2,I2)`  `=CONCATENATE(H2," ",I2)`

> CONCAT(str1, str2) has the same effect with CONCATENATE(str1, str2)
> But CONCATENATE can accept multiple parameters
> (p.s. SQL only has CONCAT, which can accept multiple inputs)

##### TRIM
**TRIM**: A function that removes leading, trailing, and repeated spaces in data. (Even in the middle of a string!)
Syntax: `=TRIM(cell_reference)`
e.g. `=TRIM(C2)`

#### Workflow automation
**Can it be automated?**
No: Communicating with your team and stakeholders; Presenting your findings
Partially: Preparing and cleaning data, Data exploration
Yes: Modeling the data

**workflow automation resources or articles:**
-   Towards Data Science’s [**Automating Scientific Data Analysis**](https://towardsdatascience.com/automating-scientific-data-analysis-part-1-c9979cd0817e "This link takes you to a Toward Data Science article about automating data analysis with Python.")
-   MIT News’ [**Automating Big-Data Analysis**](https://news.mit.edu/2016/automating-big-data-analysis-1021 "This link takes you to an MIT News article about automating data analysis.")
-   TechnologyAdvice’s [**10 of the Best Options for Workflow Automation Software**](https://technologyadvice.com/blog/information-technology/top-10-workflow-automation-software/ "This link takes you to TechnologyAdvice's blog about the best workflow automation software.")

#### Different data perspectives
**Sorting**: Arranging data into a meaningful order to make it easier to understand, analyze, and visualize.
For data cleaning, you can use sorting to put things in alphabetical or numerical order, so you can easily find a piece of data.

**Filtering**: Showing only the data that meets a specific criteria while hiding the rest.
When cleaning data, you might use a filter to only find values above a certain number, or just even or odd values.

**Pivot table**: A data summarization tool that is used in data processing.
Pivot tables sort, reorganize, group, count, total or average data stored in the database. In data cleaning, pivot tables are used to give you a quick, clutter- free view of your data. You can choose to look at the specific parts of the data set that you need to get a visual in the form of a pivot table.

Pivot table usage steps:
1. Select the data you want to use (like select all)
2. "Data --> Pivot table"
3. Choose "New sheet", then "Create"
4. In right "Pivot table editor", Add rows and choose their sorting order

**VLOOKUP**(Vertical lookup): A function that searches for a certain value in a column to return a corresponding piece of information.
To put it simply, VLOOKUP searches for the value in the first argument in the leftmost column of the specified location.
Then the value of the third argument tells VLOOKUP to return the value in the same row from the specified column.
The "false" tells VLOOKUP that we want an exact match.

Syntax: `=VLOOKUP(data to look up, 'where to look'!Range, column, false)`
e.g. `=VLOOKUP(A2, 'Sheet 2'!A1:B31, 2, false)`

Official Syntax: `=VLOOKUP(search_key, range, index, [is_sorted])`
Official Example: `=VLOOKUP(10003, A2:B26, 2, FALSE)`

**Plotting**
Plotting is very useful when trying to identify any skewed data or outliers.
Steps:
1. Select the columns you want to plot
2. "Insert --> Chart"
3. At right in "Chart editor", pick a chart type


#### Even more data-cleaning techniques
It's important to think about how your data has moved between systems and how it's evolved along its journey to your data analysis project.

**Data mapping**: The process of matching fields from one data source to another.
This is very important to the success of data migration, data integration, and lots of other data management activities.

**Compatibility**: How well two or more datasets are able to work together.

#### Data Cleaning Approach Table
![](attachments/ETYyTYXZTj62Mk2F2T4-Hw_7a4e7cafe41f4ded99d1a90edffa4ffc_data-approach-table.png)
[Learning Log Template_ Develop your approach to cleaning data.docx](https://d18ky98rnyall9.cloudfront.net/26Lfz62pSRai38-tqXkWmQ_bbcdfe84d8b1423b8db5e155d46367c4_Learning-Log-Template_-Develop-your-approach-to-cleaning-data.docx?Expires=1624060800&Signature=fzmtLMqWgXd9xmWKSgvZMs4vc0Gn7SaRuXIfDgkptLsHwbtQcJ6R0aB~bE9wB-rRvD-00QaGDwh~KOLF6EEUGtRbOFFsf6y5aRn3K1hCSG~J~bkIlM5xhaje~4b2zJAKnnY0B4vKw7GxrwlOvXDJEG9Yo3c9ZPhTkZxReRitUKM_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

1. Create your checklist
Think of this checklist as your default "what to search for" list. With a good checklist, you can efficiently and, hopefully, swiftly identify all the problem spots without getting sidetracked. You can also use the checklist to identify the scale and scope of the dataset itself.
2. List your preferred cleaning methods
After you have compiled your personal checklist, you can create a list of activities you like to perform when cleaning data.
3. Choose a data cleaning motto
The motto is a short one or two sentence summary of your philosophy towards cleaning data.

The data you encounter as an analyst won’t always conform to your checklist or activities list regardless of how comprehensive they are. Data cleaning can be an involved and complicated process, but surprisingly most data has similar problems. A solid personal motto and explanation can make the more common data cleaning tasks easy to understand and complete.


---
---

## Cleaning data with SQL
Aim:
Different data cleaning functions in spreadsheets and SQL,
How SQL can be used to clean large data sets,
Apply basic SQL functions for transforming data and cleaning strings.

SQL can process large amounts of data much more quickly than spreadsheets. This is one of the reasons why data analysts use SQL when working with vast, complex datasets.

**Relational database**: A database that contains a series of tables that can be connected to form relationships.

SQL is the primary way data analysts extract data from databases. As a data analyst, you will work with databases all the time, which is why SQL is such a key skill.

**Spreadsheets or SQL?**

| **Features of Spreadsheets**                         | **Features of SQL Databases**                                      |
|:---------------------------------------------------- |:------------------------------------------------------------------ |
| Smaller data sets                                    | Larger datasets                                                    |
| Enter data manually                                  | Access tables across a database                                    |
| Create graphs and visualizations in the same program | Prepare data for further analysis in another software              |
| Built-in spell check and other useful functions      | Fast and powerful functionality                                    |
| Best when working solo on a project                  | Great for collaborative work and tracking queries run by all users |
|                                                      |                                                                    |
| Generated with a program                             | A language used to interact with database programs                 |
| Access to the data you input                         | Can pull information from different sources in the database        |
| Stored locally                                       | Stored across a database                                           |
| Small datasets                                       | Large datasets                                                     |
| Working independently                                | Tracks changes across team                                         |
| Built-in functionalities                             | Useful across multiple programs                                    |

Analysts can use SQL and spreadsheets to perform arithmetic, use formulas, and join data.

Data stored in a SQL database is useful to a project with multiple team members because they can access the data at the same time, use SQL to interact with the database program, and track changes to SQL queries across the team.
SQL can handle huge amounts of data, can be adapted and used for multiple database programs, and offers powerful tools for cleaning data.

### SQL dialects
**Structured Query Language**, or SQL, is a language used to talk to databases.
Some database products have their own variant of SQL.
Standard SQL works with a majority of databases and requires a small number of syntax changes to adapt to other dialects. So, a lot of analysts start with Standard SQL and then adjust the dialect they use based on what database they are working with.
-   LearnSQL’s blog, [**What Is a SQL Dialect, and Which One Should You Learn?**](https://learnsql.com/blog/what-sql-dialect-to-learn/ "This link takes you to a LearnSQL blog about SQL dialects.")
-   Software Testing Help’s article, [**Differences Between SQL Vs MySQL vs SQL Server**](https://www.softwaretestinghelp.com/sql-vs-mysql-vs-sql-server/ "This link takes you to an article describing the differences between SQL, MySQL, and SQL Server.")
-   Datacamp’s blog, [**SQL Server, PostgreSQL, MySQL... what's the difference? Where do I start?**](https://www.datacamp.com/community/blog/sql-differences "This link takes you to Datacamps's blog about different SQL dialects.") Note that there is an error in this blog article. The comparison table incorrectly states that SQlite uses subqueries instead of window functions. Refer to the [**SQLite Window Functions**](https://sqlite.org/windowfunctions.html "SQLite Window Functions") documentation for proper clarification.
-   SQL Tutorial’s tutorial, [**What is SQL**](https://www.sqltutorial.org/what-is-sql/ "This link takes you to SQL Tutorial's introduction to SQL.")


### Cleaning string variables using SQL
**Text strings**: A group of characters within a cell, commonly composed of letters, numbers, or both.

Remove duplicates using SQL:
Including DISTINCT in your SELECT statement removes duplicates.

#### LENGTH (or LEN)
e.g.
```SQL
SELECT
    DISTINCT(LENGTH(country)) as letters_in_country
FROM `customer_data.customer_address`

SELECT country
FROM `customer_data.customer_address`
WHERE LENGTH(country) > 2
```

#### SUBSTR()
Syntax: `SUBSTR(string, start_index, length)`
`start_index` start with 1
e.g.
```SQL
SELECT customer_id
FROM `customer_data.customer_address`
WHERE SUBSTR(country,1,2) = 'US'
```

#### TRIM()
Useful if you find entries with extra spaces and need to eliminate those extra spaces for consistency.
e.g.
```SQL
SELECT DISTINCT customer_id
FROM `customer_data.customer_address`
WHERE TRIM(state) = 'OH'
```


#### CAST()
Can be used to convert anything from one data type to another.

**Float**: A number that contains a decimal.

**Typecasting**: Converting data from one type to another.
e.g.  from string to float:
```SQL
SELECT
    CAST(purchase_price AS FLOAT64)
FROM
    customer_data.customer_purchase
ORDER BY
    CAST(purchase_price AS FLOAT64) DESC
```

e.g. from date-time to date
```SQL
SELECT
    CAST(date AS date) AS date_only,
    purchase_price
FROM
    customer_data.customer_purchase
WHERE
    date BETWEEN '2020-12-01' AND '2020-12-31'
```

date types(schema) in BigQuery: strings, integers, timestamps, and floating values.

#### CONCAT()
Adds strings together to create new text strings that can be used as unique keys.

e.g.
```SQL
SELECT
    CONCAT(product_code, product_color) AS new_product_code
FROM
    customer_data.customer_purchase
WHERE
    product = 'couch'
```

#### COALESCE
Can be used to return non-null values in a list.
Syntax: `COALESCE(first_value_to_check, second_to_check_if_first_is_null)`
e.g.
```SQL
SELECT
    COALESCE(product, product_code) AS product_info
FROM
    customer_data.customer_purchase
```

---
---

## Verifying and reporting results
**Verification**: A process to confirm that a data-cleaning effort was well-executed and the resulting data is accurate and reliable.
It involves rechecking your clean dataset, doing some manual clean ups if needed, and taking a moment to sit back and really think about the original purpose of the project.
It also involves manually cleaning data to compare your expectations with what's actually present.

The verification process confirms that data cleaning was well executed and the resulting data is accurate and reliable. To verify data, analysts recheck the data-cleaning effort, manually fix errors in the data, and consider whether the data is credible and appropriate for the project.

**Why verification is important?**
1. Verification lets you catch mistakes before you begin analysis.
2. The other big part of the verification process is reporting on your efforts.

**Different strategies for reporting:**
- documenting your cleaning process
- creating data cleaning reports
- using something called the changelog

**Changelog**: A file containing a chronologically ordered list of modifications made to a project.
It's usually organized by version and includes the date followed by a list of added, improved, and removed features.

### Verification steps
#### Go back to your original dataset and compare it to the cleaned one
**The first step in the verification process is going back to your original unclean data set and comparing it to what you have now.**
Review the dirty data and try to identify any common problems.
For example, a lot of nulls in dirty data, so search in the cleaned data for nulls manually or use tools like conditional formatting or filters.

#### Doing some manual clean ups
Fix errors that shows up repeatedly, and can't be resolved with a quick manual edit or a tool that fixes the problem automatically.

##### In Spreadsheets
In these cases, it's helpful to create a pivot table.

e.g. An error in spreadsheets showing the misspelling suppliers' name. There are two ways to answer that question:
1. The first is using Find and replace.
**Find and replace**: A tool that looks for a specified search term in a spreadsheet and allows you to replace it with something else.
2. The second is to create a pivot table
**Pivot table**: A data summarization tool that is used in data processing.
Pivot table sort, reorganize, group, count, total or average data stored in a database.
Steps:
- Choose the column you want to create the table. then "Data-->Pivot table"
- Choose "New sheet", then "Create"
- Add a row for suppliers
- Add a value for suppliers, summarized by "COUNTA"

**COUNTA**: A function that counts the total number of values within a specified range.
(There is also a function called "COUNT", which only counts the number(not sum) of **numerical values only** within a specified range.)

##### In SQL
If you're working in SQL, you can address misspellings using a CASE statement.
**CASE statement**: The CASE statement goes through one or more conditions and returns a value as soon as a condition is met.
```SQL
SELECT
    customer_id,
    CASE
        WHEN first_name = 'Tnoy' THEN 'Tony'
        WHEN first_name = 'Tmo' THEN 'Tom'
        ELSE first_name
    END AS cleaned_name
FROM
    customer_data.customer_name
```


#### Sit back and See the big picture
Another key part of verification involves taking a big-picture view of your project.
This is an opportunity to confirm you're actually focusing on the business problem that you need to solve and the overall project goals and to make sure that your data is actually capable of solving that problem and achieving those goals.

**Taking a big picture view of your project involves doing three things:**
1. Consider the business problem
Taking a problem-first approach to analytics is essential at all stages of any project.
2. Consider the goal
For example, it's not enough just to know that your company wants to analyze customer feedback about a product. What you really need to know is that the goal of getting this feedback is to make improvements to that product.
3. Consider the data
Whether your data is capable of solving the problem and meeting the project objectives. That means thinking about where the data came from and testing your data collection and cleaning processes.

Sometimes data analysts can be too familiar with their own data, which makes it easier to miss something or make assumptions. Asking a teammate to review your data from a fresh perspective and getting feedback from others is very valuable in this stage.



### Data-cleaning verification checklist
There is no one-size-fits-all approach or a single checklist that can be universally applied to all projects. As you receive more data or a better understanding of the project goal(s), you might want to revisit some or all of these steps.

#### Correct the most common problems
Make sure you identified the most common problems and corrected them, including:

-   **Sources of errors**: Did you use the right tools and functions to find the source of the errors in your dataset?
-   **Null data**: Did you search for NULLs using conditional formatting and filters?
-   **Misspelled words**: Did you locate all misspellings?
-   **Mistyped numbers**: Did you double-check that your numeric data has been entered correctly?
-   **Extra spaces and characters**: Did you remove any extra spaces or characters using the **TRIM** function?
-   **Duplicates**: Did you remove duplicates in spreadsheets using the **Remove Duplicates** function or **DISTINCT** in SQL?

-   **Mismatched data types**: Did you check that numeric, date, and string data are typecast correctly?
-   **Messy (inconsistent) strings**: Did you make sure that all of your strings are consistent and meaningful?
-   **Messy (inconsistent) date formats**: Did you format the dates consistently throughout your dataset?
-   **Misleading variable labels (columns)**: Did you name your columns meaningfully?
-   **Truncated data:** Did you check for truncated or missing data that needs correction?
-   **Business Logic**: Did you check that the data makes sense given your knowledge of the business?

#### Review the goal of your project
Once you have finished these data cleaning tasks, it is a good idea to review the goal of your project and confirm that your data is still aligned with that goal. This is a continuous process that you will do throughout your project-- but here are three steps you can keep in mind while thinking about this:
-   Confirm the business problem 
-   Confirm the goal of the project
-   Verify that data can solve the problem and is aligned to the goal


### Documenting results and the cleaning process
Keeping track of changes is important to every data project.
It is important to document the evolution of a dataset in order to recover data-cleaning errors, inform other users of changes, and determine the quality of the data.

**Documentation**: The process of tracking changes, additions, deletions, and errors involved in your data-cleaning effort.
Changelogs are good examples of this.

**Having a record of how a data set evolved does three very important things:**
- Recover data-cleaning errors
- Inform other users of changes
- Determine quality of data

Documenting data-cleaning makes it possible to be transparent about your process, keep team members on the same page, and demonstrate to project stakeholders that you are accountable.

#### Changelogs
Data analysts usually use a changelog to access this information. You can use and view a changelog in spreadsheets and SQL to achieve similar results.
**Changelog**: A file containing a chronologically ordered list of modifications made to a project.

**In Spreadsheets**
Provides a real-time tracker of all the changes and who made them from individual cells to the entire worksheet. (Need to be assigned permission)
GoogleSheets:
For the entire worksheet: "File --> Version history"
For a cell: Right click the cell --> "Show edit history"

Excel:
use a feature called **"Tools --> Track Changes"**

**In SQL**
Depends on the software program you're using.
e.g.
In BigQuery, check "Query history".
Listed on the bottom right are all the queries that run by date and time. Click on the download icon to the right of each individual query to bring it up to the Query editor.

Here’s how it works:

|                 |                                                              |
| --------------- | ------------------------------------------------------------ |
| Google Sheets   | 1. Right-click the cell and select **Show edit history**. <br>2. Click the left-arrow < or right arrow > to move backward and forward in the history as needed. |
| Microsoft Excel | 1. If Track Changes has been enabled for the spreadsheet: click **Review**.  <br>2. Under **Track Changes**, click the **Accept/Reject Changes** option to accept or reject any change made. |
| BigQuery        | Bring up a previous version (without reverting to it) and figure out what changed by comparing it to the current version. |



Engineers use **engineering change orders** (ECOs) to keep track of new product design details and proposed changes to existing products. Writers use **document revision histories** to keep track of changes to document flow and edits. And data analysts use **changelogs** to keep track of data transformation and cleaning. Here are some examples of these:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image42.png)

Version histories record **_what_** was done in a data change for a project, but don't tell us **_why_**. Changelogs are super useful for helping us understand the reasons changes have been made.
A changelog is important when lots of changes to a spreadsheet or query have been made. Like undo change #2 but keep #3 and #4.

**Typically, a changelog records this type of information:**
-   Data, file, formula, query, or any other component that changed
-   Description of what changed
-   Date of the change
-   Person who made the change
-   Person who approved the change 
-   Version number 
-   Reason for the change

#### IRL (in real life)
Here is how a version control system affects a change to a query:
1.  A company has official versions of important queries in their **version control system**.
2.  An analyst makes sure the most up-to-date version of the query is the one they will change. This is called **syncing** 
3.  The analyst makes a change to the query.
4.  The analyst might ask someone to review this change. This is called a **code review** and can be informally or formally done. An informal review could be as simple as asking a senior analyst to take a look at the change.
5.  After a reviewer approves the change, the analyst submits the updated version of the query to a repository in the company's version control system. This is called a **code commit**. A best practice is to document exactly what the change was and why it was made in a comments area. Going back to our example of a query that pulls daily revenue, a comment might be: _Updated revenue to include revenue coming from the new product, Calypso_.
6.  After the change is **submitted**, everyone else in the company will be able to access and use this new query when they **sync** to the most up-to-date queries stored in the version control system.
7.  If the query has a problem or business needs change, the analyst can **_undo_** the change to the query using the version control system. The analyst can look at a chronological list of all changes made to the query and who made each change. Then, after finding their own change, the analyst can **revert** to the previous version.
8.  The query is back to what it was before the analyst made the change. And everyone at the company sees this reverted, original query, too.


#### Creating a changelog
A changelog for a personal project may take any form desired. However, in a professional setting, particularly when collaborating with others, readability is important. In light of this, you can follow the guiding principles that make the interpretation of the changelog accessible to others:
-   Changelogs are for humans, not machines, so write legibly
-   Versions should be ordered chronologically starting with the latest
-   Every version should have its own entry
-   Release date of each version should be noted
-   Group the same types of changes. For example, "Fixed" should be grouped separately from "Added"
-   Each change gets its own line (in its corresponding group)



Types of changes usually fall into one of the following categories:
-   (New)Added: new features introduced
-   (Changes)Changed: changes in existing functionality
-   (Deprecation)Deprecated: features about to be removed
-   Removed: features that have been removed
-   (Fixes)Fixed: bug fixes
-   Security: lowering vulnerabilities

Examine the figure below for an example of a changelog. Note that the following example is written in [Markdown](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax), as it is common to keep changelogs as a readme file in a code repository.

```markdown
# Changelog
This file contains the notable changes to the project
Version 1.0.0 (02-23-2019)
## New
   - Added column classifiers (Date, Time, PerUnitCost, TotalCost, etc. )
   - Added Column "AveCost" to track average item cost
## Changes 
   - Changed date format to MM-DD-YYYY
   - Removal of whitespace (cosmetic)
## Fixes
   - Fixed case where exception was thrown when cases didn’t match for category labels
   - Fixed SUM to run over entire column instead of partial
```

If we were working with SQL, we could include a comment in the statement describing the reason for a change without affecting the execution of the statement.

Advices:
In the final course in this certification program, you’ll have the opportunity to complete a capstone project. This is a great chance to demonstrate your ability to organize a project like a professional data analyst by keeping your own changelog. You can do this using a simple companion text file that can be included with the project write-up.

In the log, you will want to record the various changes, additions, fixes, etc. that were discussed above. Arrange them using bullets or similar with one change per bullet. Group similar changes together with a label describing the change immediately above them.

Use different version numbers for each milestone reached in your project. Within each version, place the logged changes that were made since the previous version (milestone). Dates are not generally necessary for each change, but they are recommended for each version.

Use this knowledge to create and maintain a changelog for your data cleaning capstone project. It will help you stay organized and make collaborating with others much easier.

A good changelog should indicate the notable changes to a project. If you perform any of the following changes to the dataset while cleaning, you should capture those changes in the changelog:

-   Treated missing data
-   Changed formatting
-   Changed values or cases for data

Chances are that you have made some of these changes while cleaning the data. Also, any other substantial changes should be included. As a rule-of-thumb, when in doubt about the significance of a change, you should enter it into the changelog.


#### Feedback and cleaning
Clean data is important to the task at hand. But the data-cleaning process itself can reveal insights that are helpful to a business. The feedback we get when we report on our cleaning can transform data collection processes, and ultimately business development.

Common data errors:
- Human error in data entry
- Flawed processes
- System issues

With consistent documentation and reporting, we can uncover error patterns in data collection and entry procedures and use the feedback we get to make sure common errors aren't repeated.


### Advanced functions for speedy data cleaning
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image43.png)

#### IMPORTRANGE
Syntax: `IMPORTRANGE(spreadsheet_url, range_string)`
e.g. `IMPORTRANGE("https://docs.google.com/spreadsheets/d/abcd123abcd123", "sheet1!A1:C10")`

The [**IMPORTRANGE**](https://support.google.com/docs/answer/3093340?hl=en) function in Google Sheets and the [**Paste Link**](https://professor-excel.com/how-to-paste-cell-links/ "Paste Link") feature (a Paste Special option in Microsoft Excel) both allow you to insert data from one sheet to another. Using these on a large amount of data is more efficient than manual copying and pasting. They are also helpful for data cleaning because you can “cherry pick” the data you want to analyze and leave behind the data that isn’t relevant to your project.

If you are using IMPORTRANGE in Google sheets, data can be pulled from another spreadsheet, but you must allow access to the spreadsheet the first time it pulls the data.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image44.png)
Refer to the [Google support page for IMPORTRANGE](https://support.google.com/docs/answer/3093340?hl=en# "Google support page for IMPORTRANGE") for the sample usage and syntax.

#### QUERY
Syntax: `QUERY(data, query, [headers])`
e.g. `QUERY(A2:E6,"select avg(A) pivot B")` `QUERY(A2:E6,F2,FALSE)`

`data` - The range of cells to perform the query on.
`query` - The query to perform, written in [the Google Visualization API Query Language](https://developers.google.com/chart/interactive/docs/querylanguage)
`headers` - **[** OPTIONAL **]** - The number of header rows at the top of `data`.

The [**QUERY**](https://support.google.com/docs/answer/3093343?hl=en "QUERY") function is also useful when you want to pull data from another spreadsheet. The **QUERY** function's SQL-like ability can extract specific data within a spreadsheet. For a large amount of data, using the QUERY function is faster than filtering data manually.

The **QUERY** function syntax is similar to **IMPORTRANGE**. You enter the sheet by name and the range of data that you want to query from, and then use the SQL **SELECT** command to select the specific columns. You can also add specific criteria after the **SELECT** statement by including a **WHERE** statement. But remember, all of the SQL code you use has to be placed between the quotes!

Google Sheets run the Google Visualization API Query Language across the data. Excel spreadsheets use a query wizard to guide you through the steps to connect to a data source and select the tables.

Check out the [Google support page for the QUERY function](https://support.google.com/docs/answer/3093343?hl=en "Google Support page for the QUERY function") with sample usage, syntax, and examples you can download in a Google sheet.

Link to make a copy of the sheet: [QUERY examples](https://docs.google.com/spreadsheets/d/1815H5TCe91LLT6tD6FmxMHmeJAAkr4o5Q6rNpV6xiFk/copy "examples of using the QUERY function")

#### Real life solution
Analysts can use SQL to pull a specific dataset into a spreadsheet. They can then use the **QUERY** function to create multiple tabs (views) of that dataset. For example, one tab could contain all the sales data for a particular month and another tab could contain all the sales data from a specific region. This solution illustrates how SQL and spreadsheets are used well together.

#### FILTER
Syntax: `FILTER(range, condition1, [condition2, ...])`
e.g. `FILTER(A2:B26, A2:A26 > 5, D2:D26 < 10)`
`FILTER(A2:B10, NOT(ISBLANK(A2:A10)))`

The [**FILTER**](https://support.google.com/docs/answer/3093197?hl=en "FILTER") function is fully internal to a spreadsheet and lets you view only the rows (or columns) in the source data that meet your specified conditions.

The **FILTER** function might run faster than the **QUERY** function. But keep in mind, the **QUERY** function can be combined with other functions for more complex calculations. For example, the **QUERY** function can be used with other functions like **SUM** and **COUNT** to summarize data, but the **FILTER** function can't.

Check out the [Google support page for the FILTER function](https://support.google.com/docs/answer/3093197?hl=en "Google Support page for the FILTER function") with sample usage, syntax, and examples you can download in a Google sheet.

Link to make a copy of the sheet: [FILTER examples](https://docs.google.com/spreadsheets/d/1caULJLQvQuzBnCN7rO9utg0xSKrYms7wM0Ph7A2JXY4/copy "FILTER examples")


---
---

## About the data-analyst hiring process

The application process
Write or adjust your resume
Different types of data analyst jobs

### The data analyst job-application process

#### Starting
The most common way to start is by checking out available jobs.
Job sites, company websites

Once you find a few that you like, do some research to learn more about the companies and the details about the specific positions you'll be applying for. Then you can update your resume or create a new one. You'll want it to be specific and reflect what each company is looking for. But you can definitely have a master resume that you tweak for each position.

It can also help to create a spreadsheet with all of your experiences and accomplishments to help you decide what to include in your resume for each position.

If you don't have any luck with your connections(on Linkedln), you can also reach out to employees of the companies you're interested in. They might be able to give you some insight on the best ways to highlight your skills and experience when applying. And, it's okay if they don't write back. Keep trying!

This is probably a good time to tell you of the most challenging part of a job search: hearing the word "no."

#### First connecting, recruiter
If the company you're applying to is interested, your first point of contact might be a recruiter.

A recruiter might also reach out to you based on their own research based on your professional online profile, that's another reason to keep building and refreshing your online profile.

Recruiters are there to make sure you're a legitimate candidate for the job posted in the description, so when you talk with the recruiter, whether on the phone, online or in person, be professional and personable.
It's natural to feel nervous here. So, it can help to refer back to your resume to wow them with your knowledge of the data analytics industry.
Here's another tip. Using technical terms like "SQL" and "clean data" will show recruiters that you know what you're doing.

#### Next, Hiring manager
The hiring manager's job is to evaluate whether you have the ability to do the work and whether you'd be a good fit for their team.
Your job is to convince them that yes, you do.
A good thing you can do here is use LinkedIn or other professional sites to research the hiring managers or even other analysts who have a similar role to the one you're applying for.
You should also use this opportunity to ask lots of questions to help you figure out if the company's a good fit for you. You can do this when you talk to recruiters too.

#### One more interview and offer
Now if the hiring manager sees you as a fit, it's very possible you'll have at least one more interview. The point of these interviews is to give your future stakeholders and teammates a chance to decide if you're the best candidate for the position.

If all goes well, you'll get an official offer. Usually by phone first and maybe followed by an official letter. At this point, feel free to celebrate.

But even if it's your dream job, make sure it's a competitive offer before you sign. If you're interviewing at other places, you can leverage this to figure out if negotiating for a more competitive offer is possible.

You should also research salaries, benefits, vacation time, and any other factors that are important to you for similar jobs.
If you can show specific research like company x gives y amount more for the same role, **there's usually some room to negotiate your salary, vacation days, or something else**.

Keep in mind, you'll need to find a balance between what you want, what they want to give you, and what's fair. So know your own worth but also understand that the company hiring you has already placed a certain value on your role.

#### Before start the new one
Pause and give yourself at least two weeks before you officially start.

If you're already employed somewhere else during your job search, it's customary and polite to give at least a two-week notice at your old job before starting at the new one.
Plus, it's good to give yourself a break before starting your exciting new adventure.


### Resume
The key here is to be brief. Try to keep everything in one page and each description to just a few bullet points and keep each bullet concise.

About actually building your resume. This is where templates come in. Programs like Microsoft Word or Google Docs and even some job search websites all have templates you can use. A template has placeholders for the information you'll need to enter and its own design elements to make your resume look inviting.

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image45.png)
#### Structure
##### Contact information
Information locates at the top of the document. This includes your name, address, phone number, and email address. It's also great if you can use your first and last name in your email address, like janedoe17@email.com. You should also make sure that your contact information matches the details that you've included on professional websites.

##### Summary
Some resumes begin with the summary, but this is optional. A summary can be helpful if you have experience that is not traditional for a data analyst or if you're making a career transition.

If you decide to include a summary, keep it to one or two sentences that highlight your strengths and how you can help the company you're applying to.

You'll also want to make sure your summary includes positive words about yourself, like dedicated and proactive. You can support those words with data, like the number of years you've worked or the tools you're experienced in like SQL and spreadsheets.

Summary could be sound like these:
"Hard-working customer service representative with over five years of experience"
"Entry-level data analytics professional; recently completed the Google Data Analytics Professional Certificate"

The summary might change a little as you apply for different jobs.

##### Work experience section
Outside of jobs with other companies, you could also include volunteer positions you've had and any freelance or side work you've done. The key here is the way in which you describe these experiences.

##### Qualification
Including any part of your skills and experience that matches a job description will help your resume rise above the competition.

**minimum qualifications or requirements**
Most job descriptions have minimum qualifications or requirements listed. These are the experiences, skills, and education you'll need to be considered for the job. It's important to clearly state them in your resume.

**preferred qualifications**
These aren't required, but every additional qualification you match makes you a more competitive candidate for the role.


It's helpful to describe your skills and qualifications in the same way.
One way to do this is to follow a formula in your descriptions:
Accomplished [X]
As measured by [Y],
By doing [Z].
e.g. "Selected as one of 275 participants nationwide for this 12-month professional development program for high-achieving talent based on leadership potential and academic success"


If you've gained new skills in one of your experiences, be sure to highlight them all and how they helped.
Even if this program is the first time you really thought about data analytics, now that you're equipped with some knowledge, you'll want to use that to your benefit.
e.g.
manage money --> helped the business analyze future earnings
created a budget based on your analysis of previous spending
Even if it was for your own or a friend's small business, it's still data that you've analyzed.

Just reflect on when and how and use it in your resume.

##### Education
After you've added work experience and skills, you should include a section for any education you've completed.
Yes, this course absolutely counts. You can add this course as part of your education, and you can also refer to it in your summary and skill sections.

##### Technical skills
Depending on the format of your resume, you might want to add a section for technical skills you've acquired both in this course and elsewhere.

Besides technical skills like SQL, you could also include language proficiencies in this section. Having some ability in a language other than English can only help your job search.


#### Choose the right format
There’s no "best" format for a resume. Instead, think about what you want to highlight about yourself to potential employers.

For instance, if you have relevant work experience, then pick a format to highlight that. 

If you are transitioning from a different career and don’t yet have relevant work experience, then you may want to pick a format that highlights your technical skills and portfolio projects. Some resume formats include a **Summary** or **Goals** section at the top to help candidates add context to their application, while other resume formats avoid these sections completely and save that space for sections such as **Skills** and **Experience**.

While most resumes have contact information in the same place, it's up to you how you organize that info.

A format that focuses more on skills and qualifications and less on work history is great for people who have gaps in their work history or just starting the career.
If you do want to highlight your work history, feel free to include details of your work experience starting with your most recent job.

If you're editing a resume you already have, you can keep it in the same format and adjust the details. If you're starting a new one or building a resume for the first time, choose the format that makes the most sense for you.

Whatever format you pick, make sure to follow the one-page rule and keep the completed version on just a single page. Resumes are short documents designed to communicate the most pertinent information about yourself to recruiters and hiring managers at a glance. These are different from longer, multi-page Curriculum Vitaes (CVs) that exhaustively list every relevant thing the candidate has ever done.

#### Refine the resume
For data analytics, one of the most important things your resume should do is show that you are a clear communicator.
Being direct and coherent in your resume will go a long way with the hiring managers and recruiters.

##### Summary
While you won't go into too much detail in this section about any of your work experiences, it's a good spot to point out if you're transitioning into a new career role.

One strategy you can use in your summary and throughout your resume is P-A-R, or **PAR statements**. 
PAR stands for Problem, Action, Result. This is a great way to help you write clearly and concisely.
<strike>Was responsible for writing two blogs a month</strike> --> Earned little-known website over 2,000 organic clicks through strategic blogging

Adding PAR statements to your job descriptions or skill section can help with the organization and consistency in your resume.

##### Skills
Data analysts are expected to have strong technical skills and abilities, so effectively highlighting those skills is a crucial part of crafting your resume. Make sure you include any skills and qualifications you've acquired through this course and on your own.
You don't need to be super technical. But talking about your experience with spreadsheets, SQL, Tableau, and R, will enhance your resume and your chances of getting a job.

**Include a spot for programming languages**, and then list SQL and R

You might even add in the top functions, packages or formulas that you're comfortable with in each.
It also makes sense to include skills you've acquired in spreadsheets like pivot tables.


**Get help from the real world**
Reviewing real-world resumes is always a great idea. It can help you get a feel for how others in the industry are representing their experience and skills. You can find resumes on job sites and LinkedIn or even just by searching for "data analyst resume."


###### What skills to add
The skills section on your resume likely only has room for 2-4 bullet points, so be sure to use this space effectively. You might want to prioritize technical skills over soft skills. This is a great chance for you to highlight some of the skills you’ve picked up in these courses, such as:

-   Strong analytical skills
-   Pattern recognition
-   Relational databases and SQL
-   Strong data visualization skills
-   Proficiency with spreadsheets, SQL, R, and Tableau

Many companies use algorithms to screen and filter resumes for keywords. If your resume does not contain the keywords they are searching for, a human may never even read your resume. Reserving at least one bullet point to list specific programs you are familiar with is a great way to make sure your resume makes it past automated keyword screenings and onto the desk of a recruiter or hiring manager.

To create a strong and effective skills section, you should include technical skills and data-related skills. Soft skills and interpersonal skills are very important, but can be emphasized in other parts of your resume.


#### CareerCon
Kaggle’s CareerCon is an annual and free digital event whose aim is to help new data analysts land their first job in the field. Recorded sessions from CareerCon offer tons of firsthand knowledge and expert advice from top data analysts and hiring managers through seminars, coding workshops, and resume advice.

Although the resources offered are aimed at data scientists, the principles and guidelines are still similar to what data analysts can expect on their career journey.

Browse the [full sessions for CareerCon 2019](https://www.youtube.com/playlist?list=PLqFaTIg4myu-npFrYu6cO7h7AI6bkcOlL "full sessions for CareerCon 2019").

Be sure to check out [Portfolio and resume analysis with data science hiring managers](https://www.youtube.com/watch?v=cBbYhhH399c&list=PLqFaTIg4myu-npFrYu6cO7h7AI6bkcOlL&index=8 "This link takes you to a YouTube video with a panel of hiring managers."): A panel of hiring managers discusses what they are seeking in candidates and how they examine different resumes submitted by job seekers like you.

**Highlights**
[How to build a compelling data science portfolio and resume](https://www.youtube.com/watch?v=xrhPjE7wHas&list=PLqFaTIg4myu-dNobDHQZPrD2wH27PthCG "This link takes you to a YouTube video on building a resume and portfolio."): A hiring manager from Quora reviews actual resumes from data science candidates and gives candid feedback on areas of improvement. Learn what to include and omit from your resume and  portfolio as well as formatting tips. This offers a great firsthand look into what hiring managers are seeking when reviewing your resume and portfolio.

[Overview of the Data Science Interview Process](https://www.youtube.com/watch?v=X6orAXDIrds&list=PLqFaTIg4myu-dNobDHQZPrD2wH27PthCG&index=5 "This link takes you to a YouTube video describing the interview process."): Hiring managers at Google discuss typical data science interviews, including the soft and hard skills you will want to prioritize. You will get a better sense of the interview process from both sides, and better prepare yourself for what to expect when interviewing for a data science role.

[Live Breakdown of Common Data Science Interview Questions](https://www.youtube.com/watch?v=aXUsrKPTBvY&list=PLqFaTIg4myu-dNobDHQZPrD2wH27PthCG&index=6 "This link takes you to a YouTube video discussing common interview questions."): Watch a mock interview to see how a Kaggle data scientist answers questions during a data science interview. The video also includes live coding! This video is great preparation for some of the most commonly asked data science interview questions. 

[Am I a Good Fit? Identifying Your Best Data Science Job Opportunities](https://www.youtube.com/watch?v=0W0Zrc-m5r8&list=PLqFaTIg4myu-dNobDHQZPrD2wH27PthCG&index=2 "This link takes you to a YouTube video about finding a job that fits you."): Ever wonder where you will fit in for your future career? This chat with Jessica Kirkpatrick, an intelligence manager, gives you a great breakdown of the different types of categories within the data science job market, the different types of job opportunities you may notice, and how you can frame previous work and skills from another career to fit into the data science job market. 

[Real Stories from a Panel of Successful Career Switchers](https://www.youtube.com/watch?v=iP0Fxg4oqUQ&list=PLqFaTIg4myu-dNobDHQZPrD2wH27PthCG&index=8 "This link takes you to a YouTube video of a panel discussion with career changers."): Are you switching careers? Awesome! Learn from people who were in the same position as you and successfully switched their careers into data science. This panel discusses the different experiences in their careers and life that shifted them into the data science field.


#### Soft skills
**Soft skills**: Non-technical traits and behaviors that relate to how you work.

**Transferable skills**: Skills and qualities that can transfer from one job or industry to another.

##### Communication
Communication: When job descriptions say they want strong communication skills for a data analyst, it usually means they want someone who can speak about what they do to people who aren't as technical or analytical.

In your work history section, you can highlight how your effective communication skills have helped you. You can also refer to specific presentations you've made and the outcomes of those presentations, and you can even include the audience for your presentations, especially if you present it to large groups or people in senior positions.

After listing job details, like the place and length of employment, you might add something like: "Effectively implemented and communicated daily workflow procedures to fellow team members, resulting in a 15% increase in productivity"

##### Problem-solving
Data analysts are problem-solvers. When problems arise in a database or lines of code, data analysts need to be able to find and troubleshoot the problem.
e.g. (written as a **PAR**, or problem, action, results statement)
- Problem: Previously-absent workflow procedures
- Action: Implemented and communicated daily workflow procedures
- Result: 15% increase in productivity

##### Teamwork
Team means not only the data team you're part of, but the whole company as well.

##### Detail-oriented
##### Perseverance

#### Adding skills to your resume
###### professional skills
Common professional skills for entry-level data analysts
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image46.png)
**1. Structured Query Language (SQL):** SQL is considered a basic skill that is pivotal to any entry-level data analyst position. SQL helps you communicate with databases, and more specifically, it is designed to help you retrieve information from databases. Every month, thousands of data analyst jobs posted require SQL, and knowing how to use SQL remains one of the most common job functions of a data analyst. 

**2. Spreadsheets:** Although SQL is popular, 62% of companies still prefer to use spreadsheets for their data insights. When getting your first job as a data analyst, the first version of your database might be in spreadsheet form, which is still a powerful tool for reporting or even presenting data sets. So, it is important for you to be familiar with using spreadsheets for your data insights.

**3. Data visualization tools:** Data visualization tools help to simplify complex data and enable the data to be visually understood. After gathering and analyzing data, data analysts are tasked with presenting their findings and making that information simple to grasp. Common tools that are used in data analysis include Tableau, Microstrategy, Data Studio, Looker, Datarama, Microsoft Power BI, and many more. Among these, Tableau is best known for its ease of use, so it is a must-have for beginner data analysts. Also, studies show that data analysis jobs requiring Tableau are expected to grow about 34.9% over the next decade.

**4**. **R or Python programming:** Since only less than a third of entry-level data analyst positions require knowledge of Python or R, you don’t need to be proficient in programming languages as an entry-level data analyst. But, R or Python are great additions to have as you become more advanced in your career.

##### softs skills
There is more than just data when it comes to being a data analyst—there are plenty of soft skills that can set you apart from other candidates so that potential employers will notice you and know that you have the ability to succeed in this role. Here are some of the most common soft skills you will find in an entry-level data analyst resume.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image47.png)

1. **Presentation skills**

Although gathering and analyzing data is a big part of the job, presenting your findings in a clear and simple way is just as important. You will want to structure your findings in a way that allows your audience to know exactly what conclusions they are supposed to draw. 

2. **Collaboration** 

As a data analyst, you will be asked to work with lots of teams and stakeholders—sometimes internal or external—and your ability to share ideas, insights, and criticisms will be crucial. It is important that you and your team—which might consist of engineers and researchers—do your best to get the job done. 

3. **Communication**

Data analysts must communicate effectively to obtain the data that they need. It is also important that you are able to work and clearly communicate with teams and business leaders in a language that they understand. 

4. **Research** 

As a data analyst, even if you have all of the data at your disposal, you still need to analyze it and draw crucial insights from it. To analyze the data and draw conclusions, you will need to conduct research to stay in-line with industry trends. 

5. **Problem-solving skills** 

Problem-solving is a big part of a data analyst’s job, and you will encounter times when there are errors in databases, code, or even the capturing of data. You will have to adapt and think outside the box to find alternative solutions to these problems.

6. **Adaptability** 

In the ever-changing world of data, you have to be adaptable and flexible. As a data analyst, you will be working across multiple teams with different levels of needs and knowledge, which requires you to adjust to different teams, knowledge levels, and stakeholders.  

7. **Attention to detail** 

A single line of incorrect code can throw everything off, so paying attention to detail is critical for a data analyst. When it comes to understanding and reporting findings, it helps if you focus on the details that matter to your audience.

Here are a few ways that you can add soft skills to your resume:

1.  Analyze your previous work experience and find opportunities to insert a soft skill. For example, if you worked in a restaurant, you could emphasize your communication and adaptability skills that you utilized to effectively function during peak hours. 
2.  Call attention to your problem-solving, presentation, research, and communication skills in previous projects or relevant coursework.
3.  Add a mix of soft and professional skills in the skills or summary section of your resume.


#### Best practices for writing about experience
As you think about how to represent your work experience on your resume effectively, it might be helpful to refer to these best practices:

Focus on your accomplishments first, and explain them using the formula **“Accomplished X, as measured by Y, by doing Z.”**
-   These statements help you communicate the most important things a recruiter or hiring manager is searching for—the impact of your work.
-   Whenever possible, use numbers to explain your accomplishments. For example, “Increased manufacturing productivity by 15% by improving shop floor employee engagement,” is better than “Increased manufacturing productivity.”

Phrase your work experience and duties using **Problem-Action-Result** (PAR) statements.
-   For example, instead of saying “was responsible for two blogs a month,” phrase it as “earned little-known website over 2,000 new clicks through strategic blogging.”

Describe jobs that highlight **transferable skills** (those skills that can transfer from one job or industry to another).
-   This is especially important if you are transitioning from another industry into data analytics. 
-   For example, communication is a skill often used in job descriptions for data analysts, so highlight examples from your work experience that demonstrate your ability to communicate effectively.

Describe jobs that highlight your **soft skills**.
-   These are non-technical traits and behaviors that relate to how you work.
-    Are you detail-oriented? Do you have grit and perseverance? Are you a strong critical thinker? Do you have leadership skills? 
-   For instance, you could give an example of when you demonstrated leadership on the job.
-   Showing is always more effective than telling.

To build a strong experience section, you should include any data-related work history you have or previous jobs that gave you transferable skills. Skills and your educational background should go in different sections.

This is almost always the hardest part of crafting a resume, especially if you are transitioning from a different career field. However, if you take a moment to think deeply about your previous work experience, you’ll likely discover that you can find ways to represent your work experiences in a way that highlights your ability to do things important to data analyst roles, such as thinking critically or making data-driven decisions.

Remember that the goal of a resume is to get you an interview. You may find that you need to brainstorm and carefully edit your resume to effectively summarize your background. In the end, you will have all of your various responsibilities and accomplishments from previous jobs synthesized into a few bullet points. That way, your resume will highlight what potential employers like to know about applicants.
Effective resumes communicate that you are a candidate who understands the needs of the role and you have the skills and experience to warrant an interview. During interviews, you can expect questions about your experience and that’s when you can go into more detail.


## Where does your interest lie?
Job titles and hiring needs might also change. But the opportunities, no matter what they are when you're searching, will be there. Now let's preview some of the many kinds of data analyst jobs that are out there.

The certificate you earn here will be most applicable to **junior or associate data analyst** positions.

New analysts work in a wide range of industries.
- Healthcare analyst
Gather and interpret data from sources like electronic health records and patient surveys; help improve the quality of their care; lower the cost of care and improve patient experience.

- Marketing analyst
complete quantitative and qualitative market analysis; They identify important statistics and interpret and present their findings to help stakeholders understand the data behind their marketing strategies.

- Business intelligence analysts
help companies use data they've collected to increase their efficiency and maximize their profits.
These analysts usually work with large amounts of data to identify trends and generate business insights.

- Financial analysts
Financial analysts also work with lots of data. Use the data to identify and potentially recommend business and investment opportunities.
A junior analyst'll probably start off doing a lot of data gathering and financial modeling as well as spreadsheet maintenance.

Each type we've covered can branch out into other industries as well.
For example, business intelligence analysts can work in health care, government, e-commerce and more.
