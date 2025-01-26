# crowdfunding_ETL

What is in this repo
- Located in this repo is a jupyter notebook containing my code that
creates all of the CSVs for the crowdfunding_schema. Located in the Resources
folder are the contacts.xlsx and crowdfunding.xlsx. as well as the 4 CSVs
titled campaign, category, subcategory, and contacts. The crowd_funding_db_schema
houses the code to use in postgres to create the tables and import the csvs. 
Finally, there is a screenshot of my ERD created in DBD.

How to properly run the code
- In order to correctly run the code, run the entirety of the jupyter notebook. 
The CSVS will be exported to the Resources folder I mentioned above. Once you
have created the 4 CSVs you can go into Postgres and run the crowd_funding_db_schema
file. This will create 4 tables titled, campaign, category, subcategory, and contacts.
In order to correctly import the CSVs, import the contacts CSV, then import the
subcategory CSV, the category CSV and then the campaign CSV. The order of the first three should not effect anything as long as the campaign CSV is imported last. Once the CSVs are successfully imported, you can run each of the SELECT * lines to ensure all data was
imported correctly. 

How this code was generated
- During our first classroom worktime, I worked with my classmates Toka, Makenna,
Alice, Ethan, Jacob, and Duvoe for the code on splitting columns, the liste 
comprehension to add cat and subcat to each category_id. We also worked together
to creating the category and subcategory dataframes and they helped me with the
syntax for setting launch_date and end_date to datetime. In our second classroom
work session, I worked with my classmates Alica, Toka, and Maxwell to edit
some of the mistakes in my ERD and for correcting DATETIME variables to DATE. 
My professor Thomas helped trouble shoot errors in creating the campaign
cleaned dataframe. Finally, the code for the SQL file was exported from
QuickDataBaseDiagrams.com.
