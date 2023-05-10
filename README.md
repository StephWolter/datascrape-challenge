# datascrape-challenge

# Use BeautifulSoup and python through Pandas to scrape and then analyze Mars data from a given website.

## SetUp

* Create Repository in GitHub.
[datascrape-challenge repository](https://github.com/StephWolter/datascrape-challenge.git)

* Clone sqlalchemy-challenge repository to personal computer, then create the folder structure:


            * part_1_mars_news.ipynb                # main code for first half of the challenge
            * part_2_mars_news.ipynb                # main code for the second half of the challenge
            * mars_facts.csv                        # output csv data from part_2_mars_news_ipynb
            * README.md

* Examined the brief given on the bootcampspot module challenge #11 page and pulled starter files. 
* Created new Database datascrape-challenge
* Pushed regularly to git repository.
* In Pandas opened given starter files.

## Part One

* Opened part_1_mars_news.ipynb given in the starter folder.
* Used chrome driver manager to open and connect to a browser

### Step 1: Visited the Website
    * Connected to [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html) 
    * Checked the website using Developer Tools to see the structure.

### Step 2: Scraped the Website
    * Used BeautifulSoup to pull the html data from the site.
        * Created object **mars_soup** 
        * Examined html code briefly.
    * Extracted all text elements by pulling 'div' class "list_text"
        * Called it **mars_stuff**

### Step 3: Stored the Results
    * Stored each title-and-preview pair in a Python dictionary. 
        * Created and populated a list **articles** using a for loop
        * Populated with dictionaries with the titles and previews of the articles.
        * Printed the list
### Close the browser session.

## Part Two: Scrape and Analayze Mars Weather Data

    * Opened part_1_mars_news.ipynb given in the starter folder.
    * Used chrome driver manager to open and connect to a browser

### Step 1: Visited the Website
    * Connected to [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html) 
    * Checked the website using Developer Tools to see the structure.

### Step 2: Scraped the Website
    * Used BeautifulSoup to pull the html data from the site.
        * Created object **mars_soup** 
        * Examined html code briefly.
    * Extracted all text elements by pulling 'div' class "list_text"
        * Called it **mars_stuff**


## Wrote out README
* Voila
