# Homework-3 Questions And Solutions

1. List the country names in the country column of the country table, starting with the character 'A' and ending with the character 'a'.

   `SELECT country FROM country WHERE country LIKE 'A%a';`
   
2. List the country names in the country column of the country table, consisting of at least 6 characters and ending with the character 'n'.

    `SELECT country FROM country WHERE length(country) >= 6 AND country LIKE '%n';`
   
3. List the movie names in the title column of the movie table that contain at least 4 'T' characters, regardless of whether they are uppercase or lowercase.

   `SELECT title FROM film WHERE title ILIKE '%t%t%t%t%';`
   
4. Among the data in all columns in the movie table, list the data whose title starts with the character 'C', whose length is greater than 90 and whose rental_rate is 2.99.

   `SELECT title FROM film WHERE title LIKE 'C%' AND length > 90 AND rental_rate = 2.99;`
