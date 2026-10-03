## Idee
Ich entwickle einen kleinen Webshop, der nur als Rahmen dient: Auf der Startseite

werden einige Produkte mit Bild angezeigt. Der eigentliche Kern des Projekts ist

ein Support-Ticket-System. Besucher können im Footer ein Ticket abschicken, wenn

sie ein Problem haben. Ein Admin sieht alle Tickets auf einer eigenen Seite und

kann sie bearbeiten oder löschen.

  

## Unterseiten

- **Startseite (Shop):** Zeigt drei Produkte mit Bild, Name und Preis. Im Footer

(beim Impressum) befindet sich ein Link bzw. Formular für den Support.

- **Support-Formular:** Eingabe der E-Mail-Adresse und einer Beschreibung des

Problems, danach Absenden.

- **Admin-Seite:** Tabelle mit allen eingegangenen Tickets (E-Mail, Anliegen,

Datum, Status) mit Buttons zum Bearbeiten und Löschen.

- **Impressum:** Einfache Textseite.
  

## Gespeicherte Informationen

Die Anwendung speichert Support-Tickets dauerhaft auf dem Server in einer

Datenbank. Ein Ticket enthält: ID, E-Mail-Adresse, Nachricht, Status

(offen / erledigt) und Erstellungsdatum.

  

- **Eingeben/Erstellen:** Besucher füllen das Support-Formular im Footer der

Shop-Seite aus. Beim Absenden wird das Ticket auf dem Server gespeichert.

- **Bearbeiten/Löschen:** Auf der Admin-Seite kann der Admin den Status eines

Tickets ändern (z. B. auf "erledigt" setzen) und Tickets löschen.

- **Anzeigen:** Alle gespeicherten Tickets werden auf der Admin-Seite in einer

Tabelle angezeigt.

## Technik

Die Webseiten baue ich mit HTML und CSS, und mit JavaScript sorge ich dafür, dass das Formular und die Buttons funktionieren. Die Tickets sollen in einer Datenbank gespeichert werden, damit sie nicht verloren gehen, wenn man die Seite schließt, und damit der Admin sie jederzeit ansehen kann.