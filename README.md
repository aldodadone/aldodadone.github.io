# aldodadone.github.io

Il sito personale di Aldo Dadone, formatore e grafico a Roma.

**Online:** [aldodadone.github.io](https://aldodadone.github.io/)

## Com'è fatto

Un sito statico, senza programmi da installare né servizi esterni: niente cookie, niente sistemi di tracciamento, caratteri inclusi nel sito.

| Percorso | Contenuto |
|---|---|
| `index.html` | Home |
| `en/` | La versione inglese, con gli stessi nomi di file |
| `formazione.html`, `grafica.html`, `progetti.html`, `consulenza.html`, `contatti.html` | Le altre pagine |
| `css/style.css` | Lo stile, basato sul design system «Cerchi caldi» |
| `fonts/` | Fredoka e Nunito (licenza SIL Open Font) |
| `img/` | Foto, lavori del portfolio e immagine di anteprima per i link condivisi |

## Come si pubblica

In *Settings → Pages* la voce *Source* è *Deploy from a branch*, ramo `main`, cartella `/ (root)`. Il repository si chiama `aldodadone.github.io`, così il sito risponde all'indirizzo principale.

## Come si aggiorna

Per cambiare un testo: apri la pagina nel repository, premi la matita, modifica e conferma con *Commit changes*. Il sito si aggiorna in un paio di minuti.

Per sostituire un'immagine: carica in `img/` un file con lo stesso nome.

## Crediti

La mappa dell'Unione europea nella pagina Progetti è adattata da [MapSVG](https://mapsvg.com/) (pacchetto `@svg-maps/world`), con licenza [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.it): i 27 paesi sono stati uniti in un'unica forma e i contorni leggermente smussati.
