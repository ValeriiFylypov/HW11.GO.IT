# HW11.GO.IT

Task 1.
The method takes a list of names as input. It is necessary to return a string of the form 1. Ivan, 3. Peter... with only those names that are under an odd index (1, 3, etc.)

Task 2.
The method takes a list of strings as input (you can take the list from Task 1). Returns a list of these strings in uppercase, sorted in descending order (from Z to A).

Task 3
Given an array:

["1, 2, 0", "4, 5"]

Get all the numbers from the array and print them in a sorted form, separated by commas, for example:

"0, 1, 2, 4, 5"

Task 4
Using Stream.iterate, create an infinite stream of random numbers, but without using Math.random().

Implement your linear congruent generator. To do this, start with x[0] = seed, and then calculate each subsequent element using a formula such as x[n + 1] = 1 (a x[n] + c) % m for the correct values of a, c, and m.

You need to implement a method that takes parameters a, c, and m as input and returns a Stream<Long>.

Use the following data for the test:

a = 25214903917
c = 11
m = 2^48 (2 to the power of 48`)
Task 5.
Write a public static <T> Stream<T> zip(Stream<T> first, Stream<T> second) method that "mixes" elements from streams first and second, stopping when one of the streams runs out of elements.

  
  **********************************************************************************************************************************************
  **********************************************************************************************************************************************
  **********************************************************************************************************************************************
  
  
  Aufgabe 1.
Die Methode nimmt eine Liste von Namen als Eingabe. Es muss eine Zeichenkette der Form 1. Iwan, 3. Peter... mit nur den Namen, die unter einem ungeraden Index stehen (1, 3, etc.)

Aufgabe 2.
Die Methode nimmt eine Liste von Zeichenketten als Eingabe (man kann die Liste aus Aufgabe 1 nehmen). Gibt eine Liste dieser Zeichenketten in Großbuchstaben zurück, absteigend sortiert (von Z bis A).

Aufgabe 3
Gegeben ist ein Array:

["1, 2, 0", "4, 5"]

Holen Sie alle Zahlen aus dem Array und geben Sie sie sortiert und durch Komma getrennt aus, z.B.:

"0, 1, 2, 4, 5"

Aufgabe 4
Erzeugen Sie mit Stream.iterate einen unendlichen Strom von Zufallszahlen, aber ohne Math.random() zu verwenden.

Implementiere deinen linear kongruenten Generator. Beginne dazu mit x[0] = seed und berechne dann jedes nachfolgende Element mit einer Formel wie x[n + 1] = 1 (a x[n] + c) % m für die richtigen Werte von a, c und m.

Sie müssen eine Methode implementieren, die die Parameter a, c und m als Eingabe erhält und einen Stream<Long> zurückgibt.

Verwenden Sie die folgenden Daten für den Test:

a = 25214903917
c = 11
m = 2^48 (2 hoch 48`)
Aufgabe 5.
Schreibe eine öffentliche statische <T> Stream<T> zip(Stream<T> first, Stream<T> second) Methode, die Elemente aus den Streams first und second "mischt" und anhält, wenn einer der Streams keine Elemente mehr hat.
