### Question:
Show first name, last name, and the full province name of each patient.

Example: 'Ontario' instead of 'ON'
### Answer:
```SQL
SELECT 
    p.first_name,
    p.last_name,
    pn.province_name AS province
FROM patients p
LEFT JOIN province_names pn ON p.province_id = pn.province_id;
```
### Note: 
LEFT JOIN sol tablodaki tüm kayıtları döndürürken sağ tabloda eşleşen kayıtları döndürür.
Bu noktada sol tabloda bulunan ve eşleşen kaydı olmayan satırlara NULL değerler atanır.
