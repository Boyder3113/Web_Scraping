<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <a href="#App Usage">App Usage</a></li>
    <li><a href="#built-with">Built With</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

Keeping up to date with Mars data!

*  This repository pulls Mars data from 4 seperate websites and consolodates the scaped data into one index.html file.
*  There are two scraping files, the first is a jupyter notebook file that documents the scraping process, but it is not linked to the app.
*  There is an index.html file, which provides a web template for the app to run through.
*  Finally the app.py file creates a flask api environment that runs the index.html file and allows the user to scrape new Mars data at any time.

## App Usage
*  Run the app.py file in your termnial, flask will create a local host for index.html
*  Click on the "Scrape New Mars Data" button to run the the "scrap_mars.py" file to get new Mars data at anytime!


<!-- BUILT WITH -->
## Built With

* Python
* Pandas
* Jupyter Notebook
* MongoDB
* Flask