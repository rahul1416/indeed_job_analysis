The version of Python being used for the Assignment is 3.9.12

For web scrapping puropose in Part A, we use selenium module of python along with web driver to automate the browser(Chrome). Along with installing the packages of selenium and webdriver_manager, we need to also download the chrome driver in order to automate it. It can be downloaded from the following website ("https://chromedriver.chromium.org/downloads"). Before that we need to check the version of Chrome that is currently being used. To check the version, open Chrome browser, at the top right corner there are three dots, select "Settings". Under Settings, click on the "About Chrome" there you will know about the version of Chrome that is installed on your local machine. Download it and copy the path where the file is saved for use in the code. 
The list of modules imported and their versions are listed below:
1. Pandas - 1.4.2
2. Numpy - 1.21.5
3. For  - 4.11.1
4. Selenium - 4.4.3

Using BeautifulSoup we extracted the html of the webpage. For each role of Data Engineer, Data Analyst, Data scientist and Machine Learning we extract the html of 30 pages and from each page we get 15 vacancy application. We parse each page and by tagging different html tags we extract various columns of information about the vacancy.

For part B, we have used the following modules with thier respective versions as follows:
1. Seaborn - 0.11.2
2. Pandas - 1.4.2
3. Numpy - 1.21.5
4. Matplotlib - 3.7.0
5. Plotly - 5.13.1
For the first subpart i.e., the distribution of jobs geographically, we used a pie chart to show the distribution of the jobs over different regions in India. For the second and third subpart, we used a bar graph to depict the relation between companies and thier vacancies in different roles and distribution of characters in description. For the fourth and fifth sub-part we used box plot to show the distribution of salaries in remote jobs and Bangalore.


For part C, we have listed out the top 5 locations based on the and plotted grouped-bar graph showing the mean salaries for each role in these locations.