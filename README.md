# Web-Scraping---US-Cities
Scraped data from Wikipedia for US cities using python package 'scrapy' along with CSS selector

Steps:
1. Created a Spider class 'CitiesSpider' which contains the functions 'parse' and 'parse_individual_page' which scrape data from the initial url (https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population) and individual city pages respectively.
2. CSS selector has been used to extract the data in conjunction with scrapy framework.
3. Once the data has been extracted, it is cleaned by removing unnecessary characters, replacing some unnecessary unicode characters with similar ascii, removing unnecessary comma (,) in numeric fields, etc; created function clean_data() to carry out the cleaning task.
4. Created a function create_csv() which converts the cleaned data into a csv file.
