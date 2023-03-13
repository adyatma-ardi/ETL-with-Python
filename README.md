# ETL with Python
<p align="justify">
ETL (Extract, Transform, Load) is the primary, older method of loading data from one system to another. In this project I will store data with a CSV file extension into a PostgreSQL database using the Python programming language which has previously been cleaned and transformed.
</p>

<h6>
Author&ensp;&ensp;&ensp;&nbsp; : &ensp;Achmad Adyatma Ardi <br>
Email&ensp;&ensp;&ensp;&ensp;&ensp;&nbsp;: &ensp;adyatmaardi@gmail.com <br>
LinkedIn&ensp;&ensp; :&ensp; https://www.linkedin.com/in/adyatmaardi/ <br>
</h6>
<hr>
<div>
<h4>Prerequisites :</h4>
<ol>
  <li> Postgres database already installed locally </li>
  <li> Install necessary Python-module 
        <ul>
          <li><a href ="https://pypi.org/project/pandas/">Pandas</a> module - it makes you to use high-performance data structures and data analysis tools. <br>install >>> [pip install pandas]</li>
          <li><a href ="https://pypi.org/project/DateTime/">DateTime</a> module - it supplies classes for manipulating dates and times. <br>install >>> [pip install DateTime]</li>
          <li><a href ="https://pypi.org/project/SQLAlchemy/">SQLAlchemy</a> module - it facilitates the communication between Python scripts or programs to the databases. It is used as an Object Relational Mapper (ORM) tool. <br>install >>> [pip install SQLAlchemy]</li>
          <li><a href ="https://pypi.org/project/psycopg2/">psycopg2</a> module - is a PostgreSQL database driver, its mainly used to perform operations on PostgreSQL using python and it designed for multi-threaded applications. <br>install >>> [pip install psycopg2]</li>
        </ul>
  </li>
</ol>
</div>
<hr>
<div>
 <h4>Objectives :</h4>
  <ol>
    <li>To do ETL (Extract, Transform, Load) through Python-PostgreSQL</li>
    <li>Exract CSVs files from your computer path directory to Jupyter Notebook</li>
    <li>Transform CSV files
        <ul>
          <li>drop columns</li>
          <li>rename the spesific column</li>
          <li>convert date column (as object type) to datetime</li>
          <li>merge data</li>
        </ul>
    </li>
    <li>Connect to PostgreSQL database
        <ul>
          <li>method 1 : using SQLAlchemy</li>
          <li>method 2 : using psycopg2</li>
        </ul>
    </li>
    <li>Test - CRUD operations using both methods (sqlalchemy & psycopg2)</li>
    <li>Load data
        <ul>
          <li>create schema table</li>
          <li>load merged data to the postgreSQL database</li>
          <li>try to show head() and tail() data using Jupyter Notebook from database that has been created</li>
        </ul>
    </li>
  </ol>
</div>
