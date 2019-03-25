# wiki-edit-data

## toparticles.csv

Die 250 meistgelesenen Artikel in der deutschsprachigen Wikipedia zu bestimmten politischen Themen für das Jahr 2018. Beinhaltet Artikel aus den folgenden Kategorien nach Klickzahlen analysiert:

* [Deutsche Bundesregierung](https://de.wikipedia.org/wiki/Kategorie:Deutsche_Bundesregierung)
* [Partei (Deutschland)](https://de.wikipedia.org/wiki/Kategorie:Partei_(Deutschland))
* [Politische Ideologie](https://de.wikipedia.org/wiki/Kategorie:Politische_Ideologie)
* [Politiker (Deutschland)](https://de.wikipedia.org/wiki/Kategorie:Politiker_(Deutschland))

Zusätzlich wurden die Artikel aus den Unterkategorien auf der ersten Ebene ausgewertet. Wenn die Kategorie "Politische Ideologie" also die Unterkategorie "Rechtsextremismus" besitzt, werden auch alle Artikel aus dieser Kategorie ausgewertet. Insgesamt befinden sich in den Kategorien 4.267 Artikel bzw. Unterkategorien, Duplikate sind entfernt.

## articledetails.csv

Übersicht für die 250 meistgelesenen Artikel aus toparticles.csv:
* Wie oft wurde der Artikel bearbeitet? (Total Edits)
* Wie viele Bearbeitungen davon waren geringfügig, etwa Korrektur von Rechtschreibfehlern? (Total Minors
* Wie viele Editoren haben den Artikel bearbeitet? (Total Editors)
* Wer hat den Artikel erstellt? (Creator)
* Wann wurde der Artikel erstellt? (Creation Date)
* Wie viele Edits kommen durchschnittlich auf einen Editoren? (Ratio (Edits/Editor))

## userranking.csv

Tabelle zur Aktivität aller Editoren, die in den untersuchten Artikeln aktiv waren: Anzahl der bearbeiteten Artikel sowie Anzahl der (geringfügigen) Änderungen

## Verzeichnis "articles"

In den einzelnen csv-Dateien, benannt nach dem Titel des Artikels, befindet sich eine Rangliste der Editoren für den jeweiligen Wikipedia-Eintrag mit Aufschlüsselung nach von ihnen vorgenommenen (geringfügigen) Änderungen und dem Zeitraum, in dem sie bei dem Artikel aktiv waren.

## topuserinfo.csv

Zusätzliche Informationen für die 200 aktivsten Editoren:
* Admin-Status (Admin)
* Geschlecht, falls im Nutzerprofil angegeben (Gender)
* Ist der Nutzer als Bot gekennzeichet? (Bot)
* Bearbeitungen in der gesamten deutschsprachigen Wikipedia (Global Edits)
* Verhältnis von geringfügigen Änderungen zu Gesamtänderungen im Bereich der 250 untersuchten Artikel (Rate of Minors (Politik))

## anonymousedits.csv

Auswertung, ob anonyme Autoren aus einem Netz von Bundeseinrichtungen kommen. Basiert auf der Liste von [bundesedit](https://github.com/codemonauts/bundesedit)

## Was fällt in den Daten auf?

* Insgesamt wurden die 250 untersuchten Artikel von 59594 Usern bzw. IP-Adressen bearbeitet. Der User mit den meisten Edits hat in 58 Artikel insgesamt 3.079 Mal bearbeitet. Der größte Teil, etwa 45.000, hat jeweils nur einen Edit gemacht.

* Einer der Nutzer hat in 247 von 250 Artikeln mitgewirkt. Betrachtet man die zugehörigen Änderungen, fällt auf, dass er regelmäßige Korrekturen von Rechtschreibung und Formatierung beiträgt. Am Inhalt der Artikel ändert er fast nie etwas. Das gilt auch für viele andere Artikel in der deutschsprachigen Wikipedia.

* Von den 200 aktivsten Usern sind 31 als Bot gekennzeichnet, 38 sind aktuelle Wikipedia-Admins. 61 der Nutzer haben angegeben, dass sie männlich sind, zwei weiblich, beim Rest findet sich keine Angabe direkt im Nutzerprofil. Dabei wurden Hinweiskästchen auf Nutzerseiten nicht ausgewertet.

* Der mit Abstand am häufigsten bearbeitete Artikel ist der der AfD (9.471), gefolgt von "Schwarze" (7.385), "Martin Luther" (5.605), "Die Linke" (5.123) und "Angela Merkel" (4.975).

* Trotzdem waren im AfD-Artikel relativ wenig unterschiedliche Editoren (1.235) aktiv. Das Verhältnis von Edits zu
Editoren beträgt gemittelt 7,7. Im Durchschnitt der 250 Artikel liegt es bei 2,23.

* Auch bei anderen Artikeln, die das Themenfeld Rechtspopulismus oder -extremismus berühren, fällt ein ähnlich hohes Verhältnis von Edits pro Autor auf. Dazu gehören "Ausschreitungen in Chemnitz 2018", "Identitäre Bewegung", "Politically Incorrect" und "Alexander
Gauland". Eine Erklärung dafür kann sein, dass diese Seiten [zeitweise "geschützt"](https://de.wikipedia.org/w/index.php?title=Spezial:Logbuch&type=protect&user=&page=Alternative_f%C3%BCr_Deutschland) waren oder sind. Dann können nur noch bestimmte Nutzergruppen - je nach Schutzlevel - die Artikel bearbeiten. Gerade bei sogenannten "Edit Wars" kann das zeitweise notwendig sein.

* Es fällt auf, dass bei vielen Artikeln die aktivsten Autoren mittlerweile nicht mehr aktiv sind und vor allem beteiligt waren, als die Artikel angelegt wurden.

* 31.438 Edits kamen von nicht-angemeldeten Nutzer, die nur als IP-Adresse identifiziert werden können. Das sind in der Regel einzelne Bearbeitungen, nur von 15 der IP-Adressen stammten zehn oder mehr Bearbeitungen - wobei möglich ist, dass eine Person mit mehreren IP-Adressen assoziiert ist.

* 61 IP-Adressen kamen, ausgewertet auf Basis der [bundesedit-Liste](https://github.com/codemonauts/bundesedit), aus Bundesnetzen. Der Großteil davon entfällt auf Bundeswehr und zugehörige Univeritäten, aus dem Bundestag und den IVBB-Regierungsnetzverbund.

* Politisch gefärbte Bearbeitungen führen regelmäßig zu Diskussionen und Gegenrede. Ein Beispiel dafür ist, ob im Artikel zur Alternative der Begriff ["rechtsextreme Tendenzen"](https://de.wikipedia.org/wiki/Diskussion:Alternative_f%C3%BCr_Deutschland#Tendenzen,_Tendenzen,_Tendenzen) stehen sollte.

* Mehrere Autoren, die sich auf ihren Nutzerseiten als Antifaschisten
bezeichnen, haben sich aus der Wikipedia zurückgezogen. Sie begründen das etwa damit, dass andere Nutzer wiederholt versucht haben, sie sperren zu lassen. Dazu finden sich auch öffentliche Stellungnahmen [wie diese](
https://de.wikipedia.org/wiki/Benutzerin_Diskussion:JosFritz#Sperre):

> In diesem Frühjahr scheinen sich die bereits vorhandenen deutlichen politischen Trennlinien innerhalb dieser WP-Community weiter zu vertiefen. Wir haben da beispielsweise eine Adminfraktion, die verzweifelt versucht, gerade jetzt verstärktetwas in den Griff zu bekommen, was eigentlich nicht in den Griff zu bekommen ist: "Einschränkung der Redefreiheit" nennen es die User, die vorwiegend kritisch unsere Machtstrukturen hinterfragen, Durchsetzung von "WP:KPA" und "WP:Q" koste es was es wolle, heißt es auf der A-Machtseite. Gesperrt werden daher jetzt, offenbar in einer konzertierten Aktion, alle verdächtigen, irgendwie als links empfundenen sogenannten Störenfriede.

* Es kommt in den Diskussionen zu Politik-Artikeln immer wieder zu Konflikten von Nutzern unterschiedlicher politischer Einstellung. Dazu gehören Vorwürfe, dass Nutzer bewusst [für die AfD](https://de.wikipedia.org/wiki/Benutzer_Diskussion:Lukati#AfD) in der Wikipedia zu agieren). Im Zusammenhang mit der AfD gab es auch Diskussionen über sogenannte Sockenpuppen. Nutzer sollen mehrere Accounts angelegt haben, die sich an Diskussionen beteiligen und so wirken, als würden sie die Meinung mehrerer Nutzer vertreten, [um Meinungshoheit zu erlangen](https://www.freitag.de/autoren/andreas-kemper/wikipedia-missbrauch-durch-konservativen-enttarnt).

* Gerade bei umstrittenen Artikel wird sehr schnell auf politische Färbungen egal welcher Richtung reagiert. Die Diskussionen dazu sind lang und stellenweise unsachlich. Mutmaßlich dürfte das einige Nutzer ausschließen, denen es sowohl an Zeit als auch Durchhaltekraft mangelt, um in diesem Klima aktiv zu werden.

## Datenquelle

[de.wikipedia.org](https://de.wikipedia.org/) (via [MediaWiki-API](https://www.mediawiki.org/wiki/API:Main_page))

## Lizenz

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode)
