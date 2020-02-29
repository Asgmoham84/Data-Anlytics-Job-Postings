<h1> Creating a Data Frame of Job Postings from Scratch</h1>
<h2> As a Data Scientist, in what Canadian city you will have the highest chance to get hired?</h2>

This is one type of question that we will be able to answer after creating and analyzing this data set. I started this project when I was still living in Newfoundland and was working as a Data Scientist at the Center for Health Informatics and Analytics (CHIA). After a while I decided to move to another city and was curious to see how the job market is for Data Scientists in other cities. At first it was obvious that Toronto would have the highest number of <b>job postings</b> for data scientist, but I was also thinking that if you consider the high population of Toronto, then would you still say that if you move to Toronto, would you still have the highest chance of getting hired? In this project we will show that although Toronto has the highest nmuber of Data Science jobs, but you will have a higher chance in Vancouver and Waterloo to get hired, rather compared to Toronto.</b><br><br><br>
(The first screenshot below is taken from indeed.ca)

<img src='Intro.png'>

This is what we are going to see in this project, but it is not the only thing we will do in this project.
So for this project, the first an the most important thing we need is data, but how we are going to get this data? I wasn't able to find any open data online, so I decided to create my own data set from scratch. This is what we would also do in this project.


<b>Here we are going to create our own data set from real data. </b><br>
In fact, this article would also help you if you are a data scientist and want to work with some real data, so you can create your own data set of job postings.
Here we will show how you can scrape the Internet to extract data and create your own real-life data set. The website that we are going to scrape is www.indeed.ca in order to extract job postings data.<br>
We will get the job titles, company name, location, job posting URL, and more importantly, the job description.<br>
For this purpose.<br><br>

In this notebook we will use:<br>

<b>BeautifulSoup</b> is a python library that lets you extract information from html and xml files. To see the documentation, pleae click <a href='https://www.crummy.com/software/BeautifulSoup/bs4/doc/'> here</a> 

<b>Pandas</b> for creating a data frame of the job postings data, and also for some data analysis<br><br>
<b>Matplotlib</b> for the visualization. We will create some basic graphs in the end. If you are not already familiar with Matplotlib please click <a href='https://matplotlib.org/'> here</a> <br><br>
We will use the BeautifulSoup python library for the scraping part, and after we have the data set ready, we will do some data visualizations with Matplotlib.<br><br>

<b>Your questions and comments are welcome! <br></b>

<br><br>This is how the data frame will look like after we scrape the data:

<img src='DF.png'>



<h3>These are the steps we take for this project:<br></h3>
<ul>
    <li> Importing the libraries<br>
    <li> Creating a URL (a string) to brings us to the job posting site with the searching element we have defined<br>
    <li> Getting the number of jobs that are found as our search result. We need this to loop over each and every job posting's URL, and then get the information. We need to know how many jobs and how many pages we are going to scrape<br>
    <li> Extracting job postings information from the url and having them as a data frame<br>
    <li> Saving the data into a CSV file<br>
    <li> Doing some data cleansing
    <li> Doing a group_by to get the number of jobs by location
    <li> Visualization of the distribution of the jobs by Canadian cities
    <li> Merging the results with the population data set
    <li> Calcualting rates of available jobs by 100,000 people
    <li> Visualization of the results
    
</ul>

### We have done some Natural Language Processing and some more data analysis using this data set. If you are interested, please  <a href='https://www.crummy.com/software/BeautifulSoup/bs4/doc/'> take a look</a> 
