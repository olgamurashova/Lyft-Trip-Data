## Lyft Trip Data

### General information

This is Codecademy project to practice joins syntax. In this project I used SQL statements to combine rows from three tables:

```trips```: trips information

```riders```: user data

```cars```: autonomous cars

Below is an example to a query used to create Trip Log and output combining data from there tables:
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
![Trip Log2](https://user-images.githubusercontent.com/89424060/156229746-4142a597-faaa-4305-a27d-ba60cadaef12.png)
  
  
  

### Tools used

+ SQLite
