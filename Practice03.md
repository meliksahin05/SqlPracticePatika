

--PRACTICE 03---

--1-) Sort the country names in the country column in the country table starting with the character 'A' and ending with the character 'a'.
--    List the country names in the country column in the country table that have at least 6 characters and end with the character 'n'.

SELECT * FROM country WHERE country LIKE 'A%a';


--2-) List in the title column in the film table that contain at least 4 uppercase    or lowercase 'T' characters. Case sensetive is unnecessary...


SELECT title FROM film WHERE title ILIKE '%t%t%t%t%';


--3-) from the data in all columns in the film table, sort the data whose title       starts with the character 'C' and
--    whose length is greater than 90 and whose rental_rate is 2.99.

SELECT * FROM film 
WHERE title LIKE 'C%' AND length>90 AND rental_rate = 2.99;
     
