# Mengenlehre - 02.10.2024


## Inhaltsverzeichnis

1. [Definitionen](#definitionen)
   * [Was ist eine Menge?](#was-ist-eine-menge)
   * [Was ist ein Ding?](#was-ist-ein-ding)
   * [Bildliche Vorstellung einer Menge](#bildliche-vorstellung-einer-menge)
2. [Schreibweise von Mengen](#schreibweise-von-mengen)
   * [Elemente einer Menge](#elemente-einer-menge)
   * [Leere Menge](#leere-menge)
     * [Bildliche Vorstellung einer leeren Menge](#bildliche-vorstellung-einer-leeren-menge)
     * [Leere Menge in einer Menge](#leere-menge-in-einer-menge)
   * [Verschiedene Schreibweisen der gleichen Menge](#verschiedene-schreibweisen-der-gleichen-menge)
3. [Darstellung von Mengen](#darstellung-von-mengen)
   * [Extensional](#extensional)
   * [Intensional](#intensional)


## Definitionen

### Was ist eine Menge?

Der deutsche Mathematiker Georg Cantor definiert eine Menge wie folgt:

"Eine Menge ist eine Zusammenfassung **bestimmter**, **wohlunterschiedener** Dinge unserer Anschauung oder unseres
Denkens, welche Elemente der Menge genannt werden."

Also mit eigenen Worten gesagt ist eine Menge eine Zusammenfassung von einer Anzahl an Dingen, die gewissen
Eigenschaften unterliegen. Diese Eigenschaften sind:

**bestimmt**: Für jedes Ding kann selbst entschieden werden, ob es zur Menge gehört oder nicht.

**wohlunterschieden**: Alle Dinge einer Menge sind verschieden. Das heißt, selbst wenn ein Ding mehrfach erwähnt wird,
zählt es nur einmalig zu der Menge.

### Was ist ein Ding?

Dinge können in diesem Zusammenhang eine vielzahl von Sachen sein.

Es könnten zum Beispiel Stühle, Tische, Gummibärchen, usw. sein, was wir als **konkrete** Dinge bezeichnen.

Genauso gut können es aber auch Zahlen, Vektoren, Punkte, usw. sein, was wir als **abstrakte** Dinge bezeichnen.

Im Folgenden verwenden wir den Begriff **Elemente** als ersatz für das Wort Dinge. 

Es ist möglich, verschiedenste Dinge in einer Liste zu mischen, allerdings werden in der Praxis nur Mengen von einem
Typ verwendet.

### Bildliche Vorstellung einer Menge

Um sich eine Menge von Elementen bildlich vorzustellen, kann man an einen Beutel mit zum Beispiel Murmeln denken. Das
heißt, der Beutel wäre die Menge und die Elemente dieser Menge wären die Murmeln in diesem Beutel.


## Schreibweise von Mengen

### Elemente einer Menge

Wenn x ein Teil der Menge M ist, sagen man "x ist ein Element von der Menge M", "x ist in der Menge M" oder "x ist 
Element aus der Menge M". Schriftlich sieht das ganze wie folgt aus:

```tex
x \in M
```

Wenn x kein Teil der Menge M ist, schreibt man dies wie folgt:

```tex
x \not\in M
```


### Leere Menge

Bei einer leeren Menge handelt es sich um eine Menge ohne Elemente. Wichtig ist hierbei, dass eine leere Menge immer
noch mehr ist als rein gar nichts.

Des Weiteren lässt sich sagen, dass alle leeren Mengen gleich sind, da sie alle keine Elemente enthalten.

Leere Mengen schreibt man wie folgt:
 
```tex 
\{ \} \text{ oder } \emptyset 
```

Hierbei ist es egal, welche der beiden Schreibweisen man verwendet.

##### Bildliche Vorstellung einer leeren Menge

Um sich eine leere Menge bildlich vorzustellen, kann man an einen Beutel ohne Inhalt denken.

##### Leere Menge in einer Menge

Eine Menge, welche eine leere Menge als Element beinhaltet ist nicht leer und wir wie folgt geschrieben:

```tex 
\{ \{ \} \} \text{ oder } \{ \emptyset \} 
```

Bildlich können wir uns das ganze wie einen Beutel, der einen leeren Beutel beinhaltet vorstellen.

#### Verschiedene Schreibweisen der gleichen Menge

```tex 
\{ \emptyset, \emptyset \} \text{ ist die gleiche Menge wie } \{ \emptyset \}
```
```tex 
\{ 2, \frac{4}{2}, 3-1 \} \text{ ist die gleiche Menge wie } \{ 2 \}
```


## Darstellung von Mengen

Wenn uns die Elemente einer Menge bekannt sind, dann geben wir diese auch so an. Hierfür gibt es verschiedene Varianten:

### Extensional

Bei der extensionalen Schreibweise handelt es sich um eine eher informale Schreibweise, welche oft in Verbindung mit der
pünktchen Schreibweise genutzt wird.

Folgende Mengen sind Beispiele der extensionalen Schreibweise:

Bei der Menge A handelt es sich um eine Menge bestehend aus den Buchstaben a, b und c.

```tex 
A = \{ a, b, c \}
```

Bei der Menge B handelt es sich um eine Menge bestehend aus den Vielfachen von 10.

```tex 
B = \{ 10, 20, 30, 40, ... \}
```

Bei der Menge C handelt es sich um eine Menge bestehend aus den Zahlen 1 bis 9.

```tex 
C = \{ 1, 2, 3, ..., 9 \}
```

Bei der Menge D handelt es sich um eine Menge bestehend aus allen Brüchen.

```tex 
D = \{ \frac{p}{q} \}
```

### Intensional

Bei der intensionalen Schreibweise handelt es sich um eine formale Schreibweise, welche Mengen mit Charakteristika
beschreibt.

Eine Menge wird in der intensionalen Schreibweise wie folgt geschrieben:

```tex
M = \{ x \in U \ | \ x \text{ hat die Eigenschaft P } \}
```

Und gesprochen wird diese Menge beschrieben als M ist gleich der Menge aller X aus U, welche die Eigenschaft P haben.