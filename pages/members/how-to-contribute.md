---
title: ARI@CH - Come contribuire al sito
layout: page
---

# Come aggiungere materiale al sito web dell'Associazione

Qui di seguito troverete le istruzioni per contribnuire allo sviluppo del sito della nostra Associazione.

Potrete creare pagine, news, il vostro profilo di soci, e qualsiasi altra parte del sito, in modo collaborativo.


Il sito dell'Associazione e' ospitato sulla piattaforma GitHub. GitHub non e' un sistema di web authoring come, per esempio, WordPress, ma un sito su cui ospitare codice sorgente. GitHub viene usato per ospitare il codice della maggior parte dei progetti software Open Source.

## Step 0 - Creazione account GitHub

Potete creare un vostro account GitHub accedendo al sito: [GitHub](http://www.github.com)

## Step 1 - Fai una tua copia del sito

A questo punto, per modificare il contenuto del sito, dovete fare una copia dei file che lo compongono. Per accedere ai file del sito e fare una copia, aprite questa pagina:

[github.com/ricercatoritaliani/ricercatoritaliani.github.io](https://github.com/ricercatoritaliani/ricercatoritaliani.github.io)

Quello che vedete sulla pagina appena aperta non è la struttura finale delle pagine del sito, ma quella dei file che compongono le pagine prima della generazione del codice HTML che comporrà poi le pagine che verrano visualizzate sul sito.

Per iniziare a editare il sito, dovete andare sulla pagina iniziale del progetto:

[github.com/ricercatoritaliani/ricercatoritaliani.github.io](https://github.com/ricercatoritaliani/ricercatoritaliani.github.io)

<img alt="screenshot 1" align="center" width="450" hspace="20" src="/assets/img/pages/how-to/screenshot1.png">

e cliccate sull'icona "fork" che trovate in alto a destra:

<img alt="screen shot 2" align="center" width="450" hspace="20" src="/assets/img/pages/how-to/screenshot2.png">

Il processo di copia ha inizio: vedrete una piccola animazione stile "fotocopiatrice".

A quel punto avrai una copia esatta del sito sul tuo account, che potrai modificare a piacere, e con cui potrai sperimentare le tue modfiche, senza paura di intaccare la versione ufficiale del sito.

La versione che viene pubblicata online, infatti, e' solo quella "ufficiale" ospitata sulla pagina principale dell'account dell'Associazione (e gestita dal Media Manager dell'Associazione).

Adesso siete pronti per modificare il sito e aggiungere materiale. Di seguito troverete una serie di "ricette" per i task piu' comuni.
Se invece siete esperti in web development, e volete solo sapere quali tool compongono il sito, andate direttamente alla nota tecnica.


# Step 3 - Aggiungere materiale al sito

## La sintassi

La maggior parte dei file che contengono il contenuto del sito utilizza il formato "Markdown" e finiscono con una estensione di tipo "`.md`": in pratica sono dei semplici file di testo, con dei simboli che identificano i settaggi di stile o i link. (Un esempio e' la nostra [homepage](https://raw.githubusercontent.com/ricercatoritaliani/ricercatoritaliani.github.io/master/index.md))

Markdown è un linguaggio _markup_ semplice, molto usato sul web: suona complicato ma e' piiu' facile usarlo che spiegarlo e potete trovare una introduzione qui:

[https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)

## Aggiungere il mio profilo

[...]

## Aggiungere una nuova "Attività" con i dettagli di un evento

[...]

## Aggiungere una nuova "News" per annunciare un evento o una notizia

[...]


## Modificare la home page

La home page ospita soprattutto materiale che non ha bisogno di molti update (anche detto _"evergreen"_): una breve descrizione dell'Associazione con link alla pagina "Chi Siamo" e una lista delle "News".

Nota, la lista delle "News" e' generata in modo automatico. Vedi ??? se vuoi aggiungere una news.

Se trovi errori di battitura sulla home page o vuoi migliorare il testo, allora devi modificare il seguente file:

[https://github.com/ricercatoritaliani/ricercatoritaliani.github.io/blob/master/index.md](https://github.com/ricercatoritaliani/ricercatoritaliani.github.io/blob/master/index.md)

Per modificarla, prendi la copia nel tuo account GitHub e clicca sull'icona della penna ("Edit this file") in alto a destra.

Adesso puoi modificare il testo.
La pagina e' scritta in Markdown, vedi [la sezione al riguardo](#la-sintassi).

Una volta modificato il testo, vai in basso, inserisci un commento sulle modifiche fatte, e clicca su "Commit changes".


## Come pubblicare on-line le mie modifiche

Una volta che hai modificato tutte le cose che vuoi modificare, torni alla pagina principale del sito (nella tua copia) e clicchi sul pulsante "New pull request". A quel punto il Media Manager dell'Associazione riceverà una notifica.

Una volta controllate le tue modifiche e verificato che il sito funzioni ancora senza problemi, il Media Manager passerà le tue modifiche nel repository del sito da cui viene generato il sito pubblicato on-line.

A quel punto, le tue modifiche saranno visibili sul sito ufficiale nel giro di un paio di minuti.

**Cogratulazioni! E grazie per aver contribuito a espandere e migliorare il sito della nostra Associazione!**


## Nota tecnica

Il sito e' costruito usando [Jekyll](https://jekyllrb.com/), usando una versione customizzata del theme [Cayman](https://github.com/pietromenna/jekyll-cayman-theme).

I posts sono divisi in diverse categories: per adesso, "activity", "news" e "members". Le "news" vengono elencate nella home page (e forse in futuro in una sidebar), le "activity" sono elencate nella pagina "Attività" (pages/activities/index.md), i post "member" vengono usati per ospitare i profili personali dei soci e vengono elencati nella pagina "Soci" (pages/members/index.md).

## Se avete problemi

Se avete problemi, potete scrivere al [web.ari.ch@gmail.com](Media Manager dell'Associazione).
