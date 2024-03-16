
# Homework-10 Questions And Solutions

1. Write the LEFT JOIN query in which we can see the city and country names in the city table and the country table together.

    ```
    SELECT COUNTRY.country, CITY.city FROM COUNTRY
    LEFT JOIN CITY ON CITY.country_id = COUNTRY.country_id;
    ```

2. Write the RIGHT JOIN query in which we can see the customer table, the payment_id in the payment table, and the first_name and last_name in the customer table together.

    ```
    SELECT PAYMENT.payment_id, CUSTOMER.first_name, CUSTOMER.last_name FROM customer
    RIGHT JOIN payment ON CUSTOMER.customer_id = PAYMENT.customer_id;
    ```

3. Write a FULL JOIN query in which we can see the customer table, the rental_id in the rental table, and the first_name and last_name in the customer table together.

    ```
    SELECT RENTAL.rental_id, CUSTOMER.first_name, CUSTOMER.last_name FROM customer
    FULL JOIN rental ON CUSTOMER.customer_id = RENTAL.customer_id;
    ```
