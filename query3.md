--Show the title of films where the director is from the USA
SELECT title, director.country
FROM film
INNER JOIN director ON film.director_id=director.id WHERE director.country='USA';