# lp-2 

# SmartBudget einfacher Budget-Manager

## 16.10.26 

- [x] ich habe mich für den M319 Test vorbereitet weil wir nächste woche Mittwoch den Test haben und ich noch nicht ganz mit Arays und Funktionen 

- [x] ich überlege was für ein Projekt ich starten möchte und und fange schoneinmal mit einer kleinen Planung an (Hausaufgabe)
## 23.10.26

Heute habe ich meine Planung aufgegeben weil ich erfuhr das mein Projekt so wie ich es machen wollte wahrscheinlich zu schwer gewesen wäre somit habe ich es angepasst so das ich es ohne Klassen machen kann nur mit den Sachen die wir bis jetzt gelernt haben.

- [x] Ich habe das Projekt SmartBudget aufgesetzt, Arrays für Texte und Beträge angelegt sowie die Zählervariable für die Einträge definiert.
- [x] Ich erweitere den Code so, dass in der for-Schleife (bei Option 2) die Gesamtsumme aller eingegebenen Beträge zusammengerechnet und am Ende der Liste ausgegeben wird.

## 30.10.26

Heute habe ich an meinem SmartBudget-Projekt weitergebaut und den Code ganz einfach und prozedural gehalten:

Sichere Eingabe: Mit decimal.TryParse fange ich jetzt ab, wenn aus Versehen Buchstaben statt einer Zahl eintippt werden, damit das Programm nicht abstürzt.

Liste leeren: Ich habe eine Funktion eingebaut, um alle Einträge auf einmal zurückzusetzen (anzahl = 0).

Filter: Man kann sich jetzt gezielt nur die Einträge anzeigen lassen, die über 10 CHF liegen.

- [x] Ich erweitere den Code so, dass Benutzereingaben mit try-catch oder decimal.TryParse abgefangen werden, falls man aus Versehen Buchstaben statt Zahlen eingibt.

- [x] Ich füge eine Funktion hinzu, mit der man alle bisherigen Einträge über ein Untermenü wieder komplett löschen oder zurücksetzen kann.

- [x] Ich baue eine Filterfunktion ein, damit man nur Ausgaben über einem bestimmten Betrag oder in einer bestimmten Kategorie anzeigen lassen kann.

- [x] Ich teste mein gesamtes Programm mit verschiedenen Testdaten, korrigiere eventuelle Fehler.
      
## 6.11.26

ch habe mein Budget-Programm erweitert. Man kann jetzt nach einem Text suchen (Option 5) und das Programm zeigt an, ob ein Eintrag eine Einnahme oder eine Ausgabe ist. Negative Beträge zähle ich als Ausgaben.
Ich habe eine Warnung eingebaut. Wenn man mehr als 100 CHF ausgegeben hat, kommt eine Meldung.
Man kann sich auch den höchsten und den niedrigsten Betrag anzeigen lassen (Option 6). Dafür habe ich eine Schleife gemacht, die alle Beträge vergleicht.
Das Menü habe ich angepasst, “Beenden” ist jetzt die 7.
Ich habe zwei kleine Fehler behoben: Die Beschreibung wurde schon gespeichert, auch wenn der Betrag falsch war. Und bei Option 6 ist das Programm bei einer leeren Liste abgestürzt, deshalb prüfe ich jetzt vorher, ob überhaupt etwas drin ist.

- [x] Ich baue eine einfache Suchfunktion ein, mit der man nach einem bestimmten Namen/Text im Array suchen kann.

- [x] Ich füge eine Unterscheidung zwischen Einnahmen und Ausgaben hinzu (z. B. negative Beträge als Ausgaben kennzeichnen).

- [x] Ich erstelle eine Budget-Warnung, die dem Benutzer eine Meldung anzeigt, wenn die Gesamtsumme eine bestimmte Grenze (z. B. 100 CHF) überschreitet.

- [x] Ich baue eine Funktion ein, die den höchsten und den niedrigsten Betrag in der Liste findet und ausgibt.

- [x] Ich teste den gesamten Code mit verschiedenen Testfällen, behebe kleine Fehler und aktualisiere meine Dokumentation.

## 13.11.26

- [ ] Ich baue eine Funktion ein, mit der man einen einzelnen Eintrag löschen kann. Man gibt die Nummer ein und die Einträge danach rutschen im Array nach vorne.
  
- [ ] Ich berechne den Durchschnitt von allen Beträgen und zeige ihn mit der Anzahl der Einträge an.
  
- [ ] Ich lasse den Benutzer die Budget-Grenze selbst eingeben und schreibe sie nicht mehr fest auf 100 CHF in den Code.
  
- [ ] Ich prüfe auch, ob die Eingabe eine gültige Zahl ist.
  
- [ ] Ich teste die neuen Sachen mit verschiedenen Testfällen (z. B. eine Nummer, die es nicht gibt, oder den Durchschnitt bei einer leeren Liste) und behebe kleine Fehler.
