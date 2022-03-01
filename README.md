## Lyft Trip Data

### General information

This is Codecademy project to project joins syntax. In this project I used SQL statements to combine rows from three tables:

```trips```: trips information

```riders```: user data

```cars```: autonomous cars

Below is an example to a query used to create Trips Log and output combining data from there tables:
```
SELECT trips.date, 
   trips.pickup, 
   trips.dropoff, 
   trips.type, 
   trips.cost,
   riders.first, 
   riders.last,
   riders.username
FROM trips
LEFT JOIN riders 
  ON trips.rider_id = riders.id;
 ```
  
  
  

### Tools used
