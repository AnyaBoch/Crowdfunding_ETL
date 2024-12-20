# Crowdfunding_ETL

For Project 2, we built a process to collect, clean, and store crowdfunding data using Python, Panda, PostgreSQL and ERT diagram app - app.quickdatabasediagrams.com. 
We started by pulling information from two Excel files and organizing it into four smaller files for categories, subcategories, campaigns, and contacts. 
We created unique IDs for categories and subcategories, cleaned up the campaign details like launch dates, end dates, and funding amounts, and separated contact 
information into first name, last name, and email. 
Next, we designed a database to store all this information, setting up the structure and relationships between the tables. 
Finally, we loaded the cleaned data into the database and checked to make sure everything was stored correctly.


* Pandas excels in working with structured data, managing DataFrames, and performing high-level transformations and aggregations. 
  It’s generally easier and more intuitive for typical data manipulation tasks.

* Regex shines when you need to extract or manipulate specific patterns from raw or unstructured text. It’s a go-to tool for text
  analysis but to manage when working with large amounts of structured data not a first choice.
