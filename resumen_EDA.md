# Exploración de Datos: Análisis EDA
________________________________________

### 1. restaurant_link (id restaurante)
- **Nulos:** 0 (0.00%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  
### 2. restaurant_name (nombre del restaurante)
- **Nulos:** 0 (0.00%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  
### 3. original_location 
- **Nulos:** 0 (0.00%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  
### 4. country
- **Nulos:** 0 (0.00%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
- **Eliminar 
  
### 5. region
- **Nulos:** 2 (0.00%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - fillna ('Desconocido')

### 6. province
- **Nulos:** 29570 (18.78%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - fillna ('Desconocido')

### 7. city
- **Nulos:** 102884 (65.33%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - fillna ('columna address')

### 8. address
- **Nulos:** 0 (0.00%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
- ** Romper columna para completar datos de provincia y ciudad
  
### 9. latitude
- **Nulos:** 2363 (1.50%)
- **Unique:** 
- **Tipo de Dato:** `float64`OK
- **Tratamiento de Nulos:** 
  - fillna (unknown)

### 10. longitude
- **Nulos:** 2363 (1.50%)
- **Unique:** 
- **Tipo de Dato:** `float64` OK
- **Tratamiento de Nulos:** 
  - fillna (unknown)

### 11. claimed
- **Nulos:** 286 (0.18%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - fillna (UNKNOWN)

### 12. awards
- **Nulos:** 121609 (77.22%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - fillna ('None')?

### 13. popularity_detailed - QUEDARNOS CON LA SIGUIENTE QUE ES MÁS GENERICA
- **Nulos:** 14501 (9.21%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - ELIMINAR
### 14. popularity_generic
- **Nulos:** 14842 (9.42%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - fillna (UNKNOWN)

### 15. top_tags
- **Nulos:** 15633 (9.93%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - fillna ('NONE')?

### 16. price_level € - €€
- **Nulos:** 40671 (25.83%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - fillna ('Desconocido')?

— € Económico; Precios entre 0-25€
— €€ Moderado (en la media); Precios entre 25-50€
— €€€ Caro; Precios entre 50-80€
— €€€€ Lujoso; Precios de más de 80€

### 17. price_range
- **Nulos:** 109167 (69.32%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - Crearla desde 0 con los valores que consideremos

### 18. meals
- **Nulos:** 70765 (44.94%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - fillna ('UNKNOWN')?

### 19. cuisines
- **Nulos:** 22514 (14.30%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - catgoria dominante?

### 20. special_diets - ELIMINAR NOS QUEDAMOS CON LAS COLUMNAS VEGAN FRIENDLY ETC QUE TIENE 0 NULOS
- **Nulos:** 115423 (73.29%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - eLIMINAR

### 21. features
- **Nulos:** 106563 (67.67%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - fillna ('None')?

### 22. vegetarian_friendly
- **Nulos:** 0 (0.00%)
- **Unique:** n O S (CAMBIAMOS A YES O NO)
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  
### 23. vegan_options
- **Nulos:** 0 (0.00%)
- **Unique:** n O S (CAMBIAMOS A YES O NO?)
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  
### 24. gluten_free
- **Nulos:** 0 (0.00%)
- **Unique:** n O S (CAMBIAMOS A YES O NO?)
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  
### 25. original_open_hours
- **Nulos:** 81749 (51.91%)
- **Unique:** 
- **Tipo de Dato:** `object` - CAMBIAR??
- **Tratamiento de Nulos:** 
  - fillna ('UNKNOWN')?

### 26. open_days_per_week
- **Nulos:** 81749 (51.91%)
- **Unique:** 
- **Tipo de Dato:** `float64` -CAMBIAR A INT
- **Tratamiento de Nulos:** 
  - fillna (-1)

### 27. open_hours_per_week
- **Nulos:** 81749 (51.91%)
- **Unique:** 
- **Tipo de Dato:** `float64` -CAMBIAR A INT
- **Tratamiento de Nulos:** 
  - fillna (-1)

### 28. working_shifts_per_week
- **Nulos:** 81749 (51.91%)
- **Unique:** 
- **Tipo de Dato:** `float64` -CAMBIAR A INT
- **Tratamiento de Nulos:** 
  - fillna (-1)?

### 29. avg_rating
- **Nulos:** 14811 (9.41%)
- **Unique:** 1 AL 5
- **Tipo de Dato:** `float64` -CAMBIAR A INT
- **Tratamiento de Nulos:** 
  - fillna (mean/median)

### 30. total_reviews_count
- **Nulos:** 8868 (5.63%)
- **Unique:** 
- **Tipo de Dato:** `float64`-CAMBIAR A INT
- **Tratamiento de Nulos:** 
  - fillna (MEAN/median)

### 31. default_language
- **Nulos:** 14491 (9.20%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - Eliminar

### 32. reviews_count_in_default_language
- **Nulos:** 14491 (9.20%)
- **Unique:** 
- **Tipo de Dato:** `float64`-CAMBIAR A INT
- **Tratamiento de Nulos:** 
  - fillna (MEAN/median)?

### 33. excellent
- **Nulos:** 14491 (9.20%)
- **Unique:** 
- **Tipo de Dato:** `float64` -CAMBIAR A INT
- **Tratamiento de Nulos:** 
  - fillna (MEAN/median)

### 34. very_good
- **Nulos:** 14491 (9.20%)
- **Unique:** 
- **Tipo de Dato:** `float64`-CAMBIAR A INT
- **Tratamiento de Nulos:** 
  - fillna (MEAN/median)

### 35. average
- **Nulos:** 14491 (9.20%)
- **Unique:** 
- **Tipo de Dato:** `float64`-CAMBIAR A INT
- **Tratamiento de Nulos:** 
  - fillna (MEAN/median)

### 36. poor
- **Nulos:** 14491 (9.20%)
- **Unique:** 
- **Tipo de Dato:** `float64` -CAMBIAR A INT
- **Tratamiento de Nulos:** 
  -  fillna (MEAN/median)

### 37. terrible
- **Nulos:** 14491 (9.20%)
- **Unique:** 
- **Tipo de Dato:** `float64`-CAMBIAR A INT
- **Tratamiento de Nulos:** 
  -  fillna (MEAN/median)

### 38. food
- **Nulos:** 76643 (48.67%)
- **Unique:** 
- **Tipo de Dato:** `float64`-CAMBIAR A INT
- **Tratamiento de Nulos:** 
  - KNN?

### 39. service
- **Nulos:** 75960 (48.24%)
- **Unique:** 1 AL 5
- **Tipo de Dato:** `float64`-CAMBIAR A INT
- **Tratamiento de Nulos:** 
  - KNN?
### 40. value
- **Nulos:** 76205 (48.39%)
- **Unique:** 1 AL 5
- **Tipo de Dato:** `float64`-CAMBIAR A INT
- **Tratamiento de Nulos:** 
  - KNN?

### 41. atmosphere - ELIMINAR
- **Nulos:** 125983 (80.00%)
- **Unique:** 1 AL 5
- **Tipo de Dato:** `float64`
- **Tratamiento de Nulos:** 
  - fillna (mean)?

### 42. keywords - ELIMINAR
- **Nulos:** 148469 (94.28%)
- **Unique:** 
- **Tipo de Dato:** `object` OK
- **Tratamiento de Nulos:** 
  - ELIMINAR
