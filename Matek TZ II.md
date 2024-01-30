**Tétel:** Ha $a_n$ konvergens és $a _n\to a$, és $c\in\mathbb{R}$, akkor $c\cdot a_n$ sorozat is konvergens, $c\cdot a_n \to a$
**Bizonyítás:** 
I. eset: $c=0$ nyilvánvaló
II. eset: $c\neq 0$
Legyen $\varepsilon>0$ tetszőleges, de rögzített
$|c\cdot a_n-c\cdot a| = |c|\cdot|a_n-a|$
Mivel $a_n\to a$ $\exists N$, hogy ha $n>N$, akkor
$|a_n-a| < \frac{\varepsilon}{|c|}$
$|c|\cdot|a_n-a|<\varepsilon$
$\varepsilon$-ról csak azt használtuk ki, hogy $\varepsilon>0$, ezért $c\cdot a_n\to ca$

**Tétel:** Ha $a_n$ és $b_n$ is konvergens, és $a_n\to a$, $b_n \to b$, akkor $a_n+b_n\to a+b$
**Bizonyítás:**
Legyen $\varepsilon>0$ tetszőleges, de rögzített
$|(a_n+b_n)-(a+b)| = |a_n-a + b_n -b| \leq |a_n-a| + |b_n-b|$
$a_n\to a \implies \exists N_a$ hogy ha $n>N_a$, akkor $|a_n-a| < \frac{\varepsilon}{2}$
$b_n\to b \implies \exists N_b$ hogy ha $n>N_b$, akkor $|b_n-b| < \frac{\varepsilon}{2}$
Ha $n>max\{N_a,N_b\}$, akkor mindkét egyenlőtlenség teljesül
Ezeket összeadva $|a_n-a| + |b_n-b| < \varepsilon$ adódik
$\varepsilon$-ról csak azt használtuk ki, hogy $\varepsilon>0$, ezért $a_n + b_n\to a+b$

**Tétel:** Ha $a_n$ és $b_n$ is konvergens, és $a_n \to a$, $b_n\to b$, akkor $a_n\cdot b_n \to ab$
**Bizonyítás:**
Legyen $\varepsilon>0$ tetszőleges, de rögzített
$|a_nb_n-ab|= |a_nb_n-a_nb+a_nb-ab| = |a_n(b_n-b)+b(a_n-a)| \leq$
$\leq |a_n(b_n-b)|+|b(a_n-a)| = |a_n||b_n-b|+|b||a_n-a|$
$a_n$ korlátos $\implies\exists K$, hogy $|a_n|<K\implies|a_n||b_n-b|<K|b_n-b|$
$a_n\to a\implies \exists N_a$ hogy ha $n>N_a$ akkor $|a_n-a|<\frac{\varepsilon}{2|b|}\implies$$|b||a_n-a|<\frac{\varepsilon}{2}$
$b_n\to b\implies \exists N_b$ hogy ha $n>N_b$ akkor $|b_n-b|<\frac{\varepsilon}{2K}\implies$$K|b_n-b|<\frac{\varepsilon}{2}$
Ha $n>max\{N_a,N_b\}$, akkor mindkét egyenlőtlenség teljesül
Ezeket összeadva $K|b_n-b| + |b||a_n-a|<\varepsilon$ adódik
$\varepsilon$-ról csak azt használtuk ki, hogy $\varepsilon>0$, ezért $a_n b_n\to ab$

**Tétel:** Ha $a_n$ és $b_n$ is konvergens, és $a_n\to a$, $b_n\to b$ és $b_n \neq 0 \forall n\in\mathbb{N}$ és $b \neq 0$ akkor $\frac{a_n}{b_n}\to\frac{a}{b}$
**Bizonyítás:**
Legyen $\varepsilon>0$ tetszőleges, de rögzített
$|\frac{a_n}{b_n}-\frac{a}{b}| = |\frac{a_n}{b_n} - \frac{a_n}{b} + \frac{a_n}{b} - \frac{a}{b}| = |a_n(\frac{1}{b_n}-\frac{1}{b}) + \frac{1}{b}(a_n-a)| \leq$
$\leq |a_n(\frac{1}{b_n}-\frac{1}{b})| + |\frac{1}{b}(a_n-a)| = |a_n||\frac{1}{b_n}-\frac{1}{b}| + |\frac{1}{b}||a_n-a| =$
$=|a_n||\frac{b-b_n}{b_nb}| + |\frac{1}{b}||a_n-a| = |a_n||\frac{b_n-b}{b_nb}| + |\frac{1}{b}||a_n-a| =$
$=|a_n|\frac{|b_n-b|}{|b_n||b|} + |\frac{1}{b}||a_n-a|$
$a_n$ korlátos $\implies\exists K$ hogy $|a_n|<K\implies |a_n|\frac{|b_n-b|}{|b_n||b|} < K\frac{|b_n-b|}{|b_n||b|}$
$b_n$ korlátos $\implies\exists N$, hogy ha $n>N$, akkor $|b_n|>\frac{|b|}{2}\implies\frac{|b_n-b|}{|b_n||b|} < \frac{|b_n-b|}{\frac{|b|}{2}|b|}=\frac{2|b_n-b|}{b^2}$
$a_n\to a \implies \exists N_a$, hogy ha $n>N_a$, akkor $|a_n-a|<|b|\frac{\varepsilon}{2}\implies\frac{1}{|b|}|a_n-a|<\frac{\varepsilon}{2}$
$b_n\to b\implies\exists N_b$, hogy ha $n>N_b$, akkor $|b_n-b|<\frac{b^2}{2}\frac{\varepsilon}{2}\frac{1}{K}\implies K\frac{2|b_n-b|}{b^2}<\frac{\varepsilon}{2}$
Ha $n>max\{N, N_a, N_b\}$, akkor mindhárom egyenlőtlenség teljesül
Ezeket összeadva $K\frac{2|b_n-b|}{b^2}+\frac{1}{|b|}|a_n-a|<\varepsilon$ adódik
$\varepsilon$-ról csak azt használtuk ki, hogy $\varepsilon>0$, ezért $\frac{a_n}{b_n}\to \frac{a}{b}$

**Tétel:** Ha $a_n$ konvergens és $a_n\to a$ és $a_n>0\:\forall n\in\mathbb{N}$ akkor $\sqrt{a_n}\to\sqrt{a}$
**Bizonyítás:**
Legyen $\varepsilon>0$ tetszőleges, de rögzített
I. eset $a_n\to0\implies|a_n-0|<\varepsilon^2\iff|a_n|<\varepsilon^2\iff a_n<\varepsilon^2\iff\sqrt{a_n}<\varepsilon$
$\iff |\sqrt{a_n}-0|<\varepsilon$
II. eset $a_n\to a, a\neq0$
$|\sqrt{a_n}-\sqrt{a}|=\frac{|\sqrt{a_n}+\sqrt{a}|}{\sqrt{a_n}+\sqrt{a}}|\sqrt{a_n}-\sqrt{a}| = \frac{|a_n-a|}{\sqrt{a_n}+\sqrt{a}}\leq\frac{|a_n-a|}{\sqrt{a}}$
$a_n\to a\implies\exists N$, hogy ha $n>N$, akkor $|a_n-a|<\varepsilon\sqrt{a}\iff\frac{|a_n-a|}{\sqrt{a}}<\varepsilon$
$\varepsilon$-ról csak azt használtuk ki, hogy $\varepsilon>0$, ezért $\sqrt{a_n}\to \sqrt{a}$
