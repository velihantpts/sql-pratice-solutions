### Question:
Show the total number of admissions
### Answer:
```SQL
SELECT COUNT(*) AS total_admissions
FROM admissions;
```
### Note:
COUNT() NULL olmayan satır sayısını dönerken,
COUNT(*) Tüm satırları dönmektedir.

SELECT COUNT(*) AS active_admissions FROM admissions WHERE status = 'active'; gibi where koşulları 
ekleyerek istediğimiz satırların sayısını bulabiliriz.
