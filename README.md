# UNISCI PDF

**Unisci PDF direttamente sul tuo computer. Gratis, privato, senza upload.**

PDF Privati è una piccola applicazione web gratuita per unire due o più file PDF in un unico documento.

Funziona direttamente nel browser: i PDF vengono elaborati sul computer dell’utente e non vengono caricati su alcun server.

## Caratteristiche

- Servizio completamente gratuito
- Nessuna registrazione richiesta
- Nessun upload dei file su server
- Elaborazione direttamente sul computer dell’utente
- Possibilità di aggiungere PDF anche uno alla volta
- Ordinamento dei file prima dell’unione
- Rimozione dei file selezionati
- Download automatico del PDF finale
- Interfaccia responsive per desktop, tablet e smartphone

## Come funziona

1. Seleziona uno o più file PDF.
2. Aggiungi altri PDF anche in un secondo momento.
3. Ordina i PDF usando i pulsanti **Su**, **Giù**, **Primo** e **Ultimo**.
4. Rimuovi eventuali file non necessari.
5. Clicca su **Unisci PDF**.
6. Scarica il PDF finale generato.

Tutto avviene localmente nel browser.  
I file non vengono inviati, salvati o analizzati da alcun server.

## Privacy

Questo progetto è pensato per proteggere la privacy dell’utente.

I PDF vengono elaborati direttamente sul computer dell’utente. Questo significa che:

- i file non vengono caricati su server;
- i contenuti dei PDF restano privati;
- non è necessario creare un account;
- non viene eseguita alcuna elaborazione lato server.

Messaggio consigliato da mostrare nella pagina:

```text
I PDF vengono elaborati sul tuo computer: file privati, nessun upload.
```

## Gratuità del servizio

Il progetto è totalmente gratuito.

## Tecnologie utilizzate

Il progetto usa solo tecnologie front-end:

- HTML
- CSS
- JavaScript
- pdf-lib

La libreria `pdf-lib` viene caricata tramite CDN:

```html
<script src="https://unpkg.com/pdf-lib/dist/pdf-lib.min.js"></script>
```

## Struttura del progetto

La struttura minima consigliata è:

```text
pdf-privati/
├── index.html
└── README.md
```

Il file principale della pagina deve chiamarsi:

```text
index.html
```
