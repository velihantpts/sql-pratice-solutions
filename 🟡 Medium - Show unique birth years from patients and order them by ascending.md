### Question:
Show unique birth years from patients and order them by ascending.
### Answer:
```SQL
SELECT DISTINCT YEAR(birth_date) AS birth_year
FROM patients
ORDER BY birth_year ASC;
```
### Note: 
YEAR methodu tarihin yıl özelliğini verir. Örneğin 27-04-2024 verisindeki 2024'ü döndürür. 
Biz de yıla göre sıralamak istediğimiz için bu methodu kullandık.
