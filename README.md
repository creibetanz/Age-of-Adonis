# Age-of-Adonis

## Grafikengine
* einfachste 3d engine die wir kriegen können
    
## Maps
* random erzeugen
* terrain bilder einfarbig
* höhenunterschiede? -> zunächst nein
* "matrizen" von terrain, pathing, wald/ressourcen, usw
* grid - building, units frei
* minimap
    
## Networking
* einfachster trottelcode -> siehe clemenz
```
connection = establish(connectionMitPortUndWasIchMirNochEinfallenLasseAlaUDPundTCP)
connection.send(data)
data = connection.receive()
connection.send_blocking(data)
data = connection.receive_blocking()
```
* Architektur: 1 Server <-> mehrere Clients
* Verantwortlichkeiten:
** Client: Sound, UI, Grafikengine, Models, Pathing, Ressourcen
** Server: Maps,
    
## Server
* Ressourcen checken bzw transferieren
* fog of war verwaltung
    
    
## Units
* balancing klauen
* pathing
* nils klauen -> A*
* smooth genug + predictable + im combat einfach zu bedienen
* keine schwulen verbände
* Models
* basic placeholder modelle
* COMBAT
* bisschen schneller als normales aoe
* projektile?
* long range siege nich so mega gay
    
## Buildings
* Models
* basic placeholder modelle
* weniger häuser
* burgen nich so übermächtig
    
## Ressourcensystem
* kann man erst ma klauen und dann ändern
    
## UI
* klauen
* minimap
    
## Client / Menu
* minimal
* statistiken
    
## Sound
* keiner am anfang
    
## replays
* dann wanns in lol welche gibt
    
## Tools
* python 3.4.3
* github accounts machen
* panda
* pycharm
* nilssu-san
* blender -> egg files
* Coding Guidelines: https://www.python.org/dev/peps/pep-0008/
* default language: english (the adonis has spoken)
