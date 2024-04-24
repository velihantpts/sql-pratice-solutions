### Question:
Show the first_name, last_name, and height of the patient with the greatest height.
### Answer:
```SQL
SELECT first_name, last_name, height
FROM patients
WHERE height = (SELECT MAX(height) FROM patients);
```
### Note: 
MAX bir sütundaki en büyük değeri bulmayı sağlar. 
date,datetime sütularında ise en son tarihli kaydı getirmektedir.

Burada koşulumuzun içine bir iç sorgu yazarak tablodaki en uzun boylu hastayı bulmuş olduk.
