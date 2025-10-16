# Grundlagen bei Schwingungen

## Grundbegriffe

**Elongation:**
Momentane Auslenkung

**Amplitude:**
maximale Auslenkung

**Rückstellkraft:**
Kraft, die in Richtung der Ruhelage wirkt

**Harmonische Schwingung:**
Schwingung, deren s-t-Diagramm sinuskurvenförmig ist

**Freie Schwingung:**
Eine Schwinung ohne Erreger, also ohne Kraft außer der Rückstellkraft

**Erzwungene Schwingung:**
Schwingung mit Erreger

**Ungedämpfte Schwingung:**
Schwingung ohne Energieverluste

**Gedämpfte Schwingung:**
Schwingung mit Energieverlusten

## Kraftgesetz für harmonische Schwingungen beim Federpendel

Bei einem Federpendel ist die Rückstellkraft $F$ proportional zur Elongation $s$. Die Formel ist:

$$
F=-D*s
$$

$D$ ist hier die Federkonstante. $F$ ist entweder postitv oder negativ. Wegen dem Minuszeichen vor dem $D$ zeigt die Rückstellkraft $F$ immer in die entgegengesetzte Richtung von $s$ und somit immer in die Ruhelage zurück. Diese Rückstellkraft existiert nicht nur bei Federpendeln, sondern allen Schwingenden Systemen.

## Elongationsenergie

Bei einer ungedämpften harmonischen Schwingung ist die Summe aus Elongationsenergie $W_{elong}$ und kinetischer Energie $W_{kin}$ immer konstant. Es gilt:

$$
W = W_{elong}+W_{kin} =\frac 1 2 Ds^2+\frac 1 2 mv^2 = konstant
$$

Die Elongationsenergie ist an den Umkehrpunkten (beim Federpendel ganz oben und ganz unten) maximal, während die kinetische Energie in der Ruhelage ihren Höhepunkt erreicht.

## Zeigerdiagramm

# Pendelarten

## Fadenpendel

Das Fadenpendel hat viele Ählichkeiten zum Federpendel. Auch die zurückgelegte Strecke des Fadenpendels ist in einem Diagramm sinusfömig. Die Periodendauer wird berechnet durch:

$$
T=2\pi*\sqrt{\frac l g}
$$

Eine Schwingung ist dann harmonisch, wenn die Rückstellkraft $F$ proportional zur Bogenlänge $s$ ist.

## Federpendel

Bei einem Federpendel mit der Stärke $D$ an der eine Masse $m$ anhängt, kann man die Periodendauer $T$ mit dieser Formel berechnen:

$$
T=2\pi\cdot \sqrt{\frac m D}
$$

Dadurch kann man die Winkelgeschwindigkeit $\omega$ nach dieser Formel berechnen:

$$
\omega=\sqrt{\frac D m}
$$

## Flüssigkeitspendel

Bei einem Flüssisgkeitspendel mit der Länge $L$ bei einem Ortsfaktor von $g$, kann man die Periodendauer $T$ mit dieser Formel berechnen:

$$
T=2\pi\cdot\sqrt{\frac L {2\cdot g}}
$$

Folglich ist die Winkelgeschwindigkeit:

$$
\omega=\sqrt{\frac {2\cdot g} L}
$$

# Mechanische Wellen

## Modellbildung

Hier ist ein übliches Modell zu sehen, mit dem Wellen oft anschaulich gemacht werden.

Man kann es sich wie mit mehreren Röhren vorstellen. In jeder Röhre befindet sich ein Teilchen. Jedes Teilchen ist mit zwei Federn jeweils mit den benachbarten Teilchen verbunden. Wenn sich das erste Teilchen (ganz links) nach oben bewegt, zieht es mit der Feder nach einer kurzen Verzögerung das zweite Teilchen auch hoch. Dieses zweite Teilchen zieht dann am ditten, usw.

Natürlich funktioniert das in der Realität nicht mit Röhren. Dies ist eine Vereinfachung.

![Untitled](Modell%20Mechanische%20Schwingungen.png)

## Unterschied zwischen Schwingung und Welle

Den Unterschied kann man gut an der [oben gezeigten Darstellung](https://www.notion.so/Physik-Q3-K1-ae4af428767c474fbb57779bc010ed1a?pvs=21) sehen. 

Wenn wir von einer Schwinung sprechen, betrachten wir die hin- und her-Bewegung eines einzelnen Teilchens, oder Objektes. Dieses Teilchen Schwingt dann mit einer eigenen **Frequenz ($f$)**, einer eigenen **Periodendauer ($T$)** und einer eigenen **Amplitude ($\hat s$)**. Ein Beispiel ist das Federpendel, welchem eine einzelne Kugel/ein Gewicht an einer Feder auf und ab schwingt.

Eine Welle ist eine Anreihung mehrerer Schwingender Teilchen, die räumlich nebeneinander zeitlich versetzt von einer auf und ab Schwingenden Strömung erfasst werden. Dabei kommen zur **Periodendauer ($T$)**, **Frequenz ($f$)** und **Amplitude ($\hat{s}$)** auch noch die **Ausbreitungsgeschwindigkeit ($c$**) und **Wellenlänge ($\lambda$)** dazu.

## Wellengleichung

Die **Wellengleichung** beschreibt die Auslenkung eines bestimmten Teilchens an einem bestimmten Ort zu einer bestimmten Zeit. Um diese Anwenden zu können brauchen wir die maximale Auslenkung ($\hat y$ oder $\hat s$), die Periodendauer ($T$), die Position des Teilchens ($x$), die Wellenlänge ($\lambda$) und die gewünschte Zeit.

Die Formel sieht dann folgendermaßen aus. Diese sollte man auswenig können:

$$
y(x;t)=\hat y\cdot\sin(2\pi\cdot(\frac t T -\frac x \lambda))
$$

Dabei ist es sicherlich hilfreich zu wissen, dass die **Ausbreitungsgeschwindigkeit $c$** wie folgt berechnet werden kann:

$$
c=\lambda\cdot f=\lambda\cdot \frac 1 T \\
\implies c\cdot T=\lambda
$$

Die oben beschriebene Formel gilt für eine von links nach rechts (in positiver Richtung) laufende Welle. Wenn die Welle von rechts lach links (in negative Richtung) läuft, **dann muss das $x$ in der Formel negiert zu einem $-x$ werden.**

## Differenzialgleichung

## Interferenz von Wellen durch Superposition

### Einfache Interferenz

Das Superpositionsprinip beschreibt, was passiert, wenn sich zwei (oder mehr) Wellen durchringen, ohne sich gegenseitig zu beeinflussen. Man muss sich eigentlich nur merken, dass sich die Amplituden (mit richtigem Vorzeichen) an jedem beliebigen Punkt addieren.

![Untitled](Konstruktiv%20und%20Dekonstruktiv.png)

Dabei wird eine Interferenz, bei der die Welle "stärker" wird **konstruktiv** und eine Interferenz, bei der die Welle "schwächer" wird **destruktiv** genannt

### Die Interferenz im Detail

Im oben gezeigten Schaubild lässt sich leicht erkennen, wie die resultierende Welle aussieht, wenn die Wellen perfekt konstruktiv (A) oder perfekt destruktiv (B) interferieren. Jedoch ist es nicht unwahrscheinlich, dass sich die beiden interferierenden Wellen mit einer anderen Veschiebung durchdringen. 

![Untitled](Überlagerung%20von%20Wellen.png)

Wenn dies der Fall ist, ist es sinnvoll die einzelnen Pfeile an signifikanten Stellen im Graphen der Schwinung einzuzeichnen und aneinander zu hängen.

## Reflexion von Wellen

Bei der Reflexion von Wellen wird zwischen Wellen mit einem Wellenträger mit **losem Ende** und einem Wellenträger mit **festem Ende** unterschieden. Um sie zu zeichnen, wird jeweils immer über das Ende hinaus weitergezeichnet und dann wie folgt vorgegangen:

Bei einem losen Ende, wird einfach weitergezeichnet und dann an der Linie des Endes umgeklappt. Das sieht dann so aus:

![Untitled](Loses%20Ende.png)

Bei einem festen Ende wird weitergezeichnet und dann bevor umgeklppt wird noch gespiegelt. Das sieht dann so aus:

![Untitled](Festes%20Ende.png)

## Stehende Wellen

Stehende Wellen können durch die Überlagerung zweier Wellen mit gleicher Frequenz und gleicher Amplitude in entgegengesetzte Richtungen entstehen. Dadurch entsteht eine stehende Welle mit Knoten (an denen keine Schwingung ist) und Bäuchen (an denen maximale Schwinung ist).

Knoten haben dabei **immer einen Abstand** von $\frac \lambda 2$ zu einander. Ein **festes Ende** eines Wellenträgers gilt dabei auch als Knoten. Von einem **losen Ende** hat der erste Knoten einen Abstand von $\frac \lambda 4$.

## Eigenschwingung und Resonanz

Eine stehende Welle tritt auf, wenn sich zwei Wellen gleicher Frequenz überlagern. Eine Eigenschwingung entsteht, wenn die Länge des Wellenträgers $l$ ein vielfaches der halben Wellenlänge ist.

Somit ist die Länge des Seiles folgende:

$$
l=k\cdot \frac \lambda 2=k\cdot \frac c {2\cdot f_k}
$$

Wenn man diese Formel dann umstellt, kommt man auf die Formel für die Frequenz:

$$
f_k=k\cdot \frac c {2\cdot l}
$$

Der Wert $k$ gibt bei einem Seil **mit zwei festen Enden die Anzahl der Bäuche** an, und bei einem Seil **mit zwei losen Enden die Anzahl der Knoten**.