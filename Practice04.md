


--PRACTICE 04--


-- 1) Sort the different values in the replacement_cost column in the film table.

     SELECT DISTINCT replacement_cost FROM film;

-- 2) How many different values are in the replacement_cost column in the film table?
 
    SELECT COUNT(DISTINCT replacement_cost) FROM film;

-- 3) How many of the film titles in the film table start with the character T and also have a rating column equal to 'G'?
     
     SELECT COUNT(*) FROM film WHERE title LIKE 'T%' AND rating = 'G';
     
-- 4) How many of the country names in the country table have 5 characters?
     
     SELECT COUNT(*) FROM country WHERE length(country) = 5;

-- 5) How many of the city names in the city table end with the character 'R' or r?

     SELECT COUNT(city) FROM city WHERE city ILIKE '%R';
