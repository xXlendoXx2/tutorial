
 ## Nå skal vi sette opp SSH på ubuntu på serveren/RaspberryPi
 ### 1. skriv sudo apt-get install openssh-server
 ### 2. sudo systemctl enable ssh (gjør sånn at SSH skrur seg på ved oppstart)
 ### 3. sudo systemctl start ssh (starter SSH her og nå)

## Finn IPen din – den trenger du når du skal bruke SSH
### a. ip a
### b. Hvis du har kablet nettverk, vil IP vises ved eth0: linje. Hvis du kun har trådløst, vil ipvises ved wlan0: linje. IP-adresse er vanligvis 10.2.3.x eller noe lignende (hvor x er etnummer mellom 2 og 254)