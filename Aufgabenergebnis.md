# Aufgabenergebnis

## Eingesetzte Technologien und Tools

Folgende Technologien und Frameworks habe ich in meinem Projekt eingesetzt:

- Java / Window Builder

Ich habe mich für Java entschieden, weil ich mit dieser Programmiersprache die meiste Erfahrung gesammelt habe und somit diese auch am besten beherrsche. Zudem werden mir innerhalb der IDE Eclipse, welche ich zum Programmieren der Aufgabe genutzt habe, jegliche Java-Methoden von jeglichen Java-Bibliotheken sowie verschieden Werkzeuge vom dortigen Marketplace zur Verfügung gestellt, somit ist meine Arbeitsweise in Java effizienter und einfacher.

Über den Window Builder war es mir möglich, innerhalb einer Design-Seite jegliche Elemente einer graphischen Benutzeroberfläche auf dem automatisch erstellten JFrame hinzuzufügen und diese ebenfalls zu benennen sowie zu platzieren, wie es mir am besten passt. Der Code der jeweiligen Elemente wurde, nach dem Speichern der Änderungen, automatisch an diese angepasst. Somit konnte ich einfach und effizient eine strukturierte GUI erstellen. Aus diesen Gründen habe ich mich auch für den Window Builder entschieden.

## Eingesetzte 3rd Party Libraries

Ich habe keine 3rd Party Libraries in meinem Projekt genutzt, da bestimmte Libraries, wie zum Beispiel Java.io, Java.awt, Java.swing und JavaFX, von Oracle selbst mit java ausgeliefert werden und somit ein Gesamtpaket bieten, mit welchem sich die Probeaufgabe gut bearbeiten und lösen lässt. 

Innerhalb der Tabelle habe ich alle java-Bibliotheken, die für diese Probeaufgabe genutzt wurden, erläutert. Somit kann man nachvollziehen, was mit dem oben genannten Gesamtpaket gemeint ist.

### Eingesetzte java Libraries

Name | Begründung
--- | ---
[Java.io](https://docs.oracle.com/javase/7/docs/api/java/io/package-summary.html) | Java.io dient, vor allem, dem Verarbeiten vom Eingabe- und Ausgabeströmen des Programms. Aufgrunddessen dass zwei wichtige Hauptbestandteile des Projektes aus dem Import- und dem Export der CSV-Daten bestehen, war diese 3rd Party Library nötig, um beispielsweise mit dem BufferedReader jegliche Daten aus der Datei, Zeile für Zeile, auszulesen, damit der FileReader diese in die Tabelle schreiben kann. Dasselbe gilt für den Export, während der BufferedWriter die Daten aus der Tabelle ausliest, speichert der FileWriter wiederrum diese Daten in einer Datei.
[Java.awt](https://docs.oracle.com/javase/7/docs/api/java/awt/package-summary.html) | Java.awt stellt als Bibliothek die Kommunikationsschnittstelle zwischen dem Benutzer und dem Program dar. Mithilfe der Methoden ActionEvent und ActionListener, die in dieser Bibliothek enthalten sind, ist es möglich, das der Benutzer beispielsweise mit erstellten JButtons interagieren kann.
[Java.swing](https://docs.oracle.com/javase/tutorial/uiswing/index.html) | Java.swing ist die verbesserte Version von Java.awt, weshalb diese es ermöglichst, das die Elemente der Benutzeroberfläche eine bessere Qualität sowie eine höhere Funktionalität abgeben. Daher war diese Bibliothek nötig, um zum einen innerhalb der Tabelle, durch das Panel JScrollPanel, scrollen zu können, zum anderen ist es dem Benutzer, durch den JFileChooser dieser Bibliothek, möglich, innerhalb seines Windows Explorers mit Dateien zu interagieren. Dies fördert vor allem ein anprechendes Design, da man nicht mehr innerhalb des Codes einen Pfad eingeben muss, sondern stattdessen jegliche Datei einfach am gespeicherten Ort finden und auswählen kann.
[JavaFX](https://openjfx.io/) | Mit JavaFX können hauptsächlich graphische Benutzeroberflächen erstellt werden, ähnlich wie mit Java.awt und Java.swing. Allerdings bietet JavaFX eine modernere und multimediale Lösung, weshalb es keine Standardtlösung für graphische Benutzeroberflächen ist. Mithilfe von JavaFX wurde das, in die Benutzeroberfläche integrierte, Tortendiagram erstellt.

## Importieren und Ausführen des Projektes

Wie man ein Projekt in Eclipse importiert:

1. Eclipse öffnen
2. Wähle den gewünschten Workspace aus
3. Klicke auf **File** **>** **Open Projects from File System**
4. Füge den Dateipfad des Projektes unter **Import source** ein und klicke auf **Finish**
5. Nun wird das importierte Projekt links im Package Explorer unter dem Namen **ProjectCsvVerarbeitung** angezeigt

Wie man ein Projekt in Eclipse ausführt:

1. **Links** neben dem Namen des Projektes befindet sich ein **Pfeil**, mit welchen man dieses Projekt und dessen einzelne Elemente ausfährt
2. Klicke auf den Pfeil unter **ProjectCsvVerarbeitung** **>** **src** **>** **pkgProjectCsvVerarbeitung**
3. Nun werden alle Java-Dateien angezeigt, die sich im Projekt befinden
4. Öffne **AnwendungGUI.java** per Doppelklick und führe es mit dem ersten grünen, runden Knopf neben dem Käfersymbol aus
5. Nun öffnet sich eine **graphische Benutzeroberfläche** mit dem Titel **"CSV-Verarbeitung und Aufbereitungsanwendung"**

![Eclipse - Run Button](https://i.stack.imgur.com/z72yJ.png/)

---

Folgende Komponenten müssen in Eclipse installiert und importiert sein:

- [Window Builder Current](https://www.eclipse.org/windowbuilder/) v1.11.0

Wie man Window Builder Current in Eclipse installiert:

1. Eclipse öffnen
2. Klicke auf **Eclipse Marketplace**
3. Tippe in die Suchleiste **"Window Builder"** ein
4. Klicke bei **Window Builder Current** auf **Install** und folge den Schritten 

- [JavaFX](https://gluonhq.com/products/javafx/) v19.0.2.1

Wie man JavaFX in Eclipse importiert:

1. Eclipse öffnen
2. Öffne die Optionen eines Projektes per Rechtsklick auf das gewünschte Projekt 
3. Klicke aud **Properties**
4. Unter dem **Java Build Path** im Menü links, sieht man nun die Libraries
5. Klicke auf **Add Library**, wähle **User Library** aus und klicke auf **Next**
6. Klicke **User Libraries** und erstelle eine neue Bibliothek, indem man auf **New** klickt
7. Gebe der Bibliothek einen Namen
8. Klicke nun auf **Add External JARs**  und wähle im Windows Explorer unter **javafx-sdk-19.0.2.1** **>**  **lib** alle JAR-Dateien aus
9. Füge alle JAR-Dateien des **JavaFX SDKs** in die neue Bibliothek ein, indem man im Windows Explorer auf **Öffnen** Klickt
10. Klicke auf **Apply and Close**
11. Bestätige nun im Fenster **User Library** den import der Bibliothek, indem man in das **Kästchen** klickt
12. Klicke auf **Finish**
13. Klicke auf **Apply and Close**
14. Nun befindet sich JavaFX als Bibliothek in dem gewünschten Projekt. Damit JavaFX schlussendlich vollständig funktioniert, muss der Dateipfad von JavaFX noch in den Run Configurations gespeichert werden
16. Füge **"--module-path "YOUR-PATH-HERE" --add-modules javafx.controls,javafx.fxml"** in **VM arguments** unter **Run** **>**  **Run Configurations** **>** **Arguments** ein
17. Klicke auf **Apply** und dann auf **Close**


---
