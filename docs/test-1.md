# Admin

Falls Sie für den Admin-Bereich berechtigt sind, können Sie rechts in der Navigationsleiste bei den Geräteparks "Admin" auswählen. Andernfalls ist diese Option ausgeblendet.

* [Geräteparks](#geräteparks)
* [Lieferanten](#lieferanten)
* [Gebäude und Räume](#gebäude-und-räume)
* [Audits](#audits)

#### Geräteparks

Die Startseite des Admin-Bereiches zeigt eine Liste der Geräteparks. Hier können neue Geräteparks erstellt \("Gerätepark erstellen"\) sowie bestehende konfiguriert werden \("Editieren"\) . Um das Inventar mit einer Tabellenkalkulation eingehend zu analysieren besteht die Möglichkeit, die Datenbank als CSV- oder Excel-Tabelle herunter zu laden. Die Liste alles Geräteparks in Leihs dient gleichzeitig als Liste der Auswahlmöglichkeiten für die "Verantwortliche Abteilung" eines Gegenstandes. 

Geräteparks verfügen über folgende Parameter:

* _Name_, z.B. Ausleihe Toni-Areal
* _Kurzname_ \(bzw. Abkürzung\), z.B. AUS
  * Gegenstände eines Geräteparks führen das entsprechende Kürzel in ihrer Inventarnummer, z.B. AUS12345.
* _Aktiv_ \(Ja/Nein\): Unnütze Geräteparks können deaktiviert werden, wenn keine Bestellungen und Verträge mehr offen sowie sämtliche Gegenstände ausgemustert sind. 
* _E-Mail_: Absender der E-Mail Benachrichtigungen, z.B. Mahnungen oder Reservationsbestätigungen.
* _Beschreibung_: Informationen für Kunden über den Gerätepark, z.B. Ausleih-Bedingungen. 
* _Inventory Managers_: Liste der Personen mit Berechtigung als Inventar-Verwalter. 

#### Lieferanten

Der Reiter "Lieferanten" zeigt eine Liste der für alle Geräteparks erfassten Lieferanten. Benutzen Sie die Suchfunktion, um nur Lieferanten eines bestimmten Gerätepark anzuzeigen. Ferner können neue Lieferanten erfasst \("Lieferant erstellen"\) und bestehende konfiguriert \("Editieren"\) oder im Detail angezeigt werden \("Details"\). Sowohl die Editier- wie auch die Detail-Ansicht zeigen eine Liste der Gegenstände, die auf den betreffenden Lieferanten erfasst sind.

#### Gebäude und Räume

Die Örtlichkeit jedes Gegenstands in Leihs muss zwingend mithilfe eines Gebäudes und einem Raum erfasst werden. Räume und Gebäude werden in separaten Reitern verwaltet. Jeder Raum verfügt über einen Namen sowie eine Beschreibung und ist Teil eines Gebäudes. Letztere sind üblicherweise mit ihrer Adresse \(bspw. _Limmatstrasse, 45_\) benannt und können mit einem Code \(bspw. _LS_\) versehen werden. Dieser Code kann - muss aber nicht - teil der Raum-Namen \(bspw. _LS041_\) sein.

#### Audits

Im Reiter "Audits" können Logs sämtlicher Ereignisse auf Leihs eingesehen werden. Jedes erfasste Ereignis ist mit einem Zeitstempel und dem Namen der verantwortlichen Person versehen. Ein Ereignis kann mehrere Tätigkeiten enthalten. Jede Tätigkeit wiederum enthält eine _Aktion_ \(z.B. update, create\), _Entität_ \(z.B. Reservation, Zugangsrecht, Benachrichtigung\) sowie die geänderten _Variablen_.

