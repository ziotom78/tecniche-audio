# Introduzione all’argomento di oggi

- Oggi continueremo nello studio delle onde sinusoidali, parlando della loro ampiezza

- Introdurremo poi i concetti di sovrapposizione e di interferenza

# Inquisitori accademici onorari

# Ampiezza del suono

-   Nella scorsa lezione, abbiamo visto che un’onda sinusoidale si scrive così:

    \[
    \text{onda} = A \sin (2\pi\nu t + \phi),
    \]

-   Abbiamo discusso brevemente del significato di $\phi$ (“sfasamento”) e della frequenza: il primo indica in che punto dell’oscillazione iniziamo a misurare la pressione, e il secondo il numero di oscillazioni al secondo

-   Ci resta ancora da parlare dell’ampiezza $A$

# Misura dell’ampiezza

-   Come avevamo già accennato, per un’onda acustica in un fluido come l’aria o l’acqua, l’ampiezza $A$ può essere misurata in Pascal (pressione) o in kg/m³ (densità)
-   In un mezzo solido come un muro invece l’ampiezza è uno **spostamento**, e si misura in metri

# Variazione dell’ampiezza

-   Immaginate di essere in un prato e di lanciare un urlo

-   Chi è vicino a voi sentirà il vostro grido con grande intensità

-   Ma, allontanandosi, il suono sarà sempre più debole

-   Sapete spiegare il perché?

# Variazione dell’ampiezza

::: side-by-side

::: content

-   Il motivo per cui il suono propagandosi si attenua ha a che fare con la **conservazione dell’energia**

-   L’urlo nasce dalla vostra bocca, che ha una piccola superficie. Ma il suono si propaga ovunque nello spazio (anche verso l’alto), e l’energia sonora deve necessariamente “diluirsi”

-   Ciò avverrebbe anche **in mancanza di attrito e forze viscose**!

:::

::: media

![](media/legge-inverso-quadrato.jpg)

:::
:::

# Legge del quadrato

-   In un caso ideale, l’intensità dell’onda sonora varia come **l’inverso del quadrato** della distanza $r$. Se quindi due persone misurano un’ampiezza di pressione $P_1$ e $P_2$ a due distanze $r_1$ e $r_2$, vale che

    \[
    P_1\times r_1^2 = P_2\times r_2^2.
    \]

-   La formula è più utile risolvendo per $P_2$:

    \[
    P_2 = P_1\times\frac{r_1^2}{r_2^2}.
    \]

# Esempio

-   Una persona è seduta in prima fila a 3 m dal professore ($r_1 = 3\,\text{m}$)
-   Un’altra persona è seduta più dietro, a 9 metri dal professore ($r_2 = 9\,\text{m}$)
-   Se l’orecchio della prima persona riceve un suono di ampiezza $P_1$, la seconda persona riceve un suono di ampiezza
    \[
    P_2 = P_1\times\frac{r_1^2}{r_2^2}
    = P_1\times\frac{(3\,\text{m})^2}{(9\,\text{m})^2}
    = P_1\times\frac{9}{81} = \frac{P_1}{9}
    \]

# Intensità percepita

-   Possiamo concludere che se la distanza triplica, l’ampiezza si riduce di un fattore 9, ossia 3²

-   Questo vuol dire che la seconda persona percepisce la voce del professore 9 volte meno intensa?

-   (Potete fare la prova, se volete!)

# Legge di Weber-Fechner

-   No! Se così fosse, le aule universitarie dovrebbero essere fatte in modo che il professore stia al centro, e tutti gli studenti in cerchio attorno a lui

-   L’esperienza ci mostra che se parla un compagno in prima fila, non sentiamo la metà di quello che sente chi sta in seconda fila

-   Le percezioni sensoriali seguono la cosiddetta “[legge di Weber-Fechner](https://it.wikipedia.org/wiki/Legge_di_Weber-Fechner)”

# Il lavoro di Weber

-   [Ernst Weber](https://it.wikipedia.org/wiki/Ernst_Heinrich_Weber) (1795-1878) scoprì che la variazione di uno stimolo viene percepita in modo differente a seconda dell’intensità iniziale dello stimolo

-   Weber verificò che se a una persona che regge un peso si aggiunge un ulteriore peso, questa lo percepirà diversamente:

    -   Aggiungere 100 g ad un carico di 10 kg dà una percezione minima, quasi inavvertibile
    -   Ma aggiungere 100 g ad un carico di 200 g è invece chiaramente avvertibile!

# La conclusione di Fechner

-   [Gustav Fechner](https://it.wikipedia.org/wiki/Gustav_Theodor_Fechner) (1801-1887) descrisse matematicamente quanto aveva osservato Weber, e derivò la formula

    \[
    p = k \log S + C
    \]

    dove $p$ è la “percezione” (ciò che avvertono i miei sensi), $S$ è lo stimolo (il fenomeno fisico che raggiunge i miei sensi), e $k$ e $C$ costanti che non ci interessano qui.

-   Anche se la legge di Weber-Fechner si è poi rivelata non del tutto esatta, è stata molto importante storicamente per definire il “decibel”, e quindi dovremo capire il funzionamento di $\log$, la funzione “logaritmo”.

---

![](media/starred-sky.jpg)

# Magnitudini delle stelle

::: side-by-side

::: content

-   Come descritto da Tolomeo nel suo Almagesto (150 d.C.), nell’antichità si suddividevano le stelle in sei “classi di magnitudini”, a seconda della loro intensità
-   Le “stelle di prima magnitudine” erano quelle più brillanti, come Vega
-   Via via nella scala, le stelle apparivano sempre meno brillanti, fino alle “stelle di sesta magnitudine”, appena visibili

:::

::: media

![](media/tolomeo-almagesto.jpg)

:::
:::

# Magnitudini delle stelle

-   Con l’avvento della fotografia astronomica alla fine dell’Ottocento ci fu la possibilità di misurare effettivamente l’intensità luminosa delle stelle, e qui ci furono sorprese!

-   Sebbene i sei livelli sembrassero equispaziati all’occhio nudo, in realtà le differenze tra le intensità erano molto diverse!


# Differenze tra intensità

| Magnitudini | Differenza in intensità |
|:-----------:|------------------------:|
| 1 − 2       | 8415,1                  |
| 2 − 3       | 1333,7                  |
| 3 − 4       | 211,4                   |
| 4 − 5       | 33,5                    |
| 5 − 6       | 5,3                     |

(Le unità della colonna di destra sono arbitrarie)

Anche se le sei classi appaiono equispaziate, le intensità misurate dagli strumenti non lo sono affatto!

# Intensità

Le intensità di ciascuna classe, in unità di misura arbitrarie, sono le seguenti:

| Magnitudine | Intensità |
|-------------|----------:|
| 1           |   10000,0 |
| 2           |    1584,9 |
| 3           |     251,2 |
| 4           |      39,8 |
| 5           |       6,3 |
| 6           |       1,0 |

(Notate che la differenza tra la prima e l’ultima intensità è **enorme**!)

# Rapporti tra magnitudini

Il mistero viene svelato se calcoliamo i **rapporti** tra le magnitudini!

| Magnitudini | Differenza in intensità |
|:-----------:|------------------------:|
| 1 / 2       |                     6,3 |
| 2 / 3       |                     6,3 |
| 3 / 4       |                     6,3 |
| 4 / 5       |                     6,3 |
| 5 / 6       |                     6,3 |

# Potenze

-   Abbiamo visto che ogni magnitudine ha un’intensità che è più grande della successiva di un fattore 6,3. Ad esempio:

    \[
    I_3 = 6{,}3 \times I_4, \quad I_4 = 6{,}3 \times I_5.
    \]

-   Questo vuol dire che
    \[
    I_3 = 6{,}3^2 \times I_4,
    \]
    e che
    \[
    I_1 = 6{,}3^5\times I_6 = 10.000\times I_6.
    \]

# Potenze

-   In generale, per “salire” di $n$ livelli di magnitudine, bisogna moltiplicare le intensità per
    \[
    6{,}3^n
    \]

    In altre parole, usando una potenza si può conoscere l’intensità se cambia la magnitudine.

-   Questo spiega perché l’intensità della magnitudine 1 è così grande rispetto a quella della magnitudine 6: quando si usano le potenze, i numeri diventano rapidamente grandissimi!

-   Ma qual è l’operazione contraria? Ossia, se so di quanto cambia l’intensità (ad esempio, 1580), di quanto varia la magnitudine?

# I logaritmi

-   Un logaritmo è l’operazione inversa di un elevamento a potenza

-   La domanda: “a quanto devo elevare 6,3 per ottenere 1580?” ha come risposta la quantità
    \[
    \log_{6{,}3} 1580
    \]

    che vale circa 4. Infatti $6{,}3^4 = 1580$.

-   In generale, con $\log_a b$ si indica quel numero a cui bisogna elevare $a$ per ottenere $b$.

# Proprietà dei logaritmi

-   Abbiamo visto che con le potenze è facile arrivare a numeri grandissimi:

    \[
    6{,}3^5 = 10.000
    \]

    È facile rendersi conto di ciò se si usano le potenze di 10:

    \[
    10^{11} = 10\times 10\times \ldots \times 10 = 100.000.000.000
    \]

-   Con i logaritmi è l’opposto: anche se si parte da numeri grandissimi, i logaritmi sono di solito molto piccoli:

    \[
    \log_{10} 100.000.000.000 = 11.
    \]

# I logaritmi in base 10

-   I logaritmi in base 10 sono particolarmente facili da calcolare:

    \[
    \begin{aligned}
    \log_{10} 10 &= 1,\\
    \log_{10} 100 &= 2,\\
    \log_{10} 1000 &= 3,\\
    \log_{10} 10.000 &= 4,\\
    \log_{10} 100.000 &= 5\ldots\\
    \end{aligned}
    \]

-   In questi casi, il logaritmo è sempre **il numero di cifre del numero, meno uno**

# I logaritmi in base 10

-   E per i numeri che non sono così semplici come 100 o 10.000?

-   In questo caso i logaritmi ritornano un numero con la virgola:

    \[
    \log_{10} 32.359 = 4{,}51
    \]

    Questo perché $10^{4{,}51} = 32.359$: i matematici ci dicono che è possibile definire le potenze anche quando l’esponente ha la virgola

-   Il logaritmo uguale a 4,51 può essere interpretato così: “il numero di partenza aveva cinque cifre (4 + 1), ma era un po’ più grande di 10.000, che è il più piccolo numero a cinque cifre”.

---

TODO

Vedi “Pendolo: gravità che imita una molla” in fondo per una spiegazione di come introdurre l'intensità del suono come pressione², e dei decibel.

# Sovrapposizione e interferenza

# Sovrapposizione e interferenza

-   Abbiamo sempre parlato sinora di **una** onda sonora che si propaga. Ma nella realtà siamo sempre circondati da molti suoni!

-   Quando due onde si incontrano in un punto dello spazio, vale il principio di **sovrapposizione**: se alle onde non è associata “troppa energia”, i loro effetti si sommano

-   Questo è il **principio di sovrapposizione**, e vale non solo per le onde sonore

---

<video controls width="1080">
  <source src="media/veritasium-double-slit-experiment.mp4" type="video/mp4" />
  Your browser does not support the video tag.
</video>

<small>[The original double slit experiment](https://www.youtube.com/watch?v=Iuv6hY6zsd0)</small>

# Interferenza

-   La sovrapposizione è un **principio**: dice che due onde che si incontrano nel medesimo punto producono un’onda risultante data dalla somma delle due

-   L’**interferenza** è il risultato della sovrapposizione di più onde. Esso dà origine a fenomeni molto interessanti, perché a volte l’interferenza causa un *rinforzo* delle onde, ma altre volte può annullare il loro effetto!

-   Per fare un’analogia: suono tre tasti del pianoforte e sento un accordo consonante o dissonante. Il fatto che ci arrivi il suono insieme è dato dalla sovrapposizione, la consonanza/dissonanza dall’interferenza.


# Tipi di interferenza

-   Ci sono vari modi in cui si manifesta l’interferenza:

    -   Se tutte le volte che un onda causa un massimo di pressione, anche la seconda fa lo stesso, si ha **interferenza costruttiva**: l’effetto è amplificato

    -   Se invece quando la prima onda ha un massimo di pressione, la seconda ha un minimo, l’effetto è una **interferenza distruttiva**, in cui il suono è attenuato

    -   Se le due onde non hanno la stessa frequenza, l’interferenza è alternatamente costruttiva e distruttiva, e si hanno i **battimenti**

-   Tutti questi effetti si possono vedere nell’applicazione della slide successiva

---

<iframe src="iframes/interference.html" width="100%" height="760" style="border:1px solid #ccc; border-radius: 8px;"></iframe>

# Interferenza distruttiva

::: side-by-side

::: content

-   Le cuffie a cancellazione del rumore hanno un microfono che riceve il suono ambientale e lo riproduce indirizzandolo all’orecchio, ma con uno sfasamento di mezza lunghezza d’onda
-   Nell’orecchio entra quindi il <span style="color: #269342">suono ambientale</span>, più <span style="color: #932642">ciò che produce la cuffia</span>, ossia la musica e il suono ambientale “sfasato”:
    \[
    \begin{aligned}
    \text{Risultato} &= \cancel{\textcolor{#269342}{\text{Ambiente}}} + \textcolor{#932642}{\text{Musica}} - \cancel{\textcolor{#932642}{\text{Ambiente}}} = \\
    &= \textcolor{#932642}{\text{Musica}}
    \end{aligned}
    \]

:::

::: media

![](media/cuffie-cancellazione-rumore.webp){width=320px}

:::
:::


# Battimenti

![](media/battimenti.webp){height=600px}

# Battimenti

-   I battimenti sono un tipo di interferenza in cui le due onde non hanno la stessa frequenza; l’interferenza continua quindi ad alternarsi tra costruttiva e distruttiva

-   L’effetto è quello di un’onda la cui intensità cambia da un minimo ad un massimo, con una frequenza data da

    \[
    \nu_\text{battimento} = \left|\nu_1 - \nu_2\right|.
    \]

-   Sono molto utili per accordare tra loro strumenti: se si sentono battimenti quando suonano la stessa nota, non sono accordati!

# Il timbro

# Timbro del suono

-   Abbiamo visto l’interferenza tra due onde sonore, ma ovviamente si può sovrapporre qualsiasi numero!

-   Il motivo per cui due strumenti diversi come un violino e un flauto suonino “diversi” anche quando la nota è la stessa è dovuta proprio a questo

-   Il “colore” di un suono è detto **timbro**, e dipende dal fatto che gli strumenti non emettono mai semplici onde sinusoidali, ma sovrapposizioni di onde

---

TODO: esempio di suono dato dalla sovrapposizione di tre onde

# Scomposizione di Fourier

# Scomposizione di Fourier

::: side-by-side

::: content

-   Abbiamo visto che la sovrapposizione di un suono fondamentale e di armoniche fornisce il “timbro” di quel suono

-   Un matematico francese, [Jean-Baptiste Joseph Fourier](https://it.wikipedia.org/wiki/Jean_Baptiste_Joseph_Fourier) (1768–1830), dimostrò una proprietà fondamentale delle onde, non solo sonore: ogni fenomeno periodico può essere scomposto nella somma di oscillazioni sinusoidali

:::

::: media

![](media/fourier.jpg)

:::
:::

---

TODO: esempio di scomposizione di Fourier

# Esempi applicativi

-   Un equalizzatore acustico è in grado di modificare i suoni gravi, medi ed acuti decomponendo il suono e agendo sulle ampiezze di alcune frequenze e non altre, come vedremo tra poco

-   I file MP3 riescono a registrare musica usando 10 volte meno spazio dei vecchi CD, perché usano la decomposizione di Fourier per capire quali frequenze registrare (quelle udibili) e quali no

# Filtraggio

TODO

# Fenomeni spaziali

# L’eco

::: side-by-side

::: content
-   Il motivo per cui i pipistrelli “vedono” tramite le onde sonore è dovuto a un effetto di **eco**

-   Come vedremo meglio quando studieremo le onde stazionarie, un’onda di pressione che raggiunge un corpo solido viene riflessa

-   Il meccanismo è simile a quello della luce riflessa da uno specchio (l’analogia è pertinente, perché anche la luce è un’onda)
:::

::: media

![](media/reflection.svg)

:::
:::


# Esempio numerico

::: side-by-side

::: content

-   Se mi trovo a 1 km di distanza da una parete rocciosa in montagna e lancio un urlo verso di essa, il suono verrà riflesso dalla parete e tornerà verso di me

-   Il suono percorre 1 km verso la parete e 1 km per tornare, per un totale di 2 km. Assumendo una velocità di 340 m/s, si ottiene che l’eco mi raggiungerà dopo

    \[
    \frac{2.000\,\text{m}}{340\,\text{m/s}} = 5{,}9\,\text{s}
    \]

:::

::: media

![](media/eco.webp)

:::
:::

# Il riverbero

-   Il “riverbero” è il fenomeno per cui 


# L’ecografia


# Onde stazionarie

# Onde stazionarie

<video controls loop>
    <source src="media/standing-longitudinal-waves.mp4" type="video/mp4">
</video>

<small>[Longitudinal wave using slinky coil](https://www.youtube.com/watch?v=fMJrtheQfZw)</small>

# L’effetto Doppler

# L’effetto Doppler

Ecografia Doppler: https://it.wikipedia.org/wiki/Ecografia_Doppler

# Conclusioni

# Cosa sapere per l’esame

---
title: Fisica -- Lezione 7
subtitle: Ampiezza del suono e scale logaritmiche
author: Maurizio Tomasi ([`maurizio.tomasi@unimi.it`](mailto:maurizio.tomasi@unimi.it))
date: Martedì 18 novembre 2025
...
