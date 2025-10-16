# Elektrisches Feld

erstellt von Mirza Polat ©️ 2022

---

# Elektrische Felder

## Elektrische Feldstärke

Sobald Ladungen existieren, entsteht ein elektrisches Feld im Umfeld des geladenen Teilchens. Dieses elektrische Feld kann andere Ladungen in diesem Bereich beeinflussen. Der entscheidende Faktor ist die Elektrische Feldstärke.

### Allgemeine Formel

Für die elektrische Feldstärke gilt die allgemeine Formel:

$$
\vec E = \frac {\vec F _{el}} q
$$

Dabei die elektrische Feldsärke $\vec E$ definiert als die elektrische Kraft $\vec F_{el}$, die auf die Probeladung $q$ wirkt. Die Einheit ist $\frac N C$ (Newton durch Coulomb) oder $\frac V m$ (Volt pro Meter).

Der Vektor der elektrischen Feldstärke zeigt immer vom positiven Weg, hin zum negativen. Das heißt, dass die Kraft $\vec F_{el}$ auf eine positive Ladung wirkt.

### Elektrisches Feld einer Punktladung im Raum

Eine Punktladung ist zum Beispiel ein einzelnes Elektron oder Proton, welches frei im Raum schwebt. Um diese Ladung herum existiert ein kreisförmiges elektrisches Feld. In diesem Fall nimmt die elektrische Feldstärke um die Ladung herum quadratisch ab. Das heißt, je weiter wir uns von der Ladung entfernen, desto schwächer wird das elektrische Feld.

Die Formel dafür ist:

$$
E=\frac 1 {4\cdot \pi \cdot \epsilon_0}\cdot \frac q {r^2}
$$

Dabei ist $E$ der Betrag der elektischen Feldstärke an einem Punkt, der den Abstand $r$ zur Ladung $q$ hat. 

Der gesamte erste Bruch $\frac 1 {4\cdot \pi \cdot \epsilon_0}$ in der Formel bildet eine Konstante Zahl, die von der elektrischen Feldkonstante $\epsilon_0$ (*Dieketizitätskonstante des Vakuums*) abhängig ist.

### Elektrisches Feld in einem Plattenkondensator

Wenn ein Plattenkondensator geladen wird, entsteht ein elektrisches Feld zwischen den beiden Platten, welches senkrecht von der positiv geladenen Platte zur negativ geladenen Platte zeigt.

Die Formel hierbei ist:

$$
E=\frac 1 {\epsilon_0}\cdot \frac Q A
$$

Der Betrag der elektrischen Feldstärke ist also propotrional zur Ladung $Q$ und umgekehrt proportional zum Flächeninhalt $A$ der beiden Platten.

## Definition der elektrischen Spannung

Die elektrische Spannung lässt sich gut an folgendem Beispiel darstellen. Zwei Kondensatorplatten werden an eine Spannungsquelle angeschlossen und aufgeladen. Danach werden sie von der Spannungsquelle getrennt und auseinandergezogen.

![](Elektrisches%20Feld%207600e9b23cab411ba73d32a3d6a9efac/Untitled.png)

Beim Auseinanderziehen der Kondensatorplatten wird Arbeit gegen die Feldkräfte investriert. Dadurch vergrößert sich die Energie des elektrischen Feldes (ähnlich wie mit potenzieller Energie).

$$
W_{el}=F_{el}\cdot d = q\cdot E\cdot d
$$

$$
U=\frac{W}{q}=E\cdot d
$$

## Die Coulomb-Kraft

Die Formel für die [elektrische Feldstärke bei Punktladungen](Elektrisches%20Feld%207600e9b23cab411ba73d32a3d6a9efac.md) kann auch bei der Coulomb-Kraft weiterhelfen. Die Coulomb-Kraft ist die Kraft die eine Ladung $q_1$ auf eine zweite Ladung $q_2$ auf den Abstand $r$ ausübt.

Die Formel dafür ist:

$$
F_C=\frac 1 {4\cdot\pi\cdot\epsilon_0}\cdot \frac {q_1\cdot q_2} {r^2}
$$

Die Einheit der Kraft ist $N$ (Newton).

## Das Beschleunigen von Ladungen

In einem Elektrischen Feld können Ladungen beschleunigt werden. Die Geschwindigkeit auf die sie beschleunigt werden kann mit Hilfe des Energieerhaltungssatzes berechnet werden.

Dazu werden die elektrische Feldenergie und die kinetische Energie gebraucht:

$$
W_{kin}=\frac 1 2 \cdot m\cdot v^2=q\cdot U=W_{el} \\
v^2=\frac {2\cdot q \cdot U} m\\
v=\sqrt{2\cdot U\cdot \frac q m}
$$

# Kondensatoren

## Allgemein

Ein Kondensator besteht aus zwei gegenüberliegenden elektrischen Ladungsträgern, zwischen denen ein elektrisches Feld herrschen kann. Dabei wird dem Kondensator eine Kapazität $C$ zugeordnet.

Die allgemeine Formel für die Kapazität ist:

$$
C=\frac Q U
$$

Die Kapazität $C$ beschreibt also die Menge an Ladung $Q$, mit der ein Kondensator durch eine Spannung $U$ geladen wird. $Q$ ist der Betrag des Ladungsunterschied zwischen den beiden Leitern des Kondensators.

Die Einheit der Kapazität ist $\frac {1C} {1V}=1F$ (Farad).

## Plattenkondensator

Die [Kapazität](Elektrisches%20Feld%207600e9b23cab411ba73d32a3d6a9efac.md) eines Plattenkondensators kann durch diese Formel berechnet werden:

$$
C=\epsilon_0\cdot \epsilon_r\cdot \frac A d
$$

$A$ ist der Flächeninhalt der Platten und $d$ ist der Abstand, den die beiden Platten zu einander haben. Die konstante $\epsilon_r$ ist die Dieelektrizitätskonstante des Materials zwischen den beiden Platten. Ist diese Zahl nicht extra angegeben, ist sie $1$ (Vakuum oder Luft).

## Feldstärken im homogenen Feld

Befindet sich eine Ladung $q$ im Zwischenraum von zwei geladenen Kondensatorplatten, so wird auf diese Ladung eine Kraft ausgeübt. Diese Kraft zeigt in richtung der gegenteilig Geladenen Platte.

Der Betrag der Kraft lässt sich durch diese Formel berechnen:

$$
F_{el}=\frac 1 {\epsilon_0}\cdot \frac {|Q|\cdot |q|} A
$$

## Elektrische Energie im geladenen Kondensator

Ist ein Kondensator geladen, speichert er elektrische Energie. Vergleichbar ist das mit der “potenziellen Energie”, welche für Elektronen zwischen den beiden Platten existiert. Die Formel für einen geladenen Kondensator mit der Spannung $U$, der Ladung $Q$ und der Kapazität $C$ ist dabei:

$$
W_{el}=\frac 1 2 \cdot Q \cdot U
$$

$$
W_{el}=\frac 1 2 \cdot C\cdot U^2
$$

Die Energie in einem Plattenkondensator kann auch noch durch die elektrische Feldstärke $E$ dargestellt wrden. Die Formel ist dann abhängig vom Volumen, welches zwischen den beiden Kondensatorplatten eingerahmt ist.

$$
W_{el}=\frac 1 2 \cdot \epsilon_0\cdot \epsilon_r \cdot E^2 \cdot V
$$

Das Volumen kann berechnet werden, indem der Flächeninhalt der Platten mit dem Abstand zwischen ihnen multipliziert wird. Also kann man die Formel auch so schreiben:

$$
W_{el}=\frac 1 2 \cdot \epsilon_0\cdot \epsilon_r \cdot E^2 \cdot A\cdot d
$$

## Dielektrika

Wenn man den Raum zwischen zwei Kondensatorplatten mit einem anderen Material als Luft oder Vakuum füllt, steigt die Kapazität des Kondensators. Jedes Material hat einen eigenen Multiplikator. Dieser Multiplikator ist die Dielektrizitätszahl $\epsilon_r$.

In Aufgaben wird der Wert angegeben. Wenn nicht ist $\epsilon_r=1$.

## Flächenladungsdichte

Bei einer gleichmäßigen Ladungsverteilung in einem Plattenkondensator, kann man die Dichte der Ladungen berechnen mit der Formel:

$$
\sigma=\frac Q A
$$

$$
\sigma = \epsilon_r\cdot E
$$

## Parallel und Reihenschaltung von Kondensatoren

### Parallelschaltung

Bei einer Parallelschlatung addieren sich die Kapazitäten $C_1$ und $C_2$ der beiden Kondensatoren einfach:

$$
C_{ges}=C_1+C_2+...
$$

### Reihenschaltung

Bei einer Reihenschaltung wird folgende Formel genutzt:

$$
\frac 1 {C_{ges}}=\frac 1 {C_1}+\frac 1 {C_2}+...
$$

# Elektrisches Potenzial

Elektrisches Potenzial ist vergleichbar mit der potenziellen Energie bei Gravitation. Beim elektrischen Potenzial ist es jedoch nicht die Gravitation, die die Potenzielle Energie verursacht, sondern ein elektrisches Feld. Die Formel dafür ist dann:

$$
W_{pot}=q\cdot E\cdot d
$$

Dabei steht $q$ für die Ladung, $E$ für die elektrische Feldstärke und $d$ für die Distanz zum Potenzial-Nullpunkt.

# Umlenkung von Ladungen im E-Feld am Beispiel der Elektronenstrahlablenkröhre

![Untitled](Elektrisches%20Feld%207600e9b23cab411ba73d32a3d6a9efac/Untitled%201.png)

Elektronen werden mit Hilfe einer Spannung $U_B$ beschleunigt und treten dann in das homogene Feld zwischen zwei Kondensatorplatten mit der Spannung $U_K$ und einem Abstand von $d$ ein. Die Gesamte Auslenkung $y$  beim Austritt aus dem Feld ist dann:

$$
y(l)=\frac 1 4 \cdot \frac {U_K} {d\cdot U_B}\cdot l^2
$$

Der Winkel des Austritts ist somit:

$$
\tan(\alpha)=y'(l)=\frac 1 2 \cdot \frac {U_K}{d\cdot U_B}\cdot l
$$

# Dioden

## Was sind Dioden?

Dioden sind elektrische Bauteile, die Strom nur in eine Richtung fließen lassen. Dioden selbst, leuchten nicht, es gibt allerdings Leuchtdioden (LED), welche energie Abstrahlen. Meist ist diese Energie in Form von Licht zu sehen.

![Dioden im Schaltplan](Elektrisches%20Feld%207600e9b23cab411ba73d32a3d6a9efac/Untitled%202.png)

Dioden im Schaltplan

## Funktionsweise

Eine Diode besteht aus zwei Häften, die von einander getrennt sind.

Die eine Seite ist n-Dotiert. Das heißt, dass zufällige Atome aus dem Material durch Atome ausgetauscht werden, die mehr Außenelektronen haben, sodass ein Überschuss an Elektronen vorhanden ist (links zu sehen).

Die andere Seite ist p-Dotiert. Das heißt, dass Atome so ausgetauscht werden, dass weniger Außenelektronen vorhanden sind, als genutzt werden, sodass “Löcher” entstehen, die positiv geladen sind (rechts zu sehen).

![Untitled](Elektrisches%20Feld%207600e9b23cab411ba73d32a3d6a9efac/Untitled%203.png)

In der Mitte zwischen den beiden Seiten ist eine Sperrschicht. Der gesamte Aufbau sieht dann wie folgt aus:

![Untitled](Elektrisches%20Feld%207600e9b23cab411ba73d32a3d6a9efac/Untitled%204.png)

Wenn nun eine Spannung angeschlossen wird, treten zwei Fälle auf:

![Untitled](Elektrisches%20Feld%207600e9b23cab411ba73d32a3d6a9efac/Untitled%205.png)