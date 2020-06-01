# R-Shiny Server mit docker

von Tim Degold, begonnen am 2. Juni 2020

Für mein Diplomprojekt nächstes Jahr könnte es hilfreich sein, einen docker-container zu haben, welcher die zu entwerfende Applikation ausführt.

Also habe ich hier ein kleines docker-compose geschrieben, welches die Application `src/app.R` auf Port `3838` laufen lässt.

Zum Starten einfach `docker-compose up -d` und zum herunterfahren `docker-compose down` tippen. Der Container wird `shiny-server` genannt.



## Quellen

[1] *verwendetes docker-hub image* https://hub.docker.com/r/rocker/shiny (Accessed June 2nd 2020)

[2] *einfache shiny-applikation* https://shiny.rstudio.com/tutorial/written-tutorial/lesson1/ (Accessed June 2nd 2020)

[3] *docker-compose reference guide* https://docs.docker.com/compose/compose-file/ (Accessed June 2nd 2020)
