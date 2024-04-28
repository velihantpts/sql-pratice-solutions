### Question:
Show patient_id and first_name from patients where their first_name start and ends with 's' and is at least 6 characters long.
### Answer:
```SQL
SELECT patient_id, first_name
FROM patients
WHERE first_name LIKE 's%s' AND LENGTH(first_name) >= 6;
```
### Note:
LIKE kelimesinden sonra % işareti o aralıkta herhangi bir şeyin gelebileceğini belirtir.
Örneğn %s%s ---> asas, bsbs , abcsabds
       s%s -->  s12213s,saaaas gibi olabileceği anlamına gelir.
LENGTH methodu genellikle text tabanlı veri türleri için kullanılır ve karakter sayısını verir.
