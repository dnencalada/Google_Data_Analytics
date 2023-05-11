## Programming and data analytics
**Computer programming**: Giving instructions to a computer to perform an action or set of actions.

- Introduction to programming languages
- Explore main features and functions
- Basic programming concepts in $\mathrm{R}$
- How to work with data in $\mathrm{R}$
- Clean, transform, visualize, report data in $\mathrm{R}$


### Programming as a data analyst
**Programming languages**: The words and symbols we use to write instructions for computers to follow.

Coding is writing instructions to the computer in the syntax of a specific programming language

**Benefits of using any programming language to work with your data:**
- Clarify the steps of your analysis
- Saves time
- Reproduce and share your work


### Spreadsheets, SQL, and R: a comparison
| **Key question**                                       | **Spreadsheets**                                             | **SQL**                                                      | **R**                                                        |
| :----------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| **What is it?**                                        | A program that uses rows and columns to organize data and allows for analysis and manipulation through formulas, functions, and built-in features | A database programming language used to communicate with databases to conduct an analysis of data | A general purpose programming language used for statistical analysis, visualization, and other data analysis |
| **What is a primary advantage?**                       | Includes a variety of visualization tools and features       | Allows users to manipulate and reorganize data as needed to aid analysis | Provides an accessible language to organize, modify, and clean data frames, and create insightful data visualizations |
| **Which datasets does it work best with?**             | Smaller datasets                                             | Larger datasets                                              | Larger datasets                                              |
| **What is the source of the data?**                    | Entered manually or imported from an external source         | Accessed from an external database                           | Loaded with R when installed, imported from your computer, or loaded from external sources |
| **Where is the data from my analysis usually stored?** | In a spreadsheet file on your computer                       | Inside tables in the accessed database                       | In an R file on your computer                                |
| **Do I use formulas and functions?**                   | Yes                                                          | Yes                                                          | Yes                                                          |
| **Can I create visualizations?**                       | Yes                                                          | Yes, by using an additional tool like a database management system (DBMS) or a business intelligence (BI) tool | Yes                                                          |


### Introduction to R
**R**: A programming language frequently used for statistical analysis, visualization, and other data analysis.
R is based on S. The title R refers to the first names of its two authors and plays on a single- letter tittle of its predecessor S.
The R programming language can be used for statistical analysis, visualization, and data analysis.

**Why R is popular?**
- Accessible
First R is an accessible language for beginners.
- Data-centric
It's specifically designed to make data analysis easier, more efficient and more powerful.
- Open source
**Open source**: Code that is freely available and may be modified and shared by the people who use it.
Thousands of R packages exists.
- Community
    -   [**RStudio Community:**](https://community.rstudio.com/ "This link takes you to the RStudio Community home page.") The RStudio Community forum is a great place to get help and find solutions to challenges you have with R–and maybe help someone else out, too!
    -   [**r/RLanguage**](https://www.reddit.com/r/Rlanguage/ "This link takes you to the Rlanguage subreddit dedicated to the R programming language topic."): The R language subreddit is an active online community on the social media platform Reddit, where R users go to discuss R, ask questions, and share tips. 
    -   [**rOpenSci**](https://discuss.ropensci.org/ "This link takes you to the rOpenSci discussion forums."): rOpenSci has a community forum where R users can ask questions and search for solutions. It also includes links to their Best Practices guide and support pages. 
    -   [**R4DS Online Learning Community and Slack channel:**](https://www.rfordatasci.com/ "This link takes you to the R for Data Science Online Learning Community and Slack channel.") This is a community with another Slack channel where R learners and mentors can gather and connect. This is a great place to chat about using R for data science. 
    -   [**Twitter \#rstats**](https://twitter.com/hashtag/rstats?lang=en "This link takes you to Twitter posts tagged with the #rstats hashtag."): If you use Twitter, you can connect with other R users using the hashtag \#rstats; a lot of R developers and analysts are active on Twitter.
    -   **Meetups**
    -   [**Local Data Analytics meetups:**](https://www.meetup.com/topics/data-analytics/ "This link takes you to Meetup's Data Analytics groups page.") These meetups are a great way to meet other people who are interested in data analytics and build your network. These meetups are location-based, so you can connect with other data analysts in your area. 
    -   [**R User Groups:**](https://jumpingrivers.github.io/meetingsR/r-user-groups.html "This link takes you to a list of R user groups, conferences, and meetings by country.") This list contains links to regional R communities, including subreddits and meetup groups. This is a useful resource if you are interested in finding R users in your area. 
    -   [**RLadies Meetups:**](https://www.meetup.com/pro/rladies "This link takes you to Meetup's R-Ladies groups page.") These are in-person and virtual meetups specifically for R enthusiasts who identify as underrepresented or marginalized. These meetups are also location-based and can help you connect with other data analysts in your area.


**Three specific scenarios situations when you might use R for data analysis:**
- Reproducing your analysis
R can save and reproduce every step of your analysis. Your code stores it forever. And you can share it with anyone at any time.
- Processing lots of data
Processing lots of data is also something R does really well, just like SQL.
- Creating data visualizations
R can create powerful visuals and has state-of-the-art graphic capabilities.
If you work with more advanced packages, you can make some seriously impressive data visualizations.

### When to use RStudio
R and RStudio are designed to handle large data sets, which spreadsheets might not be able to handle as well.
RStudio also makes it easy to reproduce your work on different datasets. When you input your code, it's simple to just load a new dataset and run your scripts again. You can also create more detailed visualizations using RStudio.

When the data is spread across multiple categories or groups, it can be challenging to manage your analysis, visualize trends, and build graphics. That’s where RStudio comes in.

For example, imagine you are analyzing sales data for every city across an entire country. That is a lot of data from a lot of different groups–in this case, each city has its own group of data.

Here are a few ways RStudio could help in this situation:
-   Using RStudio makes it easy to take a specific analysis step and perform it for each group using basic code. In this example, you could calculate the yearly average sales data for every city. 
-   RStudio also allows for flexible data visualization. You can visualize differences across the cities effectively using plotting features like facets–which you’ll learn more about later on.
-   You can also use RStudio to automatically create an output of summary stats—or even your visualized plots—for each group.

**For more information**
-   [**The Advantages of RStudio**](https://www.theanalysisfactor.com/the-advantages-of-rstudio/ "This article from The Analysis Factor describes the advantages of RStudio."): This web page explains some of the reasons why RStudio is many analysts’ preferred choice for interfacing with R. You’ll learn about the advantages of using RStudio for data analysis, from ease of use to accessibility of graphics and more. 
-   [**Data analysis and R programming**](https://lgatto.github.io/2017_11_09_Rcourse_Jena/before-we-start.html "This link takes you to an introductory section of an online course for data analysis and R programming."): This online introduction to data analysis and R programming is a good starting point for R and RStudio users. It also includes a list of detailed explanations about the advantages of using R and RStudio. You’ll also find a helpful guide for getting set up with RStudio.


### RStudio
**Integrated Development Environment (IDE)**: A software application that brings together all the tools you may want to use in a single place.
RStudio is an IDE.

RStudio includes R console, and also includes an editor for writing code, and tools for managing your data and creating visuals.

[RStudio Cloud](https://rstudio.cloud/plans/free)
**Packages** are units of reproducible R code.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image148.png)

The RStudio environment has **four** main windows called panes. Each pane helps you perform different functions.
(A fourth pane is hidden by default, but it's easy to open. File-->New File--> R Script)
(RStudio has lots of keyboard shortcuts. To learn more check out Keyboard Shortcuts Help.)
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image149.png)

#### Four panes
##### Source editor pane and Console pane
There are two main ways of writing code in RStudio: using the console or using the source editor.
You can type commands directly into the console, but they'll be forgotten when you close your current session.
If you save your script in the editor, you can access your work again at any time and show others how you did it.

The source editor and the console also work together in RStudio. When you execute code in the editor, the code automatically appears in the console.

> **R is ALWAYS case-sensitive**

##### Environment pane
Here you'll find all the data you currently have loaded and can easily organize and save it.
You can view each object in the Environment pane by clicking on it.
You can also toggle between a List view and a Grid view.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image150.png)

To the right of the Environment tab, you'll find the History tab. All your previous commands are saved here and they're easy to search and re-execute.
The most recent line of code locates at the bottom of the list.
Double-clicking it to copy any line to the command console

##### Files, Plots, Packages, and Help pane
In the lower right, you'll see a pane that has tabs for Files, Plots, Packages, and Help.

**Files tab**: gives you access to your file directory and shows the contents of the current working folder.
**Plots tab**: If we create a plot, the result appears here.
**Help tab**: you can find helpful resources for R and RStudio.

**Packages tab**:
R packages are custom solutions to data problems developed by R users. RStudio gives you access to a library of R packages known as the tidyverse.
You can upgrade, install, and manage your library in the Packages pane.
You only need to install a package once, but you need to reload it every time you start a new session.
Packages loaded in your current session have a check mark.


## Programming using RStudio

### Programming fundamentals
The basic concepts of $\mathrm{R}$
- **Functions**
**Functions (R)**: A body of reusable code used to perform specific tasks in $\mathrm{R}$.
**Argument (R)**: Information that a function in $\mathrm{R}$ needs in order to run.
- **Comments**
`#` Comments should be used to make an R script more readable.
- **Variables**
**Variable (R)**: A representation of a value in $\mathrm{R}$ that can be stored for use later during programming.
A variable name should start with a letter and can also contain numbers and underscores
- **Data types**
- **Vectors**
**Vector (R)**: A group of data elements of the same type stored in a sequence in $R$.
`c(x,y,z,...)`
- **Pipes**
**Pipe (R)**: A tool in $\mathrm{R}$ for expressing a sequence of multiple operations, represented with `%>%`. (percentage sign, greater sign, percentage sign)
It's used to apply the output of one function into another function.
e.g. filter and sort the data:
`ToothGrowth %>% filter(dose==0.5) %>%$ arrange(len)`

> `?print` turns a page in the help window


### Explore coding in R
**Operator**: A symbol that names the type of operation or calculation to be performed in a formula.

**Assignment operators**: Used to assign values to variables and vectors.

**Arithmetic operators**: Used to complete math calculations.
- $+$ (addition)
- $-$ (subtraction)
- $*$ (multiplication)
- $/$ (division)

**Logical operators** return a logical data type such as TRUE or FALSE.
-   AND (sometimes represented as & or && in R)
-   OR (sometimes represented as | or || in R)
-   NOT (!)

A **conditional statement** is a declaration that if a certain condition holds, then a certain event must take place.

To learn more about logical operators and conditional statements, check out DataCamp's tutorial [Conditionals and Control Flow in R](https://www.datacamp.com/community/tutorials/conditionals-and-control-flow-in-r "This link takes you to DataCamp's tutorial entitled Conditionals and Control Flow in R.").


### Coding style
#### Naming
|              | Guidance                                                                                                                                                                                                     | Examples of best practice                | Examples to avoid        |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------- | ------------------------ |
| Files        | File names should be meaningful and end in .R. Avoid using special characters in file names—stick with numbers, letters, dashes, and underscores.                                                            | # Good <br>explore_penguins.R annual_sales.R | # Bad <br>Untitled.r stuff.r |
| Object names | Variable and function names should be lowercase. Use an underscore _ to separate words within a name. Try to create names that are clear, concise, and meaningful.Generally, variable names should be nouns. | # Good <br>day_one                           | # Bad <br>DayOne             |
|              | Function names should be verbs.                                                                                                                                                                              | # Good <br>add ()                            | # Bad <br>addition ()        |

#### Syntax
|         | Guidance                                                     | Examples of best practice | Examples to avoid  |
| ------- | ------------------------------------------------------------ | ------------------------- | ------------------ |
| Spacing | Most operators (== , + , - , <- ,etc.) should be surrounded byspaces. | # Good<br> x == y <br>a <- 3 * 2 | # Bad<br> x==y<br>a<-3*2 |
|         | Always put a space after a comma (never before).              | # Good<br> y[, 2]             | # Bad<br> y[,2]<br>y[ ,2] |
|              | Do not place spaces around code in parentheses or square brackets (unless there’s a comma, in which case see above). | # Good<br> if (debug) do(x)<br>species[“dolphin”, ]             | # Bad<br> if ( debug ) do(x) =<br>species[ “dolphin” ,]         |
|              | Place a space before left parentheses, except in a function call. | # Good<br> sum(1:5)<br>plot(x, y)                               | # Bad<br> sum (1:5)<br>plot (x, y)                              |
| Curly braces | An opening curly brace should never go on its own line and should always be followed by a new line. A closing curly brace should always go on its own line (unless it’s followed by an else statement). Always indent the code inside curly braces. | # Good<br>x <- 7<br>if (x > 0) {<br>print("x is a positive number")} else {<br>print ("x is either anegative number or zero")<br>} | # Bad<br>x <- 7<br/>if (x > 0)<br/>{<br/>print("x is apositive number")<br/>}<br/>else {<br/>print ("x is either anegative number orzero")<br/>} |
| Indentation  | When indenting your code, use two spaces. Do not use tabs or mix tabs and spaces. | -                                                            | -                                                            |
| Line length  | Try to limit your code to 80 characters per line. This fits nicely on a printed page with a reasonably sized font.<br/>Note that many style guides mention to never let a line go past 80 (or 120) characters. If you’re using RStudio, there’s a helpful setting for this. Go to Tools -> Global Options -> Code -> Display, and select the option Show margin, and set margin column to 80 (or 120). |               |             |
| Assignment | Use <- , not = , for assignment.                             | # Good<br> z <- 4 | # Bad<br> Z = 4 |


#### Organization
|            | Guidance                                                                           | Examples of best practice | Examples to avoid  |
| ---------- | ---------------------------------------------------------------------------------- | ------------------------- | ------------------ |
| Commenting | Entire commented lines should begin with the comment symbol and a single space: #. | # Good <br># Load data    | # Bad <br>Loaddata |


#### Additional Resources
- Check out this [tidyverse style guide](https://style.tidyverse.org/files.html#names) to get a more comprehensive breakdown of the most important stylistic conventions for writing R code (and working with the tidyverse).

- The styler package is an automatic styling tool that follows the tidyverse formatting rules. Check out the [styler](https://styler.r-lib.org/index.html) webpage to learn more about the basic features of this tool.

#### Debugging Resources
- For more information on the technical aspects of debugging R code, check out [Debugging with RStudio](https://support.rstudio.com/hc/en-us/articles/205612627-Debugging-with-RStudio#stopping-on-a-line) on the RStudio Support website. RStudio Support is a great place to find answers to your questions about RStudio. This article will take you through the R debugging tools built into RStudio, and show you how to use them to help debug R code.

- To learn more about problem-solving strategies for debugging R code, check out the chapter on [Debugging in Advanced R](https://adv-r.hadley.nz/debugging.html). Advanced R is a great resource if you want to explore the finer details of an R topic and take your knowledge to the next level.


### Hands-On Activity: R sandbox
In this activity, you will be using a package called `tidyverse.` The `tidyverse` package is actually a collection individual `packages` that can help you perform a wide variety of analysis tasks.
```r
install.packages("tidyverse")
library(tidyverse)
```

Many of the `tidyverse` packages contain sample datasets that you can use to practice your `R` skills. The `diamonds` dataset in the `ggplot2` package is a great example for previewing `R` functions. 

#### Preview
One common function you can use to preview the data is the `head()` function, which displays the columns and the first several rows of data.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image151.png)

The `str()` and `glimpse()` functions will both return summaries of each column in your data arranged horizontally
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image152.png)

`colnames()` function returns a list of column names from your dataset
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image153.png)
The numbers [1],[10] helps you count the number of columns in your dataset

`summarize().` can be used to generate a wide range of summary statistics for your data:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image154.png)


#### Renaming
Changing the column name of `carat` to `carat_new`.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image155.png)

Rename more than one variable:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image156.png)


#### Visualizing data
One of the most commonly used visualization packages is the `ggplot2` package, which is loaded automatically when you install and load `tidyverse.`
The `diamonds` dataset that you have been using so far is a `ggplot2` dataset.

To build a visualization with `ggplot2`, you layer plot elements together with a `+` symbol.

The code below takes the `diamonds` data, plots the carat column on the X-axis, the price column on the Y-axis, and represents the data as a scatter plot using the `geom_point()` command:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image157.png)

Change the color of each point so that it represented another variable, such as the cut of the diamond:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image158.png)

Separate out some of the components by creating a different plot for each type of cut with the `facet_wrap()` function:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image159.png)


### R Packages
**Packages (R)**: Units of reproducible $\mathrm{R}$ code.
Packages are units of reproducible R code that you can use to add more functionality to R.
Packages offer a helpful combination of code, reusable R functions, descriptive documentation, tests for checking operability, and sample data sets

Packages include:
- Reusable $R$ functions
- Documentation about the functions
- Sample datasets
- Tests for checking your code

By default, R includes a set of packages called **Base R** that are available to use in RStudio when you start your first programming session.
Use `installed.packages()` to list all installed packages.
Priority:
    - base: Installed and loaded
    - recommended: installed but not loaded. (Use `library(<package_name>` to load)
In the package tab, loaded packages are checked. Click the name to open its help tab. (Or typing in `?<package_name>`)

#### Repository
Packages can be found in repositories, which are collections of useful packages that are ready to install. You can find repositories on [**Bioconductor**](http://bioconductor.org/ "This link takes you to the Bioconductor home page."), [**R-Forge**](https://r-forge.r-project.org/ "This link takes you to the R-Forge welcome page."), [**rOpenSci**](https://ropensci.org/ "This link takes you to the ROpenSci home page."), or [**GitHub**](https://github.com/ "This link takes you to the GitHub home page.").

One of the most commonly used sources of packages is [**CRAN**](https://cran.r-project.org/ "This link takes you to the home page for The Comprehensive R Archive Network (CRAN).").
**CRAN (Comprehensive R Archive Network)**: An online archive with $\mathrm{R}$ packages, source code, manuals, and documentation.

Packages will not only include the code itself, but also documentation that explains the package’s author, function, and any other packages that you will need to download. When you are using CRAN, you can find the package documentation in the DESCRIPTION file. 

Check out Karl Broman's [**R Package Primer**](https://kbroman.org/pkg_primer/ "This link takes you to Karl Broman's online primer on R packages.") to learn more.

#### Choosing the right packages
-   [**Tidyverse**](https://www.tidyverse.org/ "This link takes you to the Tidyverse home page."): the tidyverse is a collection of R packages specifically designed for working with data. It’s a standard library for most data analysts, but you can also download the packages individually. 
-   [**Quick list of useful R packages**](https://support.rstudio.com/hc/en-us/articles/201057987-Quick-list-of-useful-R-packages "This link takes you to a list of R packages recommended by RStudio Support."): this is RStudio Support’s list of useful packages with installation instructions and functionality descriptions. 
-   [**CRAN Task Views**](https://cran.r-project.org/web/views/ "This link takes you to a list of packages on CRAN by topic or task in alphabetical order."): this is an index of CRAN packages sorted by task. You can search for the type of task you need to perform and it will pull up a page with packages related to that task for you to explore.



#### Tidyverse
**Tidyverse (R)**: A system of packages in $\mathrm{R}$ with a common design philosophy for data manipulation, exploration, and visualization.
```r
install.packages("tidyverse")
library("tidyverse")
```
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image160.png)
The output in the console indicates that you have loaded the core tidyverse. Each of the core packages has a green check next to it.
Conflicts report which objects have the same name in two or more places within your session. This usually happens because an object in your workspace or a package you installed is masking a system object of the same name. 
Since you most recently loaded the tidyverse packages, they will be the default packages for your current session.

**Tidyverse workflow:**
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image161.png)

##### tidyverse core
**8 core tidyverse packages:**
- **ggplot2**
Ggplot2 is used for data visualization, specifically plots.
With ggplot2, you can create a variety of data viz by applying different visual properties to the data variables.
- **tidyr**
***tidyr (R)***: A package used for data cleaning to make tidy data.
***tidy(or clean) data***: data where every part of a data table or data frame is the right type in the right place.
- **readr**
Used for importing data. Most common function is `read_csv()`
To accurately read a dataset with readr, you can combine the function with a column specification(describes how each column should be converted to the most appropriate data type). (Not necessary because readr will figure it out automatically.)
- **dplyr**
***dplyr (R)***: Offers a consistent set of functions that help you complete some common data manipulation tasks.
For example, the select function picks variables based on their names, and the filter function finds cases where certain conditions are true.

(↑ Above four packages that are an essential part of
the workflow for data analysts ↑)
- tibble
Tibble works with data frames.
- purrr
Purrr works with functions and vectors helping make your code easier to write and more expressive.
- stringr
Stringr includes functions that make it easier to work with strings.
- forcats
Forcats provides tools that solve common problems with factors.
***Factors (R)***: Store categorical data in $\mathrm{R}$ where the data values are limited and usually based on a finite group like country or year.







#### Update
```r
# update all of your packages:
Update.packages()

# update one package
Install.packages("package name")


# tidyverse check for updates:
tidyverse_update()
```

#### vignette
A **vignette** is documentation that acts as a guide to an R package.
The **browseVignettes** function allows you to read through vignettes of a loaded package.

```r
browseVignettes()
browseVignettes("packagename")

# e.g.
browseVignettes("ggplot2")
```
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image162.png)
If you are using RStudio Cloud, running this function will open a new browser tab with links to the vignettes.

### Pip
**Pipe (R)**: A tool in $\mathrm{R}$ for expressing a sequence of multiple operations, represented with “\%>\%".
In other words, it takes the output of one statement and makes it the input of the next statement.
So instead of typing out functions contained inside other functions, you could use the pipe operator to do the same work. In programming, we describe this as nested.

**Nested**: In programming, describes code that performs a particular function and is contained within code that performs a broader function.
**Nested function**: A function that is completely contained within another function.

You can think of a pipe as a way to code the phrase `and then`.

e.g. find the mean or average of the sales data:
- Call up data (<u>and then</u>)
- Group the data (<u>and then</u>)
- Summarize the grouped data using a mean function

```r
data("ToothGrowth")
View(ToothGrowth)

# filtering the dataset with does=0.5
filtered_tg <- filter(ToothGrowth, dose==0.5)
# arrange the data in ascending order by len
arrange(filtered_tg, len)


# Nested function
arrange(filter(ToothGrowth, dose==0.5), len)

# Pip %>%  Mac:cmd+shift+m   PC:ctrl+shift+m
filtered_toothgrowth <- ToothGrowth %>% 
  filter(dose == 0.5) %>% 
  arrange(len)
View(filtered_toothgrowth)


# group with summarise
filtered_toothgrowth2 <- ToothGrowth %>% 
  filter(dose == 0.5) %>%
  group_by(supp) %>% 
  summarise(mean_len = mean(len, na.rm = T), .group="drop")
View(filtered_toothgrowth2)
```



When using pipes:
- Add the pipe operator at the end of each line of the piped operation except the last one
- Check your code after you've programmed your pipe
Remember, RStudio automatically indents lines of code that are part of a pipe. If a line in your code isn't indented, it probably hasn't been added to the pipe.
- Revisit piped operations to check for parts of your code to fix


### R resources
-   [**RStudio**](https://rstudio.com/ "This link takes you to the RStudio home page."): The best place to find help with R is in R itself! You can input ‘?’ or the help() command to search in R. You can also open the Help pane to find more R resources. 
-   [**RStudio Blog:**](https://blog.rstudio.com/ "This link takes you to the home page for RStudio blog articles.") RStudio’s blog is a great place to find information about RStudio, including company news.  You can read the most recent [**featured posts**](https://blog.rstudio.com/categories/featured/ "This link takes you to the featured RStudio blog posts.") or use the search bar and the list of categories on the left side of the page to explore specific topics you might find interesting or to search for a specific post. 
-   [**Stack Overflow:**](https://stackoverflow.blog/ "This link takes you to The Overflow which is Stack Overflow's blog feed.") The Stack Overflow blog posts opinions and advice from other coders. This is a great place to stay in touch with conversations happening in the community. 
-   [**R-Bloggers:**](https://www.r-bloggers.com/ "This link takes you to the R-Bloggers home page.") The R-Bloggers blog has useful tutorials and news articles posted by other R users in the community. 
-   [**R-Bloggers' tutorials for learning R:**](https://www.r-bloggers.com/2015/12/how-to-learn-r-2/#h.y5b98o9o2h1r "This link takes you to R-Bloggers' collection of tutorials for learning R.") This blog post from R-Bloggers compiles some basic R tutorials and also links to more advanced guides.

> "An important aspect of any type of script or when you are coding, is to structure it for overall readability."
> “An important aspect for readability and overall understanding of your code is using comments."
> "Documentation will explain in depth exactly what your code is doing, why it was built, what is the purpose for it and any limitations."
> "Building it for scalability as well as making it dynamic."


---

## Working with data in R
### Data frame (and Tibbles)
Data frames and tibbles are the building blocks for analysis in R.

**Data frame**: A collection of columns.
(Like pandas)

Data frame properties:
- Columns should be named
- Data stored can be many different types, like numeric, factor, or character
- Each column should contain the same number of data items

**Tibbles** are like streamlined data frames. (Contained in tidyverse)
Different from the standard data frame:
- Never change the data types of the inputs
- Never change the names of your variables
- Never create row names
- Make printing easier


***Tidy data (R)***: A way of standardizing the organization of data within $\mathrm{R}$.
Tidy data standards:
- Variables are organized into columns
- Observations are organized into rows
- Each value must have its own cell

#### More about tibbles
A **tibble**, or `tbl_df`, is a modern reimagining of the data.frame, keeping what time has proven to be effective, and throwing out what is not.
```r
# create a tibble from a data frame
as_tibble(iris)

# create a tibble from column vectors
tibble(x = 1:5, y = 1, z = x ^ 2 + y)

tribble(
  ~x, ~y,  ~z,
  "a", 2,  3.6,
  "b", 1,  8.5
)
```
The tibble only returns the first 10 rows in a neatly organized table:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image163.png)
-   The entry for [Tibble](https://tibble.tidyverse.org/ "This link takes you to the Tibble section of the Tidyverse documentation.") in the tidyverse documentation summarizes what a tibble is and how it works in R code. If you want a quick overview of the essentials, this is the place to go. 
-   The [Tidy chapter](https://rstudio-education.github.io/tidyverse-cookbook/tidy.html# "This link takes you to the Tidy chapter in "A Tidyverse Cookbook." ") in "A Tidyverse Cookbook" is a great resource if you want to learn more about how to work with tibbles using R code. The chapter explores a variety of R functions that can help you create and transform tibbles to organize and tidy your data.

> **Warning**: tibble will lost row names!
> ```r
> rownames(mtcars)
> # [1] "Mazda RX4" "Mazda RX4 Wag" "Datsun 710" ...
> 
> rownames(as_tibble(mtcars))
> # [1] "1"  "2"  "3"  "4" ...
> ```


#### Working with data frames
Data frames are basically the data analyst's default way to interact with data.

> 'diamonds' is a good dataset to practice with.

```r
install.packages('tidyverse')
library('tidyverse')
dataset('diamonds') # 'diamonds' dataset is in 'ggplot2'
View(diamonds)

# preview first 6 rows
head(diamonds)

# structure
str(diamonds)
glimpse(diamonds)

# get column names
colnames(diamonds)

# Create, modify, and delete columns. `mutate()` is in dplyr package
# add a new column 'carat_2' which equals to caratx100
mutate(diamonds, carat_2=carat*100)
# delete a column
diamonds %>% mutate(carat = NULL)
# add a column at location 1, remove unused columns
# .before  .after
# .keep  :  all(default),used,unused,none
diamonds %>% mutate(carat_2=carat*100, .keep = "used" .before = 1)


# create another data frame using existing one
# can be done with or without quotes ''
new_df <- select(diamonds, carat, 'cut')
```

#### Create a data frame
There are three common sources for data:
-   A`package` with data that can be accessed by loading that `package`
-   An external file like a spreadsheet or CSV that can be imported into `R`
-   Data that has been generated from scratch using `R` code

##### Generate a data frame directly in R
```r
names <- c("Tom", "Jerry", "Spike", "Tyke")
age <- c(2, 2, 3, 1)

# create a two-column-data-frame
people <- data.frame(names, age)

# another example
Data_Frame <- data.frame (  
    Training = c("Strength", "Stamina", "Other"),  
    Pulse = c(100, 150, 120),  
    Duration = c(60, 30, 45)  
)
```

##### Load dataset from packages
```r
# display data sets in package 'datasets'
data()

# load a dataset
data(mtcars)
```
The loaded dataset will also appear in the Environment pane of your RStudio.
Click directly on the name of the dataset in the Environment pane, or using `mtcars` to display the dataset.

##### Readr from files like csv
The `readr` package in R is a great tool for reading rectangular data.
**Rectangular data** is data that fits nicely inside a rectangle of rows and columns, with each column referring to a single variable and each row referring to a single observation.

Here are some examples of file types that store **rectangular data**:
-   **.csv** **(comma separated values)**: a .csv file is a plain text file that contains a list of data. They mostly use commas to separate (or delimit) data, but sometimes they use other characters, like semicolons. 
-   **.tsv (tab separated values)**: a .tsv file stores a data table in which the columns of data are separated by tabs. For example, a database table or spreadsheet data. 
-   **.fwf** **(fixed width files)**: a .fwf file has a specific format that allows for the saving of textual data in an organized fashion. 
-   **.log:** a .log file is a computer-generated file that records events from operating systems and other software programs.

**readr functions:**
-   `read_csv()`: comma-separated values (.csv) files
-   `read_tsv()`: tab-separated values files
-   `read_delim()`: general delimited files
-   `read_fwf()`: fixed-width files
-   `read_table()`: tabular files where columns are separated by white-space
-   `read_log()`: web log files

**Reading a .csv file with readr**
```r
library(tidyverse)

# list readr examples
> readr_example()
[1] "challenge.csv"     "epa78.txt"         "example.log"
[4] "fwf-sample.txt"    "massey-rating.txt" "mtcars.csv"
[7] "mtcars.csv.bz2"    "mtcars.csv.zip"

# get the path to the file
readr_example("mtcars.csv")

# read file
# Prints out a column specification and a tibble.
> read_csv(readr_example("mtcars.csv"))
── Column specification ─────────────────────────────────────────────────────────────────────────────────
cols(
  mpg = col_double(),
  cyl = col_double(),
  disp = col_double(),
  hp = col_double(),
  drat = col_double(),
  wt = col_double(),
  qsec = col_double(),
  vs = col_double(),
  am = col_double(),
  gear = col_double(),
  carb = col_double()
)

# A tibble: 32 x 11
     mpg   cyl  disp    hp  drat    wt  qsec    vs    am  gear  carb
   <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl> <dbl>
 1  21       6  160    110  3.9   2.62  16.5     0     1     4     4
 2  21       6  160    110  3.9   2.88  17.0     0     1     4     4
 3  22.8     4  108     93  3.85  2.32  18.6     1     1     4     1
 4  21.4     6  258    110  3.08  3.22  19.4     1     0     3     1
 5  18.7     8  360    175  3.15  3.44  17.0     0     0     3     2
 6  18.1     6  225    105  2.76  3.46  20.2     1     0     3     1
 7  14.3     8  360    245  3.21  3.57  15.8     0     0     3     4
 8  24.4     4  147.    62  3.69  3.19  20       1     0     4     2
 9  22.8     4  141.    95  3.92  3.15  22.9     1     0     4     2
10  19.2     6  168.   123  3.92  3.44  18.3     1     0     4     4
# … with 22 more rows
```

##### Readxl from Excel files .xlsx
```r
library(readxl)

# list readxl examples
> readxl_example()
 [1] "clippy.xls"    "clippy.xlsx"   "datasets.xls"  "datasets.xlsx"
 [5] "deaths.xls"    "deaths.xlsx"   "geometry.xls"  "geometry.xlsx"
 [9] "type-me.xls"   "type-me.xlsx"

# read an example (by default read the first tab) and returns a tibble
> read_excel(readxl_example("type-me.xlsx"))
# A tibble: 10 x 2
   `maybe boolean?` description
   <chr>            <chr>
 1 NA               "empty"
 2 0                "0 (numeric)"
 3 1                "1 (numeric)"
 4 40908            "datetime"
 5 TRUE             "boolean true"
 6 FALSE            "boolean false"
 7 cabbage          "\"cabbage\""
 8 true             "the string \"true\""
 9 F                "the letter \"F\""
10 False            "\"False\" preceded by single quote"

# list tabs in a sheet
excel_sheets(readxl_example("type-me.xlsx"))

# read with specifying a sheet by name or number
read_excel(readxl_example("type-me.xlsx"), sheet = "numeric_coercion")
```

##### Additional resources
-   If you want to learn how to use readr functions to work with more complex files, check out the [Data Import chapter](https://r4ds.had.co.nz/data-import.html "This link takes you to the Data Import chapter of the R for Data Science book.") of the R for Data Science book. It explores some of the common issues you might encounter when reading files, and how to use readr to manage those issues. 

-   The [readxl](https://readxl.tidyverse.org/ "This link takes you to tidyverse's documentation for the readxl package.") entry in the tidyverse documentation gives a good overview of the basic functions in readxl, provides a detailed explanation of how the package operates and the coding concepts behind them, and offers links to other useful resources.
-   The R "datasets" package contains lots of useful preloaded datasets. Check out [The R Datasets Package](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/00Index.html "This link takes you to a list of the datasets in the R datasets pacakge.") for a list. The list includes links to detailed descriptions of each dataset.


### Cleaning data
Here, Skimr, Janitor. These packages simplify data cleaning tasks.
Janitor packages has function of cleaning data.
```r
install.packages("here")
library("here")

install.packages("skimr")
library("skimr")

install.packages("janitor")
library("janitor")

library("dplyr")
```

> **The palmer penguin data**: has lots of information about three penguin species in the Palmer Archipelago, including size measurements, clutch sizes, and blood isotope ratios.
```r
install.packages("palmerpenguins")
library("palmerpenguins")
```

Functions that useful in data cleaning:
```r
skim_without_charts()
glimpse()
head()
select()
rename()
clean_names()
```
**skim_without_charts()**
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image164.png)

**glimpse()**
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image165.png)

**head()**
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image166.png)

**select()**
```r
# only select column species
penguins %>%
  select(species)

# select every column except species
penguins %>% 
  select(-species)
```

**rename()**
```r
# rename a column
penguins %>% 
  rename(island_new = island)
```
**rename_with()**
```r
# rename_with() function can change column names to be more consistent
# to upper case
rename_with(penguins, toupper)

# to lower case
rename_with(penguins, tolower)
```

**clean_names()**
Cleans names of an object (usually a data.frame).
Resulting names are unique and consist only of the `_`character, numbers, and letters. Capitalization preferences can be specified using the `case` parameter.
`clean_names(penguins)`


#### File-naming conventions
An important part of cleaning data is making sure that all of your files are accurately named.
Next are some helpful "do’s" and "don’ts" to keep in mind when naming your files.
##### Do
- Keep your filenames to a reasonable length
- Use underscores and hyphens for readability
- Start or end your filename with a letter or number
- Use a standard date format when applicable; example: YYYY-MM-DD
- Use filenames for related files that work well with default ordering; example: in chronological order, or logical order using numbers first

| Examples of good filenames      |
| :------------------------------ |
| 2020-04-10_march-attendance.R   |
| 2021_03_20_new_customer_ids.csv |
| 01_data-sales.html              |
| 02_data-sales.html              |


##### Don't
- Use unnecessary additional characters in filenames
- Use spaces or “illegal” characters; examples: &, %, #, <, or >
- Start or end your filename with a symbol
- Use incomplete or inconsistent date formats; example: M-D-YY
- Use filenames for related files that do not work well with default ordering; examples: a random system of numbers or date formats, or using letters first


| Examples of filenames to avoid           |
|:---------------------------------------- |
| 4102020marchattendance\<workinprogress\>.R |
| \_20210320*newcustomeridsforfebonly.csv  |
| firstfile\_for\_datasales/1-25-2020.html |
| secondfile\_for_datasales/2-5-2020.html  |


##### Additional resources
These resources include more info about some of the file naming standards discussed here, and provide additional insights into best practices.
-   [**How to name files**](https://speakerdeck.com/jennybc/how-to-name-files "This link takes you to an online presentation on how to name files."): this resource from Speaker Deck is a playful take on file naming. It includes several slides with tips and examples for how to accurately name lots of different types of files. You will learn why filenames should be both machine readable and human readable. 
-   [**File naming and structure**](https://libguides.princeton.edu/c.php?g=102546&p=930626#:~:text=File%20naming%20best%20practices%3A&text=File%20names%20should%20be%20short,date%20format%20ISO%208601%3A%20YYYYMMDD "This link takes you to Princeton University's file naming conventions and best practices."): this resource from the Princeton University Library provides an easy-to-scan list of best practices, considerations, and examples for developing file naming conventions.


### Organize data
```r
arrange()
group_by()
filter()
```

#### Sort
```r
# sort penguins with bill_length_mm in ascending order
penguins %>% 
  arrange(bill_length_mm)

# in descending order
penguins %>% 
  arrange(-bill_length_mm)
# or 
penguins %>% 
  arrange(desc(bill_length_mm))
```

#### Group by
`group_by` is usually combined with other functions. For example, we might want to `group_by` a certain column and then perform an operation on those groups.
we can `group_by` island and then use the summarize function to get the mean bill length. The summarize function lets us get high-level information about our penguin data.
You can use max,min,mean,sum, etc.. insdie the `summarize` funciton.

```r
penguins %>% 
  group_by(island) %>% 
  drop_na() %>% 
  summarize(mean_bill_length_mm = mean(bill_length_mm))
>
# A tibble: 3 x 2
  island    mean_bill_length_mm
  <fct>                   <dbl>
1 Biscoe                   45.2
2 Dream                    44.2
3 Torgersen                39.0


penguins %>% 
  group_by(species, island) %>% 
  drop_na() %>% 
  summarize(max_bl=max(bill_length_mm), mean_bl=mean(bill_length_mm))
>
`summarise()` has grouped output by 'species'. You can override using the `.groups` argument.
# A tibble: 5 x 4
# Groups:   species [3]
  species   island    max_bl mean_bl
  <fct>     <fct>      <dbl>   <dbl>
1 Adelie    Biscoe      45.6    39.0
2 Adelie    Dream       44.1    38.5
3 Adelie    Torgersen   46      39.0
4 Chinstrap Dream       58      48.8
5 Gentoo    Biscoe      59.6    47.6
```

> Be careful when you're using `drop_na`. It's useful when doing a group-level summary statistic, but it will remove rows from the data.

#### Filter
```r
penguins %>% 
  filter(species == "Adelie")

# or specify the dataset name
penguins %>% 
  filter(penguins$species == "Adelie")
```

#### Unite
```r
example_df <- bookings_df %>%
  select(arrival_date_year, arrival_date_month) %>% 
  unite(arrival_month_year, c("arrival_date_month", "arrival_date_year"), sep = " ")
```



### Transform data
```r
separate()
unite()
mutate()
```

#### Separate
```r
employee %>% 
  separate(name, into = c("First_name", "Last_name"), sep=' ')
```

#### Unite
`unite(data, col, ..., sep = "_", remove = TRUE, na.rm = FALSE)`
```r
employee %>% 
  unite('name', First_name, Last_name, sep=' ')
```

#### Mutate
```r
penguins %>% 
  mutate(body_mass_kg = body_mass_g/1000)

penguins %>% 
  mutate(body_mass_kg = body_mass_g/1000, flipper_length_m = flipper_length_mm/1000)
```

#### Wide to long with tidyr
**Wide data** has observations across several columns.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image167.png)
Same data in a long format:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image168.png)

**from wide data to long data**
`pivot_longer()`
As part of the tidyr package, you can use this R function to lengthen the data in a data frame by increasing the number of rows and decreasing the number of columns.
```r
billboard %>%
 pivot_longer(
   cols = starts_with("wk"),
   names_to = "week",
   names_prefix = "wk",
   values_to = "rank",
   values_drop_na = TRUE
 )
```

**from long data to wide data**
Similarly, if you want to convert your data to have more columns and fewer rows, you would use the `pivot_wider()` function.
```r
us_rent_income %>%
  pivot_wider(
    names_from = variable,
    names_sep = ".",
    values_from = c(estimate, moe)
  )
```

**Additional resources**
To learn more about these two functions and how to apply them in your R programming, check out these resources:
-   [**Pivoting**](https://tidyr.tidyverse.org/articles/pivot.html "This link takes you to the tidyr documentation for the pivot_longer and pivot_wider functions."): Consider this a starting point for tidying data through wide and long conversions. This web page is taken directly from tidyr package information at [**tidyverse.org**](https://www.tidyverse.org/ "This link takes you to the tidyverse home page."). It explores the components of the pivot_longer and pivot_wider functions using specific details, examples, and definitions. 
-   [**CleanItUp 5: R-Ladies Sydney: Wide to Long to Wide to…PIVOT**](https://rladiessydney.org/courses/ryouwithme/02-cleanitup-5/ "This link takes you to an R-Ladies Sydney article on converting wide to long data."): This resource gives you additional details about the pivot_longer and pivot_wider functions. The examples provided use interesting datasets to illustrate how to convert data from wide to long and back to wide. 
-   [**Plotting multiple variables**](https://scc.ms.unimelb.edu.au/resources-list/simple-r-scripts-for-analysis/r-scripts "This link takes you to the University of Melbourne's tips for plotting multiple variables by pivoting longer.")[**:**](https://www.datamentor.io/r-programming/saving-plot/) This resource explains how to visualize wide and long data, with ggplot2 to help tidy it. The focus is on using pivot_longer to restructure data and make similar plots of a number of variables at once. You can apply what you learn from the other resources here for a broader understanding of the pivot functions.

### A closer look
#### Misleading statistic
> a very famous data example, Anscombe's Quartet.
> **Anscombe's quartet**: Four datasets that have nearly identical summary statistics.
> However, those summary statistics might be misleading.

The `cor()` function returns the correlation between two variables. This determines how strong the relationship between those two variables is.
```r
install.packages('Tmisc')
library(Tmisc)
data("quartet")
View(quartet)
skim_without_charts(quartet)

# get mean, standard deviation, and´ correlation
quartet %>% 
  group_by(set) %>% 
  summarize(mean(x), sd(x), mean(y), sd(y), cor(x,y))
>
# A tibble: 4 x 6
  set   `mean(x)` `sd(x)` `mean(y)` `sd(y)` `cor(x, y)`
  <fct>     <dbl>   <dbl>     <dbl>   <dbl>       <dbl>
1 I             9    3.32      7.50    2.03       0.816
2 II            9    3.32      7.50    2.03       0.816
3 III           9    3.32      7.5     2.03       0.816
4 IV            9    3.32      7.50    2.03       0.817
```

But only look at the statistical data can be misleading. When we visualize them:
```r
ggplot(quartet, aes(x, y)) + geom_point() + geom_smooth(method = lm, se=FALSE) + facet_wrap(~set)
```
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image169.png)

If we had just gone with the statistical summaries, we never would have known that this data is actually really different.

#### Draw different shapes
The data source creates plots with the Anscombe data in different shapes.´
```r
install.packages('datasauRus')
library('datasauRus')

ggplot(datasaurus_dozen, aes(x=x, y=y, color=dataset)) + geom_point() + theme_void() + theme(legend.position = "none") + facet_wrap(~dataset, ncol=3)
```
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image170.png)


### Bias
Every data analyst will encounter an element of bias at some point in the data analysis process. That’s why it’s so important to understand how to identify and manage biased data whenever possible.

In R, we can actually quantify bias by comparing the actual outcome of our data with the predicted outcome using `bias()` function.
The `bias()` function can be used to calculate the average amount a predicted outcome and actual outcome differ in order to determine if the data model is biased.

If the model is unbiased, the outcome should be pretty close to zero.
A high result means that your data might be biased.

**e.g. 1**
Determine if a local weather channel's weather predictions are biased.
We'll use the bias function to compare forecasted temperatures with actual temperatures.
```r
install.packages('SimDesign')
library('SimDesign')

actual_temp <- c(68.3, 70, 72.4, 71, 67, 70)
predicted_temp <- c(67.9, 69, 71.5, 70, 67, 69)

bias(actual_temp, predicted_temp)
```
We can find out that the result is 0.71. That's pretty high. The predictions seem biased towards lower temperatures, which means they aren't as accurate as they could be.

**e.g. 2**
One of the tasks is called a side-by-side comparison. For example, we might show users two ads side-by-side at the same time. In our survey, we ask which of the two ads they prefer.
In one case, after many iterations, we were seeing consistent bias in favor of the first item. There was also a measurable decrease in the preference for an item if we swapped its position to second.

We used `sample()` to inject a randomization element into our R programming. In R, the sample() function allows you to take a random sample of elements from a data set.
```r
x <- 1:12
# a random permutation
sample(x)

# bootstrap resampling -- only if length(x) > 1 !
sample(x, 100, replace = TRUE)
```

**Additional Resources**
-   [**Bias function****:**](https://www.rdocumentation.org/packages/SimDesign/versions/2.2/topics/bias "This link takes you to RDocumentation's description and examples of using the bias function.") This web page is a good starting point to learn about how the bias function in R can help you identify and manage bias in your analysis.
-   [**Data Science Ethics**](https://datasciencebox.org/ethics.html "This link takes you to the data science ethics section of the Data Science in a Box course."): This online course provides slides, videos, and exercises to help you learn more about ethics in the world of data analytics. It includes information about data privacy, misrepresentation in data, and applying ethics to your visualizations.

---

## More about visualizations, aesthetics, and annotations
### Visualization in R

Some different visualization packages you can use with R:
- Base R has its own package
- General-purpose packages like Plotly let you do a wide range of visualization functions.
- Others  Includes the following:  (e.g. like RGL, focus on specific solutions like 3D visuals)
> ggplot2
Plotly
Lattice
RGL
Dygraphs
Leaflet
Highcharter
Patchwork
gganimate
ggridges

#### ggplot2
Best for data analysis.
The first two letters of ggplot2 actually stand for grammar of graphics.

**Benefits of ggplot2:**
- Create different types of plots
Including scatter plots, bar charts, line diagrams and tons more.
- Customize the look and feel of plots
You can change the colors, layout and dimensions of your plots and add text elements like titles, captions and labels.
- Create high quality visuals
- Combine data manipulation and visualization
Using the pip `%>%` operator

##### Core concepts
- **Aesthetics**
***Aesthetic (R)***: A visual property of an object in your plot.
Think of an aesthetic as a connection or mapping between a visual feature in your plot and a variable in your data.
***Mapping (R)***: Matching up a specific variable in your dataset with a specific aesthetic.
For example, in a scatterplot, aesthetics include things like the size, shape, color, or location (x-axis, y-axis) of your data points.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image171.png)
- **Geoms**
**Geom $(\mathrm{R})$**: The geometric object used to represent your data.
For example, you can use points to create a scatter plot, bars to create a bar chart, or lines to create a line diagram.
Points show the relationship between two quantitative variables. Bars show one quantitative variable varies across different categories.
- **Facets**
***Facets $(\mathrm{R})$***: Let you display smaller groups, or subsets, of your data.
With facets, you can create separate plots for all the variables in your dataset.
- **Labels and annotations**
***Labels and annotations $(\mathrm{R})$***: Let you customize your plot.
You can add text like titles, subtitles and captions to communicate the purpose of your plot or highlight important data.

##### Hands-on Activity
Plot the relationship between body mass and flipper length in the three penguin species.

**Load libraries and dataset:**
```r
install.packages("ggplot2")
install.packages("palmerpenguins")
library(ggplot2)
library(palmerpenguins)

# load the dataset (?uncessary)
data(penguins)
View(penguins)
```

**Review the code piece by piece**
Points show the relationship between two quantitative variables. A scatterplot of points would be an effective way to display the relationship between the two variables.
Put flipper length on the x-axis and body mass on the y-axis.
```r
ggplot(data = penguins) + geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g))
```

**`ggplot(data = penguins)`:** In ggplot2, you begin a plot with the ggplot() function. The ggplot() function creates a coordinate system that you can add layers to. The first argument of the ggplot() function is the dataset to use in the plot. In this case, it’s “penguins.”

**`+`**: Then, you add a “+” symbol to add a new layer to your plot. You complete your plot by adding one or more layers to ggplot().
(p.s. Always put the plus sign at the end of a line of code. Not the beginning!)

**`geom_point()`**: Next, you choose a geom by adding a geom function. The `geom_point()` function uses points to create scatterplots, the `geom_bar()` function uses bars to create bar charts, and so on. In this case, choose the geom_point function to create a scatter plot of points.

**`(mapping = aes(x = flipper_length_mm, y = body_mass_g))`**: Each geom function in ggplot2 takes a mapping argument. This defines how variables in your dataset are mapped to visual properties. The mapping argument is always paired with the `aes()` function. The x and y arguments of the `aes()` function specify which variables to map to the x-axis and the y-axis of the coordinate system. In this case, you want to map the variable `flipper_length_mm` to the x-axis, and the variable `body_mass_g` to the y-axis.

> **Pro-Tip**: You can write the same section of code above using a different syntax with the mapping argument inside the ggplot() call: <br>`ggplot(data = penguins, mapping = aes(x = flipper_length_mm, y = body_mass_g)) +  geom_point()`


**Steps to create a plot:**
`ggplot(data=<DATA>)+<GEOM_FUNCTION>(mapping=aes(<AESTHETIC MAPPINGS>))`
1. Start with the ggplot() function and choose a dataset to work with.
2. Add a `geom_function` to display your data.
3. Map the variables you want to plot in the arguments of the `aes()` function.

**Full Template**
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image172.png)



### Explore aesthetics
**Aesthetic (R)**: A visual property of an object in your plot.
For example, in a scatter plot, aesthetics include the size, shape or color of your data points.

**Aesthetics for points:**
- X
- Y
- Color
this allows you to change the color of all of the points on your plot, or the color of each data group.
- Shape
this allows you to change the shape of the points on your plot by data group.
- Size
this allows you to change the size of the points on your plot by data group.
- Alpha

Map aesthetic color to another variable "species":
```r
ggplot(data = penguins) +
  geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g, color=species))
```
We can also map the variable species to the aesthetic shape by changing `color=species` to `shape=species`.

We can map more than one aesthetic to the same variable:
`..., color=species, shape=species, size=species, alpha=species))`
Eachr colored shape will also be a different size, while alpha aesthetic controls the transparency of the points.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image173.png)

Set color outside of the aes function to a single color:
```r
ggplot(data = penguins) +
  geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g), color="purple")
```

**For more information**
-   [**Data visualization with ggplot2 cheat sheet**](https://ggplot2.tidyverse.org/): RStudio’s cheat sheet is a great reference to use while working with ggplot2. It has tons of helpful information, including explanations of how to use geoms and examples of the different visualizations that you can create. 
-   [**Stats Education’s Introduction to R**](http://statseducation.com/Introduction-to-R/modules/graphics/aesthetics/ "This link takes you to the Aesthetic Attributes section of Stats Education's Introduction to R course."): This resource is a great way to learn the basics of ggplot2 and how to apply aesthetic attributes to your plots. You can return to this tutorial as you work more with ggplot2 and your own data. 
-   [**RDocumentation aes function**](https://www.rdocumentation.org/packages/ggplot2/versions/3.3.3/topics/aes "This link takes you to the aes function documentation on the RDocumentation website."): This guide describes the syntax of the aes function and explains what each argument does.


### Doing more with ggplot
Same data using different geom: (Left uses `geom_point`. Right uses a `geom_smooth`.)
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image174.png)

**Geom (R)**: The geometrical object used to represent your data.

**Geom functions:**
- geom_point
- geom_bar
- geom_line
- etc.


#### geom_smooth

**Use two geoms in the same plot:**
```r
ggplot(data = penguins) +
  geom_smooth(mapping = aes(x = flipper_length_mm, y = body_mass_g)) +
  geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g))
```
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image175.png)

**Plot a different line types for each species of penguin:**
```r
ggplot(data = penguins) +
  geom_smooth(mapping = aes(x = flipper_length_mm, y = body_mass_g, linetype=species))
```

**Two types of smoothing:**

| **Type of smoothing** | **Description**                                                                                                       | **Example code**                                                                                |
|:--------------------- |:--------------------------------------------------------------------------------------------------------------------- |:----------------------------------------------------------------------------------------------- |
| **Loess smoothing**   | The loess smoothing process is best for smoothing  plots with less than 1000 points.                                  | `ggplot(data, aes(x=, y=))+   geom_point() +      geom_smooth(method="loess")`                    |
| **Gam smoothing**     | Gam smoothing, or generalized additive model  smoothing, is useful for smoothing plots with a large number of points. | `ggplot(data, aes(x=, y=)) +   geom_point() +      geom_smooth(method="gam",  formula = y ~s(x))` |
By default, method is chosen automatically based on the size of the largest group.

####  geom_jitter()
The `geom_jitter()` function creates a scatter plot and then adds a small amount of random noise to each point in the plot.
Jittering helps us deal with over-plotting, which happens when the data points in a plot overlap with each other.
`ggplot(data = penguins) +
  geom_jitter(mapping = aes(x = flipper_length_mm, y = body_mass_g))`

#### theme()
Rotates the text to 45 degrees to make it easier to read:
`+ theme(axis.text.x = element_text(angle = 45))`
```r
ggplot(data = hotel_bookings) +
  geom_bar(mapping = aes(x = distribution_channel)) +
  facet_wrap(~deposit_type) +
  theme(axis.text.x = element_text(angle = 45))
```
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image176.png)


#### geom_bar()
When you use geom underscore bar, R automatically counts how many times each x-value appears in the data, and then shows the counts on the y-axis. The default for geom underscore bar is to count rows.

Some aesthetics:
- color: outline color of the bars
- fill: inside color of the bars

```r
ggplot(data = diamonds) +
  geom_bar(mapping = aes(x=cut))

ggplot(data = diamonds) +
  geom_bar(mapping = aes(x=cut, fill=cut))
```
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image177.png)


If we map fill to a new variable, `geom_bar()` will display what's called a stacked bar chart. Let's map fill to clarity instead of cut.
```r
ggplot(data = diamonds) +
  geom_bar(mapping = aes(x=cut, fill=clarity))
```
Our plot now shows 40 different combinations of cut and clarity. Each combination has its own colored rectangle.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image178.png)


#### facets_
**Facets $(R)$**: Let you display smaller groups, or subsets, of your data.
A facet is a side or section of an object, like the sides of a gemstone.

**Facet functions:**
- Facet_wrap()
To facet your plot by a single variable, use facet underscore wrap.
- Facet_grid()

##### facet_wrap
Create a separate plot for each penguin species:
(a tilde symbol `~`, followed by the name of the variable)
(And rotates the text to 45 degrees to make it easier to read)
```r
ggplot(data = penguins) +
  geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g, color=species)) +
  facet_wrap(~species) + 
  theme(axis.text.x = element_text(angle = 45))
```
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image179.png)

##### facet_grid
To facet your plot with two variables, use the `facet_grid()` function.
Facet underscore grid will split the plot into facets vertically by the values of the first variable and horizontally by the values of the second variable.
```r
ggplot(data = penguins) +
  geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g, color=species)) +
  facet_grid(sex~species)
# or facet_grid(~sex~species)
```
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image180.png)

If we want, we can focus our plot on only one of the two variables:
```r
ggplot(data = penguins) +
  geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g, color=species)) +
  facet_grid(~sex) + 
  theme(axis.text.x = element_text(angle = 45))
```
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image181.png)


#### filtering data for plotting
Use the filter function from **dplyr** to make the plots you create with **ggplot2** easier to read:
```r
data %>%
    filter(variable1 == "DS") %>%  
    ggplot(aes(x = weight, y = variable2, colour = variable1)) +  
    geom_point(alpha = 0.3,  position = position_jitter()) + stat_smooth(method = "lm")

# hotel booking example in `Lesson3_Filters`
hotel_bookings %>% 
  filter(hotel=="City Hotel" & hotel_bookings$market_segment=="Online TA") %>% 
  ggplot(mapping = aes(x = lead_time, y = children)) + geom_point()
```

**Additional resources**
To learn more details about ggplot2 and filtering with dplyr, check out these resources:
-   [**Putting it all together: (dplyr+ggplot)**](https://rladiessydney.org/courses/ryouwithme/03-vizwhiz-1/#1-4-putting-it-all-together-dplyr-ggplot "This link takes you to a dplyr and ggplot section of an R-Ladies Sydney course.")**:** The RLadies of Sydney’s course on R uses real data to demonstrate R functions. This lesson focuses specifically on combining dplyr and ggplot to filter data before plotting it. The instructional video will guide you through every step in the process while you follow along with the data they have provided. 
-   [**Data transformation:**](https://r4ds.had.co.nz/transform.html "This link takes you to Chapter 5: Data Transformation in the R for Data Science book.") This resource focuses on how to use the filter() function in R, and demonstrates how to combine filter() with ggplot(). This is a useful resource if you are interested in learning more about how filter() can be used before plotting. 
-   [**Visualizing data with ggplot2:**](https://datacarpentry.org/dc_zurich/R-ecology/05-visualisation-ggplot2.html "This link takes you to Data Carpentry's documentation on visualizating data with ggplot2.") This comprehensive guide includes everything from the most basic uses for ggplot2 to creating complicated visualizations. It includes the filter() function in most of the examples so you can learn how to implement it in R to create data visualizations.



### Annotate
**Annotate**: To add notes to a document or diagram to explain or comment upon it.

Labels and annotations will point stakeholders' attention to key things and help them quickly understand your plot.

#### labs function
Titles, subtitles, and captions are labels that we put outside of the grid of our plot to indicate important information.

`labs(title="xx", subtitle="xx", caption="xx", x="xx", y="xx")`

```r
# Add a title, a subtitle and a caption
ggplot(data = penguins) +
  geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g, color=species)) +
  labs(title="Palmer Penguins: Body Mass vs. Flipper Length", subtitle="Sample of Three Penguin Species", caption="Data Collected by Dr. Kristen Gorman")
```
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image182.png)

```r
# Lesson4_Annotations.Rmd
ggplot(data = hotel_bookings) +
  geom_bar(mapping = aes(x = market_segment)) +
  facet_wrap(~hotel) +
  theme(axis.text.x = element_text(angle = 45)) +
  labs(title="Comparison of market segments by hotel type for hotel bookings",
       caption=paste0("Data from: ", mindate, " to ", maxdate),
       x="Market Segment",
       y="Number of Bookings")
```
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image183.png)


#### annotate function
If we want to put text inside the grid to call out specific data points, we can use the annotate function.
`annotate("text", x=220, y=3500, label="The Gentoos are the largest")`
\<type of label\> \<the specific location of the label\>  \<the context of the label\>.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image184.png)

We can change text color, font style, size or even angle:
`annotate("text", x=220, y=3500, label="xxx", color="purple", fontface="bold", size=4.5, angle=25)`
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image185.png)

#### Store your plot as a variable
By this point, our code is getting pretty long. If you want to use less code, you can store your plot as a variable.
```r
p <- ggplot(data = penguins) +
  geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g, color=species)) +
  labs(title="Palmer Penguins: Body Mass vs. Flipper Length", subtitle="Sample of Three Penguin Species", caption="Data Collected by Dr. Kristen Gorman")

p + annotate("text", x=220, y=3500, label="The Gentoos are the largest")
```



#### Drawing arrows and shapes
You can now add lines, arrows, and shapes to your plots using **ggplot2**.
```r
# Add rectangles
p + annotate("rect", xmin=c(2,4), xmax=c(3,5), ymin=c(20,10) , ymax=c(30,20), alpha=0.2, color="blue", fill="blue")

# Add segments
p + annotate("segment", x = 1, xend = 3, y = 25, yend = 15, colour = "purple", size=3, alpha=0.6)

# Add arrow
p + annotate("segment", x = 2, xend = 4, y = 15, yend = 25, colour = "pink", size=3, alpha=0.6, arrow=arrow())
```
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image186.png)

-   [**Create an annotation layer**](https://ggplot2.tidyverse.org/reference/annotate.html "This link takes you to the tidyverse ggplot2 documentation on creating an annotation layer. "): This guide explains how to add an annotation layer with ggplot2. It includes sample code and data visualizations with annotations created in ggplot2. 
-   [**How to annotate a plot in ggplot2**](https://www.r-graph-gallery.com/233-add-annotations-on-ggplot2-chart.html "This link takes you to the R Graph Gallery's instructions to annotate a plot in ggplot2.")**:** This resource includes explanations about how to add different kinds of annotations to your ggplot2 plots, and is a great reference if you need to quickly look up a specific kind of annotation. 
-   [**Annotations**](https://ggplot2-book.org/annotations.html "This link takes you to Chapter 8: Annotations in a ggplot2 book. ")**:** Chapter eight of the online ggplot2 textbook is focused entirely on annotations. It provides in-depth explanations of the different types of annotations, how they are used, and detailed examples. 
-   [**How to annotate a plot**](https://www.r-bloggers.com/2017/02/how-to-annotate-a-plot-in-ggplot2/ "This link takes you to an R-Bloggers post on how to annotate a plot.")**:** This R-Bloggers article includes explanations about how to annotate plots in ggplot2. It starts with basic concepts and covers more complicated information the further on you read. 
-   [**Text Annotations**](https://viz-ggplot2.rsquaredacademy.com/textann.html "This link takes you to Chapter 5: Text Annotations in the Data Visualization with ggplot2 book.")**:** This resource focuses specifically on adding text annotations and labels to ggplot2 visualizations.


### Saving your visualizations
Use the Export option in the plots tab of RStudio or the `ggsave` function provided by the ggplot2 package.

#### Export
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image187.png)

#### ggsave
It defaults to saving the last plot that you displayed and uses the size of the current graphics device.
```r
# save png file at `getwd()` location
ggsave("Three Penguin Species.png")
```

**Change your working directory**
- Use "Session --> Set Working Directory" to set the work directory. Or,
- `getwd()`,  `setwd("/path/to/my/directory")`

**specify the height and width**
- `ggsave('xxx.png', width=16, height=8)`

#### Saving images without ggsave
To save images without using ggsave(), you can open a regular R graphics device like **png()** or **pdf()**; these will allow you to save your plot as a .png or .pdf file. You can also choose to print the plot and then close the device using **dev.off()**.

| **Example of using png()**                                                                             | **Example of using pdf()**                                                                                                                                                                      |
|:------------------------------------------------------------------------------------------------------ |:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| png(file = "exampleplot.png", bg = "transparent") plot(1:10) rect(1, 5, 3, 7, col = "white") dev.off() | pdf(file = "/Users/username/Desktop/example.pdf",         width = 4,          height = 4) plot(x = 1:10,           y = 1:10) abline(v = 0) text(x = 0, y = 1, labels = "Random text") dev.off() |

-   [**Saving images without ggsave()**](https://ggplot2.tidyverse.org/reference/ggsave.html#saving-images-without-ggsave- "This link takes you to tidyverse's ggplot2 documentation on saving images without ggsave()."): This resource is pulled directly from the ggplot2 documentation at [**tidyverse.org**](https://www.tidyverse.org/). It explores the tools you can use to save images in R, and includes several examples to follow along with and learn how to save images in your own R workspace. 
-   [**How to save a ggplot**](https://www.datanovia.com/en/blog/how-to-save-a-ggplot/ "This link takes you to Data Novia's blog on how to save a ggplot."): This resource covers multiple different methods for saving ggplots. It also includes copyable code with explanations about how each function is being used so that you can better understand each step in the process.  

-   [**Saving a plot in R:**](https://www.datamentor.io/r-programming/saving-plot/ "This link takes you to Data Mentor's article on how to save a plot as a bitmap, vector image, PDF, or PostScript file.") This guide covers multiple file formats that you can use to save your plots in R. Each section includes an example with an actual plot that you can copy and use for practice in your own R workspace.


---

## Documentation and reports
Document and report your work using R Markdown.

You can use an R Markdown file as a code notebook to save, organize, and document your analysis using code chunks, comments, and other features.

An overview of R Markdown
How to install R Markdown in RStudio
How to create an R Markdown document
The structure and components of the document
How to insert and edit pieces of code called chunks in your document
The process of exporting your documentation

### Overview of R Markdown
**R Markdown**: A file format for making dynamic documents with $\mathrm{R}$.
It ties together your code and your report so you can share every step of your analysis. And you don't even have to leave RStudio to do this.

R Markdown documents are written in Markdown.
**Markdown**: A syntax for formatting plain text files.

Besides text, R Markdown also includes an interactive option called an R Notebook that lets users run your code and show the graphs and charts that visualize the code.
**$\mathrm{R}$ Notebook**: Lets users run your code and show the graphs and charts that visualize the code.

R Markdown lets you convert your files into lots of different formats:
- HTML, PDF, and Word documents
- Slide presentation
- Dashboard

The Markdown language was originally designed for HTML output.
**HTML**: The set of markup symbols or codes used to create a webpage.

**Other notebook options:**
- Jupyter
- Kaggle
- Google Colab

### Structure of R Markdown
R Markdown is a great tool for documenting your analysis at any stage
"File --> New File --> R Markdown..." to create a new markdown file.
Click the Knit button to creates a shareable HTML report.
The code chunks are run and the output appears in the HTML report.

#### YAML header
**YAML**: A language for data that translates it so it's readable.
(yet another markup language)
```yaml
---
title: "R Markdown Intro"
author: "Carrie"
date: "11/12/2020"
output: html_document
---
```

#### Code chunk
**Code chunk**: Code added in an . Rmd file.
Inline code is code that can be inserted directly into a .rmd file.

The first code chunk will set up our R environment by loading our packages using the library function.

Using "Insert" code chunk button to creates a gray section in our file and chunk delimiters.
**Delimiter**: A character that indicates the beginning or end of a data item.
```r
# Keyboard shortcut to create chunk:
# PC/Chromebook: ctrl + alt + I
# Mac: command + option + I

# add a space and label the chunk
```{r this is label}

```

Change the code chunk options:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image188.png)

### Exporting documentation
Using the Knit button to converte the Rmd file into HTML, PDF or Word doc.

But it's good practice to stick with HTML while you're working.
HTML doesn't have page breaks, so you can focus on generating content for your report and not its appearance.

#### Documents
Change the `output: html_document` inside the YAML header to set the default Knit button action. Includes:
-   **pdf_document** – This creates a PDF file with LaTeX (an open source document layout system). If you don’t already have LaTeX, RStudio will automatically prompt you to install it.
-   **word_document** – This creates a Microsoft Word document (.docx).
-   **odt_document** – This creates an OpenDocument Text document (.odt).
-   **rtf_document** – This creates a Rich Text Format document (.rtf).
-   **md_document** – This creates a Markdown document (which strictly conforms to the original Markdown specification)
-   **github_document** – This creates a GitHub document which is a customized version of a Markdown document designed for sharing on GitHub.

For a detailed guide to creating different types of R Markdown documents, check out the [Documents](https://bookdown.org/yihui/rmarkdown/documents.html "This link takes you to Chapter 3: Documents in R Markdown: The Definitive Guide.") chapter in _R Markdown: The Definitive Guide_.

#### Notebooks
-   **html_notebook** - A variation on an HTML document (html_document) which includes an embedded copy of the source code.

To learn more, check out the section on [Notebooks](https://rmarkdown.rstudio.com/lesson-10.html "This link takes you to the Notebooks section of RStudio's R Markdown documentation.") in the R Markdown documentation.


#### Presentations
-   **beamer_presentation** – for PDF presentations with beamer
-   **ioslides_presentation** – for HTML presentations with ioslides
-   **slidy_presentation** – for HTML presentations with Slidy
-   **powerpoint_presentation** – for PowerPoint presentations
-   **revealjs : : revealjs_presentation** – for HTML presentations with reveal.js (a framework for creating HTML presentations that requires the reveal.js package)

To learn more about producing presentations, check out the section on [Slide Presentations](https://rmarkdown.rstudio.com/lesson-11.html "This link takes you to the Slide Presentations section of RStudio's R Markdown documentation.") in the R Markdown documentation.

#### Dashboards
Dashboards are a useful way to quickly communicate a lot of information. The [flexdashboard](https://github.com/rstudio/flexdashboard "This link takes you to the flexdashboard package on GitHub.") package lets you publish a group of related data visualizations as a dashboard. Flexdashboard also provides tools for creating sidebars, tabsets, value boxes, and gauges. 

To learn more, visit the [flexdashboard for R](https://rmarkdown.rstudio.com/flexdashboard/ "This link takes you to RStudio's flexdashboard for R content.") page and the [Dashboards](https://rmarkdown.rstudio.com/lesson-12.html "This link takes you to Dashboard section of RStudio's R Markdown documentation.") section in the R Markdown documentation.

#### Shiny
**Shiny** is an R package that lets you build interactive web apps using R code. You can embed your apps in R Markdown documents or host them on a webpage. 

To call Shiny code from an R Markdown document, add  runtime: shiny to the YAML header:
```r
---
title: "Shiny Web App"
output: html_document
runtime: shiny
---
```
To learn more about Shiny and how to use R code to add interactive components to an R Markdown document, check out the [Shiny](https://shiny.rstudio.com/tutorial/ "This link takes you to RStudio's Shiny tutorial.") tutorial from RStudio.

#### Other formats
-   The [bookdown](https://github.com/rstudio/bookdown "This link takes you the the bookdown package on GitHub.") package is helpful for writing books and long-form articles.
-   The [prettydoc](https://github.com/yixuan/prettydoc/ "This link takes you to the prettydoc package on GitHub.") package provides a range of attractive themes for R Markdown documents.
-   The [rticles](https://github.com/rstudio/rticles "This link takes you to the rticles package on GitHub.") package provides templates for various journals and publishers.
 
 Visit the [RStudio Formats](https://rmarkdown.rstudio.com/formats.html "This link takes you to the RStudo Formats page in RStudio's R Markdown documentation.") page in the R Markdown documentation for a more comprehensive list of output formats and packages.


#### Additional resources
For more information, check out these additional resources:
-   The [R Markdown gallery](https://rmarkdown.rstudio.com/gallery.html "This link takes you to RStudio's R Markdown gallery.") from RStudio has tons of examples of the outputs you can create with R Markdown. 
-   The [R Markdown Formats](https://r4ds.had.co.nz/r-markdown-formats.html "This link takes you the Chapter 29: R Markdown Formats in the R for Data Science book.") chapter in the _R for Data Science_ book provides more details about the output formats introduced in this reading. This reading was compiled from information in this book.


### Templates
Templates allow you to use customized documents and there are lots of R packages that include custom templates for a variety of purposes. For example, there are templates for academic journal articles, for interactive presentations, or for vignettes summarizing the contents of R packages.
Creating a template for your reports allows you to run one line of code to update your data without having to recreate the report from scratch. Templates can also help you customize the appearance of your final report.

#### R packages with templates
-   The [**vitae**](https://github.com/mitchelloharawild/vitae) package contains templates for creating and maintaining a ***résumé*** or ***curriculum vitae (CV)***
-   The [**rticles**](https://github.com/rstudio/rticles) package provides templates for various ***journals*** and publishers
-   The [**learnr**](https://github.com/rstudio/learnr) package makes it easy to turn any R Markdown document into an interactive ***tutorial*** 
-   The [**bookdown**](https://github.com/rstudio/bookdown) package facilitates writing ***books*** and long-form articles
-   The [**flexdashboard**](https://github.com/rstudio/flexdashboard) package lets you publish a group of related data visualizations as a ***dashboard***

#### Example: vitae CV
```r
install.packages("vitae")
library(vitae)
```
**File** > **New File** > **R Markdown** > **From Template**
(If not exist, restart RStudio)
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image189.png)

The YAML header contains entries for general information, such as name, address, phone number, and more.
In the below, the header text introduces separate sections for topics like personal information.




### R Markdown resources
**R Markdown documentation**

RStudio's [R Markdown documentation](https://rmarkdown.rstudio.com/lesson-1.html "This link takes you to RStudio's R Markdown documentation and training.") includes a series of tutorials that will help you learn about the main features of R Markdown, including code chunks, output formats, notebooks, interactive documents, and more. The tutorials include online lessons that you can complete directly in your RStudio Cloud workspace. 

**R Markdown reference materials**

RStudio has developed a reference guide and a cheat sheet that you can bookmark and use whenever you practice writing R Markdown files.  

-   The [R Markdown Reference Guide](https://rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf?_ga=2.49295910.1034302809.1602760608-739985330.1601281773 "This link takes you to RStudio's R Markdown Reference Guide.") contains three sections: Markdown syntax, knitr chunk options, and Pandoc options. The guide is super detailed and includes tons of examples and explanations so that you can easily find the exact information you need to customize your R Markdown documents. 
-   The [R Markdown Cheat Sheet](https://rmarkdown.rstudio.com/lesson-15.html "This link takes you to RStudio's R Markdown Cheat Sheet.") is a convenient summary of the different steps and workflow processes for R. It also includes sections with abbreviated explanations of knitr and pandoc chunk options, and other useful information to review or look up while you work.

**R for Data Science book**

For a well-organized introduction to the basics of R Markdown, check out the [Communicate](https://r4ds.had.co.nz/communicate-intro.html "This link takes you to Chapter 26: Introduction in the Communicate section of the R for Data Science book.") section of the **R for Data Science** book. It covers the main features and functions of R Markdown, the various output formats, and the workflow for combining text and code to create an analysis notebook.

**R Markdown: The Definitive Guide **

If you want to really explore the capabilities of R Markdown in a systematic way, [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/ "This link takes you to the book entitled R Markdown: The Definitive Guide.") provides a comprehensive guide to the R Markdown ecosystem. This book contains four main parts:

1.  [Part I](https://bookdown.org/yihui/rmarkdown/installation.html "This link takes you to Chapter 1: Installation in R Markdown: The Definitive Guide.") explains how to install the relevant packages and offers an overview of R Markdown, including the syntax for Markdown and code chunks.
2.  [Part II](https://bookdown.org/yihui/rmarkdown/documents.html "This link takes you to Chapter 3: Documents in R Markdown: The Definitive Guide.") provides detailed documentation of the built-in output formats included in R Markdown, like document formats and presentation formats. 
3.  [Part III](https://bookdown.org/yihui/rmarkdown/dashboards.html "This link takes you to Chapter 5: Dashboards in R Markdown: The Definitive Guide.") shares several R Markdown extension packages that allow you to build different applications or generate output documents with different styles. 
4.  [Part IV](https://bookdown.org/yihui/rmarkdown/parameterized-reports.html "This link takes you to Chapter 15: Parameterized reports in R Markdown: The Definitive Guide.") covers advanced topics in R Markdown.



### Jupyter notebooks
**Jupyter notebooks** are documents that contain computer code and rich text elements – such as comments, links, or descriptions of your analysis and results. You will find them used in a variety of online tools, including Project Jupyter, Kaggle, and Google Colaboratory ("Colab" for short). These notebooks can be executable documents that you can run to perform an analysis. 

Jupyter notebooks can come in handy with everything from data cleaning and transformation, to statistical modeling and visualizations. They are compatible with R, so you can consider them as an alternative to R Markdown. And just like R Markdown documents, you can easily share Jupyter notebooks with team members and stakeholders. 

**Jupyter notebooks in Kaggle**

If you are working in Kaggle, there are two types of notebooks available: Jupyter notebooks and scripts (including R Markdown scripts). For more information, refer to the [How to Use Kaggle Notebooks](https://www.kaggle.com/docs/notebooks "How to Use Kaggle Notebooks") page.

**Jupyter notebooks in Google Colab**

Google Colab is a product from Google Research. Colab is a hosted Jupyter notebook service that requires no setup to use. For more information, refer to the [Welcome to Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb "Welcome to Colaboratory") page.

**Additional resources**

To learn more about Jupyter notebooks, check out these resources: 

-   [**Project Jupyter**](https://jupyter.org/ "Project Jupyter"): This is the home of Jupyter notebooks, as well as JupyterLab – the web-based interactive development environment for Jupyter notebooks, code, and data. 
-   [**Jupyter Notebook: An Introduction**](https://realpython.com/jupyter-notebook-introduction/ "Jupyter Notebook: An Introduction"): This detailed introduction of Jupyter notebooks comes from the people at Real Python, a tutorial-based site devoted to all things Python. You can take a video course or follow the written tutorial to get started with Jupyter notebooks and learn about its features and capabilities.

A​nd, just like R Markdown, Jupyter notebooks include basic formatting tools and rules that will help you keep your work organized and user-friendly. In fact, Jupyter uses R Markdown as its language for writing and formatting text in a notebook. 

To learn about basic formatting in Jupyter notebooks, check out these resources: 

-   [**The Jupyter** **Notebook**](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html "The Jupyter Notebook")**:** This resource provides an overview of Jupyter notebooks, including information about the structure of the user interface and notebook document. You’ll also learn about the basic workflow for using a notebook document, along with information about keyboard shortcuts and other features that will help you format your work.
-   [**Using Jupyter Notebook for Writing**](https://gtribello.github.io/mathNET/assets/notebook-writing.html "Using Jupyter Notebook for Writing")**:** This resource focuses on how to use Markdown to format your writing in a Jupyter notebook. Use this as a guide to manage the syntax of your writing, including making titles and subtitles and adding links.
-   [**The Jupyter Notebook Formatting Guide**](https://medium.com/analytics-vidhya/the-jupyter-notebook-formatting-guide-873ab39f765e "The Jupyter Notebook Formatting Guide"): This resource includes a wide variety of formatting options for Jupyter notebooks. You’ll learn about the basics as well as some more advanced options, like embedding PDF documents and videos.







---

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

---

## Appendix
### R Markdown
`R markdown` allows you to put code and writing in the same place.

When you have written, executed, and documented your code in an `R markdown` document like this, you can use the `knit` button in the menu bar at the top of the editing pane to export your work to a beautiful, readable document for others.

### R libraries
palmer penguins
```r
install.packages('palmerpenguins')
library('palmerpenguins')
```

ggplot2
```r
install.packages('ggplot2')
library('ggplot2')
```

### R-versus-Python

| Languages              | R                                                                                                                                                                                    | Python                                                                                                                                                                                                          |
|:---------------------- |:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Common  features**   | - Open-source - Data stored in data frames - Formulas and functions readily available - Community for code development and support                                                   | - Open-source - Data stored in data frames - Formulas and functions readily available - Community for code development and support                                                                              |
| **Unique  advantages** | - Data manipulation, data visualization, and   statistics packages  - "Scalpel" approach to data: *find packages to do what you want with the data*                                  | - Easy syntax for machine learning needs - Integrates with cloud platforms like Google Cloud,   Amazon Web Services, and Azure                                                                                  |
| **Unique  challenges** | - Inconsistent naming conventions make it  harder for beginners to select the right functions - Methods for handling variables may be a little   complex for beginners to understand | - Many more decisions for beginners to make about   data input/output, structure, variables, packages,  and objects - "Swiss army knife" approach to data: *figure out a way to do what you want with the data* |

-   [R versus Python, a comprehensive guide for data professionals](https://medium.com/analytics-and-data/r-vs-python-a-comprehensive-guide-for-data-professionals-321e8dead598 "R vs. Python, a comprehensive guide for data professionals"): This article is written by a data professional with extensive experience using both languages and provides a detailed comparison. 
-   [R versus Python, an objective comparison](https://www.dataquest.io/blog/python-vs-r/ "R vs. Python, an objective comparison"): This article provides a comparison of the languages using examples of code use. 
-   [R versus Python: What’s the best language for data science?](https://blog.rstudio.com/2019/12/17/r-vs-python-what-s-the-best-for-language-for-data-science/ "R vs. Python: What's the best language for data science"): This blog article provides RStudio’s perspective on the R vs. Python debate.
-   [RStudio: A Single Home for R & Python](https://www.rstudio.com/solutions/r-and-python/ "RStudio: A Single Home for R and Python")
-   [Ways to learn about programming](https://www.coursera.org/learn/data-analysis-r/supplement/y8zTf/ways-to-learn-about-programming "Ways to learn about programming")


### Programming languages by profession
#### Data analyst

A data analyst collects, transforms, and organizes data to draw conclusions, make predictions, and drive informed decision-making. The most popular programming languages used by data analysts are R and Python. 

**R** offers convenient statistical features for data analysis and is useful for creating advanced data visualizations. Check out these resources to learn more about R:

-   [The R Project for Statistical Computing](https://www.r-project.org/ "This link takes you to the R Project home page."): a website for downloading R, documentation, and help
-   [R Manuals](https://cran.r-project.org/manuals.html "This link takes you to the R manuals from the R core team."): links to manuals from the R core team, including introduction, administration, and help
-   [Coding Club R Tutorials](https://ourcodingclub.github.io/tutorials.html "This link takes you to R tutorials from the Coding Club."): a collection of coding tutorials for R
-   [R for Beginners](https://cran.r-project.org/doc/contrib/Paradis-rdebuts_en.pdf "This link takes you to a downloadable R for Beginners guide."): a starting guide to help you work with data, graphics, and statistics in R

**Python** is a general-purpose language that you can use to create what you need for data analysis. Here are a few resources to begin learning Python:

-   [The Python Software Foundation (PSF)](https://www.python.org/about/gettingstarted/ "This link takes you the Python Software Foundation's Getting Started resources."): a website with guides to help you get started as a beginner 
-   [Python Tutorial](https://docs.python.org/3/tutorial/ "This link takes you to the Python Software Foundation's Python Tutorial."): a Python 3 tutorial from the PSF site
-   [Coding Club Python Tutorials](https://ourcodingclub.github.io/tutorials.html "This link takes you to Python tutorials from the Coding Club."): a collection of coding tutorials for Python

#### Web designer

A web designer is responsible for the styling and layout of web pages containing text, graphics, and video. Web designers generally use Hypertext Markup Language v5 (HTML5) and Cascading Style Sheets (CSS) to create web pages. 

**HTML5** provides structure for web pages and is used to connect to hosting platforms. Learn more about HTML5 and CSS using these resources:

-   [HTML Tutorial](https://www.tutorialrepublic.com/html-tutorial/ "This link takes you to Tutorial Republic's basic and advanced HTML tutorials."): an introduction to HTML with links to HTML5 features, examples, and references
-   [HTML5 Cheat Sheet](https://www.wpkube.com/html5-cheat-sheet/ "This link takes you to an HTML5 cheat sheet."): a handy summary of HTML5 tags, attributes, and compatibility with HTML4
-   [HTML5 and CSS Fundamentals course](https://www.edx.org/course/html5-and-css-fundamentals "This link takes you to an edX HTML5 and CSS Fundamentals course."): a free W3C course on edX; a verified course certificate can be issued for $199 

**CSS** is used for web page design and controls graphic elements (color, layout, and font) and page presentation on multiple devices (large screens, mobile screens, and printers). Check out these cheat sheets for CSS:

-   [Interactive CSS Cheat Sheet](https://htmlcheatsheet.com/css/ "This link takes you to a CSS cheat sheet."): includes the most common CSS snippets for gradient, background, font-family, border, and much more
-   [50 Best HTML & CSS Cheat Sheets](https://sharethis.com/best-practices/2020/02/best-html-and-css-cheat-sheets/ "This link takes you to a list of top 50 HTML and CSS cheat sheets."): a list of 50 cheat sheets–choose a few that are useful to you

#### Mobile application developer

A mobile application developer uses programming to create applications used on laptops, mobile phones, and tablets. The most popular programming languages for mobile application developers are Swift, Java, and C#.

**Swift** (for Apple platforms) is an open source scripting language for macOS, iOS, watchOS, and tvOS. Its main goal is to make applications run faster. Browse these resources for more information about Swift:

-   [Swift.org](https://swift.org/about/ "This link takes you to the Swift.org home page."): an open source community with resources to learn how to use Swift, including videos and sample code
-   [Swift developer site](https://developer.apple.com/swift/ "This link takes you to Apple's Swift developer web site."): an Apple developer website with information for developers who want to use Swift 
-   [Swift development resources](https://developer.apple.com/swift/resources/ "This link takes you to Apple's resources for Swift developers."): Apple’s collection of documentation, sample code, videos, and recommended books 

**Java** (for Android devices) is the official language for Android development. The article [I want to develop Android apps - which languages should I learn?](https://www.androidauthority.com/develop-android-apps-languages-learn-391008/ "This link takes you to an article that describes languages for Android development.") explores some other languages used for Android development. Check out these resources for Java:

-   [Android Studio](https://developer.android.com/studio "This link takes you to the Android Studio home page."): a downloadable integrated development environment (IDE) with tools to build apps for Android devices
-   [Build your first Android app in Java](https://developer.android.com/codelabs/build-your-first-android-app#1 "This link takes you to a tutorial to build a Java app for Android."): instructions for installing Android Studio and creating your first app
-   [Java tutorial for beginners: write a simple app with no previous experience](https://www.androidauthority.com/java-tutorial-for-beginners-write-a-simple-app-with-no-previous-experience-1121975/ "This link takes you to an Android Authority tutorial for Java."): an overview of how to learn Java, with examples

**C#** (pronounced C-sharp) is an object-oriented programming language that is widely used to create mobile apps in the .NET open source developer platform. Xamarin extends the .NET platform with a framework for developers to create cross-platform mobile apps for both iOS and Android. Here are a few resources to help you learn C#:

-   [Microsoft .NET learning materials for C#](https://dotnet.microsoft.com/learn/csharp "This link takes you to Microsoft .NET videos for learning C#."): includes free courses, tutorials, and videos to learn the programming language C#
-   [Microsoft Xamarin learning materials](https://dotnet.microsoft.com/learn/xamarin "This link takes you to Microsoft videos on using the Xamarin framework to create mobile apps."): includes free courses, tutorials, and videos to learn about mobile development with Xamarin
-   [Xamarin Tutorial - build your first iOS or Android app in C#](https://dotnet.microsoft.com/learn/xamarin/hello-world-tutorial/intro "This link takes you to a Microsoft tutorial on building an Android app in C#."): instructions for building a mobile app that displays the text “Hello World”
-   [Learn C# from Codecademy](https://www.codecademy.com/learn/learn-c-sharp "This link takes you to a Codecademy course for C#."): a website with free basic interactive lessons, and additional activities that can be accessed with a monthly subscription

#### Web application developer

A web application developer designs and develops network applications used across the web. The most popular programming languages used by web application developers are Java, Python, Ruby, and PHP.

**Java** is widely used to create enterprise web applications that can run on multiple clients. Java’s main strength is its “Write Once, Run Anywhere” (WORA) approach.Browse these resources to learn more about Java:

-   [Oracle Java Tutorials](https://docs.oracle.com/javase/tutorial/ "This link takes you to Oracle's Java tutorials."): Java tutorials from Oracle documentation
-   [Java for Beginners](https://www.homeandlearn.co.uk/java/java.html "This link takes you to a free Java course from Home and Learn."): a free Java course for beginners from the website “Home and Learn”

**Python** is a general-purpose programming language. Check out the Python resources listed in the data analyst section.

**Ruby** is a general-purpose, object-oriented programming language used for web application development. Ruby isn't the same as Ruby on Rails, which is an open source web application framework that runs using Ruby. Browse these resources to learn more about Ruby: 

-   [Ruby news](http://ruby-doc.org/ "This link takes you to the Ruby-Doc.org home page."): information about the latest Ruby releases and links to other resources
-   [Ruby documentation](http://www.ruby-lang.org/en/documentation/ "This link takes you to the Ruby documentation from ruby-lang.org."): includes guides, tutorials, and reference material to help you learn more about Ruby
-   [Ruby programmer’s guide](http://ruby-doc.com/docs/ProgrammingRuby/ "This link takes you to a Ruby programmer's guide from Ruby-Doc.org."): a tutorial and reference guide for Ruby
-   [Learn Ruby from Codecademy](https://www.codecademy.com/learn/learn-ruby "This link takes you to a Codecademy course for Ruby."): a website with free basic interactive lessons, and additional activities that can be accessed with a monthly subscription

**PHP** is a scripting language particularly suited for web application development. It was based on Perl, another programming language. PHP is simple, flexible, and relatively easy to learn. Check out these resources to learn more about PHP:

-   [PHP downloads and documentation](https://www.php.net/ "This link takes you to the php.net home page."): information about the latest PHP releases and links to other resources
-   [PHP the Right Way](https://phptherightway.com/ "This link takes you to the "PHP The Right Way" page."): a quick reference for popular PHP coding standards
-   [Interactive PHP tutorial](https://www.learn-php.org/ "This link takes you to learn-php.org's PHP tutorial."): a free tutorial that runs PHP code in exercises

#### Game developer

A game developer is an application developer who specializes in video game creation. Game developers most commonly use the programming languages C# and C++.

**C#** is an object-oriented programming language that is widely used to create games. Check out the C# resources listed in the mobile application developer section.

**C++** is an extension of the C programming language that is also used to create console games, like those for Xbox. Browse more information about C++:

-   [Microsoft resources for C++](https://docs.microsoft.com/en-us/cpp/?view=msvc-160 "This link takes you to Microsoft's C++ documentation."): learn how to install the Visual Studio IDE and write C++ code
-   [Microsoft C++ and C# code samples for gaming](https://docs.microsoft.com/en-us/samples/browse/?languages=cpp&terms=gaming "This link takes you to Microsoft C++ and C# code samples for gaming."): a resource with over 40 C++ and C# code samples for gaming 
-   [Interactive C++ tutorial](https://www.learn-cpp.org/ "This link takes you to learn-cpp.org's tutorial on C++."): a free tutorial that runs C++ code in exercises

#### Tips for learning programming languages

Here are a few tips to follow when you start learning a new programming language:

-   Define a practice project and use the language to help you complete it. This makes the learning process more practical and engaging.  
-   Keep previous concepts and coding principles in mind. Many of these are transferable between programming languages. So, after you have learned one language, learning a second or third programming language tends to be much easier. 
-   Create and keep good notes and cheat sheets in whatever format (handwritten or typed) that works best for you.
-   Create an online filing system for information that you can easily access while you work in various programming environments.
