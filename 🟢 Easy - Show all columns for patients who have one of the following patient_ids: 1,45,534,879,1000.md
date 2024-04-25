### Question:
Show all columns for patients who have one of the following patient_ids:
1,45,534,879,1000
### Answer:
```SQL
SELECT * FROM patients
where patient_id in (1,45,534,879,1000)
```
### Note: 
IN aslında birden fazla koşulu or işlemi yapmak gibi düşünebililiriz.
