# nosql-challenge

# NoSql Challenge

• Import the data provided (establishments.json) and create a Mongo database.

• Use jupyter notebook to confirm the database is loaded properly (it exists with the proper collects and documents)

* Make the following updates prior to completing analysis

   * Add the new halal restaurant, "Penang Flavours", that just opened in Greenwich with the BusinessTypeID for "Restaurant/Cafe/Canteen"
  
   * Remove all establishments in Dover Local Authority
  
   * Convert latitude and longitude to decimal numbers
  
   * Conver RatingValue to integer numbers

* Complete the following analysis
  
    * Determine which establishments have a hygiene score equal to 20
   
    * Determine which establishments in London have a RatingValue greater than or equal to 4
      
    * Determine the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"
      
    * Determine e how many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest.

## Notes

* Resources folder contains the data that must be loaded prior to executing any of provided code

   * establishments.json contains the data provided for this challenge. Use the following command in terminal to import the data:

    mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json

• NoSQL_setup.ipynb was based off NoSQL_setup_starter.ipynb to complete the database setup and modifications prior to analysis.

• NoSQL_analysis.ipynb was based off NoSQL_analysis_starter.ipynb to complete the analysis
Starter_Code folder contains the files provided in BCS/Canvas for completing the challenge

## Built With

##### Tools :

• Python v3.10.11
• jupyter notebook v6.5.2

##### Python Modules:

• pandas v1.5.3
• pymongo v3.12.0
• pprint
