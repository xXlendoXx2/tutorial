
 ## Nå skal vi sette opp SSH på ubuntu på serveren/RaspberryPi
 ### 1. skriv sudo apt-get install openssh-server
 ### 2. skriv sudo apt update 
 ### 3. skriv: eval "$(ssh-agent -s)"
 ### 4. så må vi lage en SSH Key skriv: ssh-keygen -t ed25519 -C "din@epost"
 ### 5. ssh-add ~/.ssh/id_ed25519 
 ## for å laste ned client på en annen maskin så må du gjøre dette
 ### 1. skriv sudo apt install openssh-client
 ### 2. sudo apt update
 ## Nå skal vi logge på serveren fra clienten
 ### 1. Skriv ssh brukernavnet til Server også ip: ssh modi@10.1.2.43
 ### 2. så vil den spørre om passordet til raspberry Pi du lagde tidligere

 