# STACK-Aufgaben
Zwei beispielhafte Mathematikaufgaben für das Plugin STACK des Lernmanagementsystems Moodle, welche in Maxima programmiert wurden.
Die Aufgaben lauten:
* Aufgabe 1 - Exponentialfunktion zeichnen
* Aufgabe 2 - Textaufgabe zum Hochpunkt einer kubischen Funktion
Diese Aufgaben sind randomisiert und haben individuelle Rückmeldebäume zum Validieren der Eingaben. Dise machen nicht nur einen Soll-Ist-Vergleich, sondern geben Feedback darüber was falsch gemacht wurde. Darüber hinaus werden je nach Eingaben Punkte bzw. Teilpunkte vergeben. Je nach Aufgabentyp werden interaktive Diagramme in JavaScript zur Aufgabenvewältigung genutzt.

## Task 1 - Exponentialfunktion zeichnen
Dem User ist eine randomisierte Exponentialfunktion gegeben, welche in ein Koordinatensystem gezeichnet werden soll. Zum Zeichnen hat der User die Wahl, ob er die Parameter in separate Inputfelder einträgt oder die Slider im Koordinatensystem zum Anpassen der Parameter nutzt. Damit sich der Graph im Koordinatensystem dynamisch anpasst, wurde er mit JavaScript programmiert.

Hier eine Veranschaulichung, wie Task 1 aussieht:
![Task 1 - Aufgabenstellung, Inputs, Plot](/docs/Screenshots/Task 1 - Aufgabenstellung, Inputs, Plot.png "Aufgabe Exponentialfunktion")
Der zugehörige Rückmeldebaum:
![Task 1 - Rückmeldebaum](/docs/Screenshots/Task 1 - Rückmeldebaum.png "Exponentialfunktion Rückmeldebaum")
Validierung und Feedback:
![Task 1 - Rückmeldung](/docs/Screenshots/Task 1 - Validierung, Rückmeldung.png "Exponentialfunktion Rückmeldung")


## Task 2 - Textaufgabe zum Hochpunkt einer kubischen Funktion
Dem User ist eine randomisierte, kubische Funktion gegeben. Die Eingaben erfolgen in dem Format \([x=...,y=...]\)
![Task 2 - Validierung während der Eingabe](/docs/Screenshots/Task 2 - Validierung während Eingabe.png "kubische Funktion Aufgabenstellung, Input")
![Task 2 - Rückmeldung](/docs/Screenshots/Task 2 - Validierung nach Abgabe.png "kubische Funktion Rückmeldung")