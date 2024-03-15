# Homework-7 Questions And Solutions

1. Group the movies in the movie table according to their rating values.
    ```
   SELECT rating FROM film GROUP BY rating;
    ```

2. When we group the movies in the movie table according to the replacement_cost column, list the replacement_cost value and the corresponding number of movies if the number of movies is more than 50.
    ```
    SELECT replacement_cost, COUNT(*) FROM film 
    GROUP BY replacement_cost
    HAVING COUNT(*) > 50;
    ```

3. What are the customer numbers corresponding to the store_id values in the customer table?

    ```
    SELECT store_id, COUNT(*) FROM customer
    GROUP BY store_id;
    ```

6. After grouping the city data in the city table according to the country_id column, share the country_id information and the number of cities that contain the highest number of cities.

    ```
    SELECT country_id, COUNT(*) FROM city
    GROUP BY country_id
    ORDER BY COUNT(*) DESC
    LIMIT 1;
    ```

