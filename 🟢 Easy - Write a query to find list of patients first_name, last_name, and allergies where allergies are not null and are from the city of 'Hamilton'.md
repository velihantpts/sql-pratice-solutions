### Question:
Write a query to find list of patients first_name, last_name, and allergies where allergies are not null and are from the city of 'Hamilton'
### Answer:
```SQL
SELECT first_name,last_name,allergies from patients
where allergies IS NOT NULL  and city = 'Hamilton'
```
### Note:
