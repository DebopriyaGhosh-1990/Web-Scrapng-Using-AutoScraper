# Web-Scrapng-Using-AutoScraper
Automating Web Scraping Using Python AutoScraper Library

Web Scraping is a method or art to get or scrap data from the internet or websites and storing it locally on your system. Web Scripting is a programmed strategy to acquire a lot of information from sites. Web Scrapers can extract all the information on specific destinations or the particular information that a client needs. Preferably, it’s ideal if you indicate the information you need so the web scraper just concentrates that information rapidly.

Autoscraper is a smart, automatic. Fast and lightweight web scraper for python. It makes web scraping an easy task. It gets a URL or the HTML content of a web page and a list of sample data that we want to scrape from that page. It is easy as we only need to write a few lines of code, it’s blazingly fast because it is lightweight and It learns the scraping rules and returns the similar elements.

## Implementation:  

Autoscraper can be installed using the git repository where it is hosted. Before Installing autoscraper you need to download and install the git version according to your operating system. After git is installed we can install autoscraper by running the below-given command in the command prompt.

pip install git+https://github.com/alirezamika/autoscraper.git

- 1 **Importing Required Libraries:**
We will only import autoscraper as it is sufficient for web scraping alone.

from autoscraper import AutoScraper

- 2 **Defining Web Scraping function:**
Define a URL from which will be used to fetch the data and the required data sample which is to be fetched. 
Url = "WWW.somting.....com"
wishist = ['search string1', 'search string2',......]

- 3 **Initiate AutoScraper:**
The next step is calling the AutoScraper function so that we can use it to build the scraper model and perform a web scraping operation. 

- 4 **Building The object:**
This is the final step where we create the object and display the result of the web scraping.

- 5 **Function for Similar Result:**
Autoscraper allows you to use the model you build for fetching similar data from a different URL. We need to use the ‘get_result_similar’ function to fetch similar data.

- 6 **Saving the Model**
Autoscraper allows us to save the model created and load it whenever required.


#### Uploaded files:

Uploaded a jupyter Notebook with the step by step approach to use AutoScraper for web scraping.

You can use any URL to scrap following the same steps.


### END
