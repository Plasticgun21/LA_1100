# Projekt-Dokumentation



Jeanneret Winsky

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 23.08.22 | 0.0.1| User Stories gemacht.                                        |
| 23.08.22 | 0.0.2| Testfälle fast fertig geschrieben.                           |
| 30.08.22 | 0.0.3| Testfälle fertig.                                            |
| 30.08.22 | 0.0.4| Diagramm fertig gemacht.                                     |
| 30.08.22 | 0.0.5| Das Planen wurde begonnen.                                   |
| 30.08.22 | 0.0.6| Die Entscheidung wurde gemacht.                              |
| 30.08.22 | 0.1.0| Das Programmieren von der RNG fertig codiert.                |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Ich muss einen Random Number Generator programmieren.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |    muss         |  FA  | Als ein Informatiker möchte ich, das Programm korrekt programieren, damit es korrekt funtioniert. |
| 2    |    kann         |  RA  | Als Informatiker möchte ich, dass das Programm schön aussieht, damit es nicht hässilch aussieht. |                                   
| 3    |    kann         |  FA  | Als Spieler möchte ich, die Zahl herrausfinden, damit ich gewinnen kann. |                                    
| 4    |    muss         |  FA  | Als Infomatiker möchte ich, das die Zahl Random ist, damit es  nicht zu einfach ist. |                               
| 5    |    muss         |  QA  | Als Spieler möchte ich, dass möchte ich wissen ob die Zahl richtig oder falsch ist, damit ich gewinnen kann. |                                   

### 1.3 Testfälle

| TC-№ |  Ausgangslage| Eingabe | Erwartete Ausgabe | 
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Programm wird gestartet und Zahl wird generiert. | Das Programm wurde gestartet | Geben Sie Ihre gewünschte Zahl ein. |
| 2.1  | Programm ist am laufen, schaut ob es eine Zahl ist und Zahl ist gespeichert. | 50 | Zahl zu Gross.  | 
| 3.1  | Programm ist am laufen und Zahl wurde gefunden. | Enter | Sie haben die Zahl gefunden. |
| 4.1  | Programm ist am laufen, zeigt an wie viele Versüche man hatte und Zahl wurde gefunden. | Enter | Sie hatten 2 versüche. |
| 5.1  | Programm ist am laufen und Zahl wurde gefunden. | n | Wahl ob man nochmal spielen will. | 
| 6.1  | Programm generiert keine neue Zahl und schliesst. | Enter | Ende des Programms |


### 1.4 Diagramme

![Screenshot 2022-08-23 111458](https://user-images.githubusercontent.com/110892742/186120816-e21e458a-f17e-45a7-835a-4efdaebed1b6.png)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |23.8.22|  Luca J.W | User Stories schreiben. | 45 min.|
| 1.B  |23.8.22|  Luca J.W | Testfälle schreiben.    | 20 min.|
| 1.C  |23.8.22|  Luca J.W | Diagramm machen.     | 35 min.|
| 2.A  |30.8.22|  Luca J.W | Zufällig generierte Zahl zwischen 1 und 100 erstellen.   | 40 min.| 
| 2.B  |30.8.22|  Luca J.W | Programm soll sehen ob die Zahl grösser oder kleiner ist. | 50 min.|  
| 2.C  |30.8.22|  Luca J.W | Programm soll zeigen ob Zahl richtig ist. | 25 min.|
| 2.D  | 6.9.22|  Luca J.W | Programm fragt den Spieler ob er nochmal spielen will. | 30 min. |
| 2.E  | 6.9.22|  Luca J.W | Programm sieht ob es eine Zahl nicht und meldet eine Fehlermeldung. | 45 min. |
| 2.F  | 6.9.22|  Luca J.W | Programm zeigt an wie viele Versuche man hatte. | 60 min. |


Total: Die Userstories helfen mir, was ich in welche Rolle machen kann oder muss.
       Die Testfälle helfen mir, zu sehen wie ich die gewünschte Ausgabe bekomme.
       Das Diagramm zeigt wie der Algorithmus aussieht den ich brauch.
   



## 3 Entscheiden


## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
|  2.C |30.8.22| Luca J.W  |    40 min.    |      30 min.      |
|  2.B |30.8.22| Luca J.W  |    50 min.    |      60 min.      |
|  2.C |30.8.22| Luca J.W  |    25 min.    |      25 min.      |
|  2.D | 6.9.22| Luca J.W  |    30 min.    |      40 min.      |
|  2.E | 6.9.22| Luca J.W  |    50 min.    |      60 min.      | 
|  2.F | 6.9.22| Luca J.W  |    60 min.    |      90 min.      |


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |13.9.22|   true   |Luca J.W|
| 2.1  |13.9.22|   true (Aber das mit ob es eine Zahl ist funktioniert nicht ganz.) |Luca J.W|
| 3.1  |13.9.22|   true         |Luca J.W|
| 4.1  |13.9.22|   false       |Luca J.W|
| 5.1  |13.9.22|   true       |Luca J.W|
| 6.1  |13.9.22|   true       |Luca J.W|

Fazit: Das Problem ist wenn man etwas nicht eine Zahl imputiert schliesst das Programm. Dies sollte eigentlich sein, nur das es zu schnell geht.
Es sollte eigentlich ein Satz stehen aber der steht nicht. Es ist ein Minimal Problem weil es eigentlich was es machen soll und man sollte nicht so dumm sein um Zahlen von 1 bis 100 einzugeben.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    | Mann gibt eine sehr hohe Zahl ein.|10000000000000000000000000| Zahl zu hoch|fehlermeldung und Programm stürzt ab.|



## 6 Auswerten

