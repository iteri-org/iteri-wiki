Suchen
======

Suche entlang eines GPX-Tracks
------------------------------

Im Roadbook werden einem Track auch POIs zugeordnet.

Um diese POIs nicht alle manuell zu erstellen, bietet sich eine abstandsbezogene Suche entlang des Tracks an. 
Die meisten Tools können nur eine Suche , die die BBOX des aktuellen Fensters nutzt. Hat man nun einen sehr langen Track, 
z,B. von Dortmund nach Wien, der nicht nur viele Kilometer hat, sondern auch in südöstlicher Richtung verlaüft, hat die 
umschliessende BBOX des Tracks eine sehr große Fläche (hier halb Europa). Bisher bekannte Suchen antlang eines Tracks (Beispiele nennen!!!)
selectieren meist per BBOX und schneiden dann mit einem Buffer entlang des Track-Linestrings. Dies hat den Nachteil, erstmal sehr große 
Mengen an POIS herunterzuladen, die dann durch das Schneiden extrem veringert werden.

Besser wäre es, 
