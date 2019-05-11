# Mining Google Search History
The objective of this project is to practice Python 3 coding for data science. It consists of two components -  1) Web scraping using BeautifulSoup and 2) Data visualization using pandas, matplotlib and the natural language tool kit (NLTK).

The data file is downloaded from Google's Web & App Activity page following the instructions in the following link: 
http://uk.businessinsider.com/how-to-download-copy-of-google-search-history-2015-4

The data downloaded contains my Google search history (consisting of both Searches and Visits) from 24 Sep 2014 to 19 Oct 2018 in .html format.

# Web Scraping
Using BeautifulSoup, I scraped the information from the .html file, including date, search term, type of activity (search or visit) and timestamp, storing it in .csv.

# Data Visualization 
Using Pandas and matplotlib, I generate figures 1-6, which analyse the annual and weekly patterns of my activity. Using NLTK, I derive figure 7, which shows the most frequent search terms I used.
