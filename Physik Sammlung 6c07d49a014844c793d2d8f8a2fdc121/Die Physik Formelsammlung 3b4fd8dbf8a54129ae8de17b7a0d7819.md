# Die Physik Formelsammlung

# Elektrische Felder

## Elektrische Feldstärke

Elektrische Feldstärke allgemein:

$$
\vec E = \frac {\vec F _{el}} q
$$

Elektrische Feldstärke bei Punktladung:

$$
E=\frac 1 {4\cdot \pi \cdot \epsilon_0}\cdot \frac q {r^2}
$$

Elektrische Feldstärke beim Plattenkondensator

$$
E=\frac 1 {\epsilon_0}\cdot \frac Q A
$$

## Kondensator

Elektrische Energie Plattenkondensator:

$$
W_{el}=F_{el}\cdot d = q\cdot E\cdot d=q\cdot U
$$

Spannung bei einem Plattenkondensator

$$
U=\frac{W}{q}=E\cdot d
$$

Beschleunigung von Ladungen durch Spannung:

$$
W_{kin}=\frac 1 2 \cdot m\cdot v^2=q\cdot U=W_{el} \\
v^2=\frac {2\cdot q \cdot U} m\\
v=\sqrt{2\cdot U\cdot \frac q m}
$$

Kapazität eines Kondensators allgemein:

$$
C=\frac Q U
$$

Kapazität Plattenkondensator:

$$
C=\epsilon_0\cdot \epsilon_r\cdot \frac A d
$$

Elektrische Energie im geladenen Kondensator:

$$
W_{el}=\frac 1 2 \cdot Q \cdot U=\frac 1 2 \cdot C\cdot U^2
$$

Zusätzliche Formel für Energie im Plattenkondensator:

$$
W_{el}=\frac 1 2 \cdot \epsilon_0\cdot \epsilon_r \cdot E^2 \cdot A\cdot d
$$

Kraft auf Ladung im homogenen Feld:

$$
F_{el}=\frac 1 {\epsilon_0}\cdot \frac {|Q|\cdot |q|} A
$$

Parallelschaltung von Kondensatoren:

$$
C_{ges}=C_1+C_2+...
$$

Reihenschaltung bei Kondensatoren:

$$
\frac 1 {C_{ges}}=\frac 1 {C_1}+\frac 1 {C_2}+...
$$

## Kräfte und Ladungen

Coulomb-Kraft:

$$
F_C=\frac 1 {4\cdot\pi\cdot\epsilon_0}\cdot \frac {q_1\cdot q_2} {r^2}
$$

Dichte der Ladungen auf einer Fläche:

$$
\sigma=\frac Q A
$$

Elektrisches Potenzial:

$$
W_{pot}=q\cdot E\cdot d
$$

## Elektronenstrahlröhre

Auslenkung in der Elektronenstrahlröhre:

$$
y(l)=\frac 1 4 \cdot \frac {U_K} {d\cdot U_B} \cdot l^2
$$

Winkel in der Elektronenstrahlröhre:

$$
\tan(\alpha)=y'(l)=\frac 1 2 \cdot \frac {U_K}{d\cdot U_B} \cdot l
$$

# Magnetisches Feld

## Magnetismus

Magnetische Feldstärke allgemein:

$$
B=\frac F {I\cdot s}
$$

Magnetsischer Fluss:

$$
\Phi=B\cdot A
$$

Hall-Effekt Spannung:

$$
U_H=\frac {b\cdot l\cdot d} {N\cdot q}\cdot \frac {I\cdot B} d\\
U_H=R_H\cdot \frac {I\cdot B} d
$$

## Lorenzkraft

Allgemeine Lorenzkraft:

$$
F_L=q \cdot B \cdot v
$$

Lorenzkraft um einen Leiter herum:

$$
F_L=I\cdot B\cdot s
$$

## Massenspektrometer und Geschwindigkeitsfilter

Lorenzkraft = Zentripetalkraft im Massenspektrometer:

$$
F_L=F_Z\\
q\cdot B\cdot v = \frac {m\cdot v^2} {r}
$$

Elektrische Kraft = Lorenzkraft im Geschwindigkeitsfilter:

$$
F_{el}=F_{L}\\
q\cdot E=q\cdot v\cdot B\\v=\frac E B
$$

# Elektromagnetische Induktion

## Induktion

Induktion im Geraden Leiter:

$$
U_{ind}=-n\cdot l \cdot B\cdot v
$$

Induktion in einer Leiterschleife:

$$
U_{ind}=-n\cdot \dot B\cdot \dot A = -n\cdot B\cdot \frac {\Delta A} {\Delta t}=-n\cdot A\cdot \frac {\Delta B} {\Delta t}
$$

Änderung der effektiven Fläche durch rotation einer Leiterschleife:

$$
A_{eff}(\varphi)=A_0\cdot \cos(\varphi)\\
A_{eff}(\varphi)=A_0\cdot \cos(\omega\cdot t)
$$

## Magnetfelder

Magnetfeld einer schlanken Spule:

$$
B=\mu_0 \cdot\mu_r \cdot \frac n l \cdot I
$$

Magnetfeld einer Helmholtz-Spule:

$$
B=\mu_0\cdot \frac {8} {\sqrt{125}}\cdot \frac {n\cdot I} {r}
$$

Induktivität einer Spule:

$$
L=\mu_0\mu_r*n^2*\frac A l
$$

Gegenspannung einer selbstinduzierenden Spule:

$$
U_{ind} = -L*\dot I(t) \\
= -L *\frac{\Delta I}{\Delta t}
$$

Energie im Magnetfeld einer Spule:

$$
W_{mag} = \frac 1 2 *L*I^2
$$

Räumliche Energiedichte im Mangetfeld:

$$
\rho_{mag}=\frac{W_{mag}}{V} = \frac{B^2}{2\mu_0\mu_r}
$$

## Wechselspannung

Spannung einer sich drehenden Leiterschleife im homogenen Magnetfeld:

$$
U(t)=\hat{U}*sin(\omega*t)
$$

$$
\hat U =n*B*A*\omega
$$

Winkelgeschwindigkeit einer sich drehenden Leiterschleife:

$$
\omega =\frac{2\pi}T = \frac v r
$$

# Mechanische Schwingungen und Wellen

Kraftgesetz für harmonische Schwingungen beim Federpendel:

$$
F=-D*s
$$

Elongationsenergie:

$$
W = W_{elong}+W_{kin} =\frac 1 2 Ds^2+\frac 1 2 mv^2 = konstant
$$

Periodendauer Fadenpendel:

$$
T=2\pi*\sqrt{\frac l g}
$$

Periodendauer Federpendel:

$$
T=2\pi\cdot \sqrt{\frac m D}
$$

Periodendauer Flüssigkeitspendel:

$$
T=2\pi\cdot\sqrt{\frac L {2\cdot g}}
$$

Winkelgeschwindigkeit:

$$
\omega=\frac {2\pi} T
$$

Die Super-Wellengleichung:

$$
y(x;t)=\hat y\cdot\sin(2\pi\cdot(\frac t T -\frac x \lambda))
$$

Geschwindigkeit, Wellenlänge, Periodendauer und Frequenz:

$$
c=\lambda\cdot f=\lambda\cdot \frac 1 T \\
\implies c\cdot T=\lambda
$$

Eingenschwingungsfrequenz bei einem Seil:

$$
f_k=k\cdot \frac c {2\cdot l}
$$

# Elektromagnetische Schwingungen und Wellen

## Elektromagnetischer Schwingkreis

Thompsonsche Schwingungsgleichung:

$$
T=2\pi\cdot\sqrt{L\cdot C}
$$

## Brechung und Beugung

Brewsterformel für Brewsterwinkel:

$$
\tan(d_B)=\frac{n_2}{n_1}\implies d_B=\tan^{-1}(\frac{n_2}{n_1})
$$

Brechungsindex:

$$
n=\frac {\sin{\alpha}} {\sin\beta}
$$

Vorraussetzung für eine Beugung an einem Spalt:

$$
\tag {ist die Spaltbreite} \lambda \sim a
$$

## Doppelspalt

Maxima beim Doppelspalt:

$$
\sin(\alpha)=\frac {\Delta s} g = \frac {k\cdot \lambda} g  \\
\tan(\alpha) =\frac {d_k} a 
$$

Kleinwinkelnäherung:

$$
\sin(\alpha)\approx \tan(\alpha)\\
\frac {k*\lambda} g \approx \frac {d_k} a\\
\implies d_k=\frac a g \cdot k \cdot\lambda
$$

Abstand zwischen Maxima:

$$
d=d_{k+1}-d_k = \frac a g \cdot \lambda

$$

Minima beim Doppelspalt:

$$
\sin(\alpha)=\frac {\Delta s} g = \frac {(2k+1)\cdot \frac \lambda 2} g  \\
\tan(\alpha) =\frac {d_k} a 
$$

## Einzelspalt

Maxima beim Einzelspalt:

$$
\sin(\alpha_k)=\frac{\Delta s}{b}=\frac {(2k+1)\cdot \frac \lambda 2} b
$$

Minima beim Einzelspalt:

$$
\sin(\alpha_k)=\frac{\Delta s}{b}=\frac {k\cdot \lambda} b
$$

## Gitter

Maxima beim Gitter:

$$
\sin(\alpha_k)=\frac {k\cdot \lambda} g
$$

# Grundlagen der Quanten- und Atomphysik

## Fotoeffekt

Photonenenergie:

$$
W_\text{Photon}=h\cdot f
$$

Kinetische Energie beim Photoeffekt:

$$
W_\text{kin}=W_\text{Photon}-W_\text{A}\\
W_\text{kin}= h\cdot f-W_\text{A}
$$

Planksche Wirkungsquantum ist die Steigung der Gerade:

$$
h=\frac{\Delta W}{\Delta f} \approx6,6\cdot 10^{-34}\text{Js}
$$

Umkehrung des Photoeffekts:

$$
f_\text{G} =\frac{e\cdot U_\text{B}}{h}
$$

Masse von Photonen:

$$
W=m\cdot c^2
$$

## Effekte

Energie eines freiwerdenen Elektrons bei Paarbildung:

$$
h\cdot f=2\cdot m_e\cdot c^2+2\cdot W_{\text{kin}} \gt 1,02MeV
$$

Compton-Effekt:

$$
\Delta\lambda=\frac h {m\cdot c_0}\cdot (1-\cos(\vartheta))=\lambda_c\cdot (1-\cos(\vartheta))
$$

Compton-Wellenlänge:

$$
\lambda_{c,e}=\frac h {m_e\cdot c_0}\approx 2,43 \cdot 10^{^-12}
$$

De-Broglie Wellenlänge:

$$
\lambda=\frac h p=\frac h {m\cdot v}
$$

$$
v=\sqrt{\frac{2\cdot q\cdot  U}m}
$$

## Energieniveaus im Wasserstoffmodell

Potenzielle Energie zum Kern:

$$
W_{pot}=\frac {e^4 m_e}{4 {\epsilon_0}^2 h^2} \cdot (\frac 1 {n^2} - \frac 1 {m^2})
$$

Geschwindigkeit:

$$
W_{kin}=\frac 1 2 m_e ({v_n}^2-{{v_m}^2})
$$

Insgesamte Energie:

$$
\Delta W=W_{pot}-W_{kin}=13,6\text{ eV}\cdot (\frac 1 {n^2}-\frac 1 {m^2})
$$

## Wasserstoff Spektrum

Elektronen fallen auf eine Tiefere Ebene:

$$
h\cdot f=h\cdot \frac c \lambda=\frac {e^4 m_e}{8 {\epsilon_0}^2 h^2} (\frac 1 {n^2}-\frac 1 {m^2})
$$

Wellenlänge der Strahlung, die frei wird:

$$
\frac 1 \lambda=\frac {e^4 m_e} {8  c\cdot{\epsilon_0}^2h^3}(\frac 1 {n^2}-\frac 1{m^2})=R\cdot (\frac 1 {n^2}-\frac 1{m^2})
$$

## Heißenbergsche Unschärferelation

Ort und Impuls:

$$
h\approx\Delta p \cdot \Delta x
$$

Energie und Zeit:

$$
h\approx \Delta W \cdot \Delta t
$$