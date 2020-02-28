If you are a data scientist and want to work with some real data, this article would help you create your own data set of job postings data.
Here we will show how you can scrape the Internet to extract data and create your own real-life data set. The website that we are going to scrape is www.indeed.ca in order to extract job postings data.<br>
We will get the job titles, company name, location, job posting URL, and more importantly, the job description.<br>
For this purpose.<br><br>

In this notebook we will use:<br>

<b>BeautifulSoup</b> is a python library that lets you extract information from html and xml files. To see the documentation, pleae click <a href='https://www.crummy.com/software/BeautifulSoup/bs4/doc/'> here</a> 

<b>Pandas</b> for creating a data frame of the job postings data, and also for some data analysis<br><br>
<b>Matplotlib</b> for the visualization. We will create some basic graphs in the end. If you are not already familiar with Matplotlib please click <a href='https://matplotlib.org/'> here</a> <br><br>
We will use the BeautifulSoup python library for the scraping part, and after we have the data set ready, we will do some data visualizations with Matplotlib.<br><br>

Your questions and comments are welcome!


<h3>We will do this in five steps:<br></h3>
<ul>
<li> Importing the libraries<br>
<li> Creating a URL (a string) to brings us to the job posting site with the searching element we have defined<br>
<li> Getting the number of jobs that are found as our search result. We need this to loop over each and every job posting's URL, and then get the information. We need to know how many jobs and how many pages we are going to scrape<br>
<li> Extracting job postings information from the url and having them as a data frame<br>
<li> Saving the data into a CSV file<br>
<li> Doing some data cleansing
<li> Visualization of the distribution of the jobs by Canadian cities
    
</ul>

### We have done some Natural Language Processing and some more data analysis using this data set. If you are interested, please  <a href='https://www.crummy.com/software/BeautifulSoup/bs4/doc/'> take a look</a> 
