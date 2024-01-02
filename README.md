# data-collection-challenge

In this challenge, we used what we learned about web scraping to obtain data from two websites about Mars. We used Splinter for automated browsing and Beautiful Soup to parse the html. 

In the first part of the challenge, our task was to obtain the titles and text previews from articles on the Mars News website. This was done by finding the html element that contained the articles and isolating the title and preview text using their class. 

In the second part of the challenge, this time the information to be scraped was stored in a table. We first isolated the html element that contained the rows, then we looped through each row to parse out the text values into a list. We then combined the list from each row into a list of rows and convereted it into a pandas dataframe. From there we cleaned the data by converting them to the appropriate data types. Then we performed analyses on the data such as calculating the average minimum temp and average pressure by month and plotted the results as bar charts. Lastly we plotted the minimum daily temperature and visually estimated the length of a Martian year based on the number of days between temperature peaks. We exported the dataframe to a csv file for future use.

Help for this code was obtained from this Stack Overflow article: https://stackoverflow.com/questions/44885933/how-to-sort-bars-in-a-bar-plot-in-ascending-order