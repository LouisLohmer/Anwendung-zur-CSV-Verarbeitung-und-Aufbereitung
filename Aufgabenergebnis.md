# Aufgabenergebnis

## Eingesetzte Technologien und Frameworks

Folgende Technologien und Frameworks habe ich in meinem Projekt eingesetzt:

- Java 

Ich habe mich für Java entschieden, weil ich mit dieser Programmiersprache die meiste Erfahrung gesammelt habe und somit diese auch am besten, im Vergleich zu den anderen Technologien, behersche. Zudem werden mir innerhalb der IDE Eclipse, welche ich zum Programmieren der Aufgabe genutzt habe, jegliche Java-Methoden von jeglichen Java-Bibliotheken sowie verschieden Werkzeuge vom dortigen Marketplace zur Verfügung gestellt, somit ist meine Arbeitsweise in Java effizienter und einfacher.

## Eingesetzte 3rd Party Libraries

Ich habe keine 3rd Party Libraries in meinem Projekt genutzt, da bestimmte Libraries, wie zum Beispiel Java.io, Java.awt, Java.swing und JavaFX, von Oracle selbst mit java ausgeliefert werden und somit ein Gesamtpaket bieten, mit welchem sich die Probeaufgabe gut bearbeiten und lösen lässt.

Name | Begründung
--- | ---
[Java.io](https://docs.oracle.com/javase/7/docs/api/java/io/package-summary.html) | Java.io dient, vor allem, dem Verarbeiten vom Eingabe- und Ausgabeströmen des Programms. Aufgrunddessen das zwei wichtige Hauptbestandteile des Projektes aus dem Import- und dem Export der CSV-Daten bestehen, war diese 3rd Party Library nötig, um beispielsweise mit dem BufferedReader jegliche Daten aus der Datei, Zeile für Zeile, auszulesen, damit der FileReader diese in die Tabelle schreiben kann. Das selbe gilt für den Export, während der BufferedWriter die Daten aus der Tabelle ausliest, speichert der FileWriter wiederrum diese Daten in einer Datei.
[Java.awt](https://docs.oracle.com/javase/7/docs/api/java/awt/package-summary.html) | Java.awt stellt als Bibliothek die Kommunikationsschnittstelle zwischen dem Benutzer und dem Program dar. Mithilfe der Methoden ActionEvent und ActionListener, die in dieser Bibliothek enthalten sind, ist es möglich, das der Benutzer beispielsweise mit erstellten JButtons interagieren kann.
[Java.swing]() | Java.swing ist die verbesserte Version von Java.awt, weshalb diese es ermöglichst, das die Elemente der Benutzeroberfläche eine bessere Qualität sowie eine höhere Funktionalität abgeben. Daher war diese 3rd Party Bibliothek nötig, um zum einen innerhalb der Tabelle, durch das Panel JScrollPanel, scrollen zu können, zum anderen ist es dem Benutzer, durch den JFileChooser dieser Bibliothek, möglich, innerhalb seines Windows Explorers zu interagieren. Dies fördert vor allem ein anprechendes Design, da man nicht mehr innerhalb des Codes einen Pfad eingeben muss, sondern stattdessen jegliche Datei einfach am gespeicherten Ort finden kann.
[JavaFX](https://openjfx.io/) | Mit JavaFX können hauptsächlich graphische Benutzeroberflächen erstellt werden, ähnlich wie mit Java.awt und Java.swing. Allerdings bietet JavaFX eine modernere und multimediale Lösung, weshalb es keine Standartlösung für graphische Benutzeroberflächen ist. Mithilfe von JavaFX wurde das, in die Benutzeroberfläche integrierte, Tortendiagram erstellt.

## Importieren und Ausführen des Projektes

Wie man ein Projekt in Eclipse importiert:

1. Eclipse öffnen
2. Klicke auf **File** **>** **Open Projects form File System**
3. Füge den Dateipfade des Projektes unter **Import source** ein und klicke auf **Finish**
4. Nun wird das importierte Projekt links im Package Explorer unter dem Namen **ProjectCsvVerarbeitung** angezeigt

Wie man ein Projekt in Eclipse ausführt:
1. **Links** neben dem Namen des Projektes befindet sich ein **Pfeil**, mit welchen man dieses Projekt und dessen einzelne Elemente ausfährt
2. Klicke auf den Pfeil unter **ProjectCsvVerarbeitung** **>** **src** **>** **pkgProjectCsvVerarbeitung**
3. Nun werden alle Java-Dateien angezeig, die sich im Projekt befinden
4. Öffne AnwendungGUI.java per Doppelklick und führe es mit dem grünen, runden Knopf neben dem Käfersymbol aus

![Eclipse - Run Button](https://i.stack.imgur.com/z72yJ.png/)

---

Folgende Komponenten müssen in Eclipse installiert und importiert sein:

- [Window Builder Current](https://www.eclipse.org/windowbuilder/) v1.11.0
- [JavaFX](https://gluonhq.com/products/javafx/) v19.0.2.1

---
