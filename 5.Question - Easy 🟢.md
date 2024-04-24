### Question:
Show first name and last name concatinated into one column to show their full name.
### Answer:
```SQL
SELECT concat(first_name,' ',last_name) AS full_name 
FROM patients
```
### Note: AS yani Alias sütun isimlendirmelerinde kullanılır.
