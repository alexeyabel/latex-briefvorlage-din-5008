# Latex-Briefvorlage nach DIN 5008
Eine einfache Latex-Briefvorlage für Privatleute, die größtenteils der DIN 5008 entsprechen sollte. Erstellt auf Basis von KOMA-Script scrlttr2.

Ziel ist es eine Vorlage zu haben, die allgemeinverständlich und alltagstauglich ist. Daher ist jede Option und jeder Parameter erklärt und kommentiert. Um das Dokument möglichst kurz zu halten, sind nur Elemente enthalten, die für eine "normale" Privatperson relevant sein könnten.

Das Aussehen ist möglichst schlicht und minimalistisch, soweit dies die Gebrauchstauglichkeit nicht einschränkt.

Ein Teil der Elemente ist auskommentiert und kann bei Bedarf aktiviert werden. Z.B. "Kundenummer" oder "Ihr Zeichen", welche seltener benötigt werden. Außerdem kann das Aussehen leicht angepasst werden.

[Latex-Briefvorlage.tex](https://github.com/PanCakeConnaisseur/latex-briefvorlage-din-5008/blob/master/Latex-Briefvorlage.tex) ist alles was benötigt wird, es gibt bewusst keine Includes. Alle anderen Dateien sind Beispiele und Dokumentation.

## Briefform und Informationsblock

Die Vorlage lädt mit `\LoadLetterOption{DIN5008B}` die Briefform B. Für Form A genügt es, dort `DIN5008A` einzutragen. Benötigt wird KOMA-Script mit den Dateien `DIN5008A.lco` und `DIN5008B.lco` (ab Version 3.26).

Telefon, Fax, E-Mail, Website, Datum und gesetzte Bezugszeichen erscheinen im Informationsblock rechts neben dem Anschriftfeld. Leere Angaben entfallen; zum Ausblenden einer Angabe den zugehörigen `\setkomavar`-Eintrag auskommentieren (beim automatisch vorbelegten Datum stattdessen `\setkomavar{date}{}`).

## Screenshots

### Briefvorlage mit Standardoptionen
![Briefvorlage mit Standardoptionen](Screenshots/Briefvorlage%20mit%20Standardoptionen.png)

[im PDF-Format](Beispiele/Latex-Briefvorlage%20mit%20Standardoptionen.pdf)

### Briefvorlage mit allen Optionen
![Briefvorlage mit allen Optionen](Screenshots/Briefvorlage%20mit%20allen%20Optionen.png)

[im PDF-Format](Beispiele/Latex-Briefvorlage%20mit%20allen%20Optionen.pdf)
