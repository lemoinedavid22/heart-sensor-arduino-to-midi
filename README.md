# heart-sensor-arduino-to-midi

Objectif : 
4 capteurs cardiaques sur une arduino mega envoient chacun une note midi sur un channel différent vers Live. 

Pour l'instant : 
ça marche avec un capteur 
headless-midiserial fait le lien entre la carte et Live. 
(j'ai pris l'exemple pour piezo de ce tuto : https://www.instructables.com/id/Arduino-Sensors-and-MIDI/)

Problème : 
tout con.. j'arrive pas à savoir comment multiplier le truc dans le code pour avoir 4 capteurs sur 4 entrées analog qui envoient vers 4 channels midi séparés. 

