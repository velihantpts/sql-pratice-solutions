### Question:
Show first name and last name of patients that weight within the range of 100 to 120 (inclusive)
### Answer:
```SQL
SELECT first_name, last_name
FROM patients
WHERE weight BETWEEN 100 AND 120;
```
### Note:
Bu soruda BETWEEN yerine klasik koşul ifadeleri gibi >= 100 AND weight <= 120;  de kullanabilirdik. 
Performans açısından belirgin bir fark olmadığı için kullanım kişiye bağlıdır.
