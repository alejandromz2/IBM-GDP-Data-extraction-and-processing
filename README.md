# IBM-GDP-Data-extraction-and-processing
This is a practice projecto, it consist in extract data froma a website using webscraping and reques APIs process it using Pandas and Numpy libraries

### Project Scenario:
An international firm that is looking to expand its business in different countries across the word has recruited you. You have been hired as a junior Data Engineer and are tasked with creting a script that can extract the list of the top 10 largest economies of the world in descending order of their GDPs in Billion USD (rounded to 2 decimal places), as logged by the International Monetary Fund (IMF).
The required data seems to be available on the URL mentioned below:

URL:  https://web.archive.org/web/20230902185326/https://en.wikipedia.org/wiki/List_of_countries_by_GDP_%28nominal%29

### Exercise 1

Extract the required GDP data from the given URL using Web Scraping. You can use Pandas library to extract the required table directly as a DataFrame. Note that the required table is the third one on the website, as shown in the image bellow.

<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0101EN-SkillsNetwork/images/pandas_wbs_3.png">

### Result Table:

![image](https://github.com/alejandromz2/IBM-GDP-Data-extraction-and-processing/assets/30611516/86aba9d1-2949-4836-831d-219786dd1250)


### Exercise 2

Modify the GDP column of the DataFrame, converting the value available in Million USD to Billion USD. Use the round() method of Numpy library to round the value to 2 decimal places. Modify the header of the DataFrame to GDP (Billion USD).
