### Question:
Show first name and last name of patients who does not have allergies. (null)
### Answer:
```SQL
SELECT first_name,last_name FROM patients
where allergies IS NULL
```
### Not:
