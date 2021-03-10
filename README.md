

 <h3 align="center">WebscraptoExcel</h3> 
  
  <!-- ABOUT THE PROJECT -->
## About The Project
The following project is one I created for a certain school of medicine that was interestd in having a program that downloads covid numbers from data tables on the CDPH.CA website - https://www.cdph.ca.gov/Programs/CID/DCDC/Pages/COVID-19/Race-Ethnicity.aspx. Beautifulsoup was not used for this scraper. Pandas and xlsxwriter was all I needed.

### Prerequisites

Make sure you have these packages installed below. You will need to run these in terminal if you are on Mac or commpand prompt if you are on Windows.

*pip install python
```sh
pip install python4
```

*pip install XlsxWriter
```sh
pip install XlswWriter
```

Some knowledge of transforming a data frame in Python
```sh
https://docs.python.org/3/tutorial/index.html
```

### Installation
You will need Jupyter Notebook or any programming environment you prefer. I recommend Juypter Notebook. It is what I used to perform webscrapping.
```sh
https://jupyter.org/
```
You can always download anaconda. It is free platform and includes juypter notebook.

```sh
https://www.anaconda.com/
```

<!-- USAGE EXAMPLES -->
## Usage
You can use this Juypter Notebooks to teach yourself how to perform webscraping and convert it into an excel spreadsheet. This notebook also replaces several column names. The resulting output concatenates the dataframes for the 0-17, 18-34, 35-49, 50-64, 65-79 and 80+ age demographic data tables into one tab on the spreadsheet. 

## Future Versions
I plan to work on a new version of this webscrapper to include moving this data into a Database.
