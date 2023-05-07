Download Link: https://assignmentchef.com/product/solved-ise599-homework-2-analyze-wildfire-data-to-determine-which-states-had-large-fires
<br>
<em>                                                                                     </em>

The file StudyArea.csv contains wildfire data from 1980 to 2016 for the states California, Oregon, Washington, Idaho, Montana, Wyoming, Colorado, Utah, Nevada, Arizona, and New Mexico. There are about 400k fires and for each one the dates, location, and other relevant data is included.

In this example we analyze the data from this file to know what states have had most large fires and if the number and size of the fires has been increasing over the years. Our focus is on wildfires that burned more than 1000 acres. Remove NAs and use library ggplot2.

<ol>

 <li> Has the <em>overall </em>number of wildfires increased or decreased in the past few decades?</li>

 <li>Plot the number of fires by State and Year to find out in which states the number of wildfires has increased the most. Use facet_wrap(∼STATE) to show for different States, the number of fires by Year.</li>

 <li> Has the <em>overall </em>acreage burned increased over time?</li>

 <li></li>

</ol>

<ul>

 <li> Plot the log of the total acres burned by State and Year to find out in which states the total acres burned of wildfires has increased the most. Use aes(x=<strong>YEAR</strong>, y=log(ACRES) to plot the log of acres burned and facet_wrap(∼STATE) to see a plot for each state.</li>

</ul>

<ol start="5">

 <li> Is there a difference in the size of wildfires that were caused naturally as opposed to human induced? (Select Natural and Human from column Cause and group by CAUSE and year. Plot the log of total acres burned by Year with two lines, one for Human and other for Natural cause.)</li>

 <li>Make a violin plot to see the <em>distribution </em>of the log of acres burned by state. Show a boxplot inside each violin. Use layers geom_violin()+geom_boxplot(width=0.1) to create the graph. One vertical violin+boxplot per state.</li>

</ol>

1

<ol start="7">

 <li>Does the average wilfire size differ by federal organization?</li>

 <li>Has the length of the fire season increased over time? Make a plot with two layers of geom_line() to create lines displaying the earliest and latest <strong>start </strong>dates of fires by year. You may need to convert the start date of each fire into the day of the year (i.e. February 1st would be 32nd day in the year). Group by Year. Add a smoothed regression line to both line graphs. The length of the fire seasons increased if the gap of these lines increase.</li>

</ol>


