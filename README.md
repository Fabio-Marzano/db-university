BLOCCO 1 (ESERCIZIO 12/9/2024)

/QUERY 1/
SELECT *
FROM 'students'
WHERE YEAR ('date_of_birth')  = 1990

/QUERY 2/
SELECT *
FROM 'courses'
WHERE 'cfu' > 10

/QUERY 3/
SELECT *
FROM 'students'
WHERE TIMESTAMPDIFF (YEAR, 'date_of_birth', CURDATE()) > 30

/QUERY 4/
SELECT *
FROM 'courses'
WHERE 'period' = "I semsetre"
AND 'year' = 1