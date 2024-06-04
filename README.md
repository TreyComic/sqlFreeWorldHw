SELECT *
FROM rappers
INNER JOIN albums ON rappers.rapper_id = albums.rapper_id;

SELECT *
FROM rappers
LEFT OUTER JOIN albums ON rappers.rapper_id = albums.rapper_id;

SELECT *
FROM rappers
RIGHT OUTER JOIN albums ON rappers.rapper_id = albums.rapper_id;

SELECT *
FROM rappers
LEFT JOIN albums ON rappers.rapper_id = albums.rapper_id
UNION
SELECT *
FROM rappers
RIGHT JOIN albums ON rappers.rapper_id = albums.rapper_id

SELECT *
FROM rappers
CROSS JOIN albums;

SELECT *
FROM rappers
NATURAL JOIN albums;

SELECT *
FROM rappers
JOIN albums USING (rapper_id);

SELECT *
FROM rappers
JOIN albums ON rappers.rapper_id = albums.rapper_id;
