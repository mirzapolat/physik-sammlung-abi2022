# Allgemeines

## Elektromagnetischer Schwingkreis

Ein elektromagnetischer Schwingkreis kann verwendet werden um Elektromagnetische Wellen zu erzeugen. Dafür brauchen wir einen Kondensator, der mit einer Spule in einen Kreis geschaltet ist.

![Untitled](Aufbau%20mit%20Kondensator%20und%20Spule.png)

Der geladene Kondensator entlädt sich langsam über die Spule. Weil die Spule dabei durch Selbstinduktion ein magnetisches Feld erzeugt, werden die Ladungen nicht gleichmäßig auf beide Platten verteilt, sondern auf die andere Platte gezogen. Der Kondensator ist nun wieder geladen und das ganze passiert nochmal. Ohne Energieverluste könnte dieser Elektromagnetische Schwingkreis unendlich lange laufen.

## Thompsonsche Schwingungsgleichung

Die Thompsonsche Schwingungsgleichung kann verwendet werden um die Periodendauer (und damit auch die Frequenz) eines Elektromagnetischen Schwingkreises zu ermitteln:

$$
T=2\pi\cdot\sqrt{L\cdot C}
$$

$$
f = \frac 1 T = \frac{1}{2\pi\cdot\sqrt{L\cdot C}}
$$

Dabei ist $C$ die Kapazität des Kondensators und $L$ die Induktivität der Spule. Die Freqzenz kann dann folglich mit der üblichen Formel berechnet werden.

## Hertzsche Dipol

Der Herzsche Dipol ist die einfachste Form eines [Elektromagnetischen Schwingkreises](https://www.notion.so/Physik-Q3-K1-ae4af428767c474fbb57779bc010ed1a?pvs=21). Er entsteht, indem man den Elektromagnetischen Schwingkreis "auseinanderbiegt".

![Untitled](Herzscher%20Dipol.png)

## Aufbau elektromagnetischer Wellen

Durch einen Elektromagnetischen Schwingkreis oder einem Hertzschen Dipol lassen sich Elektromagnetische Wellen erzeugen. Diese Elektromagnetischen Wellen breiten sich dann vom Sender aus in alle Richtungen aus. Die Welle besteht dabei aus einem E-Feld und einem B-Feld, die sich getrennt von einander ausbreiten. E-Feld und B-Feld stehen dabei senkrecht zu einander und sind polarisiert.

![Untitled](Orthogonale%20Wellen.png)

## Polarisation von elektromagnetischen Wellen

Wie in der [Grafik oben](https://www.notion.so/Physik-Q3-K1-ae4af428767c474fbb57779bc010ed1a?pvs=21) zu sehen ist, verlaufen E-Feld und B-Feld bei elektromagnetischen Wellen Senkrecht zu einander. E-Feld und B-Feld sind dabei polarisiert. Das heißt, dass man das E-Feld nur auf einer Ebene empfangen kann und das B-Feld nur auf einer anderen Ebene empfangen kann.

Als Konsequenz kann man die Energie der Welle nicht mehr mit einer Empfängerantenne nutzen, wenn man diese um 90° zur Senderantenne dreht. Das Licht an der Empfängerantenne würde dabei ausgehen.

# Licht als Elektromagnetische Welle

## Polarisation von Licht

### Polarisation durch Folien

Licht kann durch verschiedene Folien polarisisert werden. Licht, welches normalerweise Schwingungen in alle möglichen Richtungen senkrecht zur Ausbreitungsrichtung hat, wird dadruch auf nur eine Schwingungsrichtung reduziert:

In dieser Grafik strahlt das Licht aus der Papierebene raus auf den Betrachter (das bist in diesem Fall du) zu. Der schwarze Punkt in der Mitte ist der Lichtstrahl in seiner groben Form.

![Untitled](Polarisation%20durch%20Folien.png)

### Polarisation durch Reflexion

Wenn Licht an der Oberfläche eines anderen Mediums reflektiert wird, wird es oft auch gleichzeitig polarisiert. Für eine Vollständige Polarisiation muss es im sogenannten Brewsterwinkel ($d_B$) einfallen.

**$n_2$ und $n_1$** sind hierbei die **Brechungsindizes** der beiden Medien oben und unten in der Grafik

![Untitled](Polarisation%20durch%20Reflektion.png)

**Herleitung:**

$$
\beta=90°-d_B \\
\implies\frac{\sin(d_B)}{\sin(90°-d_B)} =\frac{\sin(d_B)}{\cos(d_B)}=\tan(d_B)=\frac{n_2}{n_1}
$$

Nach der Herleitung oben ist die Brewsterformel folglich:

$$
\tan(d_B)=\frac{n_2}{n_1}\implies d_B=\tan^{-1}(\frac{n_2}{n_1})
$$

## Huygensche Prinzip

> Jeder Punkt, der von einer Welle erreicht wird, bildet den Ausgangspunkt einer Kreisförmigen Elementarwelle. Die neue Wellenfront ergibt sich geometrisch als einhüllende. *(Zitat: Huygen)*
> 

Das lässt sich an folgendem Beispiel geometrisch darstellen. Hier trifft eine Wellenfront schräg auf eine Wand. Nach Huygen sind alle Punkte neue Ausgangspunkte von Kreisförmigen Elementarwellen:

![Untitled](Huygensche%20Prinzip.png)

**Beachte:** Die blauen Kreise gehen in der Grafik in alle Richtungen. Allerdings ist selbstverständlich, dass sich die Elementarwellen nur in der oberen Hälfte ausbreiten, da unterhalb der waagerechten Linie die Wand ist. Es ist also durchaus sinnvoller nur Halbkreise zu zeichnen.

## Brechung im Wellenmodell

Wenn Licht von einem Medium in ein anderes Medium wechselt, bricht es und verändert die Richtung, in die es strahlt. Was wir bisher noch nicht wussten ist, dass sich auch die Ausbreitungsgeschwindigkeit verändert. Das Verhältnis der beiden Ausbreitungsgeschwindigkeiten $c_1$ und $c_2$ lässt sich wie folgt herleiten:

Das Licht trifft von links oben auf die Oberfläche. Der Strahl mit dem Pfeil stellt den Lichtstrahl dar.

![Untitled](Brechnung%20im%20Wellenmodell.png)

**Herleitung:**

$$
\sin(\alpha)=\frac{c_1\cdot t} d \\
\sin(\beta)=\frac{c_2\cdot t} d \\
\implies \frac{\sin(\alpha)}{\sin(\beta)}=\frac{\frac{c_1\cdot t}{d}}{\frac{c_2\cdot t}{d}}=\frac{c_1\cdot t}{c_2\cdot t}=\frac{c_1}{c_2} =n
$$

Die neue Konstante ist die Brechzahl $n$ die das Verhältnis der Geschwindigkeiten $c_1$ und $c_2$ bezeichnet.

Licht wird in Materie langsamer. Da die Frequenz $f$ aber gleichbleibt, da sich die Farbe des Lichtes nicht verändert, ist davon auszugehen, dass die Wellenlänge $\lambda$ kleiner wird.

## Beugung im Wellenmodell

Eine Beugung tritt auf, wenn eine Welle (oder mehrere Wellen) zum Beispiel durch einen Spalt durchgehen. Beugung tritt dabei nur auf, wenn die Größe von Hindernissen (zum Beispiel die Breite des Spaltes) vergleichbar groß ist wie die Wellenlänge. 

$$
\tag {ist die Spaltbreite} \lambda \sim a
$$

Erklären kann man dieses Phänomen mit Hilfe von Elementarwellen:

![Untitled](Elementarwellen.png)

## Dispersion

# Interferenzphänomene

## Doppelspalt

### Interferenzmuster beim Doppelspalt

![Untitled](Interferenzmuster%20Doppelspalt.png)

Beim Doppelspalt sind alle Maxima gleich breit. Die Intensität (Höhe) der Maxima nimmt mit zunehmender Ordnung ab. Der Einzelspalt dient als Einhüllende.

### Herleitung am Schaubild

Wird Licht durch einen Doppelspalt geschickt, kann man auf einem dahinterliegendem Schirm Interferenzmuster erkennen.

Wenn es darum geht die Positionen und Winkel der Maxima und Minima auf dem Schirm zu bestimmen, kommt dieses Schaubild zur Hilfe:

![Untitled](Entstehung%20Doppelspalt.png)

Dabei wird angenommen, dass beide Strahlen fast parallel zu einander sind, da sie eine weite Strecke bis zum Schirm zurücklegen und ihr Winkel sich dabei nur marginal unterscheidet. Der Winkel $\alpha$ ist zu berechnen und bezeichnet hier den Winkel des Maximas/MInimas. 

### Maxima beim Doppelspalt

Die Variable $k$ bezeichnet hier die Nummer des Maximums. $k$ ist element der natürlichen Zahlen und beginnt bei den Maxima bei *null*. Somit ist das erste Maximum beim Doppelspalt direkt in der Mitte bei einem Winkelversatz $\alpha$ von *null*. 

$$
\tag{das k-te Maximum} \Delta s =k\cdot \lambda

$$

$$
\sin(\alpha)=\frac {\Delta s} g = \frac {k\cdot \lambda} g  \\
\tan(\alpha) =\frac {d_k} a 
$$

Bei besonders kleinen Winkeln unter $8°$kann man annehmen, dass $sin(\alpha)$ ähnlich zu $tan(\alpha)$ ist. Also gilt **nur für kleine Winkel**:

$$
\sin(\alpha)\approx \tan(\alpha)\\
\frac {k*\lambda} g \approx \frac {d_k} a\\
\implies d_k=\frac a g \cdot k \cdot\lambda
$$

Der Abstand zwischen den Maxima ist folglich, wenn man das $k$ aus der Formel oben rauslässt:

$$
d=d_{k+1}-d_k = \frac a g \cdot \lambda

$$

### Minima beim Doppelspalt

Wenn es um die Minima beim Doppelspalt geht, kommt folgende Formel zum Einsatz. Wichtig zu beachten ist, dass es kein Minima “nullter” Ordnung gibt. Deswegen gilt hier $k>0$

$$
\tag{das k-te Minimum} \Delta s =(2k+1)\cdot \frac \lambda 2

$$

$$
\sin(\alpha)=\frac {\Delta s} g = \frac {(2k+1)\cdot \frac \lambda 2} g  \\
\tan(\alpha) =\frac {d_k} a 
$$

## Einzelspalt

### Interferenzmuster beim Einzelspalt

![Untitled](Interferenzmuster%20Einfachspalt.png)

Beim Einzelspalt ist das Maxima erster Ordnung ist das “nullte” Maximum in der Mitte doppelt so breit wie die anderen Maxima. Die Intensität (Höhe) nimmt mit zunehmender Ordnung ab.

### Herleitung am Schaubild

![Untitled](Entstehung%20Einfachspalt.png)

Verstehen ist der Einzelspalt als eine Ansammlung an vielen verschiedenen parallel verlaufenden Lichtstrahlen. Diese Lichtstrahlen müssen in einem Gangunterschied von einem Vielfachen der Wellenlänge $\lambda$ verlaufen um sich konstruktiv gegenseitig zu verstärken. Wenn zwei Lichtstrahlen jedoch mit einem Gangunterschied von einer halben Wellenlänge, also $\frac \lambda 2$ schwingen, löschen sie sich gegenseitig vollständig aus.

Im Schaubild von oben ist zu erkennen, dass aufgrund der Neigung nach oben jeder Lichtstrahl vom oberen Bündel einen Lichtstrahl vom unteren Bündel findet, sodass er sich auslöschen kann. Somit ist an der dargestellten Stelle ein Minimum. 

### Maxima beim Einzelspalt

Der Wert $\Delta s$ bezeichnet den Gangunterschied zwischen dem ersten (obersten) und dem letzten (untersten Lichtstrahl). Dieser ist bei einem Maximum mit dieser Formel zu berechnen. $k$ ist eine Natürliche Zahl.

$$
\tag{k-tes Maximum}\Delta s =(k+\frac 1 2)\cdot\lambda=(2k+1)\cdot \frac \lambda 2
$$

Daraus ergibt sich die allgemein gültige Formel:

$$
\sin(\alpha_k)=\frac{\Delta s}{b}=\frac {(2k+1)\cdot \frac \lambda 2} b
$$

### Minima beim Einzelspalt

Die Formel für die Minima ist sehr ähnlich zur Formel für die Berechnung der Maxima. Hier muss der Gangunterschied ein gerades Vielfachen von der halben Wellenlänge $\frac \lambda 2$ ergeben, damit sich alle Lichtstrahlen gegenseitig auslöschen.

$$
\tag{k-tes Minimum}\Delta s =k \cdot \lambda
$$

Daraus ergibt sich die allgemein gültige Formel:

$$
\sin(\alpha_k)=\frac{\Delta s}{b}=\frac {k\cdot \lambda} b
$$

## Gitter

### Interferenmuster beim Gitter

![Untitled](Interferenzmuster%20Gitter.png)

Beim Gitter sind die Maxima alle gleich breit. Zwischen ihnen sind über proportional kleinere Nebenmaxima. Die Intensität (Höhe) verringert ich langsamer als bei anderen Spalten

### Maxima beim Gitter

Die Formel für die Position der Maxima bei einem Gitter ist ähnlich zu der Formel beim Doppelspalt.

$$
\sin(\alpha_k)=\frac {k\cdot \lambda} g
$$

Der Wert $g$ beschreibt hier die Gitterkonstante des Gitters.