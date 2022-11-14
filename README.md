# bookscraper

Our team worked on a Book Scraper project. First of all, we decided to implement web scraping with the Python library BeautifulSoap to collect information in easy way. Our next step was inspecting the page of the provided book library. We extracted such book's parameters as Name, Availability, Price, URL, UPS, and Category in the "div" tag. After this, in the Python file, we coded steps for extracting data and storing results into a CSV file. If our team had more time, we would like to create an HTML website that would have a filter from table search. It would allow users to find books in a very efficient way by allowing them to search any book in different ways such as its UPC, name, category, and availability; and be able to see the cover of the book. Moreover, we would’ve like to expand our data analysis by providing an interactive physical representation of the relationship of the data such as the differences of prices depending on their category. Consequently, users would be able to access all these different functionalities by accessing the website through just a click of a link and not having to download any library. One of the biggest challenges that we faced was working in a team of four without much cumulative experience creating websites or web scraping. However, our previous experiences enabled us to be fast learners and our determination to accomplish our goal, while also excelling in our other commitments, pushed us to go past those challenges and use our abilities to create something. More time and perhaps one or more teammates would have allowed us to accomplish all our aspirations for this application.

There are 3 files attached to this project:
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
 
 
   
   
   

