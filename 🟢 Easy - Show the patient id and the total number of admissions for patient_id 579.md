### Question:
Show the patient id and the total number of admissions for patient_id 579.
### Answer:
```SQL
SELECT patient_id, COUNT(*) AS total_admissions
FROM admissions
WHERE patient_id = 579
GROUP BY patient_id;
```
### Note:
GROUP BY belirli bir sütuna göre gruplandırma yapmamızı sağlar. Yani aynı değere veya kritere sahip
kayıtları bi araya getirmeyi sağlar.
Genellikle GROUP BY sonrası COUNT(), SUM(), AVG() gibi işlemler yaparız.
