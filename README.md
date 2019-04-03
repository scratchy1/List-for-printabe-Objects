# List-for-printabe-Objects
Einer Variablen elem werden nacheinander Referenzen auf Objekte unterschiedlicher Klassen zugewiesen, deren Gemeinsamkeit nur darin besteht, dass sie Subtypen von Printable sind. Durch den Mechanismus der dynamischen Bindung wird dann die Methode print genau der Klasse ausgeführt, zu der das jeweilige Objekt tatsächlich gehört, ohne dass dazu eine explizite Fallunterscheidung nötig ist.

Ich habe mich unter anderem mit Kapselung und der Strukturierung
von Klassen beschäftigt und gesehen, wie man eine sauber gekapselte
Listenklasse mit Iterator bauen kann. Ich habe anhand von einelementigen
Behältern gesehen, wie man durch Nutzung von Subtyping Behälter bauen
kann, die Objekte verschiedener Typen aufnehmen können. Außerdem habe
ich Interfacetypen kennengelernt, mit denen sich Objekte verschiedener
Klassen, die aber eine gemeinsame Fähigkeit besitzen, zu einem Typ zusammenfassen
lassen, der genau das Vorhandensein dieser Fähigkeit beschreibt.
Diese Kenntnisse will ich jetzt in einer etwas größeren Aufgabe zusammenbringen,
indem ich eine Klasse PrintableList erstelle, eine Liste für
druckbare Objekte.
