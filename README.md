# MySQL
Solutions of Hackerrank SQL questions

* Query the list of CITY names from STATION that either do not start with vowels or do not end with vowels. Your result cannot contain duplicates.
Ans-
select distinct(city) from station where city REGEXP '^[^aeiou]' or city REGEXP '[^aeiou]$';

* Query the list of CITY names from STATION that do not start with vowels and do not end with vowels. Your result cannot contain duplicates.
Ans-
select distinct(city) from station where city REGEXP '^[^aeiou]' and city REGEXP '[^aeiou]$';

