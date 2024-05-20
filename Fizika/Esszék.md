### Forgatónyomaték, forgómozgás (2019. október 25.)
Forgó mozgásokkal a mindennapi  életünkben gyakran találkozunk, ezek kinematikai és dinamikai összefüggései rendkívül hasonlóak a haladó mozgásra vonatkozó megfelelő összefüggésekhez.

A rotációs mozgás leírásához több fizikai mennyiséget is használunk. Ezek közé tartozik a szögsebesség ($\omega=\frac{d\phi}{dt}$, ahol $\phi$ a test szögelfordulása $[\omega]=\frac{1}{s}$), ami megadja a forgás gyorsaságát, a szöggyorsulás ($\beta=\frac{d\omega}{dt}$, $[\beta]=\frac{1}{s^2}$), ami a szögsebesség változásának gyorsaságát írja le, a tehetetlenségi nyomaték ($\theta$, $[\theta]=kg \cdot m^2$), ami a test forgással szembeni tehetetlenségét adja meg az adott tengelyre, a perdület ($N=\theta \cdot \omega$, $[N] = \frac{kg \cdot m^2}{s}$), ami a lendülethez hasonló forgó mozgásra jellemző mennyiség, és a forgási energia ($E_f=\frac{1}{2}\theta\omega^2$, $[E_f]=J$), ami a forgó mozgásból származó energiát adja meg. 

Forgó test szöggyorsulásáért külső hatások felelősek, ezeket nevezzük forgatónyomatéknak. Ha egy testre $F$ erő hat a testre, és az $F$ erő hatásvonalának  forgástengelyétől vett távolsága $r$, akkor az általa kifejtett forgatónyomaték nagysága:
$M=F\cdot r$.
![[Esszék 2023-10-15 09.58.32.excalidraw]]

Kiterjedt test egyensúlyában van, ha minden pontjára igaz, hogy a rá ható erők és forgatónyomatékok összege $\vec0$.

Forgó testekre a dinamika vonatkozó alapegyenlete:
$\sum M=\theta\beta$
használatos.

Egyenletesen változó haladó mozgás esetén az utat az idő függésében a négyzetes úttörvény adja meg:
$s(t)=v_0 \cdot t + \frac{a}{2} \cdot t^2$,
ehhez hasonló az ívelfordulás ($\phi$) és a szöggyorsulás kapcsolata:
$\phi(t)=\omega_0 \cdot t+\frac{\theta}{2} \cdot t^2$.
A szögsebesség - szöggyorsulás és sebesség - gyorsulás kapcsolata is hasonló egymáshoz, mindkét esetben az utóbbi mennyiség az előbbi változásának gyorsaságát írja le. Az összefüggések képletszerűen:
$\Delta v=a \cdot t$,
illetve
$\Delta \omega = \beta \cdot t$.
A dinamika két alapegyenlete hasonló, mindkét esetben külső hatások idézik elő a mozgás gyorsaságának változását. Transzlációs mozgásra:
$\sum F = m \cdot a$,
rotációs mozgásra:
$\sum F = \theta \cdot \beta$
egyenletek érvényesek.

A mindennapi életben is találhatunk példát a fenti összefüggésekre, például amikor forgó mozgást végző korcsolyázó behúzza karjait. Ekkor a korcsolyázó csökkenti teste pontjainak forgástengelytől vett átlagos távolságát, ezzel csökkentve a tehetetlenségi nyomatékát, melynek hatására perdületmegmaradás értelmében megnő a szögsebessége.

### Mikrohullámok mint állóhullámok, a fény közelítő sebessége (2014 október)
A hullámtan vizsgálatainak egy fontos tárgyát képezik az állóhullámok. Állóhullám például a sípokban létrejövő hanghullám, vagy egy megpendített (mindkét végénél rögzített) gitárhúron kialakuló rezgések.
Állóhullámot alakíthatunk ki továbbá egy olyan gumikötélen, melynek az egyik végét rögzítettük, a másik végét pedig rezgésbe hozzuk. Ilyenkor a rögzített végről ellentétes fázisban visszaverődik a hullám és a kialakuló interferencia az eredeti és a visszavert hullám között állóhullámot hoz létre.
$k$ db ($k\in \mathbb{Z^+}$) duzzadóhely fog létrejönni, ezért fontos megfelelő frekvenciát választanunk a kezdeti rezgéshez. Ezt a frekvenciát az
$f=\frac{c}{\lambda_k}$
képlet segítségével kaphatjuk meg, ahol $c$ a kötélre jellemző, és
$\lambda_k=\frac{4}{2k-1}\cdot l$,
ahol $l$ a kötél hossza.
![[Esszék 2024-05-20 08.12.31.excalidraw]]
Az állóhullám tulajdonságait ebben a kísérletben egyértelműen meghatározza az őt keltő haladó hullám. A haladó hullámból állóhullámot kialakító folyamatok során egyedül a fázis változik meg, tehát a terjedési sebességük ($c_{álló}=c_{haladó}$), frekvenciájuk ($f_{álló}=f_{haladó}$) és hullámhosszuk ($\lambda_{álló}=\lambda_{haladó}$) is megegyezik. A duzzadóhelyeken kialakuló rezgés amplitúdója az eredeti hullám amplitúdójával megegyezik ($A_{álló}=A_{haladó}$), viszont a többi pont rezgésének amplitúdója ennél kisebb lesz.
A feladat példájában a frekvencia $f=2,45\cdot 10^9Hz$, két szomszédos duzzadóhely távolsága $d=6cm$. Ez alapján a hullámhossz $\lambda=2\cdot  d = 12 cm$. A hullámterjedés alapegyenlete miatt $c=\lambda\cdot f = 0,12m\cdot 2,45\cdot 10^9Hz = 2,94\cdot 10^8\frac{m}{s}$
A forgótányér alkalmazásával elkerülhető, hogy az állóhullámok duzzadóhelyei a melegíteni kívánt tárgy csupán egyetlen pontját melegítsék, helyette a tárgy egy körvonal menti pontjait melegítik.