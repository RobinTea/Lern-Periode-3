# Lern-Periode 3

Robin Taing

(Winterferien) 9.1.2024 - 30.1.2024 (Sportferien)

## Grob-Planung

1. Wo stehen Sie mit Ihren Noten? In welchen Modulen waren Sie besonders stark; in welchen sind die ungenügend? Welche davon sind besonders wichtig?
2. Was hatten Sie sich am Ende von LP2 vorgenommen? Was war Ihr VBV? Wie könnten Sie diesen besonders gut üben?
3. Was wäre ein geeignetes Projekt würd diese LP3?

Da es eine kurze Lernperiode ist, werde ich an meinem unfertigen Snake weiterarbeiten. Das Spiel den ich in der 2. Lernperiode gemacht habe Ist noch nicht ganz fertig und es fehlen noch wichtige "features" wie zum Beispiel: Das Essen der Apfel ist noch nicht möglich, es wird nicht regristriert. Ich möchte dieses Programm gut kommentieren weil es immer mehr code wird. Ausserdem ist der Code dieses Programmes nicht übersichtlich. Ich möchte diese Dinge ändern und das Programm in dieser Lernperiode beenden. So kann ich am Ende Stolz behaupten das ich ein weiteres Projekt abgeschlossen habe.

## 9.1.2024

Heute konnte ich die Grob-Planung für diese kurze Lernperiode gemacht. Herr Colic hat uns beigebracht was eine selbstständige Exploration ist. Ich habe das rep jetzt aufgesetzt.

## 16.1 und 23.1.2024

- [ ] **Tutorial beenden** (2AP lang) Es ist ein unerwarteter Fehler aufgetreten:
      System.Windows.Markup.XamlParseException: "Zeilennummer "12" und Zeilenposition "9" von "Die Angabe eines Werts für "System.Windows.Baml2006.TypeConverterMarkupExtension" führte zu einer Ausnahme."."

Es gibt plötzlich ein Problem im einem Program das ich noch nie gesehen habe "XamlReader.cs" die Linie 476 war folgender Code: 
internal static void RewrapException(Exception e, IXamlLineInfo lineInfo, Uri baseUri)

{

 throw WrapException(e, lineInfo, baseUri);

} 

- [ ] Kommentare hinzufügen
- [ ] Säubern

| estfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| -------------- | -------------------- | -------------- | -------------- | -------- |
| 1              | Schlange isst Apfel  | Apfel wird gegessen     |  Schlange wird länger  |          |
| 2              | Kommentare ist geschrieben | Programm wird geöffnet | Ich weiss was ich gemacht habe |          |
| 3              | Code ist übersichtlich   | Ich schaue den Code an | Ich verstehe den Code   |          |


✍️ Heute am 16.1 habe ich... (50-100 Wörter)

☝️ Vergessen Sie nicht, bis zum 16.1 einen ersten Code auf github hochzuladen, und in der Spalte **Erfüllt?** einzutragen, ob Ihr Code die Test-Fälle erfüllt

## 23.1.2024

- [ ] Farben wechseln
- [ ] Menu für Start
- [ ] Menu für Game Over
- [ ] weitere Modi: Wenn sich die Schlange in die Wand bewegt, kommt sie auf der anderen Seite wieder raus.
      
| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --------------- | -------------------- | -------------- | -------------- | -------- |
| 5               |  Schlange ist grün   | Start |    gelbe Schlange            |          |
| 6               |  Spiel hat noch nicht gestartet |  Start button  | Spiel Start|          |
|              7  |  Schlange stirbt                    | wenn Schlange stirbt| User kommt ins game over menu            |          |
| 8 |Schlange bewegt sich zur Wand (Spieler hat anderes Modi gewählt)| Schlange bewegt sich zur Wand (Map Kante oder Ecke) | Schlange kommt auf der anderen Seite wieder raus    |          |

✍️ Heute am 23.1 habe ich... (50-100 Wörter)

☝️ Vergessen Sie nicht, bis zum 23.1 Ihren fixfertigen Code auf github hochzuladen, und in der Spalte **Erfüllt?** einzutragen, ob Ihr Code die Test-Fälle erfüllt

## 30.1.2024

✍️ Heute am 23.1 habe ich... (50-100 Wörter)

## Reflexion

Formen Sie Ihre Zusammenfassungen in Hinblick auf Ihren VBV zu einem zusammenhängenden Text von 100 bis 200 Wörtern (wieder mit Angabe in Klammern).

Verfassen Sie zusätzlich einen kurzen Abschnitt, in welchem Sie über die Länge der Projekte reflektieren: Fanden Sie die 9-wöchtige LP2 oder die 4-wöchige LP3 angenehmer? Was bedeutet das für Ihre Planung der zukünftigen LP?
