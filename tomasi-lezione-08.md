# Introduzione all’argomento di oggi

-   Useremo potenze e logaritmi per definire il “decibel”, con cui si misura l’intensità del suono

-   Introdurremo i concetti di “sovrapposizione” ed “interferenza”

# Inquisitori accademici onorari

# Avete fatto gli esercizi?

![](media/uncle-sam.webp){height=560px}

# Proprietà delle potenze

-   La settimana scorsa avevamo visto queste due proprietà delle potenze:

    \[
    10^n \times 10^m = 10^{n + m},\qquad \frac{10^n}{10^m} = 10^{n - m},
    \]

    che valgono anche se $n$ e $m$ sono numeri negativi o con la virgola

-   Abbiamo anche visto che è sempre possibile scrivere un numero positivo $n$ come potenza di 10, se si usa come esponente il numero

    \[
    \log_{10} n
    \]

# Importanza dei logaritmi

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

# Lunghezza d’onda

::: side-by-side

::: content

-   La **lunghezza d’onda**, che si indica con la lettera λ (“lambda”), rappresenta la distanza fisica tra un picco di pressione e il successivo (la “semilunghezza” è la metà della lunghezza d’onda)

-   Essendo una distanza, λ si misura in metri

-   Si può trovare λ dalla relazione (intuitiva: provate a pensarci!)

    \[
    v_\text{suono} = \lambda \times \nu \quad\Rightarrow\quad \lambda = \frac{v_\text{suono}}{\nu}.
    \]

:::

::: media

![](media/longitudinal-sound-wave.webp)

:::
:::

# Esempi

-   Un suono basso a 20 Hz ha una lunghezza d’onda uguale a
    \[
    \lambda = \frac{343\,\text{m/s}}{20\,\text{s}^{-1}} \approx 17\,\text{m}
    \]

-   Il suono di un diapason a 440 Hz ha una lunghezza d’onda uguale a
    \[
    \lambda = \frac{343\,\text{m/s}}{440\,\text{s}^{-1}} \approx 78\,\text{cm}
    \]


# Interferenza e λ

::: side-by-side

::: content

-   Se riproduco il medesimo suono da due altoparlanti che sono a una distanza diversa dal mio orecchio, si avrà interferenza

-   Se la distanza del più lontano è maggiore di un numero intero di lunghezze d’onda λ (2λ, 3λ, 4λ, 5λ…), l’interferenza sarà costruttiva

-   Ma se è invece maggiore di un numero dispari di semi-lunghezze d’onda λ (λ/2, 3λ/2, 5λ/2, 7λ/2…), l’interferenza sarà distruttiva

:::

::: media

![](media/interference-wavelength.png)

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

# Suono e rumore

# Suono e rumore

-   Nella vita quotidiana, usiamo spesso le parole “suono” e “rumore” per parlare di fenomeni acustici

-   Ma sappiamo qual è la differenza tra i due? In particolare, stiamo parlando di un fenomeno fisico oggettivo, o della **sensazione** che un certo fenomeno fisico (quale?) ci provoca?


# Rumore e suono

-   La differenza tra suono e rumore è la seguente:

    -   Il **suono** è la sensazione di un’onda sonora regolare, che possiede una sua periodicità

    -   Il **rumore** è l’esatto opposto: è la sensazione di un’onda sonora priva di periodicità

-   Per rappresentare il suono che raggiunge un punto dello spazio (dove ad esempio c’è un microfono), si usa spesso un grafico che mostra la variazione temporale della pressione/oscillazione meccanica

-   Vediamo subito la differenza con un esempio interattivo, che spiegheremo meglio in questa e nelle prossime lezioni

---

<iframe src="iframes/sound-example.html" width="100%" height="580px" style="border:1px solid #ccc; border-radius: 8px;"></iframe>

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

-   Il “riverbero” è il fenomeno per cui l’eco raggiunge il nostro orecchio quando il suono che l’ha originato è ancora percepito dal nostro orecchio


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
title: Fisica -- Lezione 8
subtitle: L’effetto Doppler
author: Maurizio Tomasi ([`maurizio.tomasi@unimi.it`](mailto:maurizio.tomasi@unimi.it))
date: Martedì 25 novembre 2025
...
