<aside>
📚 esercizio di oggi: **Landing Page Product**
nome repo: ****`landing-page-product`
****
Vogliamo creare una *landing page* del nostro prodotto preferito 👩🏻‍💻.
Una Landing Page (o pagina di atterraggio) di un prodotto è una pagina web specificamente progettata per promuovere un prodotto o un servizio e convertire i visitatori in clienti. Questa pagina è spesso utilizzata come punto di arrivo per campagne di marketing online, come annunci pubblicitari, email marketing, social media e altri canali di marketing digitale.

🎯 **Obiettivo**

Segui le indicazioni del *designer* per riprodurre il layout del prototipo che ti è stato fornito (`prototype.pdf`). Il prototipo è un file pdf ad alta risoluzione quindi potete fare zoom e leggere i dettagli. Ci sono le indicazioni da sinistra verso destra su come realizzare la versione mobile e desktop della stessa pagina unica (Landing Page), trovate la sequenza di quello che deve essere mostrato a schermo come se stesse navigando con il dito o con il mouse dall’alto verso il basso. Ci sono inoltre le indicazioni per i colori e la tipografia.

Nella stessa cartella ci sono anche le icone (SVG) e due gruppi di testi (Recensioni e FAQs), il resto va estrapolato dal prototipo, così come la disposizione delle icone e le funzionalità avanzate come il menu su mobile e lo slider delle recensioni

### Milestone

1️⃣ **Milestone 1 (Struttura HTML & CSS)**

Inizia individuando le macroaree del layout e identificando le aree simili per poter riutilizzare il codice, garantendo una struttura HTML semplice e semantica. Passa poi al CSS, riproducendo fedelmente il layout assegnato per posizionare gli elementi affiancati. Crea classi riutilizzabili per mantenere il codice ordinato e ridurre la duplicazione. Infine, assicurati che il codice CSS sia pulito e facile da mantenere per facilitare eventuali aggiornamenti futuri.

2️⃣ **Milestone 2 (Contenuto)**

Una volta realizzata la base, passa all'inserimento del contenuto seguendo fedelmente le istruzioni del `prototype.pdf`

3️⃣ **Milestone 3 (Interattività)**

Aggiungi interattività alla pagina utilizzando JavaScript. In particolare, implementa la funzionalità di apertura e chiusura del menù mobile, la sezione FAQs e lo slider delle recensioni (se vuoi, prova ad usare la libreria **Swiper** per creare uno slider con le recensioni del prodotto).

🌟 **Bonus (Email)**

Lo scopo principale di una landing page è quello di catturare i contatti dei visitatori, quindi nel nostro caso bisognerebbe far funzionare il form di iscrizione alla newsletter, provaci.

</aside>

/*SOLUZIONE PROPOSTA*/

NB: per aiutarmi nell'impaginazioe utilizzarò Bootstrap 5.3

MILESTONE 1

1 - Procedo con delle aree con "rettangoli colorati" per farmi un idea di quanto spazio si dovrà occupare. Inseirò alcune delle immagini fornitomi sempre per una questione di progettazione delle macroaree
2 - provo impostare fin da esso le media query necessarie, dal momento che è stato specificato che questo esercizio dovrebbe essere impostato per "mobile first"
3 - per realizzare la sezione rubber duck debbunings ho inserito fin da subito le immagini fornite, sempre per un discorso di impaginazione.
3.1 - trovandomi in difficoltà ho commentato il codice precedente e utilizzato al suo posto un paio di div colorati per realizzare un impaginazione fedele all'immagine di mockup
3.2 - dopo un controllo ho notato che l'altezza del div bg-banner era anomala, ergo ho inserito più altezze fisse così che quest div si adatti a diversa media queries
4 - imposto la sezione della perfomance inserendo con degli div h2 e p. Dato che sono ancora nella Milestone 1 completerò il lavoro in quella successiva.
5 - creo la sezione dei testimonials. Ma prima delle recensioni vere e proprire inserisco un titolo che che le presenti
5.1 - inserico il codice fornitomi per le icone all'inizio del body
6 - avendo concluso l'impostazione della prima recensione, lascio questa sezione in questo stato finché non passerò all'esecuzione della milestone 3
    NB: ho scritto "proof copy" nel titolo del commit perché non conosco il termine giusto per "bozza" nel linguaggio da web developer