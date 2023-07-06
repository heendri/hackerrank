
# Weather Observation Station 9

Query the list of **CITY** names from **STATION** that do not start with vowels. Your result cannot contain duplicates.

**Input Format**

The **STATION** table is described as follows:

![App Screenshot](https://s3.amazonaws.com/hr-challenge-images/9336/1449345840-5f0a551030-Station.jpg)

where LAT_N is the northern latitude and LONG_W is the western longitude.



====================
## Answer

SELECT DISTINCT city FROM station WHERE NOT(city LIKE 'a%' OR city LIKE 'i%' OR city LIKE 'u%' OR city LIKE 'e%' OR city LIKE 'o%');