**Arkimédeszi axióma:** Tetszőleges $a$ számhoz található $n$ természetes szám, amely nála nagyobb ($\forall a, \exists n\in \mathbb{N}, a<n$)
**Teljességi axióma:** Minden felülről korlátos, nem üres halmaznak van egy legkisebb felső korlátja, melyet felső határnak, vagy  szuprémumnak nevezünk. ($sup \: H$)
Minden alulról korlátos, nem üres halmaznak van egy legnagyobb alsó korlátja, melyet alsó határnak, vagy  infimum nevezünk. ($inf \: H$)

**Tételek (amiket csak kimondás szintjén kell tudni)**
- Bármely két valós szám között van irracionális szám
- Bármely két valós szám között van racionális és irracionális is
- Ha $a>1, r_1,r_2 \in \mathbb{R}, r_1 > r_2$, akkor $a^{r_1}>a^{r_2}$ (relációs jelek megfordulnak, ha $a<1$)
- Minden sorozatnak van monoton részsorozata
- Ha $a_n \to a$ és $a_{n_k}$ $(a_n)$ egy részsorozata, akkor $a_{n_k} \to a$

**Definíciók**
- A $H$ halmaz felülről korlátos, ha van olyan $K$, hogy $H$ minden eleme nem nagyobb $K$-nál ($\exists K, \forall x\in H, x \leq K$) (Ha $\exists K$, akkor végtelen sok megfelelő $K$ van)
- A $H$ halmaz alulról korlátos, ha van olyan $k$, hogy $H$ minden eleme nem kisebb $k$-nál ($\exists k, \forall x\in H, x \geq k$) (Ha $\exists k$, akkor végtelen sok megfelelő $k$ van)
- $(a_n)$ sorozat felülről korlátos, ha van olyan M szám, hogy minden $n \in \mathbb{N}$-re $a_n\leq M$ ($\exists M, \forall n \in \mathbb{N}, a_n \leq M$)
- $(a_n)$ sorozat alulról korlátos, ha van olyan M szám, hogy minden $n \in \mathbb{N}$-re $a_n\geq M$ ($\exists M, \forall n \in \mathbb{N}, a_n \geq M$)
- Egy sorozat korlátos, ha alulról és felülről is korlátos
- $(a_n)$ sorozat monoton növekvő, ha bármely $n \in \mathbb{N}$-re $a_n \leq a_{n+1}$
- $(a_n)$ sorozat monoton csökkenő, ha bármely $n \in \mathbb{N}$-re $a_n \geq a_{n+1}$
- $(a_n)$ sorozat szigorúan monoton növekvő, ha bármely $n \in \mathbb{N}$-re $a_n < a_{n+1}$
- $(a_n)$ sorozat szigorúan monoton csökkenő, ha bármely $n \in \mathbb{N}$-re $a_n > a_{n+1}$
- $(a_n)$ sorozat konvergens, és $a$ a határértéke, ha bármely $\varepsilon>0$ - hoz létezik olyan $N$ küszöbszám, hogy ha $n>N$, akkor $|a_n-a|<\varepsilon$ ($a_n \to a$)
- Ha egy sorozat nem konvergens, akkor divergens
- $(a_{n_k})$ sorozat $(a_n)$ sorozat részsorozata, ha minden tagja $(a_n)$ sorozatnak is tagja, és $1\leq n_1<n_2<n_3<...<n_k<...$

**Tétel (bizonyítással): Bármely két valós szám között van racionális szám**
Legyen $a,b\in\mathbb{R}, 0\leq a< b$
$\frac{1}{b-a}$
Arkimédeszi axióma alapján: $\exists n \in \mathbb{N}, \frac{1}{b-a} < n$
Ez alapján $b-a > \frac{1}{n}$
Ez alapján ha a számegyenesen elkezdünk lépkedni $\frac{1}{n}$ lépésközzel, akkor biztosan be fogunk lépni az $a$ és $b$ közti intervallumba, azaz $\exists k \in \mathbb{N}, \frac{k}{n}\in [a,b]$

**Tétel (bizonyítással): Konvergens sorozatnak pontosan egy határértéke van**
Indirekt módon
TFH. $(a_n)$ sorozat két határértéke $a < b$
Legyen $\varepsilon = \frac{b-a}{4}$
$a_n\to a$, ezért $\exists N_a$, hogy ha $n>N_a$, akkor $|a_n-a|<\varepsilon = \frac{b-a}{4}$
$a_n\to b$, ezért $\exists N_b$, hogy ha $n>N_b$, akkor $|a_n-b|<\varepsilon = \frac{b-a}{4}$
Legyen $N=max\{N_a;N_b\}$
Ekkor számegyenesen felrajzolva látható, hogy $a$-nak és $b$-nek nincs közös $\varepsilon$ sugarú környezete
$\forall n > N$-re benne kéne lennie a két környezet metszetében, ami nem létezik 

**Tétel (bizonyítással): Minden konvergens sorozat korlátos, nem korlátos sorozat nem lehet konvergens, de nem minden korlátos sorozat konvergens**
Legyen $a_n \to a$
Definíció szerint $\varepsilon = 1$ - hez $\exists N$, hogy ha $n>N$, akkor $|a_n-a|<1$
Vagyis az n-edik tag után minden tag benne lesz az $]a-1; a+1[$ intervalumban
Ezért az intervalumon kívül marad n darab tag
Ha "valamelyik irányban" nincsen kívül maradó tag, akkor az intervalum határa ($a-1$ illetve $a+1$ megfelelő korlát)
Egyébként a kívül maradók által alkotott véges halmaz korlátjai megfelelő korlátok
Megadható olyan korlátos sorozat, amely nem konvergens, pl. $a_n = (-1)^n$
