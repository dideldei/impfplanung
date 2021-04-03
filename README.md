# impfplanung
A specialized sheet for planning Covid-19 vaccination in a family doctor's setting in Germany

Ein kurzes Einführungsvideo findet man unter https://youtu.be/n9JT0Ed_D8Q.

## Übertragen von Patientendaten in eine neue Version
Wenn man eine neue Version herunterlädt und seine alten Daten darin übertragen möchte, sollte man dies spaltenweise machen für die Spalten, die man selbst eingegeben hat und nicht für die errechneten, also etwa Name und Geburtsdatum übertragen, aber NICHT das Alter.

## Schützen der Tabelle vor Änderungen
Es bietet sich an die die Tabelle zu SCHÜTZEN. Dies geht unter Extras -> Tabelle schützen. Dabei werden in den Voreinstellungen nur die Felder mit Formeln geschützt, jedoch _nur_ in der Tabelle "Patienten".

## Löschen von Patienten
Patienten, die ihre Zweitimpfung erhalten haben und in die Systeme übertragen wurden, können eigentlich gelöscht werden. Hier ist es wichtig, dass man darauf achtet, dass dies nur im geschützten Zustand geschieht (s.o.), damit keine Formeln aus den Zeilen gelöscht werden oder felderweise, die Felder in Nr, Name, Geb.datum etc., aber _nicht_ die Felder, die Calc ausrechnet.
