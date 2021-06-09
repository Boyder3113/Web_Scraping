<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

If data was publicly available, how would you obtain it?

*  The project connects to Kaggle via API token using Python.  It downloads-and-unzips all files from the NHL Hockey source, which includes 13 CSVs and an ERD.
*  Using pandas, the CSVs are loaded to dataframes.  These dataframes are prepared/transformed for their final migration to a PostgreSQL database.
*  We SQL and pgAdmin to create the database schema.  This establishes the mini-warehouse for all hockey data from which analysis can be performed.
*  The Jupyter Notebook uses pands to_sql(), as well as a custom function using execute_values() from psycopg2, to load the transformed dataframes to the appropriate PostgresSQL database tables.
*  Queries analyzing the data have been written in SQL.

Each dataframe load to SQL prints an execution time (modular) and a total process run time.


<!-- BUILT WITH -->
## Built With

* Jupyter Notebook
* Kaggle
* MS Word
* pgAdmin
* PostreSQL
* Python