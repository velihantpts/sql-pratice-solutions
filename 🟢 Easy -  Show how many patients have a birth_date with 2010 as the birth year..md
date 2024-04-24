### Question:
Show how many patients have a birth_date with 2010 as the birth year.
### Answer:
```SQL
SELECT COUNT(*) AS num_patients_with_birth_year_2010
FROM patients
WHERE YEAR(birth_date) = 2010;
```
### Note:
YEAR() SQL fonksiyonu, bir tarihin yılını döndürmek için kullanılır.
COUNT ise satır,kayıt sayısını döndürmektedir.
