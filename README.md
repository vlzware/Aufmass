# "Selbstausfüllendes" Aufmass-Formular für Firmen, die auf Baustelle arbeiten

## Problem:
An der Baustelle wird oftmals Aufmass erstellt, üblicherweise per Hand auf Papier-Formular. Dann wird das ins Büro geschickt, wo es ausgedrückt wird und per Hand zusammengerechnet. Dabei muss man immer im Aufmass vermerken und beim Berechnen aufpassen, um was für geometrische Figur es geht - Rechteck, Kreis, Trapez... Dann wird diese Sch** ... ehhm ... ich meine schlecht-aussehedes Formular an dem Kunde geschickt. Alles in allem sehr zeitaufwändiger und fehleranfälliger Prozess.

## Lösung:
An der Baustelle wird nur eine .csv Datei erstellt - ich habe es mit dem Handy gemacht. Man muss nur beachten, welche Werte in welchem Feld gehören. Dann mit dem Laptop wird den Inhalt von der .csv Datei ins Formular übertragen und fertig - das Formular erkennt alleine was für Formel benötigt werden, rechnet und füllt einiges aus! Das Ganze - vom Eintippen bis zur Ausgabe zum Kunde braucht wesentlich weniger Zeit und sieht am Ende viel besser aus. Das Formular überprüft sogar ob es Fehler gibt und zeigt an, wo etwas nicht richtig eingetragen wurde.

## Vorgehensweise:
- Zuerst den .csv File von der Baustelle öffnen, gleichzeitig auch das Formular (Aufmass_V3.1) öffnen;
- Dort logische Unterbrechungen finden z.B. "Süd Seite", maximal 30 Reihen (baubedingt von der A4 Grösse);
- nach und nach alle so entstandene Blöcke kopieren und im Aufmass in separates Blatt einsetzen;
- beim Einsetzen aufpassen auf "paste and keep destination formating" oder "paste as unformatted text" je nach Software;
- die nicht benötigte leere Restblätter zusammen markieren und entfernen;
- alle Blätter markieren und die identische Felder eingeben - Name vom Auftraggeber, Baustelle, gesamt Nummer von Blätter, Datum - so erscheinen diese auf jedes Blatt (nicht 5 Mal "Dressler Bau" schreiben, dann 5 Mal Datum o.ä.);
- und das war's - sollte nicht mehr als 3-4 Minuten dauern 

## Dateien:
- aufmass\_V3.1 : das Formular, das sich selber ausfüllt;
- aufmass\_figuren : Beispiel mit alle mögliche geometrische Figuren, die unterstützt sind;
- aufmass\_real\_world\_example : das sind zwei Dateien, die aus eine echte Baustelle stammen. Die .csv Datei aus der Baustelle und die selbe Information dann übertragen im Formular.

## Gesperrte Felder:
Für die eigene Sicherheit, dass man nicht aus Versehen eine Formel überschreibt, sind viele Felder schreibgeschützt. Das Passwort um die Sperren aufzuheben, z.B. um die Formel zu ändern (Achtung!), ist "vlzware".

## Lizenz
<a href="LICENSE">MIT</a>

## 
<a href="https://vlzware.com">Vladimir Zhelezarov</a> © 2018
