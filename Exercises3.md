Exercises
==========

1. *Slurp JSON data*
    
    Access the data at [Exchange Rates](http://openexchangerates.org/latest.json) using a `JsonSlurper`. 

2. *Geocode addresses*

   See the [Google Geocoder documentation](https://developers.google.com/maps/documentation/geocoding/).
   
   Build a map of query parameters. The required parameters are `address` and `sensor`. The address is a combination of street, city, and state. The individual values must be URL encoded and then concatenated, separated by ",+". The value of sensor is true if the call comes from a GPS device and false otherwise, so it will be false for us.
   
   Create a list of street, city, and state strings. Use the `collect` method to transform them using the `java.net.URLEncoder.encode(...,'UTF-8')` method. Join the resulting strings using ",+" and save that as the URL encoded address.
   
   Build the full query string by transforming the map into a list of "key=value" elements and join the list with &.
   
   Assemble the full URL using the XML version. Transmit the request to Google and extract the latitude and longitude values.
   
   Do the same using the JSON version.

3. *Implement a DAO using Groovy SQL*

   For the `Product` class, create a `ProductDAO` that has methods to find a product by id, find by name, find all products, add a product, and delete a product. Use the `groovy.sql.Sql` class to implement the DAO.
   
4. *Yahoo! Weather service*

   Access the Yahoo! Weather web service and parse the XML result to get the expected high and low temperatures.