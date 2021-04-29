# **Mission-to-Mars**

**Objectives**

- Use BeautifulSoup and Splinter to automate a web browser and scrape high-resolution images.
- Use a MongoDB database to store data from the web scrape.
- Update the web application and Flask to display the data from the web scrape.
- Use Bootstrap to style the web app.

**Resources**

- Python 3.7.7
- Jupyter Notebook
- Modules/Libraries: splinter, BeautifulSoup, pandas, datetime
- VS Code (.py, .html, .css files)
- MongoDB
- Flask
- Bootstrap 3

**Installation**

- Open MongoDB (mongod command in Bash), create/use a database named &quot;mars\_app&quot;
- run app.py to bring up local host address
- click Scrape New Data button to start app

**Description**

The web scrape is performed in the functions written in the python script: [scraping.py]. Output is pushed to a browser with Flask, with the app routes being set up in the python script [app.py].
 The app routes in the app.py script calls the scraping.py script which contains the code that is doing the work.
 Data is stored in a MongoDB, where it is retrieved to display on the browser through a locally hosted Flask instance.
 The page is set up and formatted with an html file. This file uses Bootstrap 3 components to clean up the display and add responsive image types to allow for optimized viewing across various devices.
