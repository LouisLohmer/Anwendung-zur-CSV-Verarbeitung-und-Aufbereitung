# Aufgabenergebnis

## Eingesetzte Technologien und Frameworks

Folgende Technologien und Frameworks habe ich in meinem Projekt eingesetzt:

- Java / (JavaFX)

Ich habe mich für Java entschieden, weil ich mit dieser Programmiersprache die meiste Erfahrung gesammelt habe und somit diese auch am besten, im Vergleich zu den anderen Technologien, behersche. Zudem werden mir innerhalb der IDE Eclipse, welche ich zum Programmieren der Aufgabe genutzt habe, jegliche Java-Methoden von jeglichen Java-Bibliotheken sowie verschieden Werkzeuge vom dortigen Marketplace zur Verfügung gestellt, somit ist meine Arbeitsweise in Java effizienter und einfacher.

## Eingesetzte 3rd Party Libraries

Ich habe folgende 3rd Party Libraries in meinem Projekt eingesetzt:

Name | Begründung
--- | ---
[Java.io](https://docs.oracle.com/javase/7/docs/api/java/io/package-summary.html) | Java.io dient, vor allem, dem Verarbeiten vom Eingabe- und Ausgabeströmen des Programms. Aufgrunddessen das zwei wichtige Hauptbestandteile des Projektes aus dem Import- und dem Export der CSV-Daten bestehen, war diese 3rd Party Library nötig, um beispielsweise mit dem BufferedReader jegliche Daten aus der Datei, Zeile für Zeile, auszulesen, damit der FileReader diese in die Tabelle schreiben kann. Das selbe gilt für den Export, während der BufferedWriter die Daten aus der Tabelle ausliest, speichert der FileWriter wiederrum diese Daten in einer Datei.
[Bootstrap](https://getbootstrap.com/) | Einfaches RWD Framework zur Gestaltung des Frontends

## Installation / Ausführen des Projektes

Beschreibe, wie wir uns das Projekt lokal anschauen können.

Zum Beispiel:

---

Folgende Komponenten müssen lokal installiert sein:

- [nodejs](https://nodejs.org/en/) v13.2.0
- [.NET Core](https://dotnet.microsoft.com/download) v3.1

Um das Projekt lokal auszuführen, folgendes in der Commandline / Bash eingeben:

```console
$ git clone <linktorepository> udg-probeaufgabe
$ cd udg-probeaufgabe
$ npm install
$ npm run start
```
---
