# Algorithmen - 07.10.2024


## Inhaltsverzeichnis

1. [Was ist ein Algorithmus?](#was-ist-ein-algorithmus)
2. [Was ist eine Anweisung?](#was-ist-eine-anweisung)
   * [Einzelanweisung](#einzelanweisungen)
   * [Sequenz](#sequenz)
   * [Selektion](#selektion)
   * [Mehrfachselektion](#mehrfachselektion)
   * [Iteration](#iteration)
3. [Darstellungsmöglichkeiten](#darstellungsm-glichkeiten)
   * [UML-Aktivitätsdiagramm](#uml-aktivit-tsdiagramm)
   * [Struktogramm](#struktogramm)
   * [Programmcode](#programmcode)
4. [Unterladen](#unterlagen)


## Was ist ein Algorithmus?

Ein Algorithmus ist eine Arbeitsanweisung zur systematischen und schrittweise Lösung einer Klasse von Problemen.

Das heißt, bei einem Algorithmus handelt es sich um eine sehr detaillierte Anleitung, welche in kleine Arbeitsschritte
unterteilt ist. Diese Arbeitsschritte folgen einer klar definierten Reihenfolge. Ein Beispiel für einen solchen 
Algorithmus ist zum Beispiel eine Wegbeschreibung oder ein Kochrezept.


## Was ist eine Anweisung?

Eine Anweisung ist ein Teilschritt eines Algorithmus. Wenn wir uns also auf die oben gegebene Definition eines
Algorithmus beziehen handelt es sich bei einer Anweisung um einen Arbeitsschritt, der befolgt werden muss.

Es gibt verschiedene Arten von Arbeitsschritten beziehungsweise Anweisungen welche folgend kurz erläutert werden.

### Einzelanweisungen

Bei Einzelanweisungen handelt es sich um die kleinste mögliche Anweisung. In der Regel bestehen Einzelanweisungen aus
einem einzigen kurz und präzise formulierten Arbeitsschritt, der so ohne weiteres ausgeführt werden kann.

Ein Beispiel für eine Einzelanweisung ist: "Ersetze Wert X durch Wert Y".

### Sequenz

Bei einer Sequenz handelt es sich um eine Verkettung von Einzelanweisungen, welche nacheinander ausgeführt werden.
Diese Einzelanweisungen können durch ein Semicolon getrennt dargestellt werden.

Ein Beispiel für eine solche Sequenz ist: "Erfrage den Wert Y; Ersetze den Wert X durch den erfragten Wert Y".

### Selektion

Bei einer Selektion handelt es sich um Auswertungen, bei denen eine Aktion nur dann ausgeführt wird, wenn die
auszuwertende Bedingung wahr ist.

Ein Beispiel für eine solche Bedingung wäre: "Geben Sie 500 Gramm Mehl hinzu, wenn die Butter komplett geschmolzen ist".

### Mehrfachselektion

Bei einer Mehrfachselektion handelt es sich wie bei einer Selektion um eine Auswertung einer Bedingung. Allerdings ist
das Resultat der Auswertung in diesem Fall nicht wahr oder falsch, sondern ein spezifischer Wert aus einer
Ergebnismenge, der eine bestimmte Aktion als Folge hat.

Ein Beispiel für eine Mehrfachselektion wäre also: "Wenn es sich bei dem Handy um ein Samsunggerät handelt, dann nehmen
Sie Akkutyp A, wenn es sich um ein iPhone handelt, nehmen Sie Akkutyp B und wenn es sich um ein Huawei handelt, dann
nehmen Sie Akkutyp C".

### Iteration

Bei einer Iteration handelt es sich um eine sich wiederholende Anweisung, welche sich so lange wiederholt, wie eine
zugrunde liegende Bedingung wahr ist.

Ein Beispiel für eine Iteration wäre: "Solange noch Kuchenstücke übrig sind, muss ich noch Kuchen verkaufen".


## Darstellungsmöglichkeiten

Es gibt verschiedenste Möglichkeiten einen Algorithmus darzustellen, wobei wir hierbei auch anhand der Größe des
Algorithmus unterscheiden.

Kleine Algorithmen werden in der Regel durch einen einfachen Einzeiler dargestellt. Ein solcher kleiner Algorithmus
kann beispielsweise eine Formel aus der Mathematik sein.

Für unseren Anwendungsfall von mittelgroßen Algorithmen gibt es drei weit verbreitete Darstellungsmöglichkeiten, welche
anschließend erläutert werden.

Für große und sehr komplexe Algorithmen wird in der Regel UML als Darstellungsmöglichkeit verwendet, da UML eine
vielzahl an Komponenten zur Darstellung von komplexen Beziehungen bietet.

### UML-Aktivitätsdiagramm

Bei einem UML-Aktivitätsdiagramm handelt es sich um eine grafische Darstellungsmöglichkeit von Algorithmen, welche einem
Flussdiagramm oder Programmablaufplan ähnelt. Hierfür werden die Anweisungen über verschiedene Bausteine dargestellt
und mit Hilfe von Pfeilen in die richtige Reihenfolge gebracht.

Ein Nachteil von diesen Aktivitätsdiagrammen ist, dass sie bei zunehmender Größe sehr leicht unübersichtlich werden
und nicht alle Anweisungen gut dargestellt werden können.

Eine Erläuterung von Aktivitätsdiagrammen und deren einzelner Teilkomponenten befindet sich auf dem dazugehörigen
[Cheat-Sheet](UML_Aktivitätsdiagramm.md).

### Struktogramm

Ein Struktogramm ist eine weitere grafische Darstellungsmöglichkeit, die die Anweisungen in Kästchen untereinander
darstellt.

Eine Erläuterung von Struktogrammen und deren Bestandteilen befindet sich im dazugehörigen 
[Cheat-Sheet](Struktogramm.md).

## Programmcode

Im Gegensatz zu den beiden vorherigen Darstellungsmöglichkeiten handelt es sich bei Programmcode um keine grafische
Möglichkeit. Programmcode ist darauf ausgelegt, verallgemeinert zu sein und sein Hauptvorteil ist die Tatsache, dass
er von Maschinen und Menschen gelesen werden kann.


## Unterlagen

[Folien 16-40](https://berrendorf.inf.h-brs.de/lehre/ws2425/eidp/vorlesung/Woche_02.pdf)