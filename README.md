# R-Shiny Server mit docker

von Tim Degold, begonnen am 2. Juni 20202

Für mein Diplomprojekt nächstes Jahr könnte es hilfreich sein, einen docker-container zu haben, welcher die zu entwerfende Applikation ausführt.

Also habe ich hier ein kleines docker-compose geschrieben, welches die Application `src/app.R` auf Port `3838` laufen lässt.

Zum Starten einfach `docker-compose up -d` und zum herunterfahren `docker-compose down` tippen. Der Container wird `shiny-server` genannt.



## Quellen

[1] *verwendetes docker-hub image* 

[2] *einfache shiny-applikation*

[3] *docker-compose reference guide*