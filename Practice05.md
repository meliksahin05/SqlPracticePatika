

---Practice 5--

--1-) List the 5 longest (length) film in the film table whose film title ends with the character 'n'.
 
     SELECT * FROM film
     WHERE title LIKE '%n'
     ORDER BY length DESC
     LIMIT 5;

--2-) Sort the second (6,7,8,9,10) 5 film (6,7,8,9,10) in the film table and the shortest (length) film name (title) ending with the character 'n'.

      SELECT * FROM film
      WHERE title LIKE '%n'
      ORDER BY length
      LIMIT 5
      OFFSET 5;


--3-) Sort the first 4 data in descending order according to the last_name column in the customer table, provided that store_id is 1.

    SELECT * FROM customer
    WHERE store_id = 1
    ORDER BY last_name DESC
    LIMIT 4;
    
