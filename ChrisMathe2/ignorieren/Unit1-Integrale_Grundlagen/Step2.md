# 2: Die wichtigsten Stammfunktionen

Gehen wir Schritt für Schritt die wichtigsten Stammfunktionen durch. 
Anmerkung: Ich bin schreibfaul und verzichte überall auf die Konstante C aus dem vorherigen Kapitel.




<span style="color: red">1.2.1: 
Was ergibt das Integral hier? 
$ \int 0 dx = ?$
<details>
<summary><span style="color: red">Lösung</span></summary>

$ \int 0 dx $ = 0

Manchmal hilfreich, wenn man zeigen kann, dass ein Term 0 im Integral ist, verschwindet dieser.

</details>
-----


<span style="color: red">1.2.2: 
Was ergibt das Integral hier? $ \int k dx = ? $ mit $k \in \R$
<details>
<summary><span style="color: red">Lösung</span></summary>

$ \int k dx $ = kx

Hat man einen konstanten Wert, wird hier einfach ein x drangehängt

Interessant wird es, wenn es zwei Variablen gibt x und y.
Dabei wird die Variable, die nicht durch dx bzw. dy gekennzeichnet ist wie eine Konstante behandelt.

$$ \int y dx  = yx $$
und
$$ \int x dy  = xy $$



</details>
-----


Jetzt fügen wir x hinzu, sodass wirklich die Funktion auch von x abhängt


<span style="color: red">1.2.3: 
Was ergibt das Integral hier? $ \int x dx = ? $
<details>
<summary><span style="color: red">Lösung</span></summary>

$ \int x dx  = \frac{1}{2} x^2$

Das Ergebnis wirkt im ersten Moment komisch.
Aber es leuchtet ein, wenn man die Probe macht.
Wenn man $ \frac{1}{2} x^2$ ableitet, merkt man überraschenderweise, dass es aufgeht




</details>
-----


Das Muster können wir auch weiter spannen.


<span style="color: red">1.2.4: 
Was ergibt das Integral hier? $ \int x^2 dx = ? $
<details>
<summary><span style="color: red">Lösung</span></summary>

$ \int x dx  = \frac{1}{3} x^3$

Auch hier wundert man sich im ersten Moment, aber die Probe gibt uns wieder recht.


</details>
-----

Und vielleicht erkennst du das Muster schon. Mann kann das ganze auch zu einem Gesetz zusammenfassen

<span style="color: red">1.2.5: 
Was ergibt das Integral hier? $ \int x^n dx =  $ mit $n \in \mathbb{Z} \setminus \{-1\}$? Also für alle ganzzahligen n bis auf die -1.
<details>
<summary><span style="color: red">Lösung</span></summary>

$ \int x^n dx  = \frac{1}{n+1} x^{(n+1)}$

Das funktioniert nicht nur für die positiven Zahlen also z.B. für n=8 oder n=99999, sondern auch für die negativen Zahlen.

Beispilsweise gilt das hier :
$ \int x^{-5} dx  = \frac{1}{-4} x^{-4}$

Und vielleicht hast du dich gewundert, wieso es nicht für -1 geht. Setz mal die -1 in die Formel ein und schon merkst du $\frac{1}{-1 +1}$ ist etwas Verbotenes, durch Null teilt man schließlich nicht.

</details>
-----

Das bringt uns direkt zur nächsten Frage.

<span style="color: red">1.2.6: 
Was ergibt das Integral hier? $ \int x^{-1} dx =  $ ? 
<details>
<summary><span style="color: red">Lösung</span></summary>



$ \int x^{-1} dx  = \int\frac{1}{x} dx = \ln|x| $

Also der Betrag von x und dann noch der natürliche Logarithmus.
Das kann man sich natürlich alles irgendwie kompliziert herleiten, aber es ist hier etwas pragmatischer es sich einfach zu merken.

Kleiner Reminder:
$x^{-1} = \frac{1}{x}$


</details>
-----

Was passiert eigentlich, wenn meine Form etwas komplizierter ist?

<span style="color: red">1.2.7: 
Was ergibt das Integral hier? $ \int 9 x^{2} dx =  $ ? 
<details>
<summary><span style="color: red">Lösung</span></summary>

Die Form mit dem x kennen wir ja schon, jetzt steht aber noch eine konstante 9 vor unserem Term.
Und das schöne ist, eine konstante bleibt einfach stehen und mit ihr passiert nichts

$ \int 9 x^{2} dx = 9 \cdot \frac{1}{3}x^3 $

So funktioniert es auch mit allen anderen Varianten bei dem eine konstante vor einem Term mit x vorsteht. 
Das gedanklich zu trennen ist oft sehr sehr hilfreich um Terme zu vereifachen. Die Konstanten kann man für die Integration quasi vergessen und später einfach wieder dazu multiplizieren:

$\int 9 x = 9 \cdot (\int x dx)$




</details>