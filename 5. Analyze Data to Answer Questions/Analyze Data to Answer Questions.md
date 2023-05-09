You'll start by covering best practices for organizing your data and the different ways you can sort through that data using spreadsheets and SQL.
We'll also spend time learning three important ways to work with data that will boost your analytical skills.
Then we'll talk about saving time. You'll discover tips and tricks that can help you analyze data more efficiently.
Last but not least, we'll work together to identify techniques to help you be as fair and unbiased as possible.

### The analysis process
**Analysis**: The process used to make sense of the data collected.
The goal of analysis is to identify trends and relationships within data so you can accurately answer the question you're asking.

**The 4 phases of analysis:**
1. Organize data
2. Format and adjust data
An analyst sorts and filters data during the format and adjust analysis phase.
3. Get input from others
Getting input involves soliciting information from other sources to inform your decisions.
4. Transform data
Involves identifying relationships and patterns in the data, and making calculations.

## Organizing data to begin analysis
Most of the data you'll use in your analysis will be organized in tables. Tables help you organize similar kinds of data into categories and subject areas that you can focus on as you analyze.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image48.png)
Database organization(the structure of the database) enables analysts to make decisions about which data is relevant to pull for a specific analysis. It also helps them decide which data types and variables are appropriate.

If you're performing your analysis in a spreadsheet, you want to make sure that the columns and rows are effectively organized. You can even hide columns that you won't need for analysis or that show duplicate information. Once you have the data organized and formatted, you'll be ready to sort and filter it to find the data you need.

#### Keeping data organized with sorting and filters
**Sorting** and **filtering** are two ways you can keep things organized when you adjust the data to work with it.

**Sorting** is when you arrange data into a meaningful order to make it easier to understand, analyze, and visualize.
It ranks your data based on a specific metric you choose. You can sort data in spreadsheets, SQL databases (when your dataset is too large for spreadsheets), and tables in documents.
Sorting also helps you to group similar data together by a classification. For movies, you could sort by genre -- like action, drama, sci-fi, or romance.

**Filtering** is used when you are only interested in seeing data that meets a specific criteria while hiding the rest.
Filtering can be done by single variable or multiple variables, depending on the query’s needs.
For example, a filter can help you find errors or outliers so you can fix or flag them before your analysis.
(**Outliers** are data points that are very different from similarly collected data and might not be reliable values.)

> To recap, the easiest way to remember the difference between sorting and filtering is that you can use sort to quickly ***order*** the data, and filter to display **_only_** the data that meets the criteria that you have chosen.
> (Use filtering when you need to reduce the amount of data that is displayed.)
> After you filter data, you can **sort the filtered data**, too.

Sorting in a pivot table: 
Items in the row and column areas of a pivot table are sorted in ascending order by any custom list first.


#### Sort and filter in spreadsheets
In spreadsheets, you can sort data by ascending or descending order using numbers or letters. If cells are labeled with color, you can sort them by color, too.

##### Sort sheet/range
**Sort sheet**: All of the data in a spreadsheet is sorted by the ranking of a specific sorted column-data across rows is kept together.

**Sort range**: Nothing else on the spreadsheet is rearranged besides the specified cells in a column.

steps:
1. Select the column x you want to be used as a criterion during sorting
2. "Data --> Sort sheet by column x"

>**The key takeaway is the difference between sorting a sheet by a column and sorting a range (the values in the column).**

###### Customized sort order
**Customized sort order**: When you sort data in a spreadsheet using multiple conditions.
1. Select the data you want to sort
2. "Data --> Sort range"
3. (Optional: Check "Data has header row")
4. Select the "Sort by" creterion and order
5. (Optional: "Add another sort column" then go to step 4.)


##### Sort by color
1. (Optional: Using like "Format-->Conditional formatting" to fill the color)
2. Select a range of cells.
3. "Data --> Create a filter"  or  just click the filter button in the toolbar
4. click Filter ![Filter](https://lh4.googleusercontent.com/NSe_cMW8YwmX-aH1yLdqXfBSWCm7c2_a3I1yyfDUoXa2PenxrVnKxR-uzTNBZ_duF6x5D4AiRe5Xt4eoFuq4LHXTjEfuX9wZ5sLQD9BpcRbcRtW1Rd8KtXl-fjq01AIPYqrjEFFm "Filter") in the column header
5. **Sort by color:** Choose which text or fill color to filter or sort by. Cells with the color you choose to sort by will move to the top of the range. You can sort by conditional formatting colors, but not alternating colors.
6. To turn the filter off, click "Data --> Remove filter" (will not change the sorted order)

##### Sort function
Sorts the rows of a given array or range by the values in one or more columns.

**Syntax**: `=SORT(range, sort_column, is_ascending, [sort_column2, is_ascending2, ...])`
e.g. `=SORT(A2:D6, 2, TRUE)`

-   `range` - The data to be sorted.
-   `sort_column` - The index of the column in `range` or a range outside of `range` containing the values by which to sort.
-   `is_ascending` - `TRUE` : ascending order;  `FALSE` : descending order.
-   `sort_column2, is_ascending2 ...` **[** OPTIONAL **]** - Additional columns and sort order flags beyond the first, in order of precedence.

> A menu sort function rearranges the data, while the written SORT function changes the existing data.



##### Filter view (Google sheets)
1. "Data --> Filter views --> Create new filter view"
2. Sort and filter the data
3. To close and save your filter view, at the top right, click Close ![Close](https://lh5.googleusercontent.com/hLvx9eaY30CffRGDn5Mmo6XgkNhrF9pkfg4-DnWTUi9ZaUWHt7Ojmh47IugVoGyED1k5fyU8Pj9-FnbH02vdx9PfUIC4R4OUVOU97b7K0WIOXrHMQHlsLQ130HTUn_mykIEfv8Ax "Close").

To delete or duplicate a filter view, in top right, click Options ![Settings](https://lh5.googleusercontent.com/fWREtTzikDvHNVKPmb4SGDT3X0qAS8w3_kQRMJluw__Q41jsNEVwocE0AQWds3y2qeTTd3lZzTYIyCYQbGNHoeTmzR1QFJ4iGfplqdIrXZjEl_PULy6e3kNhi3TBdbZbVPpgk53R "Settings") ![and then](https://lh4.googleusercontent.com/Cr6I_zMwmDCgu6ZTAPsigJ9QagsLg5Xl4FQE18GgNYlIQNahzO7pW7AsixcbfUCS0nX-IdkTGTrCEUPlrh9TEOKGCSkacxo9Oc6TFdTfSyvoV898Hrv8rou1wr_w2HftCxe6PQg- "and then") **Delete** or **Duplicate**.


##### FILTER function
Returns a filtered version of the source range, returning only rows or columns that meet the specified conditions.

**Syntax:** `=FILTER(range, condition1, [condition2, ...])`
e.g. `=FILTER(A2:B26, A2:A26 > 5, D2:D26 < 10)`
`=FILTER(A2:C6, ISBLANK(C2:C6))`
`=FILTER(A2:C5, {TRUE; TRUE; FALSE; TRUE})`  (row  2,3,4,5 select or not booleans. Highest priority among conditions)

`condition` arguments must have exactly the same length as `range`.

**UNIQUE:**
Returns unique rows in the provided source range, discarding duplicates. (Only `UNIQUE` keeps the rows' original number unchanged, others shrinks)
**Syntax**: `=UNIQUE(range)`


##### Sorting and filtering in Excel
Excel offers **Smallest to Largest** and **Largest to Smallest** sorting when you are working with numbers.
Similar to the SORT function in Google Sheets, Excel includes custom sort capabilities that are available from the menu. After you select the data range, click the **Sort & Filter** button to select the criteria for sorting. You can even sort by the data in rows instead of by the data in columns if you select **Sort left to right** under Options. (**Sort top to bottom** is the default setting to sort the data in columns.)

Excel also has [SORT](https://support.microsoft.com/en-us/office/sort-function-22f63bd0-ccc8-492f-953d-c20e8e44b86c "This link takes you to the Micosoft Support page for the SORT function in Excel."), [SORTBY](https://support.microsoft.com/en-us/office/sortby-function-cd2d7a62-1b93-435c-b561-d6a35134f28f "This link takes you to the Microsoft Support page for the SORTBY function in Excel."), and [FILTER](https://support.microsoft.com/en-us/office/filter-function-f4f7cb66-82eb-4767-8f7c-4877ad80c759 "This link takes you to the Microsoft Support page for the FILTER function in Excel.") functions.
Resources:
-   [Sort data in a range or table](https://support.microsoft.com/en-us/office/sort-data-in-a-range-or-table-62d0b95d-2a90-4610-a6ae-2e545c4a4654 "This link takes you to the Microsoft Support page for sorting data in Excel.") (Microsoft Support): instructions and video to perform sorting in 11 different use cases 
-   [Excel training: sort and filter data](https://support.microsoft.com/en-us/office/video-sort-data-in-a-range-or-table-ffb9fcb0-b9cb-48bf-a15c-8bec9fd3a472#ID0EAABAAA=Transcript "This link takes you to the Microsoft Support videos for sorting and filtering data in Excel.") (Microsoft Support): sorting and filtering videos with transcripts
-   [Excel: sorting data](https://www.youtube.com/watch?v=Ep5q1cUhQas "This link takes you to a YouTube video on how to use Excel's Sort & Filter and Data menu options."): video of how to use the Sort & Filter and Data menu options for sorting


#### Sorting queries in SQL
You can use the ORDER BY clause to sort results returned in a query.

e.g. figure out which 10 counties had the lowest birth count for 2016-2018:
```SQL
SELECT 
  * 
FROM 
  `bigquery-public-data.sdoh_cdc_wonder_natality.county_natality` 
WHERE
    Year >= "2016-01-01" AND Year <= "2018-12-31"
ORDER BY 
    Births 
LIMIT
  10
```

> You may have noticed that the query did not specify whether it should be sorted **ASC** (ascending) or **DESC** (descending). When this is not specified, SQL defaults to sorting by ascending order.


**IF**
Syntax: `IF(expr, true_result, else_result)`
[Conditional expressions in Standard SQL](https://cloud.google.com/bigquery/docs/reference/standard-sql/conditional_expressions#if)

**e.g.**
This query gives you the average `temperature`, `wind_speed` and `precipitation` for stations `La Guardia` (725030) and `JFK` (744860) for every year on 12th June post 2010, in descending order of date and ascending order of station ID (stn).
```SQL
SELECT
  -- Create a timestamp from the date components.
  stn,
  TIMESTAMP(CONCAT(year,"-",mo,"-",da)) AS timestamp,
  -- Replace numerical null values with actual null
  AVG(
  IF
    (temp=9999.9,
      NULL,
      temp)
  ) AS temperature,
  AVG(
  IF
    (wdsp="999.9",
      NULL,
      CAST(wdsp AS Float64))
  ) AS wind_speed,
  AVG(
  IF
    (prcp=99.99,
      0,
      prcp)
  ) AS precipitation
FROM
  `bigquery-public-data.noaa_gsod.gsod20*`
WHERE
  CAST(YEAR AS INT64) > 2010
  AND CAST(MO AS INT64) = 6
  AND CAST(DA AS INT64) = 12
  AND (stn="725030" OR  -- La Guardia
    stn="744860")    -- JFK
GROUP BY
  stn,
  timestamp
ORDER BY
  timestamp DESC,
  stn ASC
```
Result:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image49.png)

---
**e.g.**
This query gives you the number of complaints `num_complaints` for all individual complaint types `complaint_type` created every year and ordered in descending order of count of complaints `num_complaints`.
```SQL
SELECT
  EXTRACT(YEAR
  FROM
    created_date) AS year,
  complaint_type,
  COUNT(1) AS num_complaints
FROM
  `bigquery-public-data.new_york.311_service_requests`
GROUP BY
  year,
  complaint_type
ORDER BY
  num_complaints DESC
```
Result:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image50.png)

---

e.g. Save query results into a new table
1. select your qwiklabs project and click on the `View action` icon (three dots) then select **Create Dataset**.
2. Click **COMPOSE NEW QUERY**, along the top of the Query editor, click **More** > **Query settings**.
3. Select "Set a destination table for query results" and enter table name,  check "Allow large results" --> Save
4. Run the query. The results are now saved in the dataset you created.
5. (Optional: Navigate back to **More** > **Query settings** and, in the _Destination field_ select **Save query results in a temporary table**. This removes the demos dataset as a destination for future queries.)



## Formatting and adjusting data
### Convert and format data
Sometimes, you need to convert data when you're working with spreadsheets. That might mean changing numbers into dates, strings, percentages, or even currency.

If the spreadsheet cast column value types as strings instead of dates. etc., it might sort them alphabetically.

**Incorrectly formatted data can:**
- Lead to mistakes
- Take time to fix
- Affect stakeholder's decision-making

#### Data conversion scenarios
##### String to date
Both Excel and Google sheets store dates as integer numbers (values differ 1). And only Google sheets support negative numbers to express dates before 1899-12-30.
The same goes for time units -- they are merely decimals.
So a date paired with time is kept as an integer with decimal places:
e.g.   31,528.058 is April 26, 1986, 1:23 AM

[**How to convert text to date in Excel**](https://www.ablebits.com/office-addins-blog/2015/03/26/excel-convert-text-date/#:~:text=Excel%20DATEVALUE%20function%20%2D%20change%20text,Excel%20recognizes%20as%20a%20date.&text=So%2C%20the%20formula%20to%20convert,stored%20as%20a%20text%20string. "This link takes you to a blog on how to convert text to a date in Microsoft Excel.")

| Source         | Example            | Formula                                       | Formula result | Formatted date     |
| -------------- | ------------------ | --------------------------------------------- | -------------- | ------------------ |
| 8-digit number | 20160310           | `=DATE(LEFT(A4,4), MID(A4,5,2), RIGHT(A4,2))` | 2016-03-10     |                    |
| text string    | 1-Mar              | `=DATEVALUE(A4)`                              | 44256          | 2021-03-01         |
| text string    | 03/01/2015 3:00 PM | `=VALUE(A4)`                                  | 42064.625      | 1-Mar-2015 3:00 PM |
| text string    | 03-01-2015         | `=A4+0` `=A4*1`  `=A4/1`  `=--A4`             | 42064          | 3/1/2015           |

(p.s. DATEVALUE and VALUE not work well on mac EXCEL)

[**Google Sheets: Change date format**](https://www.ablebits.com/office-addins-blog/2019/08/13/google-sheets-change-date-format/ "This link takes you to a blog on how to change to a date format in Google Sheets.")

1. (Optional: "File --> Spread settings --> General --> Locale" to apply the date formatting to the entire spreadsheet.)
2. Change date format:
- Default Google Sheets date format
Select all cells you'd like to format, then "Format --> Number --> Date/Time/etc."
- Custom date formats
"Format --> Numer --> More formats --> More date and time formates"
- QUERY function
e.g. `=QUERY(A1:C7,"select * format B 'd-mmm-yy (ddd)'")`
- convert date to text
Syntax: `=TEXT(number,format)`  e.g. `=TEXT("8/17/2019","YYYY-MM-DD")`
- **DATE**, **DATEVALUE**, **VALUE** function
Same usage as EXCEL

##### String to numbers
[**How to convert text to number in Excel**](https://www.ablebits.com/office-addins-blog/2018/07/18/excel-convert-text-to-number/ "This link takes you to a blog on how to convert text to a number in Excel.")
- Formula `=VALUE(A2)`
- Mathematic operations  `=A2+0` `=A2*1` `=A2/1`
- Convert to number with error checking
Select all the cells containing numbers formatted as text --> Click the warning sign and select **Convert to Number**.
- Convert text into number by changing the cell format
Select the cells with text-formatted numbers --> On the _Home_ tab, in the _Number_ group, choose **General** or **Number** from the _Number Format_ drop-down list.
- Paste Special
Copy a blank cell --> Select the cells you want to convert to numbers, right-click, and then click **Paste Special** --> In the _Paste Special_ dialog box, select **Values** in the _Paste_ section and **Add** in the _Operation_ section.
- Text to Columns
Select the cells --> Switch to the _Data_ tab, _Data Tools_ group, and click the **Text to Columns** button --> In step 1 of the _Convert Text to Columns Wizard_, select **Delimited** under _Original data type_, and click **Finish**.

[**How to convert text to numbers in Google Sheets**](https://productivityspot.com/convert-text-to-numbers-google-sheets/ "This link takes you to instructions to convert text to a number in Google Sheets.")
- `=VALUE(A2)`   <-- To get pure numeric number, only use this one!
- `=REGEXREPLACE(A2, "[.]", ",")`
Syntax: `=REGEXREPLACE(text, regular_expression, replacement)`
- `=TO_PURE_NUMBER(A2)`
- `=SPLIT(REGEXREPLACE(A1, "[^\d]+", "|"), "|")`
- `=SPLIT(A1,CONCATENATE(SPLIT(A1,".0123456789")))`


##### Combining columns
[**Convert text from two or more cells**](https://support.microsoft.com/en-us/office/combine-text-from-two-or-more-cells-into-one-cell-81ba0946-ce78-42ed-b3c3-21340eb164a6 "This link takes you to a Microsoft Support page to merge text in multiple cells in Excel.")
- `=A2&" "&B2`
- `=CONCAT(A2, " ", B2)`

[**How to split or combine cells in Google Sheets**](https://www.techrepublic.com/article/how-to-split-or-combine-text-cells-with-google-sheets/ "This link takes you to an article with instructions to split or combine text in cells in Google Sheets.")
- `=A2&" "&B2`
- `=CONCATENATE(A6," ",B6," ",C6)`

**Split:**
- "Data --> Split text to columns"
- `=SPLIT(A2,",")`

##### Number to percentage
[**Format numbers as percentages**](https://support.microsoft.com/en-us/office/format-numbers-as-percentages-de49167b-d603-4450-bcaa-31fba6c7b6b4 "This link takes you to a Microsoft Support page for formatting numbers as percentages.")
Click **Percent Style** ![Button image](https://support.content.office.net/en-us/media/6130b268-ad5b-457f-b429-7656dc1689ed.gif) or  in the **Category** list, click **Percentage**.
- Formatting cells that already contain numbers:  2 --> 200%
- Formatting empty cells, then input
    - Numbers>=1:       10 --> 10%
    - Numbers<1:          0.5 --> 50%

[**TO_PERCENT**](https://support.google.com/docs/answer/3094284?hl=en "This link takes you to the help page for the TO_PERCENT function in Google Sheets.")
Syntax: `=TO_PERCENT(value)`
e.g. `=TO_PERCENT(1)` --> 100%,   `=TO_PERCENT(0.25)` --> 25%

> See also [`TO_TEXT`](https://support.google.com/docs/answer/3094285?hl=en), [`TO_PERCENT`](https://support.google.com/docs/answer/3094284), [`TO_DOLLARS`](https://support.google.com/docs/answer/3094241), [`TO_DATE`](https://support.google.com/docs/answer/3094239)

##### Others
**Change number to currency format:**
1. Select the columns you want to change format
2. Hit the currency shortcut **$** , or "Format --> Number --> Currency"

**Changing the unit of measurement in a spreadsheet from Fahrenheit to Celsius:**
Syntax: `=CONVERT(value, start_unit, end_unit)`
e.g. `=CONVERT(5.1, "g", "kg")` `=CONVERT(35.7, "in^2", "m^2")`
`=CONVERT(32, "C", "F")` `=CONVERT(A1, A2, A3)`

1. In an empty cell of a new column, put `=CONVERT(B2, "F", "C")`
2. Double click the ＋ icon to fill down
(p.s. When adding data to tables using a formula, go back and paste the data in as values afterwards. That way they're locked in and avoid confusing.)
3. Copy the column
4. Right click the target column, "Paste special --> Paste values only"

##### Additional resources
If you find yourself needing to convert other types of data, you can find resources on [**Microsoft Support**](https://support.microsoft.com/ "This link takes you to the Microsoft Support home page.") for Excel or [**Google Docs Editor Help**](https://support.google.com/docs/?hl=en#topic=1382883 "This link takes you to the Google Help Center home page.") for Google Sheets.

**Pro tip:** Keep in mind that you may have lots of columns of data that require different formats. Consistency is key, and best practice is to make sure an entire column has the same format.


### Data validation(function)
Allows you to control what can and can't be entered in your worksheet.

**Three use of Data validation in spreadsheets**
- Add dropdown lists with predetermined options
    1. Select the column and "Data --> Data validation"
    2. Set Criteria to "List of items" and type in using ',' as delimiter like "text1, text2, text3"
- Create custom checkboxes
    1. Select the column and "Data --> Data validation"
    2. Set Criteria to "Checkbox", check "Use custom cell values"
    3. Put in checked and unchecked option names, like "Approved", "Not Approved"
(You need to use developer tab to insert checkbox in the Excel)
- Protect structured data and formulas
    - In "Data --> Data validation --> On invalid data", select "Reject input"


### Conditional formatting
**Conditional formatting**: A spreadsheet tool that changes how cells appear when values meet specific conditions.

**Combing conditional formatting with data validation**
1. Create checkboxes using data validation
2. "Format --> Conditional formatting"
3. Select the range or type in like "C:C"
4. Choose "Text is exactly", and put in the check boxes text and its corresponding format

**Combine data validation and conditional formatting to track upcoming deadlines**
1. Select the column you want users only input date, "Data --> Data validation", set creteria to "Date --> is valid date" and reject invalid input
2. "Format --> Conditonal formatting" and select the column
3. Set "Format rules" to "Date is after" , set "today/yesterday/exact date"


### Transforming data in SQL
In this reading, you will go over the conversions that can be done using the **CAST** function. There are also more specialized functions like **COERCION** to work with big numbers, and **UNIX_DATE** to work with dates. **UNIX_DATE** returns the number of days that have passed since January 1, 1970 and is used to compare and work with dates across multiple time zones. You will likely use **CAST** most often.

#### CAST
**CAST** is an American National Standards Institute (ANSI) function used in lots of programming languages, including BigQuery.
**Syntax**: `CAST(expression AS typename)`

##### examples
- Converting a number to a string
```SQL
SELECT CAST(MyCount AS STRING) FROM MyTable
```

- Converting a string to a number
```SQL
SELECT CAST(MyString AS INT) FROM MyTable
```

- Converting a date to a string
```SQL
SELECT CAST(MyDate AS STRING) FROM MyTable
```

- Converting a date to a datetime
(Datetime values have the format of YYYY-MM-DD hh: mm: ss format)
```SQL
SELECT CAST(MyCount AS DATETIME) FROM MyTable
```

##### typenames
**In BigQuery:**
INT64, NUMERIC, BIGNUMERIC, FLOAT64, BOOL, STRING, BYTES, DATE, DATETIME, TIME, TIMESTAMP, ARRAY, STRUCT

**In SQL Server:**
bigint, int, smallint, tinyint, bit, decimal, numeric, money, smallmoney, float, real, datetime, smalldatetime, char, varchar, text, nchar, nvarchar, ntext, binary, varbinary, or image


##### SAFE_CAST
The **SAFE_CAST** function returns a value of Null instead of an error when a query fails.
The syntax for **SAFE_CAST** is the same as for **CAST**. Simply substitute the function directly in your queries.

##### Common conversions
The following table summarizes some of the more common conversions made with the **CAST** function. Refer to [Conversion Rules in Standard SQL](https://cloud.google.com/bigquery/docs/reference/standard-sql/conversion_rules "This link takes you to the Google Cloud BigQuery documentation on SQL.") for a full list of functions and associated rules.

| Starting with    | CAST function can convert to:                                |
| :--------------- | :----------------------------------------------------------- |
| Numeric (number) | - Integer - Numeric (number) - Big number - Floating integer - String |
| String           | - Boolean - Integer - Numeric (number) - Big number - Floating integer - String - Bytes - Date - Date time - Time - Timestamp |
| Date             | - String - Date - Date time - Timestamp                      |


##### More information
-   [CAST and CONVERT](https://docs.microsoft.com/en-us/sql/t-sql/functions/cast-and-convert-transact-sql?view=sql-server-ver15 "This link takes you to Microsoft SQL Server documentation for CAST and CONVERT."): SQL Server reference documentation
-   [MySQL CAST Functions and Operators](https://dev.mysql.com/doc/refman/8.0/en/cast-functions.html "This link takes you to MySQL reference documentation for CAST functions."): MySQL reference documentation
-   [How to: SQL Type Casting](https://www.blendo.co/blog/how-to-sql-type-casting/ "This link takes you to a blog on type casting in SQL."): Blog about type casting that has links to other SQL short guides


### Merging and multiple sources
#### CONCAT / CONCATENATE
**CONCATENATE**: A function that joins together two or more text strings. (In Spreadsheet)
**Text string**: A group of characters within a cell, most often composed of letters.

In **SQL**, **CONCAT** can be used to combine strings from *multiple* tables in order to create a create new string.

> CONCAT(str1, str2) has the same effect with CONCATENATE(str1, str2)
> But CONCATENATE can accept multiple parameters
> (p.s. SQL only has CONCAT, which can accept multiple inputs)

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image51.png)


#### Strings in spreadsheets
LEN, LEFT, RIGHT, FIND (in SQL)
Find is case-sensitive, so it’s necessary to input the substring exactly how it appears.

#### Manipulating strings in SQL
A **string** is a set of characters that helps to declare the texts in programming languages such as SQL.
**CONCAT**, is commonly used to manipulate various information about the characters. Below are the CONCAT function and its variations:

| Function      | Usage                                                                                            | Example                                                                                                                                      |
|:------------- |:------------------------------------------------------------------------------------------------ |:-------------------------------------------------------------------------------------------------------------------------------------------- |
| CONCAT        | A function that adds strings together to create new text strings that can be used as unique keys | CONCAT (‘Google’, ‘.com’);                                                                                                                   |
| CONCAT_WS     | A function that adds two or more strings together with a separator                               | CONCAT_WS (‘ . ’, ‘www’, ‘google’, ‘com’) *The separator (being the period) gets input before and after Google when you run the SQL function |
| $+$ | Adds two or more strings together using the + operator                                           | ‘Google’ + ‘.com’                                                                                                                            |


W3 Schools is an excellent resource for interactive SQL learning:
[SQL functions](https://www.w3schools.com/sql/sql_ref_sqlserver.asp "This link takes you to the W3 Schools SQL reference page for SQL functions."): This is a comprehensive list of functions to get you started.
[SQL Keywords](https://www.w3schools.com/sql/sql_ref_keywords.asp "This link takes you to the W3 Schools reference page for SQL keywords."): This is a helpful SQL keywords reference to bookmark as you increase your knowledge of SQL.


#### Get support during analysis
Calculate number of hours between times in spreadsheets?
--> Problem: Add 1 minus the start time to the formula that's being used for the multi-day trip; then try to apply to another trip that happened in the same day.

Ask others --> `=IF(end>start, end-start, 1-start+end`
Ask Google --> `=MOD(end-start, 1)`

The best data analysts know that finding answers to their problems online can be empowering and give them new knowledge for the future.

**Best practices for searching online:**
- Thinking skills
Practicing the thinking skills we've learned in this program. You've learned about different kinds of thinking skills and how to practice them in your data analysis work. From analytical, to mathematical, to structured thinking. This helps build your mental model, or your thought process, and the way you approach a problem.
- Data analytics terms
Using the right terms. Knowing how to frame data analytics questions with the same language other analysts are using will help you get more search results, and it'll help you understand what other analysts are saying.
<strike>Four characters in a column</strike> --> Left string query SQL
- Basic knowledge of tools
When an online resource is walking you through a new function and a tool that you've used before, you'll know how those tools work.

**Mental model**: Your thought process and the way you approach a problem.


##### Stack Overflow
You can read questions on the Stack Overflow [Home page](https://stackoverflow.com/) and [Questions](https://stackoverflow.com/questions) page.
The Questions page provides different categories of questions for you to choose. Some examples include the "Newest" and "Active" categories.
Tags will help you find questions. On the left pane, click on **Tags**. On the Tags page, type in a tag name and then press **Enter**.
Use the **Search** bar at the top of the web page to search for different keywords and questions.
If you would like to view only questions that have a certain tag, include the tag name in brackets with your search. For example, if you want to only find questions that have the tag “SQL,” then type **[SQL]** in the search field, along with your keywords or question.
`[SQL] How to use CONCAT`

To learn more about searching, read the [instructions about how to search](https://stackoverflow.com/help/searching). For a quick guide on syntax structures, check out this list of [search types and search syntax](https://stackoverflow.com/search).

**Learn how to write questions on Stack Overflow**
When asking a question on Stack Overflow, you should ask only specific questions, not general questions. Don’t use Stack Overflow for questions that have opinion-based answers.
It is a best practice to first search the Stack Overflow website in case someone has asked the same question already.
Write clear and concise questions in complete sentences.
![Screenshot of stack overflow homepage. There are options to input Title, Body, and Tags](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/SyYWOs-KQS2mFjrPinEtgg_0e9121f550394af2b1503f042d030d36_DAC5M2L4SR1_StackOverflow.png?expiry=1625011200000&hmac=NR1avOsuwLULJaigQAgo_TsTXwR_F9Tw3R9huA21tkY)
The form for asking a question has three sections: **Title**, **Body**, and **Tags**.

-   **Title**: This is where you ask your question. 
-   **Body**: Summarize your problem and include expected and actual results. Include any error codes. If you think that inserting code into the Body section will help, press **ctrl** + **K** on your keyboard at the same time. Then type your code.
-   **Tags**: Tags include specific keywords, like program names. They help other people find your question. Note: You can add up to five tags.


#### Advanced spreadsheet tips and tricks
##### Google Sheets

-   [**Keyboard shortcuts for Google Sheets:**](https://support.google.com/docs/answer/181110 "This link takes you to the Google Help Center page for keyboard shortcuts in Google Sheets.") This is a great resource for quickly learning a range of keyboard shortcuts that can make regular tasks quicker and easier, like navigating your spreadsheet or accessing formulas and functions. This list contains shortcuts for the desktop and mobile versions of Google Sheets so that you can apply them to your work no matter what device you are using. 
-   [**L​ist of Google Sheets functions**](https://support.google.com/docs/table/25273?hl=en "This link takes you to the Google Help Center page listing the functions in Google Sheets.")**:** This is a comprehensive list of the Google Sheets functions and syntax. Each function is listed with a link to learn more.
-   [**2​0 Google Sheets Formulas You Must Know:**](https://automate.io/blog/google-spreadsheet-formulas/ "This link takes you to a blog with 20 useful formulas in Google Sheets.") This blog article summarizes and describes 20 of the most useful Google Sheets formulas.
-   [**18 Google Sheets Formula Tips and Techniques:**](https://www.benlcollins.com/spreadsheets/google-sheets-formulas-techniques/ "This link takes you to tips and techniques for working with forumulas in Google Sheets.") These are tips for using Google Sheets shortcuts when working with formulas.

##### Excel

-   [**Keyboard shortcuts in Excel****:**](https://support.microsoft.com/en-us/office/keyboard-shortcuts-in-excel-1798d9d5-842a-42b8-9c99-9b7213f0040f?ui=en-US&rs=en-US&ad=US "This link takes you to the Microsoft Support page for keyboard shortcuts in Excel.") Earlier in this list, you were provided with a resource for keyboard shortcuts in Google Sheets. Similarly, this resource provides a list of keyboard shortcuts in Excel that will make performing regular spreadsheet tasks more efficient. This includes keyboard shortcuts for both desktop and mobile versions of Excel, so you can apply them no matter what platform you are working on. 
-   [**222 Excel shortcuts****:**](https://exceljet.net/keyboard-shortcuts "This link takes you to a list of Excel keyboard shortcuts.") A compilation of shortcuts includes links to more detailed explanations about how to use them. This is a great way to quickly reference keyboard shortcuts. The list has been organized by functionality, so you can go directly to the sections that are most useful to you. 

-   [**List of spreadsheet functions:**](https://exceljet.net/excel-functions "This link takes you to an online list of Excel functions.") This is a comprehensive list of Excel spreadsheet functions with links to more detailed explanations. This is a useful resource to save so that you can reference it often; that way, you’ll have access to functions and examples that you can apply to your work. 

-   [**List of spreadsheet formulas:**](https://exceljet.net/formulas "This link takes you to an online list of Excel formulas.") Similar to the previous resource, this comprehensive list of Excel spreadsheet formulas with links to more detailed explanations and can be saved and referenced any time you need to check out a formula for your analysis. 

-   [**Essential Excel Skills for Analyzing Data****:**](https://learntocodewith.me/posts/excel-skills/ "This link takes you to a blog article about advanced Excel skills.") This blog post includes more advanced functionalities of some spreadsheet tools that you have previously learned about, like pivot tables and conditional formatting. These skills have been identified as particularly useful for data analysis. Each section includes a how-to video that will take you through the process of using these functions step-by-step, so that you can apply them to your own analysis. 

-   [**Advanced Spreadsheet Skills:**](https://www.slideshare.net/markjhonoxillo/advanced-spreadsheet-skills) Mark Jhon C. Oxillo’s presentation starts with a basic overview of spreadsheet but also includes advanced functions and exercises to help you apply formulas to actual data in Excel. This is a great way to review some basic concepts and practice the skills you have been learning so far.




#### When to use which tool
**R**: A programming language frequently used for statistical analysis, visualization, and other data analysis.

If you find yourself stuck on a problem, it can be a good idea to take a step back and reconsider how you're approaching a task.
Do you have too much data for a single spreadsheet? Switch to SQL.
Are you spending more time debugging queries than actually analyzing data? Maybe you should consider R.

A quick search can be useful.



## Aggregating data for analysis
**Aggregation**: Collecting or gathering many separate pieces into a whole.
e.g. Milky Way galaxy is an aggregation of stars, dust, and gases.

**Data aggregation**: The process of gathering data from multiple sources in order to combine it into a single summarized collection.
In data analytics, a summarized collection, or summary, describes identifying the data you need and gathering it all together in one place.

For example, let's say you have a cabinet full of different puzzles. One day, a shelf breaks, and all the boxes topple over, scattering the puzzle pieces everywhere. To get each puzzle organized again, you need to identify the pieces that correspond to each particular puzzle, gather them together and put them back into their correct boxes. Only then can you work with these pieces and create a complete picture.
- Puzzle pieces = data
- Organization = aggregation
- Pile of pieces = summary
- Putting the pieces together = gaining insights

**Data aggregation helps data analyst:**
- Identify trends
- Make comparisons
- Gain insights

Data can also be aggregated over a given time period to provide statistics such as:
- Averages
- Minimums
- Maximums
- Sums

Functions help make data aggregation possible.

**Subquery**: (also called an inner or nested query) A query within another query.

### VLOOKUP in spreadsheets
**VLOOKUP (Vertical Lookup)**: A function that searches for a certain value in a column to return a corresponding piece of information.

Syntax: `=VLOOKUP(search_key, range, index, [is_sorted])`
- **search_key**: The value to search for. e.g. 42, "Cats", or I24.
- **range**: The range to consider for the search. The first column in the range is searched for the key specified in search_key.
- **index**: The column index of the value to be returned, where the first column in range is numbered 1.
- **is_sorted**: Indicates whether the column to be searched (the first column of the specified range) is sorted. TRUE by default.
It’s recommended to set is_sorted to FALSE. If set to FALSE, an exact match is returned.
If is_sorted is TRUE or omitted, the nearest match (less than or equal to the search key) is returned.

> Warning: When data is not in a consistent format or a format that the spreadsheet application recognizes, VLOOKUP won't know what to do with that data, and it will return an error. (e.g. dates formatted as numbers, or numbers represented as text strings instead of numeric values)

#### When do you need to use VLOOKUP?
Two common reasons to use VLOOKUP are:
-   Populating data in a spreadsheet
VLOOKUP can connect your two sheets together, on a matching column, to populate one single sheet.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image52.png)
-   Merging data from one spreadsheet with data in another
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image53.png)
Remember to **Paste special** > **Values only** to store the data.




#### Preparation
Clean data is the fundation that everything else is built on.

**converting text to numeric values:**
- Format menu to select a type of number
- use the VALUE function `=VALUE(A2)`
**VALUE**: A function that converts a text string that represents a number to a numerical value.

**Removing leading or trailing or middle spaces:**
`=TRIM(A2)`

**Remove duplicates**
A tool that automatically searches for and eliminates duplicate entries from a spreadsheet.
If there are duplicate rows in the VLOOKUP search, it will return only the first match it finds.
"DATA --> Remove duplicates"

#### Troubleshooting
Recognize the limitations of VLOOKUP and fix some of the most common problems.

##### Troubleshooting questions
- How should I prioritize these issues?
- In a single sentence, what's the issue l'm facing?
- What resources can help me solve the problem?
- How can I stop this problem from happening in the future?

##### Factors that may effect VLOOPUP results
- VLOOKUP only returns the first match it finds.
- VLOOKUP can only return a value from the data to the right. It can't look left.
(Workaround: copying and pasting a column to the left of the data they want to look at.)
- Absolute reference: A reference that is locked so that rows and columns won't change when copied.
- Something else that can throw off your VLOOKUP results are version control issues.
(e.g. A user inserts a new column)
Solution:
    1. Lock the spreadsheet "Data-->Protected sheets and ranges" --> Choose range or sheet
    2. **MATCH**: A function used to locate the position of a specific lookup value.
- Exact and approximate matching
TRUE tells VLOOKUP to look for approximate matches; FALSE tells VLOOKUP to look for exact matches.
(When TRUE: VLOOKUP starts at the top of a specified range and searches downward vertically in each cell to find the right value. It stops searching when it finds any value that's greater than or equal to the lookup value.)

##### \#N/A
\#N/A indicates that a matching value can't be returned as a result of the VLOOKUP. In other words, VLOOKUP cannot find out the value.
You can use the **IFNA** function to replace the \#N/A error with something more descriptive, like "Does not exist."
`=IFNA(VLOOKUP(44,D:E,2,false),"Does not exist")`


#### Create a summary table
You can create a summary table, or pivot table. If you are using Excel, please follow the [documentation for how to manually create a Pivot Table in Excel](https://support.microsoft.com/en-us/office/create-a-pivottable-to-analyze-worksheet-data-a9a84538-bfe9-40a9-a8e9-f99134456576).
1. Select the data table including the headers.
2. Click on the **Data** tab, then select **Pivot Table.**
3. A pop-up window will display. Click on **New Sheet,** then click the **Create** button.
4. On the side of the new sheet, the **Pivot table editor** will display.
    1. Click the Add button for *Rows*. Select Names.
    2. Click the Add button for *Values*. Select Pay Rate.
    3. Click the Add button for *Values* again. Select Total Pay.
5. (Convert the cells in the **Sum of Total Pay** column to currency)

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image54.png)


#### Helpful VLOOKUP reminders
-   TRUE means an approximate match, FALSE means an exact match on the search key. If the data used for the search key is sorted, TRUE can be used.
-   You want the column that matches the search key in a VLOOKUP formula to be on the left side of the data. VLOOKUP only looks at data to the right after a match is found. In other words, the index for VLOOKUP indicates columns to the right only. This may require you to move columns around before you use VLOOKUP.
-   After you have populated data with the VLOOKUP formula, you may copy and paste the data as values only to remove the formulas so you can manipulate the data again.


#### VLOOKUP resources for Microsoft Excel
-   [How to use VLOOKUP in Excel](https://support.microsoft.com/en-us/office/vlookup-function-0bbc8083-26fe-4963-8ab8-93a18ad188a1 "This link takes you to the Microsoft Support page for VLOOKUP."): This tutorial includes a video to help you get a general understanding of how the VLOOKUP function works in Excel, as well as practical examples to look through.
-   [VLOOKUP in Excel tutorial](https://www.youtube.com/watch?v=d3BYVQ6xIE4 "This link takes you to an Excel VLOOKUP tutorial on YouTube."): Follow along in this video lesson and learn how to write a VLOOKUP formula in Excel and master time-saving useful tips and tricks.
-   [23 things you should know about VLOOKUP in Excel](https://exceljet.net/things-you-should-know-about-vlookup "This link takes you to an article about VLOOKUP use in Excel."): Explore this list of 23 VLOOKUP facts as well as challenges you might run into, and start to learn how to master them.
-   [How to use Excel's VLOOKUP function](https://edu.gcfglobal.org/en/excel-tips/how-to-use-excels-vlookup-function/1/ "This link takes you to an article about applying VLOOKUP in searches."): This article shares a specific example around how to apply VLOOKUP in your searches.
-   [VLOOKUP in Excel vs Google Sheets](https://infoinspired.com/sheets-vs-excel-formula/vlookup-formula-in-excel-and-google-sheets/ "This link takes you to an article comparing VLOOKUP use in Excel and Google Sheets. "): This guide offers a VLOOKUP comparison of Excel and Google Sheets.


### JOINS in SQL
How to use JOIN in SQL to aggregate data in databases.

**JOIN**: A SQL clause that is used to combine rows from two or more tables based on a related column.
(A SQL version of VLOOKUP)

#### Common JOINs
- Inner
**`INNER JOIN`**: A function that returns records with matching values in both tables.
INNER is _optional_ in this SQL query because it is the default as well as the most commonly used `JOIN` operation.
- Left
**`LEFT JOIN`**: A function that will return all the records from the left table and only the matching records from the right table.
(The table mentioned first is left, and the table mentioned second is right)
(Or `LEFT OUTER JOIN`)
- Right
**`RIGHT JOIN`**: A function that will return all records from the right table and only the matching records from the left.
(Practically speaking, `RIGHT JOIN` is rarely used. Most people simply switch the tables and stick with `LEFT JOIN`.)
(Or `RIGHT OUTER JOIN`)
- Outer
**`FULL OUTER JOIN`**: A function that combines RIGHT and LEFT JOIN to return all matching records in both tables.
If there's records in one table without a match, it'll create a record with NULL values for the other table.
(Remember that this can potentially be a large data pull as a result)
(Or `FULL JOIN`)

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image55.png)

They are the same:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image56.png)

Primary keys reference columns in which each value is unique.
Foreign keys are primary keys in other tables.
JOINs use these keys to identify relationships and corresponding values.

> In other words, other values in the primary key's table, are inserted into foreign key's table, just like VLOOKUP.
> Foreign INNER JOIN Primary: Find matches pairwisely, and insert left values from both
> Foreign LEFT JOIN Primary: INNER JOIN + No matches records on left with null
> Foreign RIGHT JOIN Primary: INNER JOIN + No matches records on the right with null
> Foreign FULL OUTER JOIN Primary: (INNER JOIN + No matches from both)
>
> (Does it mean the condition must contains one Primary key, one Foreign key?
> No. For a match with id=1, if *table_1* has 2 rows with id=1, and *table_2* has 3 rows with id=1, then join will create $2\times 3 = 6$ new rows in the query result.)

> **Note:** Foreign keys don’t always have the same names across tables. If you’re ever unsure if the columns are the same, you can always double-check. You can query the column from each table and confirm that they contain the same kinds of information.

e.g.
```SQL
SELECT
    employee.name AS employee_name,
    employee.role AS employee_role,
    department.name AS department_name
FROM
    employees
INNER JOIN  --- LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN
    departments
ON  employees.department_id = departments.department_id
```

`INNER JOIN`:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image57.png)

`LEFT JOIN`:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image58.png)

`RIGHT JOIN`:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image59.png)

`FULL OUTER JOIN`:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image60.png)

#### The importance of aliases
**Aliases** are used in SQL queries to create temporary names for a column or table. 
Instead of having to write out the long table/column name, you can use a meaningful nickname that you decide.


**Basic syntax for aliasing**
**Aliasing**: When you temporarily name a table or column in your query to make it easier to read and write.
Aliasing is the process of using aliases. In SQL queries, aliases are implemented by making use of the `AS` command.

```SQL
SELECT column_name AS alias_name
FROM table_name;

SELECT column_name(s)
FROM table_name AS alias_name;
```

> **Alternate syntax for aliases**
> If using `AS` produces an error, using the alternate syntax for aliasing:
> `FROM table_name alias_name`
> `SELECT column_name alias_name`
> The key takeaway is that queries can run with or without using AS for aliasing, but using AS has the benefit of making queries more readable.

e.g.
```SQL
SELECT 
    edu.country_name,
    summary.country_code,
    edu.value
FROM 
    `bigquery-public-data.world_bank_intl_education.international_education` AS edu
INNER JOIN 
    `bigquery-public-data.world_bank_intl_education.country_summary` AS summary
ON edu.country_code = summary.country_code
```


**For more information**
-   [**SQL Aliases**](https://www.w3schools.com/sql/sql_alias.asp "This link takes you to the W3 Schools tutorial on SQL aliases.")**:** This tutorial on aliasing is a really useful resource to have when you start practicing writing queries and aliasing tables on your own. It also demonstrates how aliasing works with real tables. 
-   [**SQL Alias**](https://www.sqltutorial.org/sql-alias/ "This link takes you to SQL Tutorial's SQL Alias tutorial.")**:** This detailed introduction to aliasing includes multiple examples. This is another great resource to reference if you need more examples. 
-   [**Using Column Aliasing**](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.5&docsetId=sqlproc&docsetTarget=p0aymxwsvbt5wcn1lncugwjtf758.htm&locale=en "This link takes you to SAS documentation that describes column aliasing.")**:** This is a guide that focuses on column aliasing specifically. Generally, you will be aliasing entire tables, but if you find yourself needing to alias just a column, this is a great resource to have bookmarked.


#### For more information
-   [**SQL JOINs**](https://www.w3schools.com/sql/sql_join.asp "This link takes you to a W3 Schools tutorial on SQL JOINs.")**:** This is a good basic explanation of JOINs with examples. If you need a quick reminder of what the different JOINs do, this is a great resource to bookmark and come back to later.  
-   [**Database JOINs - Introduction to JOIN Types and Concepts**](https://www.essentialsql.com/introduction-database-joins/ "This link takes you to a series of articles about database JOINs.")**:** This is a really thorough introduction to JOINs. Not only does this article explain what JOINs are and how to use them, but it also explains the various scenarios in more detail of when and why you would use the different JOINs. This is a great resource if you are interested in learning more about the logic behind JOINing.
-   [**SQL JOIN Types Explained in Visuals**](https://dataschool.com/how-to-teach-people-sql/sql-join-types-explained-visually/ "This link takes you to an article that visually explains SQL JOIN types.")**:** This resource has a visual representation of the different JOINs. This is a really useful way to think about JOINs if you are a visual learner, and it can be a really useful way to remember the different JOINs. 
-   [**SQL JOINs: Bringing Data Together One Join at a Time**](https://towardsdatascience.com/sql-join-8212e3eb9fde "This link takes you to a Toward Data Science article about SQL JOINs.")**:** Not only does this resource have a detailed explanation of JOINs with examples, but it also provides example data that you can use to follow along with their step-by-step guide. This is a useful way to practice JOINs with some real data. 
-   [**SQL JOIN:**](https://www.dofactory.com/sql/join "This link takes you to an SQL tutorial on SQL JOIN.") This is another resource that provides a clear explanation of JOINs and uses examples to demonstrate how they work. The examples also combine JOINs with aliasing. This is a great opportunity to see how JOINs can be combined with other SQL concepts that you have been learning about in this course.


### COUNT
**COUNT (in spreadsheets)**: Can be used to count the total number of numerical values within a specific range in spreadsheets.

**COUNT (in SQL)**: A query that returns the number of rows in a specified range.

**COUNT DISTINCT**: A query that only returns the distinct values in a specified range.
COUNT DISTINCT doesn't count repeating values.

You'll use COUNT and COUNT DISTINCT any time you want to answer questions about "how many".

```SQL
SELECT 
    # orders.*,
    # warehouse.warehouse_alias,
    warehouse.state,
    COUNT(DISTINCT orders.order_id) as num_orders
FROM 
    `ggcloud-200201.warehouse_orders`.Warehouse AS warehouse
JOIN
    `ggcloud-200201.warehouse_orders`.Orders AS orders
ON  warehouse.warehouse_id = orders.warehouse_id
GROUP BY warehouse.state

--

COUNT(DISTINCT warehouse.state) as num_state
```


### Subquery
**Subquery**: A SQL query that is nested inside a larger query.
Image it as matryoshka, Russian nesting dolls.
Because the logic of your outer query relies on the inner query, you can get more done with a single query.

The statement containing the subquery can also be called the ***outer query*** or the ***outer select***. This makes the subquery the ***inner query*** or ***inner select***.
The inner query executes first so that the results can be passed on to the outer query to use. Keep in mind that the innermost query executes first.

Subqueries can also be nested inside all sorts of other queries. Usually you'll find subqueries nested in FROM or WHERE clauses.

e.g.
Nested in `SELECT`
```SQL
SELECT 
    station_id,
    num_bikes_available,
    (SELECT 
        AVG(num_bikes_available)
    FROM bigquery-public-data.new_york.citibike_stations) AS avg_num_bikes_available
FROM
    bigquery-public-data.new_york.citibike_stations
```

Nested in `FROM`
```SQL
SELECT 
    station_id,
    name,
    number_of_riders AS number_of_riders_starting_at_station
FROM
    (SELECT 
        start_station_id,
        COUNT(*) AS number_of_riders
    FROM
        bigquery-public-data.new_york.citibike_trips
    GROUP BY 
        start_station_id
    )
    AS station_num_trips
    
    INNER JOIN
    bigquery-public-data.new_york.citibike_stations
    ON station_id = start_station_id
    
    ORDER BY number_of_riders DESC
```

Nested in `WHERE`
```SQL
SELECT 
    station_id,
    name
FROM 
    bigquery-public-data.new_york.citibike_stations
WHERE 
    station_id IN 
    (
        SELECT 
            start_station_id
        FROM 
            bigquery-public-data.new_york.citibike_trips
        WHERE 
            -- gender = 'female'
            usertype = 'Subscriber'
    )
```

**There are a few rules that subqueries must follow:**
-   Subqueries must be enclosed within parentheses
-   A subquery can have only one column specified in the SELECT clause. But if you want a subquery to compare multiple columns, those columns must be selected in the main query.
-   Subqueries that return more than one row can only be used with multiple value operators, such as the IN operator which allows you to specify multiple values in a WHERE clause.
-   A subquery can’t be nested in a SET command. The SET command is used with UPDATE to specify which columns (and values) are to be updated in a table.


#### Aggregate data with subqueries
When you want to use `GROUP BY` first and then use `WHERE` on that output, you'll need a different function. This is where HAVING comes in.

**HAVING**: Allows you to add a filter to your query instead of the underlying table that can only be used with aggregate functions.
The `HAVING` clause was added to SQL because the `WHERE` keyword could not be used with aggregate functions, like `COUNT`.

> The **WHERE** clause is used to make filters on your table, like a filter for certain date ranges or specific countries. The **HAVING** clause is used to make filters on your aggregations and has to be paired with a GROUP BY clause.

> It is a good idea to try minimizing your usage of the **HAVING** clause whenever possible because of resources. But, if you do need to use **HAVING**, try using temporary tables.

**CASE**: Returns records with your conditions by allowing you to include if/then statements in your query.

```SQL
SELECT 
    Warehouse.warehouse_id,
    CONCAT(Warehouse.state, ": ", Warehouse.warehouse_alias) AS warehosue_name,
    COUNT(Orders.order_id) AS number_of_orders,
    (
        SELECT 
            COUNT(*)
        FROM 
            warehouse_orders.Orders AS Orders
    )AS total_orders,
    CASE 
        WHEN COUNT(Orders.order_id)/(SELECT COUNT(*) FROM warehouse_orders.Orders Orders) <= 0.20
        THEN "fulfilled 0-20% of Orders"
        WHEN COUNT(Orders.order_id)/(SELECT COUNT(*) FROM warehouse_orders.Orders Orders) > 0.20
        AND COUNT(Orders.order_id)/(SELECT COUNT(*) FROM warehouse_orders.Orders Orders) <= 0.60
        THEN "fulfilled 21-60% of Orders"
        ELSE "fulfilled more than 60% of Orders"
    END AS fulfillment_summary
FROM 
    warehouse_orders.Warehouse AS Warehouse
LEFT JOIN
    warehouse_orders.Orders AS Orders
ON  Warehouse.warehouse_id = Orders.warehouse_id
GROUP BY 
    Warehouse.warehouse_id,
    warehosue_name
HAVING 
    COUNT(Orders.order_id) > 0
```

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image61.png)

Clauses like HAVING and CASE, paired with subqueries, will help you build more and more complex queries.

-   [**SQL HAVING**](http://www-db.deis.unibo.it/courses/TW/DOCS/w3schools/sql/sql_having.asp.html "This link takes you to the W3 Schools tutorial on the SQL HAVING clause.")**:** This is an overview of the HAVING clause, including what it is and a tutorial on how and when it works.
-   [**SQL CASE**](https://www.w3schools.com/sql/sql_case.asp "This link takes you to a W3 Schools tutorial on the SQL CASE statement.")**:** Explore the usage of the CASE statement and examples of how it works.
-   [**SQL IF**](https://www.w3schools.com/sql/func_mysql_if.asp "This link takes you to a W3 Schools tutorial on the SQL IF function.")**:** This is a tutorial of the IF function and offers examples that you can practice with.
-   [**SQL COUNT**](http://www-db.deis.unibo.it/courses/TW/DOCS/w3schools/sql/sql_func_count.asp.html "This link takes you to a W3 Schools tutorial on the SQL COUNT function.")**:** The COUNT function is just as important as all the rest, and this tutorial offers multiple examples to review.

**Additional resources:**
-   [**SQL subqueries:**](https://www.w3resource.com/sql/subqueries/understanding-sql-subqueries.php "This link takes you to a w3r resource for SQL subqueries.") This detailed introduction includes the definition of a subquery, its purpose in SQL, when and how to use it, and what the results will be
-   [**Writing subqueries in SQL**](https://mode.com/sql-tutorial/sql-sub-queries/ "This link takes you to a Mode SQL tutorial on writing subqueries.")**:** Explore the basics of subqueries in this interactive tutorial, including examples and practice problems that you can work through


### Data calculations
- Formulas for basic calculations
- Conditional formulas that use the IF function
- The SUMPRODUCT function
- Pivot tables to organize calculations
- Queries and calculations in SQL
- Temporary tables in SQL

**Summary table**: A table used to summarize statistical information about data.

#### Common calculation formulas
To calculate the sum/min/max/average of a range of cells from A2 through F2, the correct syntax is
`=SUM(A2:F2)`.
`=MIN(A2:F2)`
`=MAX(A2:F2)`
`=AVERAGE(A2:F2)`

##### COUNTIF
Syntax: `=COUNTIF(range, criterion)`
Returns a conditional count across a range.
e.g. `=COUNTIF(A1:A10, ">20")`
- **range**: The range that is tested against criterion.
- **criterion**: The pattern or test to apply to range.

**COUNTIFS**
Syntax: `=COUNTIFS(criteria_range1, criterion1, [criteria_range2, criterion2, ...])`
e.g. `=COUNTIFS(A1:A9, "Coffee", C1:C9, "12/15/2020")`

##### SUMIF
Syntax: `=SUMIF(range, criterion, [sum_range])`
Returns a conditional sum across a range.
e.g. `=SUMIF(A1:A10, ">20", B1:B10)`  `=SUMIF(A1:A9,"Fuel",B1:B9)`

- **range**: The range which is tested against criterion.
- **criterion**: The pattern or test to apply to range.
- sum_range[optional]: The range to be summed, if different from range.

**SUMIFS**
Syntax: `=SUMIFS(sum_range, criteria_range1, criterion1, [criteria_range2, criterion2, ...])`
e.g. `=SUMIFS(B1:B9, A1:A9, "Fuel", C1:C9, "12/15/2020")`


##### AVERAGEIF
Syntax: `=AVERAGEIF(criteria_range, criterion, [average_range])`
Returns the average of a range depending on criteria.
e.g. `=AVERAGEIF(A1:A10, ">20", B1:B10)`
- **criteria_range**: The range to check against criterion.
- **criterion**: The pattern or test to apply to criteria_range.
- **average_range**[optional]: The range to average. If not included, criteria_range is used for the average instead.

**AVERAGEIFS**

##### MAXIFS
`=MAXIFS(range, criteria_range1, criterion1, [criteria_range2, …], [criterion2, …])`
Returns the maximum value in a filtered range of cells, filtered by a set of criteria applied to additional ranges.

- **range**: The range of cells from which the maximum will be determined.
- **criteria_range1**: The range of cells over which to evaluate criterion1.
- **criterion1**: The pattern or test to apply to criteria_range1, such that each cell that evaluates to TRUE will be included in the filtered set.

> No MAXIF, only MAXIFS
> **Note for Microsoft Excel users:** MAXIFS can only be used with an Office 365 subscription on Excel 2016 or newer.


##### For more information
-   [**How to use the Excel IFS function**](https://exceljet.net/excel-functions/excel-ifs-function "This link takes you to a description of the Excel IFS function."): This resource includes an explanation and example of the IFS function in Excel. This is a great reference if you are interested in learning more about IFS. The example is a useful way to understand this function and how it can be used. 
-   [**VLOOKUP in Excel with multiple criteria**](https://exceljet.net/formula/vlookup-with-multiple-criteria "This link takes you to a description of how to use VLOOKUP in Excel with multiple criteria."): Similar to the previous resource, this resource goes into more detail about how to use VLOOKUP with multiple criteria. Being able to apply VLOOKUP with multiple criteria will be a useful skill, so check out this resource for more guidance on how you can start using it on your own spreadsheet data.  
-   [**INDEX and MATCH in Excel with multiple criteria**](https://exceljet.net/formula/index-and-match-with-multiple-criteria "This link takes you to a description of how to use Excel's INDEX and MATCH functions with multiple criteria.")**:** This resource explains how to use the INDEX and MATCH functions with multiple criteria. It also includes an example which helps demonstrate how these functions work with multiple criteria and actual data. 
-   [**Using IF with AND, OR, and NOT functions in Excel**](https://support.microsoft.com/en-us/office/using-if-with-and-or-and-not-functions-d895f58c-b36c-419e-b1f2-5c193a236d97 "This link takes you to a Microsoft Support page for using the IF function with the AND, OR, and NOT functions.")**:** This resource combines IF with AND, OR, and NOT functions to create more complex functions. By combining these functions, you can perform your tasks more efficiently and cover more criteria at once.


#### Composite functions
> Stealing with pride.


Fellow team members, message board posts, online searches, I've used all of these resources for ideas. With pride! Of course, I always cite my sources when I do.

**SUMPRODUCT**: A function that multiplies arrays and returns the sum of those products.
(对位相乘再相加)
**Array**: A collection of values in cells.
Calculates the sum of the products of corresponding entries in two equal-sized arrays or ranges.
Syntax: `=SUMPRODUCT(array1, [array2, …])`
e.g. `=SUMPRODUCT(A2:C5, D2:F5, G2:I5)`

- **array1**: The first array or range whose entries will be multiplied with corresponding entries in the second such array or range.
- **array2**… - [optional] repeatable: The second array or range whose entries will be multiplied with corresponding entries in the first such array or range.


**Profit margin**: A percentage that indicates how many cents of profit has been generated for each dollar of sale.


#### Pivot table
Pivot tables let you view data in multiple ways to find insights and trends.

> The data set used in the example is `Movie Data Starter Project.xlsx`
> **Analysis steps**
> - Find out how much revenue was generated each year
> - Build a pivot table to show the revenue per year
> - Find the average revenue per movie
> - Check our findings for some possible trends
> 
> **In action:**
> 1. Adding the pivot table in a new sheet, keeping the data range from cell A1 to cell N509
> (Adding as a new sheet helps keep our calculations together in one place and separate from the rest of the data.)
> 2. Sort the rows by release date to find the revenue for each year.
> 3. Right-click in one of the cells in the Release Date column to create a pivot date group, and group by year
> 4. Click Add in Values, and add Box Office Revenue
> (The ***Summarize By*** drop-down menu changes the function applied to the values. The SUM function is the default function, but there are other options, such as COUNT. SUM shows the sum of the revenue, and COUNT shows the number of movies generated each year)
> 5. Add a filter and in condition set Less than 10,000,000.00 to filter the whole table
> 6. **Add a Calculated field**: "Values Add --> Calculated field". Use the column's original name and a function, like `=SUM('Box Office Revenue ($)')/COUNT('Box Office Revenue ($)')`


**Calculated field**: A new field within a pivot table that carries out certain calculations based on the values of other fields.
If the column is filtered, the Calculated field is based on the filtered values.
The calculated field is added as an additional row or column in a pivot table.

**Using your pivot table for analysis**
##### Perform calculations

| Microsoft Excel                                              | Google Sheets                                                |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [**Calculate values in a pivot table**](https://support.microsoft.com/en-us/office/calculate-values-in-a-pivottable-11f41417-da80-435c-a5c6-b0185e59da77)**:** Microsoft Support’s introduction to calculations in Excel pivot tables. This is a useful starting point if you are learning how to perform calculations with pivot tables specifically in Excel. | [**Create and use pivot tables**](https://support.google.com/docs/answer/1272900?co=GENIE.Platform%3DDesktop&hl=en)**:** This guide is focused on using pivot tables in Google Sheets and it provides instructions for creating calculated fields. This is a quick how-to guide you can save and reference as a quick reminder on how to add calculated fields. |
| [**Pivot table calculated field example**](https://exceljet.net/pivot-table/pivot-table-calculated-field-example)**:** This resource includes a detailed example of a pivot table being used for calculations. This step-by-step process demonstrates how calculated fields work, and provides you with some idea of how they can be used for analysis. | [**All about calculated field in pivot tables**](https://infoinspired.com/google-docs/spreadsheet/all-about-calculated-field-in-pivot-table-in-google-sheets/)**:** This is a comprehensive guide to calculated fields for Google Sheets. If you are working with Sheets and are interested in learning more about pivot tables, this is a great resource. |
| [**Pivot table calculated fields: step-by-step tutorial**](https://powerspreadsheets.com/pivottable-calculated-fields/)**:** This tutorial for creating your own calculated fields in pivot tables is a really useful resource to save and bookmark for when you start to apply calculated fields to your own spreadsheets. | [**Pivot tables in Google Sheets**](https://www.benlcollins.com/spreadsheets/pivot-tables-google-sheets/)**:** This beginner’s guide covers the basics of pivot tables and calculated fields in Google Sheets and uses examples and how-to videos to help demonstrate these concepts. |

##### Sort your data

| Microsoft Excel                                              | Google Sheets                                                |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [**Sort data in a pivot table or PivotChart**](https://support.microsoft.com/en-us/office/sort-data-in-a-pivottable-or-pivotchart-e41f7107-b92d-44ef-861f-24430830450a)**:** This is a Microsoft Support how-to guide to sorting data in pivot tables. This is a useful reference if you are working with Excel and are interested in checking out how filtering will appear in Excel specifically. | [**Customize a pivot table**](https://support.google.com/docs/answer/7572895?co=GENIE.Platform%3DDesktop&hl=en)**:** This guide from Google Support focuses on sorting pivot tables in Google Sheets. This is a useful, quick reference if you are working on sorting data in Sheets and need a step-by-step guide. |
| [**Pivot tables- Sorting data**](https://www.tutorialspoint.com/excel_pivot_tables/excel_pivot_tables_sorting_data.htm)**:** This tutorial for sorting data in pivot tables includes an example with real data that demonstrates how sorting in Excel pivot tables works. This example is a great way to experience the entire process from start to finish. | [**How to sort pivot table columns**](https://infoinspired.com/google-docs/spreadsheet/pivot-table-columns-in-custom-order-in-google-sheets/)**:** This detailed guide uses real data to demonstrate how the sorting process for Google Sheet pivot tables will work. This is a great resource if you need a slightly more detailed guide with screenshots of the actual Sheets environment. |
| [**How to sort a pivot table by value**](https://exceljet.net/lessons/how-to-sort-a-pivot-table-by-value)**:** This source uses an example to explain sorting by value in pivot tables. It includes a video, which is a useful guide if you need a demonstration of the process. | [**Pivot table ascending and descending order**](https://medium.com/actiondesk/pivot-table-ascending-descending-order-in-google-sheets-and-excel-1-minute-ultimate-beginners-8f9f4c560492)**:** This 1-minute beginner’s guide is a great way to brush up on sorting in pivot tables if you are interested in a quick refresher. |

##### Filter your data

| Microsoft Excel                                              | Google Sheets                                                |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [**Filter data in a pivot table**](https://support.microsoft.com/en-us/office/filter-data-in-a-pivottable-cc1ed287-3a97-4e95-b377-ddfafe79fa8f)**:** This resource from the Microsoft Support page provides an explanation of filtering data in pivot tables in Excel. If you are working in Excel spreadsheets, this is a great resource to have bookmarked for quick reference. | [**Customize a pivot table**](https://support.google.com/docs/answer/7572895?co=GENIE.Platform%3DDesktop&hl=en)**:** This is the Google Support page on filtering pivot table data. This is a useful resource if you are working with pivot tables in Google Sheets and need a quick resource to review the process. |
| [**How to filter Excel pivot table data**](https://www.dummies.com/software/microsoft-office/excel/how-to-filter-excel-pivot-table-data/)**:** This how-to guide for filtering data in pivot tables demonstrates the filtering process in an Excel spreadsheet with data and includes tips and reminders for when you start using these tools on your own. | [**Filter multiple values in pivot table**](https://infoinspired.com/google-docs/spreadsheet/filter-multiple-values-in-pivot-table-sheets/)**:** This guide includes details about how to filter for multiple values in Google Sheet pivot tables. This resource expands some of the functionality that you have already learned and sets you up to create more complex filters in Google Sheets. |

##### Format your data

| Microsoft Excel                                              | Google Sheets                                                |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [**Design the layout and format of a PivotTable**](https://support.microsoft.com/en-us/office/design-the-layout-and-format-of-a-pivottable-a9600265-95bf-4900-868e-641133c05a80): This Microsoft  Support article describes how to change the format of the PivotTable by applying a predefined style, banded rows, and conditional formatting. | [**Create and edit pivot tables**](https://support.google.com/a/users/answer/9308944#group_data_in_a_pivot_table): This Help Center article provides information about how to edit a pivot table to change its style, and group data. |



#### SQL calculations
**Oerator**: A symbol that names the type of operation or calculation to be performed in a formula.

The syntax of a query is its structure.
It should include all the specific details of the data you want to pull into a new table where those details should be placed.

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image62.png)

**Modulo**: An operator $(\%)$ that returns the remainder when one number is divided by another.

In SQL, functions like SUM,AVG are considered aggregate functions because they perform a calculation on one or more values and return a single value.

**Underscores**: Lines used to underline words and connect text characters.
Using underscores instead of spaces helps avoid potential issues while keeping the names readable.

```SQL
SELECT 
    Date,
    Region,
    Total_bags,
    Small_bags,
    (Small_bags/Total_bags)*100 AS Small_bags_percent
    -- SAFE_DIVIDE(Small_bags, Total_bags)*100 AS Small_bags_percent
FROM 
    avocado_data.avocado_prices
WHERE 
    Total_bags != 0  -- or using <>
```

##### Calculations with other statements
Sometimes you'll need to group data before completing calculations:
    - GROUP BY
    - ORDER BY
These commands are usually paired with aggregate functions like SUM or COUNT.

**GROUP BY**: A command that groups rows that have the same values from a table into summary rows.

**Extract command**: Lets us pull one part of a given date to use.
Returns a value that corresponds to the specified `part` from a supplied `datetime_expression`.
Syntax: `EXTRACT(part FROM datetime_expression)`
Allowed `part` values are:
`MICROSECOND`, `MILLISECOND`, `SECOND`, `MINUTE`, `HOUR`, `DAYOFWEEK`, `DAY`, `DAYOFYEAR`, `WEEK`, `WEEK(<WEEKDAY>)`, `ISOWEEK`, `MONTH`, `QUARTER`, `YEAR`, `ISOYEAR`, `DATE`, `TIME`
[Expressions, functions, and operators in Standard SQL](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators#extract_2)

```SQL
SELECT 
    EXTRACT (YEAR FROM STARTTIME) as year,
    COUNT(*) AS number_of_riders
FROM
    `bigquery-public-data.new_york_citibike.citibike_trips`
GROUP BY 
    year
ORDER BY 
    year DESC
```

#### Data-validation process
**Data validation process**: Checking and rechecking the quality of your data so that it is complete, accurate, secure and consistent.
The data validation process is a form of data cleaning.
You should always do data validation no matter what analysis tool you're using. (SQL or Spreadsheet)

##### Types of data validation
The first five are validation types associated with the data (type, range, constraint, consistency, and structure) and the sixth type focuses on the validation of application code used to accept data from user input.

| Types            | Purpose                                                                                                                                                                              | Example                                                                                                                                                              | Limitations                                                                                                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Data type        | Check that the data matches the data type defined for a field.                                                                                                                       | Data values for elementary school grades 1-12 must be a numeric data type.                                                                                           | The data value 13 would pass the data type validation but would be an unacceptable value. For this case, data range validation is also needed.                                                                       |
| Data range       | Check that the data falls within an acceptable range of values defined for the field.                                                                                                | Data values for elementary school grades should be values between 1 and 12.                                                                                          | The data value 11.5 would be in the data range and would also pass as a numeric data type. But, it would be unacceptable because there aren't half grades. For this case, data constraint validation is also needed. |
| Data constraints | Check that the data meets certain conditions or criteria for a field. This includes the type of data entered as well as other attributes of the field, such as number of characters. | Content constraint: Data values for grades 1-12 must be whole numbers.                                                                                               | The data value 13 is a whole number and would pass the content constraint validation. But, it would be unacceptable since 13 isn’t an elementary school grade. For this case, data range validation is also needed.  |
| Data consistency | Check that the data makes sense in the context of other related data.                                                                                                                | Data values for product shipping dates can’t be earlier than product production dates.                                                                               | Data might be consistent but still incorrect or inaccurate. A shipping date could be later than a production date and still be wrong.                                                                                |
| Data structure   | Check that the data follows or conforms to a set structure.                                                                                                                          | Web pages must follow a prescribed structure to be displayed properly.                                                                                               | A data structure might be correct with the data still incorrect or inaccurate. Content on a web page could be displayed properly and still contain the wrong information.                                            |
| Code validation  | Check that the application code systematically performs any of the previously mentioned validations during user data input.                                                          | Common problems discovered during code validation include: more than one data type allowed, data range checking not done or ending of text strings not well defined. | Code validation might not validate all possible variations with data input.                                                                                                                                          |



#### Temporary tables
**Temporary table**: A database table that is created and exists temporarily on a database server.
**Temporary tables,** or temp tables, store subsets of data from standard data tables for a certain period of time. When you end your SQL database session, they are automatically deleted.

**Features:**
-   They are automatically deleted from the database when you end your SQL session.
-   They can be used as a holding area for storing values if you are making a series of calculations. This is sometimes referred to as **pre-processing** of the data.
-   They can collect the results of multiple, separate queries. This is sometimes referred to as data **staging**. Staging is useful if you need to perform a query on the collected data or merge the collected data.
-   They can store a filtered subset of the database. You don’t need to select and filter the data each time you work with it. In addition, using fewer SQL commands helps to keep your data clean.

Using a temporary table will let you run several queries about this data without having to keep filtering it.

The **WITH** clause is a type of temporary table that you can query from multiple times.

```SQL
WITH longest_used_bike AS (
    SELECT 
        bikeid,
        SUM(duration_minutes) AS trip_duration
    FROM 
        bigquery-public-data.austin_bikeshare.bikeshare_trips
    GROUP BY 
        bikeid
    ORDER BY 
        trip_duration DESC
    LIMIT 1
)
```
> If you run it now, it’ll return an error because you haven’t written any queries yet.

Type two # signs to begin a comment and describe the purpose of your query. Then write your query:
```SQL
## find station at which the longest-used bike leaves most often
SELECT 
    start_station_id,
    COUNT(*) AS trip_ct
FROM 
    longest_used_bike AS longest
INNER JOIN 
    bigquery-public-data.austin_bikeshare.bikeshare_trips AS trips
ON
    longest.bikeid = trips.bikeid
GROUP BY 
    trips.start_station_id
ORDER BY
    trip_ct DESC 
LIMIT 1
```

or

```SQL
## find station at which the longest-used bike leaves most often
SELECT 
    start_station_id,
    COUNT(*) AS trip_ct
FROM 
    bigquery-public-data.austin_bikeshare.bikeshare_trips
WHERE 
    bikeid IN (SELECT bikeid FROM longest_used_bike)
GROUP BY 
    start_station_id
ORDER BY
    trip_ct DESC 
LIMIT 1
```

##### Other types of temp tables
There are also other ways to create a temp table. Instead of using the **WITH** clause, you can use the **SELECT INTO** or the **CREATE TABLE** clauses.

**`SELECT INTO` in other databases (not supported in BigQuery):**
The **SELECT INTO** clause copies data from one table into a new table, but doesn’t add the new table to the database. It’s useful if you want to make a copy of a table with a specific condition.
> BigQuery doesn't currently recognize the SELECT INTO command.
> It's supported in most relational database management systems or RDBMSs:

```SQL
SELECT
    *
INTO
    AfricaSales
FROM
    GlobalSales
WHERE
    Region = "Africa"
```

**User-managed temporary table creation:**
The **CREATE TABLE** clause is a good option when several people need to access the same temp table. This statement adds the table into the database.
```SQL
CREATE TABLE AfricaSales AS
(
    SELECT *
    FROM GlobalSales
    WHERE Region = "Africa"
)

DROP TABLE AfricaSales
```
After you have completed working with your temporary table, you can remove the table from the database using the **DROP TABLE** clause. Some databases use **CREATE TEMP TABLE** instead of **CREATE TABLE**, but the general syntax is the same.

> A `CREATE TABLE` statement provides access for anyone to use the temporary table. The `SELECT INTO` statement is better suited for one person.

How to create temporary tables:
- WITH clauses
- SELECT INTO statements
- CREATE TABLE statements
- CREATE TEMP TABLE statements


##### Best practices when working with temporary tables
-   **Global vs. local temporary tables:** Global temporary tables are made available to all database users and are deleted when all connections that use them have closed. Local temporary tables are made available only to the user whose query or connection established the temporary table. You will most likely be working with local temporary tables. If you have created a local temporary table and are the only person using it, you can drop the temporary table after you are done using it.

-   **Dropping temporary tables after use:** Dropping a temporary table is a little different from deleting a temporary table. Dropping a temporary table not only removes the information contained in the rows of the table, but removes the table variable definitions (columns) themselves. Deleting a temporary table removes the rows of the table but leaves the table definition and columns ready to be used again. Although local temporary tables are dropped after you end your SQL session, it may not happen immediately. If a lot of processing is happening in the database, dropping your temporary tables after using them is a good practice to keep the database running smoothly.

**For more information**
-   [BigQuery Documentation for Temporary Tables](https://cloud.google.com/bigquery/docs/reference/standard-sql/data-definition-language#temporary_tables "This link takes you to the BigQuery documentation for temporary tables.")**:** Documentation has the syntax to create temporary tables in BigQuery
-   [How to use temporary tables via WITH in Google BigQuery](https://www.pascallandau.com/bigquery-snippets/use-temporary-tables-with-named-subquery/?utm_source=blog&utm_medium=rss&utm_campaign=development-feed)**:** Article describes how to use **WITH** 
-   [Introduction to Temporary Tables in SQL Server](https://codingsight.com/introduction-to-temporary-tables-in-sql-server/ "This link takes you to an article that describes how to create a temporary table in SQL Server.")**:** Article describes how to use **SELECT INTO** and **CREATE TABLE** 
-   [SQL Server Temporary Tables](https://www.sqlservertutorial.net/sql-server-basics/sql-server-temporary-tables/ "This link takes you to a tutorial on how to create temporary tables in SQL Server.")**:** Article describes temporary table creation and removal
-   [Choosing Between Table Variables and Temporary Tables](https://www.red-gate.com/hub/product-learning/sql-prompt/choosing-table-variables-temporary-tables "This link takes you to a description of how using table variables differs from using temporary tables.")**:** Article describes the differences between passing variables in SQL statements vs. using temporary tables
