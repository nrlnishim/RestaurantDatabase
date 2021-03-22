# RestaurantDatabase
Simple Restaurant DB using MySQL Unicode. Steps to insert data and functions.
1.	CREATE DATABASE eboristorante;

2.	CREATE TABLE;

i.	Customer

ii.	Meal

iii.Payment

iv.	Receipt

v.	Feedback

vi.	Administration

3.	INSERT INTO;
i.	Customer

ii.	Meal

iii.Payment

iv.	Receipt

v.	Feedback

vi.	Administration

4.	SELECT* FROM; (to display all record from the tables)

i.	Customer

ii.	Meal

iii.Payment

iv.	Receipt

v.	Feedback

vi.	Administration

5.	DISTINCT;

i.	Payment – method:

SELECT method
FROM payment;

SELECT DISTINCT method
FROM payment;

ii.	Receipt – date:

SELECT date
FROM receipt;

SELECT DISTINCT date
FROM receipt;

6.	COMPARISON;

i.	payment - amount

ii.	feedback - rating

7.	PATTERN MATCHING;

i.	Customer - email

ii.	Payment- method

SELECT payment_id, cust_id, method, amount

FROM payment

WHERE method LIKE '%cash%';
