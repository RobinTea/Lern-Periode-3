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

hier ist das Vieo (ich konnte es bis 44:31min bearbeiten.)
https://www.youtube.com/watch?v=uzAXxFBbVoE

dieser Link führt sie zu einem Bild der Fehlermeldung
https://cdn.discordapp.com/attachments/1184022119688966165/1196714138223775806/image.png?ex=65b8a1e4&is=65a62ce4&hm=7e95531853f3674263db6b33db354fc34b7896c776e06b9c4176bcddf7f324bd&

- [ ] Kommentare hinzufügen
- [ ] Säubern

| estfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| -------------- | -------------------- | -------------- | -------------- | -------- |
| 1              | Schlange isst Apfel  | Apfel wird gegessen     |  Schlange wird länger  |          |
| 2              | Kommentare ist geschrieben | Programm wird geöffnet | Ich weiss was ich gemacht habe |          |
| 3              | Code ist übersichtlich   | Ich schaue den Code an | Ich verstehe den Code   |          |


## 23.1.2024

- [x] Farben wechseln
- [ ] Menu für Start
- [ ] Menu für Game Over
- [ ] weitere Modi: Wenn sich die Schlange in die Wand bewegt, kommt sie auf der anderen Seite wieder raus.
      
| Testfall-Nummer | Ausgangslage (Given) | Eingabe (When) | Ausgabe (Then) | Erfüllt? |
| --------------- | -------------------- | -------------- | -------------- | -------- |
| 5               |  Schlange ist grün   | Start |    gelbe Schlange            |          |
| 6               |  Spiel hat noch nicht gestartet |  Start button  | Spiel Start|          |
|              7  |  Schlange stirbt                    | wenn Schlange stirbt| User kommt ins game over menu            |          |
| 8 |Schlange bewegt sich zur Wand (Spieler hat anderes Modi gewählt)| Schlange bewegt sich zur Wand (Map Kante oder Ecke) | Schlange kommt auf der anderen Seite wieder raus    |          |

löakdsjf dieser Fehler hat dazubeigetragen dass der Code so unübersichtlich geworden ist, dass ich nicht mehr richtig verste was genau was im Code macht. Ich habe absolut keine ahnung mehr.
Ich werde es trotzdem weiterhin versuchen.

Mitlerweile sind neue Fehler aufgetreten weil ich Code importiert habe.

## 30.1.2024

Ich konnte die neuen Fehler beheben, jedoch ist der alte immer noch vorhanden und ich glaube ich bin gescheitert. Nach meinem Leherer versuchte ich den Code zu "clearen" aber in WinForms kann sich es als sehr schwierig erweisen. Alsohabe ich es einfach gelasen. 

Ich habe nach übungen im Internet gesucht und folgende Seite gefunden: https://dd.countit.at/dojos/csharp

Da habe ich neue Dinge wie collections, Klassenstruktur und Enumeration.
Code:

      namespace FishPond
      {
          internal class Pond
          {
              static void Main(string[] args)
              {
                  string name = "alöksdfj";
                  string race = "aölkdjf";
      
                  /*
                  string[] FishInPond =
                  {
      
                  };
      
                  string[] FishRaceInPond =
                  {
      
                  };
                  */
      
                  name = nameOffAnimal(name);
                  race = raceOffAnimal(race);
      
      
                  Console.WriteLine("\n Der " + race + " namens " + name + " wurde hinzugefügt");
      
              }
      
              public static string nameOffAnimal(string name)
              {
                  
                  Console.WriteLine("Name des Tieres eingeben");
                  name = Console.ReadLine();
      
                  return name;
              }
      
              public static string raceOffAnimal(string race)
              {
      
                  Console.WriteLine("Rasse des Tieres eingeben");
                  race = Console.ReadLine();
      
                  return race;
              }
          }
      }

## Reflexion

In dieser Lernperiode war ich zugegeben sehr unproduktiv ich habe ein sehr herausforndender Fehler bekommen den ich nicht so schnell fixen konnte. Die vier Wochen sind schneller vergangen als ich erwartet haben. Es ging fast schon zu schnell. Ich habe zwar richtigen Code aber ich bin trotzdem nicht fertig geworden. In der LP2 konnten wir frei auswählen was wir machen mussten.

Das nächste mal sollte ich nicht mehr WinForms benutzen. Es ist sehr aufwendig einen Fehler zu erkennen und zu beheben. In meinem Programm waren 2 Fehler, ein logischer und ein Syntaxfehler. Aus diesem Grund konnte ich nur wenige geplante Arbeitspakete beenden.

