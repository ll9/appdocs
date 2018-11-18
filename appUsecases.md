# Use Cases

/UC 10/ Kauf

Aktor: Kunde

* Angabe NN (und passwort)
* Auswahl Lizenzdauer (Jahr, Testversion)
* Kauf (Kreditkarte etc.)
* Download

/UC 20/ Softwareaktivierung

Aktor: Kunde, Server

* Kunde gibt NN + PW
* Server prüft Kundendaten und sendet Lizenz
* Lizenz wird gespeichert

Alternativen:

* Kunde wird informiert, dass er keine Lizenz mehr hat

/UC 30/ Lizenzerneuerung

Aktor: Kunde, Server

* Kunde gibt NN + PW ein
* Wird an Zahlungsseite weitergeleitet
* Server aktualisiert Lizenz bei Zahlung
* Erhält neue Lizenz per Mail / durch Knopfdruck

/UC 40/ Lizenz freigeben

Aktoren: Kunde, Server

* Kunde Klickt bei Lizenzverwaltung auf Lizenz freigeben
* Lizenz wir dgelöscht
* Server gibt Lizenz frei

/UC 50/ Neue Lizenz bei Hardwareverlust anfordern

Aktoren: Kunde, Server

* Fordert neue Lizenz mit neuer Hardware-ID
* Es wird mit guten willen neue Lizenz an Kunden gesendet

Alternative:
* alle alten IDs werden gebannt, neue freigegeben (Software muss bei Programm beim Server fragen, ob Lizenz noch gültig ist)
* Neue Lizenz wird gespeichert

/UC 51/ Troll neue Lizenz bei Hardwareverlust

Aktor: Troll

* Anwendung fragt bei Programmstart den Server, ob die Hardware-ID Lizenz noch verwenden darf
* Ist sie es nicht wird Lizenz gelöscht
* Alle Accounts müssen bei Hardwareverlustmeldung und Internetverbindung NN + PW neu eingeben



/UC 70/ Login

Aktor: Kunde

* Nutzer meldet sich mit NN + PW in der App an

/UC 80/ Datenerfassung

Aktor: Kunde

* wählt Koordinaten
* gibt Daten ein
* macht optional Bilder
* Sendet Daten

/UC 90/ Datenimport

Aktor: Kunde

* meldet sich in LDS an
* Forder Daten
    * Daten leer oder Felder stimmen überein => Import und ggf Spalten erstellen
    * Sonst Nutzer fragen, ob  Spalten erstellt werden sollen

/UC 100/ Punkte auf Karte betrachten

Aktor: Kunde

* kann bereits erfasste Punkte auf der Karte ansehen
* Durch Klick auf den Punkt öffnet sich der Bearbeitungs-Dialog

/UC 110/ Daten Bearbeiten

Aktor: Kunde

* Bearbeitet Daten des erfassten Lichtpunkt

/UC 120/ Bestand betrachten

* Auflistung erfasster Punkte
* Klick auf Punkt führt zu Bearbeitungs-Dialog

/UC 130/ Ändern NN + PW

/UC 140/ Bilder in LDS anzeigen

# Glossar

* __NN__ Nutzername (Email oder richtiger Nutzername)
* __PW__ Passwort