# Module 11 Challenge

# Project Description

The purpose of this repository is to use Splinter and BeautifulSoup to retrieve data from two webpages,
- https://static.bc-edx.com/data/web/mars_news/index.html (used in part_1_mars_news.ipynb)
- https://static.bc-edx.com/data/web/mars_facts/temperature.html (used in part_2_mars_news.ipynb)
containing mars related news and data and to perform some elementary analysis.
 
The analysis is done in two separate jupyter notebooks, 'part_1_mars_news.ipynb', and 'part_2_mars_weather.ipynb'. The first notebook uses beautiful soup and chromedriver to retrieve 


# Installations

The required libraries to run the two notebooks are,

- Splinter
- bs4
- pandas
- matplotlib.pyplot
- pprint (standard library)

pandas and matplotlib.pyplot can simply be installed in your environment using the commandline/terminal,

pip install pandas <br>
pip install matplotlib

Inorder to use Splinter and bs4 in the provided jupyter notebooks the following commands can be used,

pip install "splinter[selenium4]" <br>
pip install bs4 <br>
pip install html5lib <br>
pip install lxml

where html5lib and lxml libraries are used by Beautiful Soup. <br>
Finally, for automation of the chrome browser, it is required that Chromedriver is downloaded. Instructions for installation can be found here: https://splinter.readthedocs.io/en/latest/install/external.html.

Once the installation of the above packages is completed, the repository can be downloaded to your local computer and run using VScode or JupyterLab.

# Acknowledgements

Starter code for both jupyer notebooks and instructions on installations of the required libraries were provided by 
the Monash Data Analytics Bootcamp.
