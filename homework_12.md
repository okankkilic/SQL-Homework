# Homework-12 Questions And Solutions

1. In the movie table, the movie length is shown in the length column. How many movies are longer than the average movie length?

```
SELECT COUNT(film) FROM film 
WHERE length > 
(
SELECT AVG(length) FROM film
);
```

2. How many movies have the highest rental_rate in the movie table?

```
SELECT COUNT(film) FROM film 
WHERE rental_rate = 
(
SELECT MAX(rental_rate) FROM film
);
```

3. In the movie table, list the movies with the lowest rental_rate and lowest replacement_cost values.

```
SELECT film FROM film
WHERE 
rental_rate = (SELECT MIN(rental_rate)FROM film) 
AND 
replacement_cost = (SELECT MIN(replacement_cost) FROM film);
```

4. List the customers who made the most purchases in the payment table.

```
```
