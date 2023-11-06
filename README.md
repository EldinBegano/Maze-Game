# Maze-Game (Schwierigkeit 3 von 5)
## Spiel
### Struktur
* Das Spiel soll in einem Array spielen gemacht aus 0 und 1.
* Man fängt oben links im Labyrinth an und muss nach unten kommen.
* Die Spieler soll als X angezeigt werden
* Die Ausgabe soll so aussehen

````
X . . # . . . . . . 
. # . # . # . # # . 
. # . . . # . . . . 
. # # # # # # # # . 
. . . . # # . . . . 
# # # # . . . # # . 
. . . # . # # # . . 
# # . # . # . # # # 
# . . . . . . . . . 
. # . # # # # # . # 
# # . # . # . # # # 
# . . . . . . . . . 
. # # # # # # # # . 
````

### Bewegung
Man soll sich in dem Labyrinth bewegen können mit wasd, das heißt das man einen Switch anlegen soll in dem des vier Cases gibt mit Groß und Kleinbuchstaben und falls die Person nicht mehr weiter kommt, kommt eine Fehlermeldung die sagt das man nicht mehr weiter kommt.

````
Wohin gehst du jetzt? (W/A/S/D): w
Du kannst da nicht hin
````

### Ende
Wenn der Spieler das Ende erreicht, kommt eine Gratulationsmeldung.
````
Du hast es geschafft!
Danke fürs Spielen
````
