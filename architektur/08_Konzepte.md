Konzepte
========


Fachliche Strukturen und Modelle
--------------------------------


Typische Muster und Strukturen
------------------------------


Persistenz
----------


Userinterface
-------------

Die folgenden Userinterfaces sind zu unterscheiden.
* Web
* Mobile
* Administration

##### Web
Das Web-Userinterface ist einfach gehalten. 

**Login-Maske**

Zu Beginn muss sich ein Anwender anmelden. Dies erfolgt über die Login-Maske. Hier muss der Anwender einen Anwendernamen (username) und ein Password (password) angeben.

Mit einem Click auf "Login" kann der Anwender den Login durchführen. Sind username/password korrekt, wird der Anwender zur Haupt-Maske weitergeleitet. Liegt ein Fehler vor, wird dies in der Login-Maske angezeigt. 

Alternativ zum Click auf "Login" kann sich der Anwender auch mit einem Click auf "Login via Twitter" anmelden. Hierzu muss der Anwender seinen Twitter-Login und sein Twitter-Password angeben. Zur Anmeldung wird dann die von Twitter zur Verfügung gestellt "Sign-in with Twitter" Funktionalität verwendet (s. "https://dev.twitter.com/web/sign-in").   

TBD: "Login via Facebook", "Login via Google+", "Login via GitHub" 

**Haupt-Maske** 

Nachdem sich der Anwender angemeldet hat, stehen ihm in der Haupt-Maske die folgenden Funktionen zur Verfügung:

* Ansicht der bereits eingegebenen Todos (in einer Liste)
* Hinzufügen eines neuen Todos
* Editieren eines bereits eingegebenen Todos
* "Abhaken" eines erledigten Todos.
* "Löschen" eines Todos.

Die nachfolgende Abbildung skizziert die Ansicht von Todos.

![moqup_web_todos_main](Abbildungen/Moqup_Web_ToDos_Main.png)
<br>
_Abbildung: Todo-Liste im Web_

Jedes Todo kann hierbei über die Checkbox als "erledigt" gekennzeichnet werden. Des Weiteren kann über das kleine "x" (in der oberen rechten Ecke) ein Todo aus der Liste gelöscht werden.

Neue Todos können über das "Plus" Icon in der oberen rechten Ecke der Webseite hinzugefügt werden. Anwender, die lieber intensiv die Tastatur verwenden, können auch über die Numpad-Taste "+" ein neues Todo einfügen. Wird ein neues Todo eingefügt, erscheint eine Textbox, in der der Anwender den Text des Todos eintragen kann. Mit "Return" wird das Todo in die Liste der bestehenden Todos eingefügt. Will der Anwender die Erstellung des Todos abbrechen, kann er dies mit "Esc" durchführen.

Eine Suchfunktion unterstützt den Anwender darin, alle Todos (entlang des eingegebenen Suchbegriffs) zu durchsuchen. Das Suchergebnis wird dann (so, wie bereits zuvor die Gesamtliste aller Todos) angezeigt. 

Ergonomie
---------


Ablaufsteuerung
---------------


Transaktionsbehandlung
----------------------


Sessionbehandlung
-----------------


Sicherheit
----------


Kommunikation und Integration mit anderen IT-Systemen
-----------------------------------------------------


Verteilung
----------


Plausibilisierung und Validierung
---------------------------------


Management des Systems & Administrierbarkeit
--------------------------------------------


Logging, Protokollierung, Tracing
---------------------------------


Geschäftsregeln
---------------


Konfigurierbarkeit
------------------


Parallelisierung und Threading
------------------------------


Internationalisierung
---------------------


Migration
---------


Testbarkeit
-----------


Skalierung, Clustering
----------------------


Hochverfügbarkeit
-----------------


Codegenerierung
---------------


Buildmanagement
---------------


Stapel-/Batchverarbeitung
-------------------------


Drucken
-------


Reporting
---------


Archivierung
------------
