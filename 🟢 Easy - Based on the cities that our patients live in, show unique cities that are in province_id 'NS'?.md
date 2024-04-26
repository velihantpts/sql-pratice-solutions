### Question:
Based on the cities that our patients live in, show unique cities that are in province_id 'NS'?
### Answer:
```SQL
SELECT DISTINCT(city) AS unique_cities
FROM patients
WHERE province_id = 'NS';
```
### Note:
DISTINCT yapısında birden fazla sütunu da kullanabiliriz. Bu sayede kombinasyonların tekilliğini kontrol edebiliriz.    
        SELECT DISTINCT CONCAT(first_name, ' ', last_name) AS full_name FROM users;
