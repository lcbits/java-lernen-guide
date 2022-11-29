## java-lernen-guide

## Was ist Java?
Java ist eine beliebte Programmiersprache, die 1995 entwickelt wurde.
Sie ist Eigentum von Oracle, und mehr als 3 Milliarden Geräte laufen mit Java.
Sie wird verwendet für:

    Mobile Anwendungen (insbesondere Android-Anwendungen)
    Desktop-Anwendungen
    Webanwendungen
    Webserver und Anwendungsserver
    Spiele
    Datenbankanbindung
    Und vieles, vieles mehr!
    
 
## Java Einführung
In Java beginnt jede Anwendung mit einem Klassennamen, und diese Klasse muss mit dem Dateinamen übereinstimmen.
Erstellen wir unsere erste Java-Datei mit dem Namen Main.java, die mit einem beliebigen Texteditor (z. B. Notepad++) erstellt werden kann.
Die Datei sollte eine "Hello World"-Nachricht enthalten, die mit folgendem Code geschrieben wird:

Main.java
```java
public class Main {
  public static void main(String[] args) {
    System.out.println("Hallo Welt");
  }
}
```
Das da Oben musst du noch nicht verstehen.
Es dient einfach nur dazu, dass du testen kannst, ob JAVA korrekt auf deinem Gerät installiert und einsatzbereit ist.


## Java-Syntax
Im vorigen Abschnitt haben wir eine Java-Datei mit dem Namen Main.java erstellt und den folgenden Code verwendet, um "Hello World" auf dem Bildschirm auszugeben:

Main.java
```java
public class Main {
  public static void main(String[] args) {
    System.out.println("Hallo Welt");
  }
}
```
Beispiel erklärt:
Jede Codezeile, die in Java ausgeführt wird, muss sich innerhalb einer Klasse befinden. In unserem Beispiel haben wir die Klasse Main genannt. Eine Klasse sollte immer mit einem großen Anfangsbuchstaben beginnen.
Hinweis: Java unterscheidet zwischen Groß- und Kleinschreibung: "MyClass" und "myclass" haben unterschiedliche Bedeutungen.

Der Name der Javadatei muss mit dem Klassennamen übereinstimmen. Wenn Du die Datei speicherst, verwende den Klassennamen und füge ".java" an das Ende des Dateinamens an. Um das obige Beispiel auf Ihrem Computer auszuführen, stelle sicher, dass Java ordnungsgemäß installiert ist: Erster Abschnitt.
Die Ausgabe sollte sein:
```java
Hallo Welt
```

###Die main-Methode
Die main()-Methode wird benötigt und Sie werden sie in jedem Java-Programm sehen:
```java
public static void main(String[] args)
```
Jeder Code innerhalb der main()-Methode wird ausgeführt. Kümmere Dich nicht um die Schlüsselwörter vor und nach main. Du wist sie beim nach und nach kennen lernen.
Erinnere Dich jetzt einfach daran, dass jedes Java-Programm einen Klassennamen hat, der mit dem Dateinamen übereinstimmen muss, und dass jedes Programm die main()-Methode enthalten muss.

# System.out.println()
Innerhalb der main()-Methode können wir die println()-Methode verwenden, um eine Textzeile auf dem Bildschirm auszugeben:
```java
public static void main(String[] args) {
  System.out.println("Hallo Welt");
}
```

## Text drucken
Du hast im vorigen Abschnitt gelernt, dass Sie die Methode println() verwenden können, um Werte auszugeben oder Text in Java zu drucken:
Beispiel
```java
System.out.println("Hallo Welt!");
```
Du kannst so viele println()-Methoden hinzufügen, wie Du willst. Beachten jedoch, dass für jede Methode eine neue Zeile hinzugefügt wird:

Beispiel:
```java
System.out.println("Hallo Welt!");
System.out.println("Ich lerne gerade Java.");
System.out.println("Es ist großartig!");
```

Wenn Du mit Text arbeitest, muss dieser in doppelte Anführungszeichen "" eingeschlossen werden.
Wenn Du die doppelten Anführungszeichen vergisst, tritt ein Fehler auf:

Beispiel
```java
System.out.println("Dieser Satz wird funktionieren!");
System.out.println(Dieser Satz wird einen Fehler erzeugen);
```

# Die Methode Print()
Es gibt auch eine print()-Methode, die ähnlich wie println() ist.
Der einzige Unterschied besteht darin, dass sie keine neue Zeile am Ende der Ausgabe einfügt:

Beispiel
```java
System.out.print("Hallo Welt! ");
System.out.print("Ich werde in der gleichen Zeile drucken.");
```

## Zahlen drucken
Du kannst auch die Methode println() verwenden, um Zahlen zu drucken.

Im Gegensatz zu Text werden Zahlen jedoch nicht in doppelte Anführungszeichen gesetzt:
Beispiel
```java
System.out.println(3);
System.out.println(358);
System.out.println(50000);
```
Du kannst auch mathematische Berechnungen innerhalb der Methode println() durchführen:
Beispiel
```java
System.out.println(3 + 3);
```
Beispiel
```java
System.out.println(2 * 5);
```
