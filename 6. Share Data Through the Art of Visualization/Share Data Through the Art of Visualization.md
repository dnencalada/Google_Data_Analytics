## Visualizing data
- The basic concepts of visualization.
- How to plan for and start building effective visualizations
- Tableau helps create visualizations from our analysis
- Data visualizations, including visual dashboards, can help bring your data to life
- Presentations and slideshows continue telling a story with data
- Anticipate and answer questions; Respond to feedback

### Understand data visualization
**Data visualization**: The graphic representation and presentation of data.

Visualizing data began long ago with maps, which are the visual representation of geographic data. Scientists and mathematicians began to truly embrace the idea of arranging data visually in the 1700s and 1800s.

As an analyst in today's world, you'll probably split your time with data visuals in two ways:
- Looking at visuals in order to understand and draw conclusions about data
- Creating visuals using raw data to tell a story.

> *best practices that are helpful to keep in mind::*
> -   Your audience should know what they are observing within five seconds of being shown it--visuals should be clear and easy to follow.
> -   In the five seconds after that, your audience should understand the conclusion your visualization is making--even if they aren’t familiar with the research you’ve been doing. 
> -   As a general rule, as long as it’s not misleading, you should visually represent only the data that your audience needs in order to understand your findings.

Basically, an effective data visualization should lead viewers to reach the same conclusion you did, but much more quickly.

### Effective data visualizations
#### Frameworks
Frameworks can help you organize your thoughts about data visualization and give you a useful checklist to reference. Here are two frameworks that may be useful for you as you create your own data viz:

##### The McCandless Method
[**The McCandless Method**](https://www.informationisbeautiful.net/visualizations/what-makes-a-good-data-visualization/ "The McCandless Method")
The McCandless Method lists four elements of good data visualization:
1.  **Information**: the data you are working with
2.  **Story**: a clear and compelling narrative or concept
3.  **Goal**: a specific objective or function for the visual
4.  **Visual form**: an effective use of metaphor or visual expression

"Based on **Data**, tell a **Story**, achieving a **Goal** with a beautiful **Visual form**."

The Venn diagram by David McCandless identifies four elements of successful visualizations:
-   **Information (data):** The information or data that you are trying to convey is a key building block for your data visualization. Without information or data, you cannot communicate your findings successfully.
-   **Story (concept):** Story allows you to share your data in meaningful and interesting ways. Without a story, your visualization is informative, but not really inspiring. 
-   **Goal (function):** The goal of your data visualization makes the data useful and usable. This is what you are trying to achieve with your visualization. Without a goal, your visualization might still be informative, but can’t generate actionable insights.
-   **Visual form (metaphor):** The visual form element is what gives your data visualization structure and makes it beautiful. Without visual form, your data is not visualized yet.
Each element has value, but visualizations only become truly powerful and effective when you combine all four elements in a way that makes sense.

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image63.png)


> One useful way of approaching this framework is to notice the parts of the graphic where there is incomplete overlap between all four elements. For example, visual form without a goal, story, or data could be a sketch or even art. Data plus visual form without a goal or function is eye candy. Data with a goal but no story or visual form is boring. All four elements need to be at work to create an effective visual.


###### Examples
**Example 1: visualization of lifespan data**
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image64.png)
-   **Information (data):** The data is organized and outlined in the visualization, so this visualization clearly is based on plenty of information or data. 
-   **Story (concept):** The concept behind this data visualization is clearly stated in the title: finding out what really extends a lifespan. But, the visualization also uses the data gathered and presented earlier to put together the ultimate recipe for a long life, which is a nice ending to the overarching story being told in this visualization. 
-   **Goal (function):** The goal of this data visualization is also pretty clear from the title: It is trying to find out what can extend someone’s lifespan, which might help people make better choices about their own lives. 
-   **Visual form (metaphor):** The data visualization uses a lot of visual components to help structure the information. First, it has been organized as a horizontal bar chart and has both years lost and years gained as a result of particular choices. This makes it easier to read each choice and the commentary. It also draws your eye downward so that you have to read all of the elements before you get to the ultimate recipe at the end. This data visualization also uses color to communicate how strong the science behind each finding was, which makes this data visualization beautiful and informative.

**Example 2: visualization of dog breed comparison**
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image65.png)
-   **Information (data):** If you view the data, you can explore the metrics being illustrated in the visualization. 
-   **Story (concept):** The visualization shows which dogs are overrated, which are rightly ignored, and those that are really hot dogs! And, the visualization reveals some overlooked treasures you may not have known about previously.
-   **Goal (function):** The visualization is interested in exploring the relationship between popularity and the objective data scores for different dog breeds. By comparing these data points, you can learn more about how different dog breeds are perceived. 
-   **Visual form (metaphor):** In addition to the actual four-square structure of this visualization, other visual cues are used to communicate information about the dataset. The most obvious is that the data points are represented as dog symbols. Further, the size of a dog symbol and the direction the dog symbol faces communicate other details about the data.


**Example 3: visualization of rising sea levels**
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image66.png)
-   **Information (data):** This visualization uses climate data on rising sea levels from a variety of sources, including NASA and the Intergovernmental Panel on Climate Change. In addition to that data, it also uses recorded sea levels from around the world to help illustrate how much rising sea levels will affect the world. 
-   **Story (concept):** The visualization tells a very clear story: Over the course of 8,000 years, much of the world as we know it will be underwater. 
-   **Goal (function):** The goal of this project is to demonstrate how soon rising sea levels are going to affect us on a global scale. Using both data and the visual form, this visualization makes rising sea levels feel more real to the audience. 
-   **Visual form (metaphor):** The city silhouettes in this visualization are a beautiful way to drive home the point of the visualization. It gives the audience a metaphor for how rising sea levels will affect the world around them in a way that showing just the raw numbers can’t do. And for a more global perspective, the visualization also uses inset maps.



##### Kaiser Fung’s Junk Charts Trifecta Checkup
[**Kaiser Fung’s Junk Charts Trifecta Checkup**](https://junkcharts.typepad.com/junk_charts/junk-charts-trifecta-checkup-the-definitive-guide.html "Kaiser Fung’s Junk Charts Trifecta Checkup")

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image67.png)

This approach is a useful set of questions that can help consumers of data visualization critique what they are consuming and determine how effective it is. The Checkup has three questions:

1.  What is the practical question? 
2.  What does the data say?
3.  What does the visual say?

> Note: This checklist helps you think about your data viz from the perspective of your audience and decide if your visual is communicating your data effectively to them or not. In addition to these frameworks, there are some other building blocks that can help you construct your data visualizations.


##### Three essential elements
**Visual journalists Dona Wong proposes that effective visuals have three essential elements:**
1. Clear meaning
Good visualizations clearly communicate their intended insight.
2. Sophisticated use of contrast
Which helps separate the most important data from the rest using visual context that our brains naturally look for.
3. Refined execution
Paying deep attention to detail. This is done by using visual elements such as lines, shapes, colors, value, space, and movement.

---

#### Pre-attentive attributes
**Pre-attentive attributes** are the elements of a data visualization that people recognize automatically without conscious effort.
(Creating effective visuals means leveraging what we know about how the brain works, and then using specific visual elements to communicate the information effectively.)

##### Marks
**Marks** are basic visual objects like points, lines, and shapes. Every mark can be broken down into four qualities:
1. **Position** - Where a specific mark is in space in relation to a scale or to other marks
2. **Size** - How big, small, long, or tall a mark is
3. **Shape** - Whether a specific object is given a shape that communicates something about it
4. **Color** - What color the mark is

##### Channels
**Channels** are visual aspects or variables that represent characteristics of the data.
1. **Accuracy** - Are the channels helpful in accurately estimating the values being represented?
(For example, color is very accurate when communicating categorical differences, like apples and oranges. But it is much less effective when distinguishing quantitative data like 5 from 5.5.)
2. **Popout** - How easy is it to distinguish certain values from others?
There are many ways of drawing attention to specific parts of a visual, and many of them leverage pre-attentive attributes like line length, size, line width, shape, enclosure, hue, and intensity.
3. **Grouping** - How good is a channel at communicating groups that exist in the data?
Consider the proximity, similarity, enclosure, connectedness, and continuity of the channel.

> But, remember: the more you emphasize *different* things, the less that emphasis counts. The more you emphasize *one single* thing, the more that counts.


#### Design principles
These design principles are important to your work as a data analyst because they help you make sure that you are creating visualizations that communicate your data effectively to your audience.

| **Principle**               | **Description**                                              |
| :-------------------------- | :----------------------------------------------------------- |
| Choose the right visual     | One of the first things you have to decide is which visual will be the most effective for your audience. Sometimes, a simple table is the best visualization. Other times, you need a more complex visualization to illustrate your point. |
| Optimize the data-ink ratio | The data-ink entails focusing on the part of the visual that is essential to understanding the point of the chart. Try to minimize non-data ink like boxes around legends or shadows to optimize the data-ink ratio. |
| Use orientation effectively | Make sure the written components of the visual, like the labels on a bar chart, are easy to read. You can change the orientation of your visual to make it easier to read and understand. |
| Color                       | There are a lot of important considerations when thinking about using color in your visuals. These include using color consciously and meaningfully, staying consistent throughout your visuals, being considerate of what colors mean to different people, and using inclusive color scales that make sense for everyone viewing them. |
| Numbers of things           | Think about how many elements you include in any visual. If your visualization uses lines, try to plot five or fewer. If that isn’t possible, use color or hue to emphasize important lines. Also, when using visuals like pie charts, try to keep the number of segments to less than seven since too many elements can be distracting. |

#### Avoiding misleading or deceptive charts
Here are some common errors to avoid so that your visualizations aren’t accidentally misleading:

| **What to avoid**                                            | **Why**                                                      |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| Cutting off the y-axis                                       | Changing the scale on the y-axis can make the differences between different groups in your data seem more dramatic, even if the difference is actually quite small. |
| Misleading use of a dual y-axis                              | Using a dual y-axis without clearly labeling it in your data visualization can create extremely misleading charts. |
| Artificially limiting the scope of the data                  | If you only consider the part of the data that confirms your analysis, your visualizations will be misleading because they don’t take all of the data into account. |
| Problematic choices in how data is binned or grouped         | It is important to make sure that the way you are grouping data isn’t misleading or misrepresenting your data and disguising important trends and insights. |
| Using part-to-whole visuals when the totals do not sum up appropriately | If you are using a part-to-whole visual like a pie chart to explain your data, the individual parts should add up to equal 100%. If they don’t, your data visualization will be misleading. |
| Hiding trends in cumulative charts                           | Creating a cumulative chart can disguise more insightful trends by making the scale of the visualization too large to track any changes over time. |
| Artificially smoothing trends                                | Adding smooth trend lines between points in a scatter plot can make it easier to read that plot, but replacing the points with just the line can actually make it appear that the point is more connected over time than it actually was. |


Use these tips to think critically about data visualization—both as a creator and as an audience member.

#### Further reading
-   [The beauty of data visualization](https://www.ted.com/talks/david_mccandless_the_beauty_of_data_visualization?language=en#t-150183 "The beauty of data visualization"): In this video, David McCandless explains the need for design to not just be beautiful, but for it to be meaningful as well. Data visualization must be able to balance function and form for it to be relevant to your audience. 

-   [‘The McCandless Method’ of data presentation](https://artscience.blog/home/the-mccandless-method-of-data-presentation "‘The McCandless Method’ of data presentation"): At first glance, this blog appears to be written by a David McCandless fan, and it is. However, it contains very useful information and provides an in-depth look at the 5-step process that McCandless uses to present his data.

-   [Information is beautiful](https://informationisbeautiful.net/ "Information is beautiful"): Founded by McCandless himself, this site serves as a hub of sample visualizations that make use of the McCandless method. Explore data from the news, science, the economy, and so much more and learn how to make visual decisions based on facts from all kinds of sources. 

-   [Beautiful daily news](https://informationisbeautiful.net/beautifulnews/ "Beautiful daily news"): In this McCandless collection, explore uplifting trends and statistics that are beautifully visualized for your creative enjoyment. A new chart is released every day so be sure to visit often to absorb the amazing things happening all over the world.

-   [The Wall Street Journal Guide to Information Graphics: The Dos and Don'ts of Presenting Data, Facts, and Figures](https://www.amazon.com/Street-Journal-Guide-Information-Graphics/dp/0393072959 "The Wall Street Journal Guide to Information Graphics: The Dos and Don'ts of Presenting Data, Facts, and Figures"): This is a comprehensive guide to data visualization, including chapters on basic data visualization principles and how to create useful data visualizations even when you find yourself in a tricky situation. This is a useful book to add to your data visualization library, and you can reference it over and over again.



### Examples of data visualizations
Presenting your data visually is an effective way to communicate complex information and engage your stakeholders.
One question to ask yourself is: "what is the best way to tell the story within my data?" 

#### Line chart
A **line chart** is used to track changes over short and long periods of time.
When smaller changes exist, line charts are better to use than bar graphs.
Line charts can also be used to compare changes over the same period of time for more than one group.

e.g. the difference of graduation rates between male and female students
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image68.png)

e.g. Popularity between dogs and cats over time
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image69.png)

#### Bar graphs
**Bar graphs**: (*also known as Bar Chart or Column Graph*) use size to contrast and compare two or more values, using height or lengths to represent the specific values.

The **x-axis** is a horizontal line used to represent categories, time periods, or other variables. The **y-axis** is a vertical line that usually has a scale of values for variables.

e.g. Sales of vehicles with a competing car brand over the course of 5 months:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image70.png)

Bar graphs are also a great way to clarify trends.
e.g. Here, it's clear this person's motivation is low at the beginning of the day and gets higher and higher by the end of the workday.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image71.png)
This type of visualization makes it very easy to identify patterns.

> Misleading Warning: A truncated bar chart (the values on the y-axis don't start at zero)

A bar chart should always be ranked by value, unless there's a natural order to the data like age or time, for example.

**Histogram**: A chart that shows how often data values fall into certain ranges. x-axis: Range; y-axis: Number of instances inside the range.
(resembles a bar graph but not the same)

#### Heatmap
Similar to bar charts, heatmaps also use color to compare categories in a data set.
They are mainly used to show relationships between two variables and use a system of color-coding to represent different values.

e.g. The following heatmap plots temperature changes for each city during the hottest and coldest months of the year.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image72.png)


#### Pie charts
The **pie chart** is a circular graph that is divided into segments representing proportions corresponding to the quantity it represents, especially when dealing with parts of a whole.

e.g. This pie chart shows us all the activities that make up someone's day. From a quick scan, you can easily tell which activities make up a good chunk of the day in this pie chart and which ones take up less time.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image73.png)

> Misleading Warning: Each part of the circle or pie should reflect its percentage to the whole, if it is not equal to 100 percent, then it may be a misleading.

#### Scatter plot
**Scatter plots** show relationships between different variables. Scatter plots are typically used for two variables for a set of data, although additional variables can be displayed.

e.g. data of the relationship between temperature changes and ice cream sales
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image74.png)

As you may notice, the higher the temperature got, the more demand there was for ice cream – so the scatter plot is great for showing the relationship between the two variables.

#### Distribution graph
A **distribution graph** displays the spread of various outcomes in a dataset.

e.g. how many cups of coffee consumed during the week
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image75.png)

> If outcomes are categorized on the x-axis by distinct numeric values (or ranges of numeric values), the distribution becomes a **histogram**.

#### Maps
**Maps**: Help organize data geographically.
The great thing about maps is they can hold a lot of location-based information and they're easy for your audience to interpret.

To make the map more effective, you make the intensity of the colors stronger, select more varied hues, and choose darker values. Intensity will make the colors brighter. Different hues will help the states stand out from one another. And darker values will make the color differences easier to see.

e.g. This example shows survey data about people's happiness in Europe.
The borderlines are well-defined and the colors added make it even easier to tell the countries apart.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image76.png)


### Choose the right visual
#### Evaluating patterns in data to find the visual fit best
Meaningful patterns in data can take many forms, such as:
-   **Change:** This is a trend or instance of observations that become different over time. A great way to measure change in data is through a line or column chart.
-   **Clustering:** A collection of data points with similar or different values. This is best represented through a distribution graph.
-   **Relativity:** These are observations considered in relation or in proportion to something else. You have probably seen examples of relativity data in a pie chart.
-   **Ranking:** This is a position in a scale of achievement or status. Data that requires ranking is best represented by a column chart.
-   **Correlation:** This shows a mutual relationship or connection between two or more things. A scatter plot is an excellent way to represent this type of data pattern.

#### Data grows on decision trees
A **decision tree** is a decision-making tool that allows you, the data analyst, to make decisions based on key questions that you can ask yourself.
Since different visualizations have different strengths and weaknesses, a decision tree can help you pick the best visualization for your given information and audience.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image77.png)

Start off by evaluating the type of data you have and go through a series of questions to determine the best visual source:

- **Does your data have only one numeric variable?**
If you have data that has one, continuous, numerical variable, then a histogram or density plot are the best methods of plotting your categorical data.
For example, if you have data pertaining to the height of a group of students, you will want to use a histogram to visualize how many students there are in each height range:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image78.png)
- **Are there multiple datasets?** (#?)
For cases dealing with more than one set of data, consider a line or pie chart for accurate representation of your data. A line chart will connect multiple data sets over a single, continuous line, showing how numbers have changed over time. A pie chart is good for dividing a whole into multiple categories or parts.
e.g. quarterly sales figures of your company on both a line and pie chart
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image79.png)
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image80.png)
- **Are you measuring changes over time?**
A line chart is usually adequate for plotting trends over time. However, when the changes are larger, a bar chart is the better option.
e.g. measuring the number of visitors to NYC over the past 6 months
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image81.png)
- **Do relationships between the data need to be shown?**
When you have two variables for one set of data, it is important to point out how one affects the other. Variables that pair well together are best plotted on a scatter plot. However, if there are too many data points, the relationship between variables can be obscured so a heat map can be a better representation in that case.
If you are measuring the population of people across all 50 states in the United States, your data points would consist of millions so you would use a heat map. If you are simply trying to show the relationship between the number of hours spent studying and its effects on grades, your data would look like this:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image82.png)


**Additional resources:**
-   [From data to visualization](https://www.data-to-viz.com/ "From Data to Visualization"): This is an excellent analysis of a larger decision tree. With this comprehensive selection, you can search based on the kind of data you have or click on each  graphic example for a definition and proper usage.

-   [Selecting the best chart](https://www.youtube.com/watch?v=C07k0euBpr8 "Selecting the best chart"): This two-part YouTube video can help take the guesswork out of data chart selection. Depending on the type of data you are aiming to illustrate, you will be guided through when to use, when to avoid, and several examples of best practices. [Part 2](https://www.youtube.com/watch?v=qGaIB-bRn-A "Part 2") of this video provides even more examples of different charts, ensuring that there is a chart for every type of data out there.



#### Data visualization impact
Choosing the right visualization for your data findings can often come down to one question:
***Which one will make it easiest for the user to understand the point you're trying to make?***

Let's say you want to highlight the differences among the age groups to compare them or directly, for that you might use a positive negative bar chart like this.

Bar graphs and stacked bar graphs, along with area charts, can also be good ways to visualize how data changes over time.

when you're comparing distinct objects like in the example about mobile versus computer usage, ordered bar, and group bar graphs, and ordered column charts are useful.

Then there's charts that show parts of a whole. This is known as data composition.
**Data composition**: Combining the individual parts in a visualization and displaying them together as a whole.
Stack bars, donuts, stacked areas, pie charts and tree maps can do all this.

Now To show relationships in your data, you might want to use scatterplot and bubble charts, column/line charts and heatmaps.


---


### Inspiration
One of the best ways to understand the importance of data visualization is to go through different examples of it. 
Below is a list of resources that can inspire your next data-driven decisions, as well as teach you how to make your data more accessible to your audience:
-   [The data visualization catalogue](https://datavizcatalogue.com/#google_vignette "The Data Visualization Catalogue"): Not sure where to start with data visualization? This catalogue features a range of different diagrams, charts, and graphs to help you find the best fit for your project. As you navigate each category, you will get a detailed description of each visualization as well as its function and a list of similar visuals. 

-   [The 25 best data visualizations](https://visme.co/blog/best-data-visualizations/ "The 25 best data visualizations"): In this collection of images, explore the best examples of data that gets made into a stunning visual. Simply click on the link below each image to get an in-depth view of each project, and learn why making data visually appealing is so important.

-   [10 data visualization blogs](https://www.tableau.com/learn/articles/best-data-visualization-blogs "10 data visualization blogs"): Each link will lead you to a blog that is a fountain of information on everything from data storytelling to graphic data. Get your next great idea or just browse through some visual inspiration.  

-   [Information is beautiful](https://informationisbeautiful.net/wdvp/gallery-2019/ "Information is beautiful"): Founded by David McCandless, this gallery is dedicated to helping you make clearer, more informed visual decisions based on facts and data. These projects are made by students, designers, and even data analysts to help you gain insight into how they have taken their own data and turned it into visual storytelling.

-   [Data studio gallery](https://datastudio.google.com/gallery?category=visualization "Data studio gallery"): Information is vital, but information presented in a digestible way is even more useful. Browse through this interactive gallery and find examples of different types of data communicated visually. You can even use the data studio tool to create your own data-driven visual.


### A recipe for a powerful visualization
One of your biggest considerations when creating a data visualization is where you'd like your audience to focus.
Showing too much can be distracting and leave your audience confused. On the other hand, showing too little can make your visualization unclear and less meaningful.

As a general rule, as long as it's not misleading, you should visually represent only the data that your audience needs in order to understand your findings.

**Correlation charts**: Show relationships among data.
(should be used with caution because they might lead viewers to think that the data shows causation.)
**Causation**: (or a cause-effect relationship) Occurs when an action directly leads to an outcome.

#### Correlation and causation
-   **Correlation** in statistics is the measure of the degree to which two variables move in relationship to each other. An example of correlation is the idea that “As the temperature goes up, ice cream sales also go up.” It is important to remember that correlation doesn’t mean that one event causes another. But, it does indicate that they affect each other positively or negatively. If one variable goes up and the other variable also goes up, it is a positive correlation. If one variable goes up and the other variable goes down, it is a negative correlation.
-   **Causation** refers to the idea that an event leads to a specific outcome. For example, when lightning strikes, we hear the thunder (sound wave) caused by the air heating and cooling from the lightning strike. Lightning causes thunder.

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image83.png)
    
**Key takeaways**
In your data analysis, remember to: 
-   Critically analyze any correlations that you find 
-   Examine the data’s context to determine if a causation makes sense (and can be supported by all of the data)
-   Understand the limitations of the tools that you use for analysis


Further information
-   [**Correlation is not causation**](https://towardsdatascience.com/correlation-is-not-causation-ae05d03c1f53 "Correlation is not causation")**:** This article describes the impact to a business when correlation and causation are confused.
-   [**Correlation and causation**](https://www.khanacademy.org/test-prep/praxis-math/praxis-math-lessons/gtp--praxis-math--lessons--statistics-and-probability/a/gtp--praxis-math--article--correlation-and-causation--lesson "Correlation and causation") **(Khan Academy lesson):** This lesson describes correlation and causation along with a working example. Follow the examples of the analysis and notice if there is a positive correlation between frostbite and sledding accidents.


### Dynamic visualizations
**Static visualizations**: Do not change over time unless they're edited.
Any visualization printed on paper is automatically static.

**Dynamic visualizations**: Visualizations that are interactive or change over time.
The interactive nature of these graphics means that users have some control over what they see.
Some dynamic visualizations update new data automatically. If you need to, you can show trends in real-time.

**Tableau**: A business intelligence and analytics platform that helps people see, understand, and make decisions with data.
Visualizations in Tableau are automatically interactive.

> **The choice between using a static or dynamic visualization**
> Having an interactive visualization can be useful for both you and the audience you share it with. But it's good to remember that the more power you give the user, the less control you have over the story you want the data to tell.
> You want to find the right balance between interactivity and control.
> This will usually depend on the data you're visualizing, the audience you're presenting to, and how you're giving your presentation.


### Design data visualizations
#### The elements of art
##### Line
Lines add visual form to your data and help build the structure for your visualization.
Curved or straight, thick or thin, vertical, horizontal, or diagonal.

##### Shape
Shapes create visual contrast that can help differentiate different data points, like different countries on a map visualization.
Should always be two-dimensional. Three-dimensional objects can complicate the visual and confuse the audience.
Shapes are also a great way to add eye-catching contrast, especially size contrast to your data story.
##### Color
- Hue(red, green, blue)
- Intensity(bright or dull)
- Value (how light or dark the color is. Value indicates how much light is being reflected.)
    *Light values with white added are called tints, like these tints of blue.*
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image84.png)
    *Dark values with some black added are called shades of color, like these shades of green.*
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image85.png)

> A lot of people associate green with positive results and red with negative results. 

##### Space
Space is the area between, around and in the objects.
For example, the space between the bars of a bar graph like this one should be smaller than the width of the bars themselves. This will draw the viewer's attention to the bar and the data it represents instead of the empty space.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image86.png)

##### Movement
Movement is used to create a sense of flow or action in a visualization.
Remember, this is something that should be used sparingly. There's a fine line between attracting attention and distracting the audience.


#### Nine Principles of design
Communicating data visually is a form of art.

There are **nine basic principles of design** that data analysts should think about when building their visualizations.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image87.png)
**1. Balance**: The design of a data visualization is balanced when the key visual elements, like color and shape, are distributed evenly. This doesn’t mean that you need complete symmetry, but your visualization shouldn’t have one side distracting from the other. If your data visualization is balanced, this could mean that the lines used to create the graphics are similar in length on both sides, or that the space between objects is equal. For example, [**this column chart**](https://developers.google.com/chart/interactive/docs/gallery/columnchart "this column chart") (also shown below) is balanced; even though the columns are different heights and the chart isn’t symmetrical, the colors, width, and spacing of the columns keep this data visualization balanced. The colors provide sufficient contrast to each other so that you can pay attention to both the motivation level and the energy level displayed.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image88.png)

**2. Emphasis:** Your data visualization should have a focal point, so that your audience knows where to concentrate. In other words, your visualizations should emphasize the most important data so that users recognize it first. Using color and value is one effective way to make this happen. By using contrasting colors, you can make certain that graphic elements—and the data shown in those elements—stand out. 

For example, you will notice a heat map data visualization below from [**The Pudding’s “Where Slang Comes From"**](https://pudding.cool/2017/02/new-slang/ "The Pudding's "Where Slang Comes From"") article. This heat map uses colors and value intensity to emphasize the states where search interest is highest. You can visually identify the increase in the search over time from low interest to high interest. This way, you are able to quickly grasp the key idea being presented without knowing the specific data values.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image89.png)

**3. Movement:** Movement can refer to the path the viewer’s eye travels as they look at a data visualization, or literal movement created by animations. Movement in data visualization should mimic the way people usually read. You can use lines and colors to pull the viewer’s attention across the page. 

For example, notice how the average line in [**this combo chart**](https://developers.google.com/chart/interactive/docs/gallery/combochart "this combo chart") (also shown below) draws your attention from left to right. Even though this example isn’t moving, it still uses the movement principle to guide viewers’ understanding of the data.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image90.png)

**4. Pattern:** You can use similar shapes and colors to create patterns in your data visualization. This can be useful in a lot of different ways. For example, you can use patterns to highlight similarities between different data sets, or break up a pattern with a unique shape, color, or line to create more emphasis.

In the example below, the different colored categories of [**this stacked column chart**](https://developers.google.com/chart/interactive/docs/gallery/barchart "this stacked column chart") (also shown below) are a consistent pattern that makes it easier to compare book sales by genre in each column. Notice in the chart that the Fantasy & Sci Fi category (royal blue) is increasing over time even as the general category (green) is staying about the same.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image91.png)

**5. Repetition:** Repeating chart types, shapes, or colors adds to the effectiveness of your visualization. Think about the book sales chart from the previous example: the repetition of the colors helps the audience understand that there are distinct sets of data. You may notice this repetition in all of the examples we have reviewed so far. Take some time to review each of the previous examples and notice the elements that are repeated to create a meaningful visual story.

**6. Proportion:** Proportion is another way that you can demonstrate the importance of certain data. Using various colors and sizes helps demonstrate that you are calling attention to a specific visual over others. If you make one chart in a dashboard larger than the others, then you are calling attention to it. It is important to make sure that each chart accurately reflects and visualizes the relationship among the values in it. In [**this dashboard**](https://developers.google.com/chart/interactive/docs/gallery/controls "this dashboard") (also shown below), the slice sizes and colors of the pie chart compared to the data in the table help make the number of donuts eaten by each person the focal point.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image92.png)

> These first six principles of design are key considerations that you can make while you are creating your data visualization. These next three principles are useful checks once your data visualization is finished. If you have applied the initial six principles thoughtfully, then you will probably recognize these next three principles within your visualizations already.

**7. Rhythm:** This refers to creating a sense of movement or flow in your visualization. Rhythm is closely tied to the movement principle. If your finished design doesn’t successfully create a flow, you might want to rearrange some of the elements to improve the rhythm.

**8. Variety:** Your visualizations should have some variety in the chart types, lines, shapes, colors, and values you use. Variety keeps the audience engaged. But it is good to find balance since too much variety can confuse people. The variety you include should make your dashboards and other visualizations feel interesting and unified.

**9. Unity:** The last principle is unity. This means that your final data visualization should be cohesive. If the visual is disjointed or not well organized, it will be confusing and overwhelming.

---

### Design thinking
**Design thinking**: A process used to solve complex problems in a user-centric way.
(User-centricity means considering the user and their needs first.)
e.g. Airbnb: help their customers replace the not so great photos with more professional looking ones.


#### Five phases of the design process
Design thinking for data visualization involves five phases:
##### Empathize
**Thinking about the emotions and needs of the target audience for the data visualization.**
Thinking about the emotions and needs of the target audience of your data viz.
Here you should avoid areas where people might face obstacles interacting with your visualizations.
If there's someone on your team who is vision impaired, you want to find a way to explain the data verbally as well.
e.g. void using too bright or dramatic colors which might not be right for the seriousness of the data when working on an analysis for a pharmaceutical company.

##### Define
**Figuring out exactly what your audience needs from the data.**
Helps you to find your audiences' needs, their problems and your insights.
You could use this phase to think about which data to show in your visualization.
There might be data that could make some people uncomfortable.
You can think of ways to position that data to make it more digestible. Or if you're presenting to different audiences, you can adjust your visualizations to meet each group's needs

##### Ideate
**Generating ideas for data visualization.**
Start to generate your data viz ideas. You'll use all of your findings from the empathize and define phases to brainstorm potential data viz solutions.
This might involve creating drafts of your visualization with different color combinations or maybe experimenting with different shapes.
Always remember your audience when coming up with ideas and strategies.

##### Prototype
**Putting visualizations together for testing and feedback.**

##### Test
**Showing prototype visualizations to people before stakeholders see them.**
In the final two phases, you'll start putting your charts, dashboards or other visualizations together.

In the spirit of design thinking, these phases don't have to follow a set order. Instead, think of them as an overview of actions that can help you produce a user centered design in your visualizations.

The phrase thinking outside the box is used a lot, but it definitely applies here. The box in this case is your own usual way of approaching data, and its visualization.

#### An example: online banking dashboard
Suppose you are an analyst at a bank that has just released a new dashboard in their online banking application.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image93.png)

**Empathize**
First, empathize by putting yourself in the shoes of a customer who has a checking account with the bank. 

- Do the colors and labels make sense in the visualization? 
- How easy is it to set or change a budget? 
- When you click on a spending category in the donut chart, are the transactions in the category displayed?

What is the main purpose of the data visualization? If you answered that it was to help customers stay within budget or to save money, you are right! Saving money was a top customer need for the dashboard. 

**Define**
Now, imagine that you are helping dashboard designers define other things that customers might want to achieve besides saving money. 

What other data visualizations might be needed? 

- Track income (in addition to spending)
- Track other spending that doesn’t neatly fit into the set categories (this is sometimes called **discretionary spending**)
- Pay off debt


**Ideate**
Next, ideate additional features for the dashboard and share them with the software development team. 

- What new data visualizations would help customers?
- Would you recommend bar charts or line charts in addition to the standard donut chart?
- Would you recommend allowing users to create their own (custom) categories?


**Prototype**
Finally, developers can prototype the next version of the dashboard with new and improved data visualizations. 

**Test**
Developers can close the cycle by having you (and others) test the prototype before it is sent to stakeholders for review and approval.


#### Key takeaways
This design thinking example showed how important it is to:
-   Understand the needs of users
-   Generate new ideas for data visualizations
-   Make incremental improvements to data visualizations over time

You can refer to the following articles for more information about design thinking:
-   [Three Critical Aspects of Design Thinking for Big Data Solutions](https://dataconomy.com/2019/05/three-critical-aspects-of-design-thinking-for-big-data-solutions/ "Three critical aspects of design thinking for big data solutions")

-   [Data and Design Thinking: Why Use Data in the Design Process?](https://www.enginess.io/insights/data-and-design-thinking "Data and design thinking: why use data in the design process")

---

### Explore visualization considerations
The three basic visualization considerations are headlines, subtitles, and labels.

#### Highlighting key information
Your audience will be less likely to have questions about what you're sharing if you add headlines, subtitles, and labels.

##### Headlines that pop
One of the easiest ways to highlight key data in your data viz, is through headlines.
**Headline**: A line of words printed in large letters at the top of the visualization to communicate what data is being presented.

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image94.png)
Be sure to use clear, concise language, explaining all information as plainly as possible. Try to avoid using abbreviations or acronyms, even if you think they're common knowledge.
Make it bold or a few sizes larger than the rest of the text and place it directly above the chart, aligned to the left.

##### Subtitles that clarify
**Subtitle**: Supports the headline by adding more context and description.
Adding a subtitle will help the audience better understand the details associated with your chart.
Use a smaller font size than the headline and place the subtitle directly underneath the headline.

##### Labels that identify
A **label** in a visualization identifies data in relation to other data.

**1. Label the axes**
Most commonly, labels in a chart identify what the x-axis and y-axis show. Always make sure you label your axes.
We can add “**Months (January - June 2020)**” for the x-axis and “**Average Monthly Rents ($)**” for the y-axis in the average rents chart.

**2. Label the data**
Data can also be labeled directly in a chart instead of through a chart legend.
This makes it easier for the audience to understand data points without having to look up symbols or interpret the color coding in a legend.

![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image95.png)


**Legend**: (or key) Identifies the meaning of various elements in a data visualization.

Direct labeling like above keeps the audience's attention fixed on your graphic and helps them identify data quickly. While legends force the audience to do more work, because a legend is positioned away from the chart's data.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image96.png)


##### Annotations that focus
An **annotation** briefly explains data or helps focus the audience on a particular aspect of the data in a visualization.
Suppose in the average rents chart that we want the audience to pay attention to the rents at their ***highs***. Annotating the data points representing the highest average rents will help people focus on those values for each city.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image97.png)


#### Guidelines and pro tips
Think of these guidelines as guardrails.

| Visualization components | Guidelines                                                                                                                                                                 | Style checks                                                                                                                                                             |
|:------------------------ |:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Headlines                | - **Content**: Briefly describe the data <br>- **Length**: Usually the width of the data frame <br>- **Position**: Above the data                                          | - Use brief language  <br>- Don’t use all caps <br>- Don’t use italic <br>- Don’t use acronyms <br>- Don't use abbreviations <br>- Don’t use humor or sarcasm                |
| Subtitles                | - **Content**: Clarify context for the data <br>- **Length**: Same length or shorter than headline  <br>- **Position**: Directly below the headline                        | - Use smaller font size than the headline <br>- Don’t use words that need definition <br>- Don’t use all caps, bold, or italic <br>- Don’t use acronyms or abbreviations |
| Labels                   | - **Content**: Replace the need for legends <br>- **Length**: Usually <= 30 characters, unless for axes  <br>- **Position**: Next to data, or below or to the left of axes | - Use a few words only <br>- Use thoughtful color-coding <br>- Use callouts to point to the data <br>- Don’t use all caps, bold, or italic                               |
| Annotations              | - **Content**: Draws attention to certain data  <br>- **Length**: Varies, limited by available open space <br>- **Position**: Immediately next to data annotated           | - Don’t use all caps, bold, or italic <br>- Don't use rotated text <br>- Don’t distract viewers from the data                                                            |

#### Accessible visualizations
Designing with an accessibility mindset involves thinking about your audience ahead of time; focusing on simple, easy to understand visuals; and creating alternative ways for your audience to access and interact with your data.

Keep the fact in mind: over 1 billion people in the world have a disability, and not everyone has the same abilities.

> "Accessibility is really about making sure that you are creating data visualizations, graphs, charts, tables that anyone can interact with, whether they have a long-term or even a temporary form of impairment."

**Ways to make data visualizations accessible:**
- **Labeling**
label data directly instead of relying exclusively on legends, which require color interpretation and more effort by the viewer to understand.
(This can also just make it a faster read for those with or without disabilities.)
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image98.png)
- **Text alternatives**
Provide text alternatives, so that it can be changed into other forms people need, such as large print, braille, or speech.
**Alternative text**: Alternative text provides a textual alternative to non-text content.
It allows the content and function of the image to be accessible to those with visual or certain cognitive disabilities.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image99.png)
- **Text-based format**
Make data from charts and diagrams available in a text-based format through an export to Sheets or Excel.
- **Distinguishing**
Make it easier for people to see and hear content by separating foreground from background.
Using bright colors, that contrast against the background can help those with poor visibility, whether permanently or temporarily clearly see the information conveyed.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image100.png)
Avoid relying solely on color to convey information, and instead distinguished with different textures and shapes.
- **Simplify**
Avoid over complicating data visualizations.
Breaking down data into simple visualizations is key.
A common mistake is including too much information in a single piece, or including long chunks, of text or too much information and graphs and charts.
Simplifying your data visualizations can help your audience understand and focus on the important data. To do this, avoid overly complicated visuals or unnecessary information.
Bad chart:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image101.png)



Ultimately, designing with an accessibility mindset means thinking about your audience ahead of time. Focusing on simple, easy to understand visuals, and most importantly, creating alternative ways for your audience to access and interact with your data.


#### Designing a chart in 60 minutes
Choosing to represent your data via a chart is usually the most simple and efficient method.
The goal here is to develop a prototype or mock up of your chart that you can quickly present to an audience in 60 minutes.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image102.png)

Follow this high level 60-minute chart to guide your thinking whenever you begin working on a data visualization.
##### Prep (5 min)
Create the mental and physical space necessary for an environment of comprehensive thinking. This means allowing yourself room to brainstorm how you want your data to appear while considering the amount and type of data that you have.

##### Talk and listen (15 min)
Identify the object of your work by getting to the "ask behind the ask" and establishing expectations. Ask questions and really concentrate on feedback from stakeholders regarding your projects to help you hone how to lay out your data.

##### Sketch and design (20 min)
Draft your approach to the problem. Define the timing and output of your work to get a clear and concise idea of what you are crafting.

##### Prototype and improve (20 min)
Generate a visual solution and gauge its effectiveness at accurately communicating your data. Take your time and repeat the process until a final visual is produced. It is alright if you go through several visuals until you find the perfect fit.


**Key takeaway**
This is a great overview you can use when you need to create a visualization in a short amount of time. As you become more experienced in data visualization, you will find yourself creating your own process. You will get a more detailed description of different visualization options in the next reading, including line charts, bar charts, scatter plots, and more. No matter what you choose, always remember to take the time to prep, identify your objective, take in feedback, design, and create.


#### Hands-On
1. Select the data you want to make a chart
2. "Insert --> Chart"
3. In **Stepup** tab, you can change chart type
4. In **Customize** tab, click on the **Chart & axis titles** to add title, subtitle and axes' labels

In order to make an effective visualization, you must consider the type of data you’re visualizing, the needs of your audience, and the design thinking process. An effective visualization can be made in any visualization software. Going forward, you can use your knowledge of creating data visualizations in the chart editor to explore more types of data visualizations. This will help you better present your data and findings to peers and stakeholders.



## Data visualizations with Tableau
**Tableau**: A business intelligence and analytics platform that helps people see, understand, and make decisions with data.
Tableau enables you to observe and understand data to make decisions, connect to data in databases, spreadsheets, or CSV files, and create and share interactive dashboards with data.


Like tableau, **Looker** and **Google data studio** help you take raw data and bring it to life visually.

Difference:
While tableaus offered in a variety of formats like browser and desktop, looker and google data studio are completely browser based.

**[Tableau Public](https://public.tableau.com/en-us/s/)**
Here are a few useful links within Tableau Public:
-   [**Public Gallery**](https://public.tableau.com/en-us/s/viz-gallery "Public Gallery")**:** These are data visualizations created by other users that you can scroll through. 
-   [**Featured Gallery**](https://public.tableau.com/en-us/gallery/?tab=featured&type=featured "Featured Gallery")**:** This is a collection of featured data visualizations created by other users. This is a great source of inspiration.
-   [**Viz of the Day**](https://public.tableau.com/en-us/gallery/?tab=viz-of-the-day&type=viz-of-the-day "Viz of the Day")**:** Tableau Public features a new data viz every day; check back for new visualizations daily!
-   [**Google Career Certificates page on Tableau Public**](https://public.tableau.com/profile/grow.with.google/#!/)**:** This gallery contains all of the visualizations created in the video lessons; you can explore these examples more here. 
-   [**Tableau Public resources page**](https://public.tableau.com/en-us/s/resources "Tableau Public resources page")**:** This links to the resources page, including some how-to videos and sample data.
-   [**Tableau user forum**](https://community.tableau.com/s/ "Tableau user forum")**:** Search for answers and connect with other users in the community on the forum page.


### Hands-on activities

#### Load the data

1. Log in to [Tableau Public](https://public.tableau.com/en-us/s/). Hover over the avatar and click **My Profile**. Click **Create a Viz**.
2. In the **Connect to Data** window, drag and drop data file. (If not in the **Connect to Data** window, in the tab click "Data --> New Data Source")
3. The sheets contained in the data file are located on the left. For example, double click **CO2 Data Cleaned** to load this sheet. (You may have to click "update now")
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image103.png)
Tableau interprets the type of data in each column. The following icons, which are above in the column name, refer to how Tableau interprets the data type in the column:
    -   **#:** Numeric data
    -   **Abc**: String data
    -   **Globe:** Geographic data
    -   **Calendar**: Date data
    -   **Calendar with a clock:** Date and time data
    
#### Create a visualization
1. click on the **Sheet1** tab in the lower-left of the display.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image104.png)
Clicking this tab will change the display to this:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image105.png)
2. Double-click the **Country Name** dimension to show a map of the countries on the planet with dots indicating which countries are represented in the data. (Tableau defaults to scale each country equally so the dots are all the same size)
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image106.png)
3. Double-click (or drag and drop onto "Size" icon in the middle) the measure **CO2 (kt)**.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image107.png)
4. Tableau has a wide selection of options for depicting the measure for a given dimension.
(e.g. Click the Size icon on the left of the **SUM(CO2(kt))** measure and change it to "Color")
(e.g. Using Label to display the population of each country on the map.)
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image108.png)
5. Customize. e.g. Click the box with the **Color** label to change the color. Use the back arrow to undo changes.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image109.png)
6. Edit the title. Double click the title or hover over the title box and click the arrow in the upper-right of the box, then **Edit Title**.


#### Change dimensions and measures
1. Suppose that instead of visualizing the CO2 per country, you want to chart the CO2 per capita per region. To do this, double-click on the dimension **Region** and then do the same for the measure **CO2 Per Capita**. This will result in a new chart like the example below:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image110.png)

#### Delete a chart
- If you want to delete a chart from the sheet, select the **Clear Sheet** button in the toolbar. (The **Back** button can bring the chart back.)
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image111.png)
- If you want to delete a sheet in its entirety, all you need to do is right-click on the sheet's tab at the bottom of the screen and select **Delete**. Note that you will not be able to delete a sheet if it is the only sheet in your file.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image112.png)


#### Example: hapiness vs other measures
Creates a scatter graph of the countries:
1. Drag the **year** into Filters and select 2016
2. Drag **Hapiness score** into Rows shelf
3. Drag other measures like **Economy** into Columns shelf. (Duplicate sheets to create more)
4. Drag and drop **Country** into Detail section

**Add a trend line:**
1. Open the **Analytics** tab
2. Drag the **Trend line** and drop on **Linear**

**Create Dashboard**
1. "Dashboard --> New Dashboard"
2. Drag your sheet on the left "Sheets" column into right
3. Drag another to align them, horizontally, vertically or quarterly
4. (Drop the data to show the data with chart simultaneously)


#### Multiple connections
> Data sets used here: CO2.xlsx, Energy data.xlsx, totalpopulation.xlsx, gdptotal.xlsx

1. Create a vis, add the first dataset, use the + icon on the right of "Connections" to add other datasets.
2. If one of the datasets has already been loaded in, you can remove it by dragging the box to the left-hand side (the grey area) of the screen.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image113.png)
3. (To save the workbook, create extract in the datasource, if no this option, open any table in any dataset, then create)
4. Open **CO2**--> **CO2 Data Cleaned**, double click to load it into right. 
5. Hover your cursor over the right side of the **CO2 Data Cleaned** box and click on the **arrow**. Select **Open** to open the **CO2 Data Cleaned** dataset. (Or double click it directly to open the join panel.)
6. Drag **energy** sheet under **energy** dataset and mange join clauses.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image114.png)
7. Click **Update now** to examine the dataset.
8. (Because **Year** and **Year1** have a number sign above them, change the data type to date for each of these columns. Click on the **#** (not the arrow next to it) and select **Date** from the available options.)
9. Still in the join panel, drag **gdptotal** sheet of **gdptotal** dataset into the white space underneath the **energy** box, which creates another join.
10. Scroll to the right until you find the column **Year(Gdptotal).** Click on **#** above it to change the data type to Date.
11. Click on the Venn diagram between energy and gdptotal to add join clauses.
Under **CO2 Data Cleaned** click on **Country Name**, equals to **Country1** in **gdptotal**.
12. Use similar steps to add **totalpopulation** sheet of **totalpopulation** dataset.

### Visualizations in spreadsheets and Tableau
Most if not all of the charts that you can create in spreadsheets are available in Tableau. But, Tableau offers some distinct charts that aren’t available in spreadsheets.
Seven primary chart types: column, line, pie, horizontal bar, area, scatter, and combo.

Handy guides to help you select chart types in Tableau:
-   [Which chart or graph is right for you?](http://www.tableau.com/sites/default/files/media/which_chart_v6_final_0.pdf "Which chart or graph is right for you?") This presentation covers 13 of the most popular charts in Tableau.
-   [The Ultimate Cheat Sheet on Tableau Charts](https://towardsdatascience.com/the-ultimate-cheat-sheet-on-tableau-charts-642bca94dde5 "The ultimate cheat sheet on tableau charts"). This blog describes 24 chart variations in Tableau and guidelines for use.


Examples or the steps to create visualizations in Tableau:
-   **Highlight tables** appear like tables with conditional formatting. Review the [steps to build a highlight table](https://help.tableau.com/current/pro/desktop/en-us/buildexamples_highlight.htm "steps to build a highlight table"). 
-   **Heat maps** show intensity or concentrations in the data. Review the [steps to build a heat map](https://help.tableau.com/current/pro/desktop/en-us/buildexamples_highlight.htm "steps to build a heat map").
-   **Density maps** show concentrations (like a population density map). Refer to [instructions to create a heat map for density](https://help.tableau.com/current/pro/desktop/en-us/maps_howto_heatmap.htm "instructions to create a heat map for density").  
-   **Gantt charts** show the duration of events or activities on a timeline. Review the [steps to build a Gantt chart](https://help.tableau.com/current/pro/desktop/en-us/buildexamples_gantt.htm "steps to build a Gantt chart").
-   **Symbol maps** display a mark over a given longitude and latitude. Learn more from this [example of a symbol map](https://interworks.com/blog/ccapitula/2014/08/18/tableau-essentials-chart-types-symbol-map/ "example of a symbol map").
-   **Filled maps** are maps with areas colored based on a measurement or dimension. Explore an [example of a filled map](https://interworks.com/blog/ccapitula/2014/09/23/tableau-essentials-chart-types-filled-map/ "example of a filled map").
-   **Circle views** show comparative strength in data. Learn more from this [example of a circle view](https://interworks.com/blog/ccapitula/2014/10/17/tableau-essentials-chart-types-circle-view/ "example of a circle view").
-   **Box plots** also known as **box-and whiskers charts** show the distribution of values along a chart axis. Refer to the [steps to build a box plot](https://help.tableau.com/current/pro/desktop/en-us/buildexamples_boxplot.htm "steps to build a box plot").
-   **Bullet graphs** compare a primary measure with another and can be used instead of dial gauge charts. Review the [steps to build a bullet graph](https://help.tableau.com/current/pro/desktop/en-us/qs_bullet_graphs.htm "steps to build a bullet graph").
-   **Packed bubble charts** display data in clustered circles. Review the [steps to build a packed bubble chart](https://help.tableau.com/current/pro/desktop/en-us/buildexamples_bubbles.htm "steps to build a packed bubble chart").


### Create vis in tableau
**Diverging color palette**: Displays two ranges of values using color intensity to show the magnitude of the number and the actual color to show which range the number is from.
(Intensity is a color’s brightness or dullness.)

The colors you choose should fit within the scope of the audience's expectations.
A lot of people associate green with positive results and red with negative results. 

e.g. Here is a good example, where green is associated with higher numbers and red with lower numbers.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image115.png)

Bad example:
- Bad color:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image116.png)
- Too many labels:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image117.png)



#### Rules
A few rules about what makes a good data visualization:
-   Five-second rule: A data visualization should be **clear, effective, and convincing** enough to be absorbed in 5 seconds or less.
-   Graphs and charts should use a **diverging color palette** to show contrast between elements
-   Should align with **audience expectations** and **cultural conventions**. For example, if the majority of your audience associates green with a positive concept and red with a negative one, your visualization should reflect this.
-   Should use as **few labels** as it takes to make sense. 
-   Having too many labels makes your graph or chart too busy, it takes up too much space, and it prevents the labels from being shown clearly.



#### Combining multiple data sources
Drag and drop two or more tables to create relationships. Double click on the table to open the join canvas. Then drag and drop tables to create the join. You can include calculations in the join if necessary.
The join merges the tables together to form a single, new table. (A join icon shows that.)
After joining, the new joined **Logical table** replaces the original **Physical table**. Related tables remain distinct.

Relationships are always "Equal to".

| **Resource**                                                 | **Description**                                              |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [**Set up data sources**](https://help.tableau.com/current/pro/desktop/en-us/datasource_prepare.htm) | This page links to other resources explaining how to **set up your data sources** and prepare them for analysis once you have connected them to your Tableau account. It specifically includes articles explaining how to join or blend data, and what a union is and how they work. This is a great starting point as you get ready to begin using and combining data sources. |
| [**Join your data**](https://help.tableau.com/current/pro/desktop/en-us/joining_tables.htm) | **Joining** refers to the process of combining data sources based on common fields. This article gives a more detailed explanation of the different joins, how to use them in Tableau, and an example join with a step-by-step guide. |
| [**Don’t be scared of relationships**](https://help.tableau.com/v2020.2/pro/desktop/en-us/datasource_dont_be_scared.htm) | **Relationships** allow you to combine multiple data sources in Tableau. This is a more flexible alternative to joins, and doesn’t force you to create one single table with your multiple data sources. This article will give you more insight into how relationships work. |
| [**How relationships differ from joins**](https://help.tableau.com/current/online/en-us/datasource_relationships_learnmorepage.htm) | This article goes into more detail about the differences between using **relationships and joins**, and guides you through the process of using relationships to combine data. |
| [**Blend your data**](https://help.tableau.com/current/pro/desktop/en-us/multiple_connections.htm) | **Data blending** is another method you can use to combine multiple data sources. Instead of truly combining the data, blends allow you to query and aggregate data from multiple sources. This resource goes into more detail about blending and includes a tutorial. |
| [**Combining multiple date fields**](https://kb.tableau.com/articles/howto/combining-start-and-end-dates-into-a-single-axis) | This resource provides examples that explain how to **combine date fields** when using four different methods of data combination in Tableau. |

---

## Crafting data stories
**Data visualization**: The representation and presentation of data to help with understanding.

**Dashboard**: A tool that organizes information from multiple datasets into one central location for tracking, analysis, and simple visualization.

**Dashboard filter**: A tool for showing only the data that meets a specific criteria while hiding the rest.

### Data storytelling
**Data storytelling**: Communicating the meaning of a dataset with visuals and a narrative that are customized for each particular audience.

For example, some music-streaming companies send their customers a "year in review" email. In these emails, they tell their customers which artists and songs they were a top fan of. This way, the companies use their customers’ data to tell a story.

**Data visualization** is the representation and presentation of data to help with understanding. You can use graphs, charts, word clouds, and other visual depictions to help your audience see and clearly understand your data.

The effects of data storytelling and data visualization can be powerful. Data storytelling and data visualization can captivate your audience, make stories memorable, touch people’s hearts, and inspire people to take action.

> "Numbers have an important story to tell. They rely on you to give them a clear and convincing voice."
> -Stephen Few

#### 3 data storytelling steps
##### 1. Engage your audience
**Engagement**: Capturing and holding someone's interest and attention.
Engaging your audience requires gathering audience and stakeholder insights so you can plan to tell a story that resonates.
Images can draw us in at a subconscious level. This is the concept of engaging people through data visualizations.
Every data story should start with audience engagement, all successful storytellers consider who's listening first.
To engage their audience, data analysts ask about what roles the people in the audience play, their stake in the project, and what they hope to do with the data insights.
##### 2. Create compelling visuals
Creating compelling visuals means making the data tell a story at a glance. If possible, make visuals interactive.
In other words, you want to show the story of your data, not just tell it.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image118.png)
##### 3. Tell the story in an interesting narrative
Telling the story in an interesting narrative means crafting a compelling story and giving your audience recommendations to take away.
It should connect the data you've collected to the project objective and clearly explain important insights from your analysis. To do this, it's important that your data storytelling is organized and concise.

**Your scope of work**
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image119.png)

#### Word Cloud
One of the many ways that companies use visualization to tell data stories, is with word clouds.
These words are presented in different sizes based on how often they appear in your data set.
Word clouds can be used in social media to show you which topics show up in posts most often; or in blogs to highlight the ideas that interest readers the most.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image120.png)

#### Take a tour of a data-driven article
[Mapping New York's Noisiest Neighborhoods](https://www.newyorker.com/tech/annals-of-technology/mapping-new-york-noise-complaints "Mapping New York's Noisiest Neighborhoods")

In data analytics, **data storytelling** is communicating the meaning of a dataset with visuals and a narrative that is customized for a particular audience, which has a lot in common with data journalists.

##### Tour stop 1: setting context
**Context** is the condition in which something exists or happens.

In that article, the data journalist used a combo table and bar chart to effectively summarize the noise categories, and answered the question, "what is noise?"
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image121.png)

But a defectiveness here is that the total is ninety-eight percent if you add the percentages in the combo table and bar chart.
So one lesson is to always make sure that your percentages add up correctly. Sometimes rounding decimal places up or down causes percentages to be off so they don’t add up to 100%.


##### Tour stop 2: analyzing variables
The [stacked area chart](https://media.newyorker.com/photos/590965cd1c7a8e33fb38d4ac/master/w_1600%2Cc_limit/Wellington-noise-ComplaintsHours.jpg "stacked area chart") showing the distribution of noise complaints versus the time of day:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image122.png)
It's a good vis because:
The color coding in the legend aligns with the colors in the chart.
A chart legend normally has the largest category at the top, but the data journalist chose to order the legend so the largest category, "Loud music or party" appears at the bottom instead.

As a best practice, both the x-axis and y-axis shuold be labeled.
The data journalist chose to include % or A.M. and P.M. instead of labeling the x-axis "Time of Day'' and the y-axis "Percentage of Noise Complaints".

##### Tour stop 3: drawing conclusions
After describing how the data was analyzed, the data journalist shares which neighborhoods are the noisiest using a variety of visualizations: [combo table and bar chart](https://media.newyorker.com/photos/590965ceebe912338a3758c2/master/w_1600%2Cc_limit/Wellington-noise-ComplaintsNeighborhoods.jpg "combo table and bar chart"), [density map](https://media.newyorker.com/photos/590965cfc14b3c606c1067b0/master/w_1600%2Cc_limit/Wellington-noise-complete.jpg "density map"), and [neighborhood map](https://media.newyorker.com/photos/590965d0ebe912338a3758c8/master/w_1600%2Cc_limit/Wellington-noise-WilliamsburgDetail.jpg "neighborhood map").
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image123.png)
The data journalist observed that one of the noisiest neighborhoods was right next to one of the quietest neighborhoods. The neighborhood map is effective in emphasizing this observation as a dark blue area versus a white area.

Best practice here: Each neighborhood is directly labeled so a legend isn’t necessary.


##### Additional information
For additional information about effective data storytelling, read these articles:
-   [What is Data Storytelling?](https://www.nugit.co/what-is-data-storytelling/ "What is Data Storytelling?")
-   [The Art of Storytelling in Analytics and Data Science | How to Create Data Stories?](https://www.analyticsvidhya.com/blog/2020/05/art-storytelling-analytics-data-science/ "The Art of Storytelling in Analytics and Data Science | How to Create Data Stories?")
-   [Use Data and Analytics to Tell a Story](https://www.gartner.com/smarterwithgartner/use-data-and-analytics-to-tell-a-story/ "Use Data and Analytics to Tell a Story")
-   [Tell a Meaningful Story With Data](https://www.thinkwithgoogle.com/marketing-resources/data-measurement/tell-meaningful-stories-with-data/ "Tell a Meaningful Story With Data")


#### Speaking to your audience
To get the response you're seeking, you've got to understand your audience's point of view.

Ask yourself a few questions:
- What role does this audience play?
- What is their stake in the project?
- What do they hope to get from the data insights deliver?


**Example**
*Analyzing readership data from customers to help a magazine publisher decide if they should switch from quarterly to monthly.*
***Stakeholder audience:***
Printing company --> they have to order paper and ink more frequently; assign more staff members.
Magazine authors and editors --> write and edit stories at a faster pace than they're used to.

Once you've considered the answers to those questions, it's time to choose your primary message.
Every single part of your story flows from this one key point, so it's got to be clear and direct.

Your data may show that readers feel the information is outdated; or the readers prefer shorter articles with quick takeaways.
To get the key message, you'll need to take a few steps back and pinpoint only the most useful pieces. (And eliminate the less important details.)
One way to do this is with something called spotlighting.

##### Spotlighting
**Spotlighting**: Scanning through data to quickly identify the most important insights.
Spotlighting involves scanning through data to quickly identify the most important insights. This can be done with notes on a whiteboard, by searching for broad ideas, and by identifying concepts that arise repeatedly.

Lots of data analysts like to use sticky notes on a whiteboard.
It's important not to get bogged down in every tiny detail. Instead, look for broad universal ideas and messages.
Next, explore your discoveries. The idea is to identify which insights are most likely to help solve your business problem or give you the answers you've been seeking.

Remember to keep your key message clear and concise.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image124.png)


### Tableau dashboard
Just like a car's dashboard, data analytics dashboards take tons of information and bring it to life in a clear, visually-interesting way. Which is extremely important in the second step of the 3-story-telling-step: Create compelling visuals

**Dashboard**: A tool that organizes information from multiple datasets into one central location for tracking, analysis, and simple visualization through tables, charts and graphs.
Dashboards do this by constantly monitoring live incoming data.

You can think about who will be looking at the data and what they need from it and how often they'll use it. Then you can make a dashboard with the perfect information just for your stakeholders.
People can get confused and distracted when they're presented with too much data.. A dashboard keeps things neat and tidy and easy to understand.

An important part of dashboard design is the placement or layout of your charts, graphs, and other visuals. These elements need to be cohesive, which means they're balanced and make good use of the space on the dashboard.

When designing a dashboard, data analysts can ensure that charts and graphs are most effective by placing them in a balanced layout and making good use of available space.

In Tableau you can choose between a vertical or horizontal layout, and select either tiled or floating layouts.
A vertical layout adjusts the height. A horizontal layout resizes the width of the views and objects it contains.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image125.png)

Dashboards put storytelling power in the hands of the viewer. That means they'll craft their own narrative and draw their own conclusions.


#### Live versus static
##### Static
**Static data** involves providing screenshots or snapshots in presentations or building dashboards using snapshots of data. There are pros and cons to static data.
**PROS**
-   Can tightly control a point-in-time narrative of the data and insight
-   Allows for complex analysis to be explained in-depth to a larger audience

**CONS**
-   Insight immediately begins to lose value and continues to do so the longer the data remains in a static state
-   Snapshots can't keep up with the pace of data change

##### Live
**Live data** means that you can build dashboards, reports, and views connected to automatically updated data.
**PROS**
-   Dashboards can be built to be more dynamic and scalable
-   Gives the most up-to-date data to the people who need it at the time when they need it
-   Allows for up-to-date curated views into data with the ability to build a scalable “single source of truth” for various use cases
-   Allows for immediate action to be taken on data that changes frequently
-   Alleviates time/resources spent on processes for every analysis

**CONS**
-   Can take engineering resources to keep pipelines live and scalable, which may be outside the scope of some companies' data resource allocation
-   Without the ability to interpret data, you can lose control of the narrative, which can cause data chaos (i.e. teams coming to conflicting conclusions based on the same data)
-   Can potentially cause a lack of trust if the data isn’t handled properly


Analysts need to familiarize themselves with the business and data so they can recommend when an updated static analysis is needed or should be refreshed.


#### From filters to charts
**Filtering**: Showing only the data that meets a specific criteria while hiding the rest.
You might choose to use filters in order to highlight individual data points or to zero in on what's important to your stakeholders.

Filters in Tableau can be used to limit information, customize information, or highlight a data point.
Pre-filtering saves stakeholders time and effort because it directs them to the most important data.

Filtering usage in tableau:
- Select one data point, click in the pop up window and exclude
- Select multiple data points, show only or exclude them
- In column, select the rows and filter them
- Or if you like, we can even prefilter a Tableau dashboard.

Appropriate uses for filters in Tableau include highlighting individual data points, limiting the number of rows or columns in view, and providing data to different users based on their particular needs.

#### charts in spreadsheets additional resources
Here are a few more resources you can reference as you learn more about charts in spreadsheets: 

-   [Graphs in Google Sheets](https://www.datacamp.com/community/tutorials/graphs-in-spreadsheets): Not only does this resource contain a detailed example of chart creation in spreadsheets, but it also provides you with downloadable sample data you can use to practice. As you have learned throughout this course, practicing these skills helps you learn more about the tools you are using. This example data is a great way to start!
-   [Add and edit a chart or graph in Google Sheets](https://support.google.com/docs/answer/63824): This article includes steps for creating, editing, and changing charts in Google Sheets with how-to videos. It also has a more in-depth guide to editing and customizing your chart after you have created it.  
-   [Create a Microsoft Excel chart from start to finish](https://support.microsoft.com/en-us/office/create-a-chart-from-start-to-finish-0baf399e-dd61-4e18-8a73-b3fd5d5680c2): This how-to guide from Microsoft’s support site includes instructions and a video tutorial for adding charts to Excel spreadsheets. This is a useful resource if you are working specifically with Excel spreadsheets. It also links to other useful articles about creating charts in Excel. 

[Microsoft Excel: Creating and modifying charts](https://guides.lib.umich.edu/c.php?g=283162&p=1886446): This is an explanation of Excel charts with downloadable handouts. This resource is especially useful because it has downloadable content that you can save to reference later when you start creating charts in your own spreadsheets.

#### Hands-on activity
##### Open the template and load the data
> The data usd here:
> ```
> Starter project and dataset/
>           Dashboards Starter Template.twbx
>           CO2 Dataset.xlsx

1. Open `Dashboards Starter Template.twbx` in Tableau Public Desktop.
2. Currently, the Tableau workbook does not contain the actual dataset. Next, you will load the dataset.
3. Put your dataset into `~/Documents/My Tableau Repository/Datasources` for a better organization.
4. Click the **Data Source** tab in the bottom left-hand corner of the window to load the data.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image127.png)

##### Create a dashboard
1. Click the **Add Dashboard** button, which is the middle button on the bottom row with a symbol that appears like a spreadsheet with a plus sign.
2. Drag **Sheet 1** onto the area that says **Drop sheets here**.
3. Click and drag **Sheet 2** onto the visualization and put it at the bottom half.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image128.png)
4. Remove the legend: click the topmost legend and then click the **X** attached to it
5. Float a legend: Click a legend, then click the arrow pointing downwards for **More Options**. From there, select **Floating**.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image129.png)
6. Drag the legend onto the top-right corner of the map visualization.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image130.png)

---

### Sharing data stories

#### The key parts of the narrative
The narrative you share with your stakeholders needs:
##### 1. Characters
The characters are the people affected by your story. This could be your stakeholders, customers, clients, and others.
##### 2. Setting
describes what's going on, how often it's happening, what tasks are involved, and other background information about the data project that describes the current situation.
##### 3. Plot
The plot, or conflict, is used to create tension in the data story.
This could be a challenge from a competitor, an inefficient process that needs to be fixed, or a new opportunity that the company just can't pass up.
This complication of the current situation should reveal the problem your analysis is solving and compel the characters to act.
##### 4. Big reveal
The big reveal, or resolution, involves how the data has shown that the problem can be solved.
It's how the data has shown that you can solve the problem the characters are facing by becoming more competitive, improving a process, inventing a new system, or whatever the ultimate goal of your data project may be.
##### 5. Aha moment
Your "aha moment" is when you share your recommendations and explain why you think they'll help your company be successful.

Using these basic elements to outline your presentation could be a great place to start, and they can help you organize your findings into a clear story.

And once you decided on these five key parts of your story, it's time to think about how to pair your narrative with interesting visuals because as you're learning, an interesting and persuasive data story needs interesting and persuasive visuals.

#### Sharing a narrative (Presentation)
If it's messy, disorganized, or full of images that don't support your story, your audience could easily lose confidence in your results and recommendations.
On the other hand, if your slideshow looks professional and appealing, you've got a better chance to capture your audience's attention and keep them focused on your main points. 

##### Theme
Themes make slideshows more consistent and professional by controlling color, font types and sizes, and positioning of text and visuals.

By choosing a theme that matches the tone and information you're communicating, your presentation will have a consistent look and support the argument you are trying to make.

##### Title
It's good to include a title and subtitle that describe what you're about to present.

You should include the date of your presentation too, especially if you're including data that's likely to change over time.
Specifying a date, such as a "date created" or "date last updated," gives anyone viewing your presentation important context.

##### Slideshow
A good slideshow guides the audience through your main communication points, but it doesn't repeat every word you say or give a lot of written information.
This might be a description of what's being shown in a visual, the first step in a process, a set of directions, or an important message that you want to be sure your audience understands and remembers.

##### Word and font
Also, be sure to adjust the font size so your audience can easily read what you've written.
A good rule is to keep texts to less than five lines and 25 words per slide.
Basically, you want your audience focused on what you're saying, not busy reading the slides.
Also, choose your words carefully. It's always smart to avoid slang terms, abbreviations that people might not know, and words or phrases that are specific to one particular region.
Best practices for writing text for a slideshow include choosing a readable font size, avoiding slang terms, and defining unfamiliar abbreviations.


##### Visuals
Visuals help the audience quickly understand the content of each slide.
Great visuals don't leave room for interpretation because the meaning is instantly understood.

When you include visuals on a slide, try not to share too many details all at once. Choose just the data points that support your points, especially your key message.

> Ask yourself: What's the single most important thing I want my audience to learn from my analysis?

If you have several important things you need to include, don't cram them all on one slide; instead, create a new visual for each point. Then add an arrow, a call-out, or another clearly-labeled element to direct your audience's attention toward what you want them to look at.

##### Conclusion
Finally, when you get to your big reveal and aha moment, your visuals must communicate these messages with clarity and excitement.
These are the most powerful discoveries from your analysis—make it feel that way.

##### Copy,link or embed
A quick tip for knowing when to copy and paste, link, or embed a visual into a slideshow.

**Copy and paste**
When you copy and paste a visual into your presentation, you can edit it directly within your slideshow.
Your visuals won't be updated if the original dataset changes. This means the visual might not reflect the latest information.

**Link**
If you link your visual within your presentation, the visual lives within its original file, and the slideshow connects to it with the visual's URL.
Changes in the original file will automatically appear in your presentation.
Useful if the data is likely to change over time.

**Embedded object**
An embedded object also lives in the original source file, but the difference is that it doesn't get automatically updated if the source file changes.
The embedded copy is completely independent. 
Changes you make in your presentation will not affect the original file.

The main difference between pasted, linked, and embedded objects has to do with where you store them and how you update them after you place them in your slideshow.

Create a new slideshow and select an appropriate **theme**. Add your **text**, **visuals**, and an exciting **reveal** at the end. Try **pasting**, **linking**, and **embedding** visuals from different sources to see how they behave differently.


#### Hands-On Activity: Practice presenting
**Create your slides**
-   [Google Slides](https://www.google.com/slides/about/) (Google account required)
-   [Microsoft 365](https://www.microsoft.com/en-us/microsoft-365/free-office-online-for-the-web) (Microsoft account required)
-   [Prezi](https://prezi.com/) (login required)

You can use [Screencastify](https://www.screencastify.com/ "Screencastify screen capture software") or a free trial of [Camtasia](https://www.techsmith.com/download/camtasia/ "Camtasia Free Trial Download") to record the slides of your presentation.


##### Evaluating your presentation:
Watch the video of your presentation.
Do you:
-   Use an attention-grabbing opening?
-   Start with broad ideas and later talk about specific details?
-   Speak in short sentences?
-   Pause for five seconds after showing a data visualization?
-   Pause intentionally at certain points?
-   Keep the pitch of your voice level?
-   Stand still and move with purpose?
-   Maintain good posture?
-   Look at your audience (or camera) while speaking?
-   Keep your message concise?
-   End by explaining why the data analysis matters?

##### Evaluate your slide deck
Do you:
-   Include a good title and subtitle that describe what you’re about to present?
-   Include the date of your presentation or the date when your slideshow was last updated?
-   Use a font size that lets the audience easily read your slides?
-   Showcase what business metrics you used?
-   Include effective visuals (like charts and graphs)?


---


## Developing presentations and slideshows
Present like a pro.
### Presenting with a framework
The ***purpose*** of a framework is to:
- create logical connections that tie back to the business task
(business task:  describes the question or problem your data analysis answers)
- gives your audience context about your data
- helps you focus on the most important information.

#### Business task
The framework of your presentation starts with your understanding of the business task.
Use the business task to frame our data and make it easier to understand.
If you present your data in the context of the business task, your audience will have a much easier time connecting with it.

**e.g.**
*Business task: Identify trends in online searches for avocados to help make seasonal stocking decisions.*

During our presentation, we want to make sure that we continue focusing on this task and framing our information with it.
We can begin our presentation by framing it with the business task in the title and the outline:
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image130.png)
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image131.png)

#### Outline
Clearly outlines the presentation so our audience knows what to expect.
It also lets them know how the information we share is going to be connected to the business task.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image132.png)

> Speaker notes: a great place to add important points you want to remember during the presentation ahead of time.

#### Metrics
You also want to make sure you're outlining and connecting with your business metrics by showcasing what business metrics you use, which can help your audience understand the impact your findings will have
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image133.png)



### Weaving data into your presentation
#### 1. Understand the data
First, it's helpful for your audience to understand what data was available during data collection.
You can also tell them if any new relevant data has come up, or if you discovered that you need different data.

#### 2. Establish the initial hypothesis
Establishing a hypothesis provides the audience with context about the analyst’s presentation.
**Hypothesis**: The theory you're trying to prove or disprove with data.
The purpose of a hypothesis is to theorize about your data.
Establishing the hypothesis early in the presentation will also help your audience understand the data.

#### 3. Explain the solution
Explain the solution to your business tasks using examples and visualizations.
Like the chart below.


#### The McCandless Method
The McCandless method for presenting a data visualization is to start with broad, general ideas and then work your way into the details.
1. **Introduce the graphic by name**
When we present it, we'll be sure to share that title with our audience so they know where to focus and what the graphic is all about.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image134.png)
2. **Answer obvious questions before they're asked**
e.g. 1. We added in the information about when, where, and how this data was gathered to answer an easy question "Where is this data from, and what does it cover?"
e.g. 2. Add an explanation to our speaker notes to answer how to read this graph as soon as this graph is introduced.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image135.png)

3. **State the insight of your graphic**
We can write in some key takeaways to this slide to help our audience understand the most important insights from the graphic.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image136.png)

4. **Call out data to support that insight**
This is your chance to really wow your audience, so gives many examples as you can.

5. **Tell your audience why your graphic matters**
When presenting to stakeholders, this is when you discuss the clear actions they can take and the impact of your findings.
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image138.png)


### Improve a slide presentation
Consider the following best practices for slide decks:
-   Include a title, subtitle, and date
-   Use a logical sequence of slides
-   Provide an agenda with a timeline
-   Limit the amount of text on slides. Your audience should be able to scan each block of text on your slides within 5 seconds
-   Start with the business task. Focus on the business task and frame the information in the context of the business task.
-   Establish the initial hypothesis
-   Show what business metrics you used
-   Use visualizations
-   Introduce the graphic by name
-   Provide a title for each graph
-   Go from the general to the specific
-   Use speaker notes to help you remember talking points
-   Include key takeaways

**Messy data presentation**
-   No story or logical flow
-   No titles
-   Too much text
-   Inconsistent format (no theme)
-   No recommendation or conclusion at the end

**Good data presentation**
-   Title and date the presentation was last updated
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image139.png)
-   Flow or table of contents
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image140.png)
-   Transition slides 
What are all the slides that are following this going to be driving towards?
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image141.png)
-   Visual introduction to the data (also used as a repeated theme)
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image142.png)
-   Animated bullet points
Bullet appears with clicks
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image143.png)
-   Annotations on top of visuals
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image144.png)
-   Logic and progression
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image145.png)
-   Limitations to the data (caveats) - what the data can’t tell you
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image146.png)




**Presentation skills for new data analysts**
> "Keep the concepts that you're presenting as simple and straightforward as possible."
> "Make your presentation fun."
> One of the things that I try to do to break it up is I try to think of little fun games or quizzes, or I'll play a video or ask questions to the audience just to make sure that they're fully engaged and that they are talking back to me.
> Story telling. "Everybody loves a good story. And when you do it right, you are able to connect and make your audience engage in a way that they probably wouldn't if you weren't telling that story'
> “Make sure you have an ally in the room."
> Not only to present my content to them ahead of time, but also to rescue.


### Proven presentation tips
Two key responsibilities of a data analyst:
1. Analyze the data
2. Present your findings effectively

If the idea of giving a presentation makes you nervous, don't worry—a lot of people feel that way. Here's a secret: it gets easier the more you practice.

**Basic tips**
1. Channel your excitement
To help keep that excitement in check, try taking deep, controlled breaths to calm your body down.
2. Start with the broader ideas
Start with the broader ideas, the obvious questions your audience might have, and what they need to understand to put your findings in context. Then you can get more specific about your analysis and the insights you've uncovered.
3. Use the five second rule
Whenever you introduce a data visualization, you should use the five-second rule and ask two questions:
    - First, wait five seconds after showing a data visualization to let your audience process it, then ask if they understand it. If not, take time to explain it.
    - Then give your audience another five seconds to let that sink in before telling them the conclusion you want them to understand. Try not to rush through data visualizations.
4. Preparation is key
Doing dress rehearsals, or writing out a script and repeating it in the head. Try to find a method that works for you.


### Guide: Sharing data findings in presentations
#### Tips
##### Tip 1: Know your flow
Just like in any good story, a data story must have a good plot (theme and flow), good dialogue (talking points), and a great ending or big reveal (results and conclusions).
Ask yourself these two questions to help you define the overall flow and build out your presentation:
**Who is my audience?**
- executives, board members, etc. --> storytelling should be kept at a high level
- stakeholders and managers --> Be prepared with talking points about the aspects of your analysis
- other analysts --> the most freedom, the most time, to go more deeply

**What is the purpose of my presentation?**
- request/recommend something --> have each slide work toward the recommendations
- focus on the results --> mark the path to the results
- provide a report --> clearly summarize your data and key findings

##### Tip 2: Prepare talking points and limit text on slides
As you create each slide in your presentation, prepare **talking points** (also called **speaker notes**) on what you will say.
![This illustration is of a slide with an area underneath reserved for talking points or speaker notes.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/h0SR-BF5Qs2EkfgReQLNyw_7312b185b23a486e83ed977de4149c14_Screen-Shot-2021-02-26-at-5.49.14-PM.png?expiry=1626566400000&hmac=SEm7y6PdKD6uLk7bgedklUNRcNPgW5u45qZCuKMNB8I)
Make it easy for your audience to skim read the slides while still paying attention to what you are saying. In general, follow the five-second rule.

##### Tip 3: End with your recommendations
Making recommendations at the end of your presentation is like getting to the mountaintop.
-   Use one slide for your recommendations at the end. Be clear and concise.
-   If you are recommending that something be done, provide next steps and describe what you would consider a successful outcome.

##### Tip 4: Allow enough time for the presentation and questions
Assume that everyone in your audience is busy. Keep your presentation on topic and as short as possible by:
-   Being aware of your timing. This applies to the total number of slides and the time you spend on each slide. 
-   Presenting your data efficiently. Make sure that every slide tells a unique and important part of your data story. If a slide isn’t that unique, you might think about combining the information on that slide with another slide.
-   Saving enough time for questions at the end or allowing enough time to answer questions throughout your presentation.


#### Your slide deck layout
![This illustration has the order and content on the slides: agenda, purpose, data/analysis, pitch, and a call to action](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/5UsZIrETQt6LGSKxEwLeOg_977ef053bf9045d396d5b4973c2f660f_Screen-Shot-2021-02-28-at-5.02.32-PM.png?expiry=1626566400000&hmac=43Y2peIisl3CbEeM4HmzKipKxgp7BQ68wnaLAu_d-Es)

##### First slide: Agenda
in general, most presentations run from 30 minutes to an hour at most. Here is an example of a 30-minute agenda:
-   Introductions (4 minutes)
-   Project overview and goals (5 minutes)
-   Data and analysis (10 minutes)
-   Recommendations (3 minutes)
-   Actionable steps (3 minutes)
-   Questions (5 minutes)

##### Second slide: Purpose
This slide summarizes the purpose of the project and why it is important to the business for your audience.

##### Third slide: Data/analysis
First, It's possible to tell your data story **in a single slide**. You may have supporting slides with additional data or information in an appendix.

But, if you choose to tell your story using **more than one slide**, keep the following in mind:
- Slides typically have a logical order
- Each slide should logically introduce the slide that follows it.
- Not to use too much text on the slides
- The high-level information that people read from the slides shouldn’t be the same as the information you provide in your talking points. There should be a nice balance between the two to tell a good story. You don’t want to simply read or say the words on the slides.

For extra visuals on the slides, use **animations**. For example, you can:
-   Fade in one bullet point at a time as you discuss each on a slide.
-   Only display the visual that is relevant to what you are talking about (fade out non-relevant visuals).
-   Use arrows or callouts to point to a specific area of a visual that you are using.

##### Fourth slide: Recommendations
This is when you might get a lot of questions about how your data supports your recommendations. Be ready to communicate how your data backs up your conclusion or recommendations in different ways. Having multiple words to state the same thing also helps if someone is having difficulty with one particular explanation.

##### Fifth slide: Call to action
Sometimes the call to action can be combined with the recommendations slide. If there are multiple actions or activities recommended, a separate slide is best.


##### Getting feedback
Consider asking your manager or another data analyst for candid thoughts about your storytelling and presentation overall. Feedback is great to help you improve.
When you have to write a brand new data story (or a sequel to the one you already told), you will be ready to impress your audience even more!



### Present like a pro
#### Your audience
- **Will not always see the steps you took to reach a conclusion**
This is called the curse of knowledge. To slove it:
    1. Answer basic questions.
    2. Include your guiding hypothesis and the goals that drove your analysis.
    3. Adding any assumptions or methods you used to reach your conclusions can also be useful.
    4. Explain your conclusion and how you reached it.
- **Has a lot on their mind**
Try to keep your presentation focused and to the point to keep their minds from wandering.
- **Is easily distracted**
Try to avoid including information in your presentations that you don't think will be productive to discussions with your audience, sharing the right amount of content to keep your audience focused and ready to take action.
For example, the more you include in a chart, the more your audience will need to explore it.
The practices that help keep an audience focused include making eye contact, reducing nervous habits, and pausing intentionally.
If you notice your audience is losing interest, you can redirect to a new question or ask a question to your audience to re-engage them.

#### Best practices
It's also good to note that how you present information is just as important as what you present.
Some best practices for delivering presentations:
First, pay attention to how you speak
**How you speak**
- Keep your sentences short
- Build in intentional pauses
- Keep the pitch of your sentences level

Also, try to be mindful of any nervous habits you have.
Maybe you talk faster, tap your toes, or touch your hair when you're nervous.
**Be mindful of nervous habits**
- Stay still and move with purpose
- Practice good posture
- Make positive eye contact

It’s helpful to channel your excitement to keep from getting nervous about a presentation. Preparing materials beforehand can help you remember your material, which may alleviate nerves.
Practicing breathing exercises can make it easier to keep your body calm before a presentation.

Remember that these are skills that you can practice with every presentation.
Feedback is a gift and an opportunity to grow.


> Important aspects to a presentation
>- Define your purpose
>- Keep it concise
>- Have some logical flow to your presentation
>- Make the presentation visually compelling
>- How easy is it to understand?


### Question and Objection
#### Anticipate the question
Remember to focus on stakeholder expectations and project goals, identify possible questions with your team, review your presentation with zero assumptions, and consider the limitations of your data.

**Stakeholder expectations**
- Understand your stakeholder's expectations
- Make sure you have a clear understanding of the objective and what the stakeholders wanted
If you misunderstood your stakeholders' expectations or the project objectives, you won't be able to correctly answer their questions

**Start with zero assumptions**
Don't assume that your audience is already familiar with jargon, acronyms, past events, or other necessary background information
![](https://github.com/dnencalada/Google_Data_Analytics/blob/main/Images/image147.png)
(*We'll fully explain what GDP means as soon as this graphic comes up.*)

**Work with your team**
Work with your team to anticipate questions and draft responses.

**Considering limitations of your data**
Be prepared to consider any limitations of your data by:
- Critically analyzing the correlations
- Looking at the context
- Understanding the strengths and weakness of the tools


A great way to identify audience questions is to do a test run of your presentation.
Or call it **the colleague test**.
Show your presentation or your data viz to a colleague who has no previous knowledge of your work, and see what questions they ask you.
A colleague test helps you assess what questions your stakeholders might have, what assumptions they might make, and what areas of your presentation might be unclear.


#### Preparing for the Q&A
##### Before the presentation
1.  Assemble and prepare your questions.
2.  Discuss your presentation with your manager, other analysts, or other friendly contacts in your organization.
3.  Ask a manager or other analysts what sort of questions were normally asked by your specific audience in the past.
4.  Seek comments, feedback, and questions on the deck or the document of your analysis.
5.  At least 24 hours ahead of the presentation, try and brainstorm tricky questions or unclear parts you may come across- this helps avoid surprises.
6.  It never hurts to practice what you will be presenting, to account for any missing information or simply to calm your nerves.

##### During the presentation
1.  Be prepared to respond to the things that you find and effectively and accurately explain your findings.
2.  Address potential questions that may come up.
3.  Avoid having a single question derail a presentation and propose following-up offline.
4.  Put supplementary visualizations and content in the appendix to help answer questions.

#### Q&A best practices
- **Listen to the whole question**
- **Repeat the question (if necessary)**
For one, it helps you make sure that you're understanding the question.
And, it gives the person asking it a chance to correct you if you're not.
Second, anyone who couldn't hear the question will still know what's being asked.
Plus, it gives you a moment to get your thoughts together.
- **Understand the context**
Think about who is your audience and what kinds of concerns or backgrounds they might have.
- **Involve the whole audiences**
It is best to involve the entire audience while answering a question. This keeps everyone involved in the discussion.
- **Keep your responses short and to the point**
Answer the question as directly as possible using the fewest words you can. From there, you can expand on your answer or add color, contexts, and detail as needed.(If the stakeholders care about it)

Remember, you don't have to answer every question on the spot. If it is a tough question that will require additional analysis or research, it's fine to let your audience know that you'll get back to them; just remember to follow up in a timely manner.

Appendix is a great place to keep extra information that might not be necessary for our presentation but could be useful for answering questions afterwards.

#### Handling objections
Stakeholders might raise objections during or after your presentation.

##### Types of objections
- **About the data**
    - ***Where you got the data?***
    (You can address data sources in the beginning of your presentation and provide resources for stakeholders to dive further into the data.)
    (When you receive an objection with merit, the best way to respond is by acknowledging its validity. Then, follow up with details and promise to investigate the matter further.)
    - ***What system is it came from?***
    - ***What transformations happened to it?***
    (Keeping a detailed log of data transformations is useful)
    - ***How fresh and accurate is the data?***
- **About your analysis**
    - ***Is your analysis reproducible?***
    (It helps to keep a change log documenting the steps you took.)
    (Or providing extra detail about your analytical process in the appendix.)
    - ***Who did you get feedback from?***
    (Making sure to include lots of perspectives throughout your analysis process will help you back up your findings during your presentation.)
- **About your findings**
    - ***Do these findings exist in previous time periods?***
    - ***Did you control for the differences in your data?***

##### Responding to possible objections
- Communicate any assumptions
- Explain why your analysis might be different than expected
- Acknowledge that those objections are valid and take steps to investigate further
(If your stakeholder has a concern about a problem you didn’t realize, you can acknowledge the objection and promise to take steps to investigate further.)

Appropriately respond to the objection:
- acknowledged that the objection was valid
- describing the approach you took in the analysis
- promising to investigate the matter further



## Course challenge Scenario
Scenario1.
You're asked to lead an upcoming client presentation and will be responsible for creating the data story, identifying the right tools to use, building the slideshow, and delivering the presentation to stakeholders.

1. You begin by getting together with your team to discuss the data story you want to tell.
Storytelling steps: engage your audience, ... . 
Use spotlighting to scan the data in order to identify the most important insights.
2. After revealing key insights, based on these insights, you create a clear and direct primary message, which will guide your data story.
3. Next, decide on your data narrative’s characters, setting, plot, big reveal, and aha moment.
4. Consider which tools to use to create data visualizations that will clearly communicate the results of your analysis. e.g. dashboard
5. Create data visualizations
6. highlight what your team’s analysis discovered
7. turn to projections for the future
