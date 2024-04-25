### Question:
Show all the columns from admissions where the patient was admitted and discharged on the same day.
### Answer:
```SQL
SELECT *
FROM admissions
WHERE DATE(admission_date) = DATE(discharge_date);
```
### Note:
Burada DATE() kullanımı sadece tarih bazlı yani saat bazlı bir sorgulma yapmak istemediğimiz için kullanılmıştır.
