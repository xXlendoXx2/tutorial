 
## Lag ny database-bruker og sett riktige rettigheter
### a. Logg inn i MariaDB >i. sudo mariadb –u root
### b. Lag ny bruker >i. CREATE USER 'username'@'localhost' IDENTIFIED BY 'password';
### c. Gi ny bruker rettigheter >i. GRANT ALL PRIVILEGES ON *.* TO 'username'@’localhost’IDENTIFIED BY 'password';
### d. Oppdater rettigheter. FLUSH PRIVILEGES;

## Lag ny database bruker som ikke kan endre på noe
### a. logg inn i mariaDB med Root slik som tidligere
### b. lag ny bruker CREATE USER "username_watch@localhost" IDENTIFIED BY "password";
### C. gi den riktige rettigheter. GRANT SELECT ON *.* TO 'username_watch'@'localhost';
### D. for å legge til endringene: FLUSH PRIVILEGES;

