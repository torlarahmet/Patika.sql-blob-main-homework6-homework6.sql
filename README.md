# Patika.sql-blob-main-homework6-homework6.sql

-- 1. soru

SELECT AVG (rental_rate)  FROM film;

-- 2. soru

SELECT COUNT (title) FROM film
WHERE title LIKE 'C%';

-- 3. soru

SELECT MAX(length) FROM film
WHERE rental_rate = 0.99;

-- 4. soru


SELECT COUNT(DISTINCT replacement_cost) FROM film
WHERE length > 150;

