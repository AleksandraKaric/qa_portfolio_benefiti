Welcome to creating SQL queries in MySQL using dump files hogwards.library and hogwarts.characters. In this task, I utilized commands such as SELECT, WHERE, BETWEEN, AS, LIKE, ORDER BY, UNION, and JOIN to extract and manipulate data from these files.

**1. This query retrieves the first name, last name, and patronus of characters from the table with a specified patronus assigned to them.** <br />

SELECT fname, lname, patronus <br />
FROM characters <br />
WHERE patronus IS NOT NULL;<br />

**2. This query will return all last names from the table that meet this specific criteria, allowing for the retrieval of character last names that end with the letter "e."** <br />

SELECT lname <br />
FROM characters <br />
WHERE lname LIKE '%e';<br />

**3. This query will return the first name, last name, and age of characters from the table, with the results arranged in descending order of age.** <br />

SELECT fname, lname, age <br />
FROM characters <br />
ORDER BY age DESC; <br />

**4. This query will return the character ID and known patronus in ascending order based on the patronus column.** <br />

SELECT char_id, patronus <br />
FROM characters <br />
WHERE patronus IS NOT NULL <br />
ORDER BY patronus ASC; <br />

**5. This query will return the first and last names of the characters from characters table and the name of the book that belongs to them from library table using inner join.** <br />

SELECT characters.fname, characters.lname, library.book_name <br />
FROM characters <br />
INNER JOIN library <br />
ON characters.char_id = library.char_id; <br />


**6. The SQL query provided selects the "fname" column from the table "characters" where the first name either starts with the letter 'N' followed by any characters and has a length of 5 characters, or starts with the letter 'L'.** <br />

SELECT fname FROM characters <br />
WHERE (fname LIKE 'N%' AND length(fname)=5)  <br />
OR fname LIKE 'L%'; <br />

**7. This query retrieves the count of students in each faculty, groups the results by faculty, and filters out faculties with only one student, providing information on faculties with multiple students.** <br />

SELECT faculty, COUNT(faculty) AS num_student <br />
FROM characters <br />
GROUP BY faculty <br />
HAVING num_student >1; <br />

