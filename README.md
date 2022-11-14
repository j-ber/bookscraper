# bookscraper

Our team worked on a Book Scraper project. First of all, we decided to implement web scraping with the Python library BeautifulSoap to collect information in easy way. Our next step was inspecting the page of the provided book library. We extracted such book's parameters as Name, Availability, Price, URL, UPS, and Category in the "div" tag. After this, in the Python file, we coded steps for extracting data and storing results into a CSV file. If our team had more time, we would like to create an HTML website that would have a filter from table search. It could make the process of finding the book easier and much more convenient for customers.

There are 3 files attahced to this project:
1) books_scraper.ipynb
   here you will find a code that we used to get books data from http://books.toscrape.com/  
2) books_scraped.csv
   this is a csv file that shows a dataframe, which is a result of web scraper above
3) data_analysis_dash_app.ipynb
   here is a code for analysis we did and dash app we created based on web scraped data
4) Dash.html
   here you can find the result of the above code, website application with analysis
   
   
Please make sure that before running the code following libraries must be installed:
 - pandas
 - numpy
 - BeautifulSoap
 - requests
 - lxml.html
 - jupyterdash
 - dash
 - plotly
 - plotly.express
 
 
   
   
   

