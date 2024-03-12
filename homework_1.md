# Homework-1 Questions And Solutions

1. Sort the data in the title and description columns in the movie table.

    `SELECT title, description FROM film;`

2. Sort the data in all columns in the movie table, with the movie length being greater than 60 AND less than 75.

    `SELECT * FROM film WHERE length > 60 AND length < 75;`

3. Sort the data in all columns in the movie table as rental_rate 0.99 AND replacement_cost 12.99 OR 28.99.

    `SELECT * FROM film WHERE rental_rate = 0.99 AND (replacement_cost = 12.99 OR replacement_cost = 28.99)`;

4. What is the value in the last_name column of the customer whose value is 'Mary' in the first_name column in the customer table?

    `SELECT last_name FROM customer WHERE first_name = 'Mary';`

5. Sort the data in the movie table whose length is NOT greater than 50 and whose rental_rate value is NOT 2.99 or 4.99.

   `SELECT * FROM film WHERE NOT length > 50 AND (rental_rate = 2.99 OR rental_rate = 4.99);`

   
   
