# Walgreens COVID-19 Vaccine Distribution

This project serves to model the distribution of the COVID-19 vaccine at all United States Walgreens locations. It is important to note that the Walgreens Company reports that vaccines will eventually be available at all of its locations across the United States.


## Data Retrieval

The Walgreens location dataset was scraped from the [Walgreens database](https://www.walgreens.com/storelistings/storesbystate.jsp?requestType=locator) using the Selenium WebDriver automated scraping tool and manually cleaned and formatted for completeness and cleanliness using regex, lambda functions, and packages such as BeautifulSoup. 

Additional data was then cleaned and appended, such as county-level population, income, COVID-19 cases, and deaths per county (updated 2/5/2021).

## Installation

Ensure that Selenium WebDriver is installed and that other configurations are installed according to the appropriate browser type. 

```bash
pip install -U selenium
```


## License
[MIT](https://choosealicense.com/licenses/mit/)
