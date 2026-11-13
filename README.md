# XML – Kursmaterialien und Übungen

Dieses Repository enthält die Beispiele und Übungen zum Unterrichtskurs **XML (Extensible Markup Language)**. Die Dateien begleiten den Einstieg in die XML-Syntax und führen schrittweise von einfachen XML-Dokumenten über Dokumenttypdefinitionen (DTD) bis hin zu Namensräumen und einem Ausblick auf XML-Schema und CSS.

## Kursinhalte

- Einführung in XML und grundlegende XML-Standards
- Aufbau eines XML-Dokuments, Elemente und Attribute
- Wohlgeformtheit und Validität
- Interne und externe Dokumenttypdefinitionen (DTD)
- Elementdeklarationen, Inhaltsmodelle und Häufigkeitsangaben
- Zeichen- und Text-Entities
- Attributdeklarationen in der DTD mit `#REQUIRED`, `#IMPLIED`, `#FIXED`, `CDATA`, `ID`, `IDREF` und `IDREFS`
- Externe und Parameter-Entitäten sowie `NOTATION`
- XML-Namensräume, Präfixe und qualifizierte Namen
- Ausblick auf XML-Schema (XSD) und die Darstellung von XML mit CSS

## Aufbau des Repositorys

Die Dateien im Hauptverzeichnis sind überwiegend nummerierte Unterrichtsbeispiele. Mehrere davon entwickeln die **Musiksammlung** Schritt für Schritt weiter.

| Dateien | Inhalt |
| --- | --- |
| `01-grundaufbau.xml` | Grundstruktur eines XML-Dokuments |
| `02-musiksammlung.xml` | XML-Beispiel mit Elementen und Attributen |
| `03-entities.xml` | Sonderzeichen, Entities und CDATA |
| `04-musiksammlung.xml` | Interne DTD und Elementdefinitionen |
| `05a-musiksammlung-extern.xml`, `05b-musiksammlung.dtd` | Externe DTD |
| `06a-*` bis `06d-*` | Attributdeklarationen und Attributtypen |
| `07a-token-idref.xml`, `07b-token-idrefs.xml` | Verweise mit `ID`, `IDREF` und `IDREFS` |
| `08-musiksammlung.xml`, `09-musiksammlung.xml`, `09a-musiksammlung.dtd` | Weiterführende DTD- und Entity-Beispiele |
| `10-param-entity.dtd` | Parameter-Entitäten |
| `11-externe-entity.xml` | Externe Entitäten und `NOTATION` |
| `12-namensraum.xml` bis `14b-ns-externe-dtd.dtd` | Namensräume und qualifizierte Namen |
| `dtdvsschema.*` | Vergleich und Beispiele zu DTD und XML-Schema |
| `seminar.xml`, `seminar.css` | XML-Dokument mit CSS-Darstellung |
| [`uebungen/`](uebungen/) | Ergänzende Übungsdateien zu verschiedenen Kursthemen |

Bei zusammengehörenden XML- und DTD-Dateien müssen die relativen Dateipfade erhalten bleiben.

## Verwendung der Kursdateien

1. Das Repository klonen oder über GitHub als ZIP-Datei herunterladen.
2. Die Dateien in einem geeigneten Code-Editor, beispielsweise **Visual Studio Code**, öffnen.
3. Die nummerierten Beispiele in der Reihenfolge der Unterrichtsthemen durcharbeiten.
4. Die Aufgaben und Beispiele im Ordner [`uebungen/`](uebungen/) zum selbstständigen Üben verwenden.
5. XML-Dateien auf Wohlgeformtheit und – soweit eine passende DTD oder ein Schema vorliegt – auf Validität prüfen.

> **Hinweis:** Einige Dateien enthalten absichtlich unvollständige oder fehlerhafte XML-Konstruktionen oder dienen der schrittweisen Entwicklung im Unterricht. Sie sind daher nicht alle als unmittelbar valide, eigenständig ausführbare Beispieldokumente gedacht.

## Voraussetzungen

Grundlegende Kenntnisse im Umgang mit Dateien und einem Code-Editor sind hilfreich. Für die Bearbeitung reichen ein Texteditor mit XML-Unterstützung und gegebenenfalls ein XML-Validator. Es ist keine spezielle Programmierumgebung erforderlich.

## Ziel des Kurses

Nach dem Kurs sollen die Teilnehmenden XML-Dokumente verstehen und selbst erstellen, deren Aufbau mit DTDs beschreiben, Entitäten und Namensräume einsetzen sowie den Unterschied zwischen DTD und XML-Schema grundlegend einordnen können.
