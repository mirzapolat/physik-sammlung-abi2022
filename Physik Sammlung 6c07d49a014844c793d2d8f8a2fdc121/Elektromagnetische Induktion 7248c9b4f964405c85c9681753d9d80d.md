# Elektromagnetische Induktion

erstellt von Mirza Polat ©️ 2022

---

# Induktionsgesetz

Induktion entsteht, wenn sich der Wert des magnetischen Flusses ändert. Der magnetische Fluss $\Phi$ ist abhängig von der magnetischen Flussdichte $B$ und der Fläche in der dieses Magnetfeld wirkt.

Die Formel dafür ist:

$$
\Phi=B\cdot A
$$

Sobald sich also die Stärke des Magnetfeldes oder die Fläche auf der es wirkt ändert, fließt ein induzierter Strom.

# Arten von Induktion

## Induktionsempfang

### Induktion im geraden Leiter

$$
U_{ind}=-n\cdot l \cdot B\cdot v
$$

### Induktion an einer Leiterschleife

$$
U_{ind}=-n\cdot \dot B\cdot \dot A = -n\cdot B\cdot \frac {\Delta A} {\Delta t}=-n\cdot A\cdot \frac {\Delta B} {\Delta t}
$$

### Änderung der effektiven Fläche durch Rotation

$$
A_{eff}(\varphi)=A_0\cdot \cos(\varphi)\\
A_{eff}(\varphi)=A_0\cdot \cos(\omega\cdot t)
$$

## Magnetfelderzeugung

### Magnetfeld in der schlanken Spule

Bei einer schlanken Spulel mit $n$ Wicklungen und der Länge $l$ durch die der Strom mit der Stärke $I$ fließt, kann die magnetische Flussdichte des Magnetfelds mit dieser Formel berechnet werden. Die Zahl $\mu_r$ ist bei Luft und Vakuum $\mu_r=1$.

$$
B=\mu_0 \cdot\mu_r \cdot \frac n l \cdot I
$$

![Untitled](Elektromagnetische%20Induktion%207248c9b4f964405c85c9681753d9d80d/Untitled.png)

### Magnetfeld in Helmholz-Spulen

Wenn an einer Helmholtzspule ein Strom von $I$ anliegt und die beiden Wicklungen der Spule jeweils den Radius $r$ und die Wicklungszahl $n$ haben, kann man die magnetische Flussdichte der mit folgendenr Formel berechnen:

$$
B=\mu_0\cdot \frac {8} {\sqrt{125}}\cdot \frac {n\cdot I} {r}
$$

![Untitled](Elektromagnetische%20Induktion%207248c9b4f964405c85c9681753d9d80d/Untitled%201.png)

# Energieerhaltung und Lenzsche Regel

**Nach Lenz:** *Der Induktionsstrom ist stets so gerichtet, dass der Induktionsstrom der Ursache seiner Entstehung entgegenwirkt.*

Durch das Lenzsche Gesetz bekommen die Formel für die Induktionsspannungen ein Minuszeichen an den Anfang.

# Wirbelströme

Wirbelströme können entstehen, wenn sich zum Beipiel eine Metallplatte durch ein kleineres Magnetfeld bewegt. 

![](Elektromagnetische%20Induktion%207248c9b4f964405c85c9681753d9d80d/Untitled%202.png)

Die Lorenzkraft bewirkt, dass die Elektronen (nach der Drei-Finger-Regel) nach links gedrückt werden und nur auf die Seite ausweichen können, auf der kein Magnetfeld ist. Somit fließen sie innerhalb des Magnetfeldes in die eine richtung und außerhalb des Magnetfeldes in die andere.

Nach der Lenzschen Regel wirkt dieser Strom der Ursache seiner Entstehung entgegen, in diesem Fall also entgegen der Fallrichtung. Die Metallplatte wird abgebremst. Auch entsteht Wärme, die die Platte erhitzt.

Vorraussetzung dafür ist, dass sich der Magnetische Fluss verändern muss. Dies kann passieren indem sich die Platte bewegt (wie in dem Beispiel), oder auch indem sich das Magnetfeld ändert (zum Beispiel durch Wechselstrom).

# Selbstinduktion

Baut man eine Spule in einen Stromkreis ein, verzögert sich der Strom durch die Selbstinduktion, die innerhalb der Spule entsteht.

![](Elektromagnetische%20Induktion%207248c9b4f964405c85c9681753d9d80d/Untitled%203.png)

Beim Einschalten wird in der Spule ein Magnetfeld erzeugt. Dieses Wirkt, der Ursache seiner Entstehung entgegen (nach Lenzscher Regel) und bremst somit den Strom. Beim Ausschalten passiert das selbe in entgegengesetzter Richtung.

Um die Induktionsspannung in der Spule zu berechnen, werden zu erst die Grundeigenschaften (wie Windungszahl, Länge, Querschnittsfläche und die Permeablilitätszahl) in einer konstante zusammengefasst. Diese Konstante ist die Induktivität $L$. Ihre Einheit ist Henry $[H]$.

$$
L=\mu_0\mu_r*n^2*\frac A l
$$

Die Funktion für die induzierte Spannung (selbstinduziert) ist dann:

$$
U_{ind} = -L*\dot I(t) \\
= -L *\frac{\Delta I}{\Delta t}
$$

# Energie im Magetfeld

Wenn man einer Spule mit der Induktivität $L$ einen Strom $I$ zuführt, entsteht ein Magnetfeld, welches Energie besitzt. Diese Energie nennt man Magnetische Energie.

$$
W_{mag} = \frac 1 2 *L*I^2
$$

Die räumliche Energiedichte im Raum gibt an, wie viel Energie pro Raum vorhanden ist. Sie wird berechnet nach:

$$
\rho_{mag}=\frac{W_{mag}}{V} = \frac{B^2}{2\mu_0\mu_r}
$$

# Erzeugung von Wechselspannung

Eine Moglichekeit um Wechselnspannung zu erzeugen ist mit Hilfe einer sich drehenden Leiterschleife in einem homogenen Magnetfeld.

![](Elektromagnetische%20Induktion%207248c9b4f964405c85c9681753d9d80d/Untitled%204.png)

Da sich die Richtung, aus der das Magnetfeld kommt nicht ändert, verändert sich durch die Drehung der Spule die Fläche (also die Anzahl der Magnetfeldlinien, die durch die Spule kommen). Da es aber eine Drehung ist verändert sich diese Fläche nicht konstant. Abhängig ist die Fläche von dem Winkel der Drehung und der Länge des Stabes.

Zum Bestimmen der Spannung zu einem bestimmen Zeitpunkt wird diese Formel verwendet. $\omega$ (omega) ist hierbei die Winkelgeschwindigkeit der Drehung und $\hat U$ die Scheitelspannung.

$$
U(t)=\hat{U}*sin(\omega*t)
$$

$$
\hat U =n*B*A*\omega
$$

$$
\omega =\frac{2\pi}T = \frac v r
$$

Die Winkelgeschwindigkeit beschreibt, wie viel "Winkel" die Drehung in einer Sekunde zurücklegt. Sie ist somit "Winkel pro Sekunde". Allerdings wird dieser Winkel im Bogenmaß angegeben und nicht in Grad (180° = $\pi$).