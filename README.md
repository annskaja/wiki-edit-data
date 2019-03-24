= wiki-edit-data

== toparticles.csv

Die 250 meistgelesenen Artikel in der deutschsprachigen Wikipedia zu bestimmten politischen Themen für das Jahr 2018. Beinhaltet Artikel aus den folgenden Kategorien nach Klickzahlen analysiert:

* Deutsche Bundesregierung
* Partei (Deutschland)
* Politische Ideologie
* Politiker (Deutschland)

Zusätzlich wurden die Artikel aus den Unterkategorien auf der ersten Ebene ausgewertet. Wenn die Kategorie "Politische Ideologie" also die Unterkategorie "Rechtsextremismus" besitzt, werden auch alle Artikel aus dieser Kategorie ausgewertet. Insgesamt befinden sich in den Kategorien 4.267 Artikel bzw. Unterkategorien, Duplikate sind entfernt.

== articledetails.csv
Übersicht für die 250 meistgelesenen Artikel aus toparticles.csv:
* Wie oft wurde der Artikel bearbeitet? (Total Edits)
* Wie viele Bearbeitungen davon waren geringfügig, etwa Korrektur von Rechtschreibfehlern? (Total Minors
* Wie viele Editoren haben den Artikel bearbeitet? (Total Editors)
* Wer hat den Artikel erstellt? (Creator)
* Wann wurde der Artikel erstellt? (Creation Date)
* Wie viele Edits kommen durchschnittlich auf einen Editoren? (Ratio (Edits/Editor))

== userranking.csv
Tabelle zur Aktivität aller Editoren, die in den untersuchten Artikeln aktiv waren: Anzahl der bearbeiteten Artikel sowie Anzahl der (geringfügigen) Änderungen

== Verzeichnis "articles"
In den einzelnen csv-Dateien, benannt nach dem Titel des Artikels, befindet sich eine Rangliste der Editoren für den jeweiligen Wikipedia-Eintrag mit Aufschlüsselung nach von ihnen vorgenommenen (geringfügigen) Änderungen und dem Zeitraum, in dem sie bei dem Artikel aktiv waren.

== topuserinfo.csv
Zusätzliche Informationen für die 200 aktivsten Editoren:
* Admin-Status (Admin)
* Geschlecht, falls im Nutzerprofil angegeben (Gender)
* Ist der Nutzer als Bot gekennzeichet? (Bot)
* Bearbeitungen in der gesamten deutschsprachigen Wikipedia (Global Edits)
* Verhältnis von geringfügigen Änderungen zu Gesamtänderungen im Bereich der 250 untersuchten Artikel (Rate of Minors (Politik))

== anonymousedits.csv
Auswertung, ob anonyme Autoren aus einem Netz von Bundeseinrichtungen kommen. Basiert auf der Liste von [bundesedit](https://github.com/codemonauts/bundesedit)
