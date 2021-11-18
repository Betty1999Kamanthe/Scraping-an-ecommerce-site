# Scraping-an-ecommerce-site

Scrape the below mentioned website for all the Cars and their Details.
We recommend a two-stage scrape whereby first stage you scrape all the listings and the URLs and then in stage 2 scrape individual cars. https://www.bilbasen.dk/brugt/bil?IncludeEngrosCVR=true&PriceFrom=0&includeLeasing=true

The section outlined in red in the first screenshot represents the total number of cars of the website, the script should be written in a way that user can input choose between Dealer and Private as mentioned in the screenshot .

After going into each of the results that show up, the items shown in the screenshots above should be scrapped. The list of attributes to be scrapped is given below for your reference as per the screenshots above:

1. Basic Information
2. Detailed Information
3. Contact (dealership/private)
The output of the web scrapper should be fed into an Excel Workbook (.xlsx or csv) where each of these attributes are written in separate columns.


# Explanation of the different csv files

1. Private.csv - Contains the name and URL's of all cars in the private link
2. Dealer.csv - Contains the name and URL's of all cars in the dealer link
3. privateinfo.csv - Has Name,Basic information, Detailed information and contacts of all cars in the private link
4. dealerinfo.csv - Has Name,Basic information, Detailed information and contacts of all cars in the dealer link

# Dviz.ipnb
Contains the python code

# Dvizapi.ipnd
Contains the flask API
