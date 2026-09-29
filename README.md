# TripRotarVisor — La Venezia del Nord

Sito vetrina statico in **HTML e CSS** per la promozione turistica di
**San Pietroburgo**, realizzato come esercitazione scolastica.

Il sito presenta la città, le sue attrazioni principali, gli eventi, dove dormire
e mangiare e i contatti dell'ente turistico (fittizio).

- **Sito online:** https://eliseyrotar.github.io/TripRotarVisor/
- **Argomento:** ente di promozione turistica — San Pietroburgo
- **Gruppo 5, classe 5BI, ITIS Marconi:** Abbiati Andrea, Varisco Nicolò, Rotar Elisey

## Pagine del sito

| File | Pagina | Contenuto |
|---|---|---|
| `index.html` | Home | Presentazione della città: fondazione, centro UNESCO, musei |
| `attrazioni.html` | Attrazioni | Ermitage, Peterhof, Fortezza di Pietro e Paolo, Teatro Mariinskij |
| `ermitage.html` | Museo dell'Ermitage | Storia, edifici, cosa vedere |
| `peterhof.html` | Peterhof e i palazzi | Grande Cascata, palazzi, consigli sulle fontane |
| `chiesa.html` | Chiesa del Salvatore | Storia, architettura, i mosaici |
| `eventi.html` | Eventi | Notti Bianche, Festival delle Stelle, Vele Scarlatte, Maslenica |
| `dormire_e_mangiare.html` | Dove dormire e mangiare | Hotel e piatti tipici (borsch, pelmeni, blini) |
| `contatti.html` | Contatti | Ufficio turistico, orari, il gruppo |

Tutte le pagine condividono lo stesso layout e sono collegate tra loro tramite
il menu orizzontale (5 voci) e il sottomenu laterale (3 voci). La voce del menu
della pagina corrente è evidenziata in oro.

## Layout

Il layout segue la consegna in `Layout_homepage.pdf`:

```
+--------------------------------------------------+
| Logo o nome del sito (TripRotarVisor)            |
+--------------------------------------------------+
| Menu orizzontale (5 pulsanti)                    |
+--------------------------------------------------+
| Sottomenu | Immagine                             |
| (sinistra)|                                      |
|           +--------------------------------------+
|           | Descrizione della pagina             |
+-----------+--------------------------------------+
| Footer (gruppo, classe, anno, email)             |
+--------------------------------------------------+
```

Regole tecniche rispettate:

- affiancamento dei contenitori solo con la proprietà CSS `float`
- larghezze dei contenitori in percentuale (`#sottomenu` 33%, colonna destra 64%)
- misure di font e spaziature in pixel
- nessun JavaScript, solo HTML e CSS statici
- un solo foglio di stile (`style.css`) condiviso da tutte le pagine

## Colori e font

Palette definita con variabili CSS in `:root` dentro `style.css`:

| Ruolo | Nome | HEX |
|---|---|---|
| Principale | Navy | `#0B2A5B` |
| Navy scuro | Notte | `#06183A` |
| Accento | Oro | `#C8992F` |
| Oro per testo | Oro scuro | `#8A6410` |
| Sfondo pagina | Crema | `#FAF7F0` |
| Sfondo box | Azzurro chiaro | `#E8EDF5` |
| Testo | Inchiostro | `#1C2333` |
| Chiaro | Bianco | `#FFFFFF` |

Font di sistema in stile GitHub (stack Primer, sui PC Windows si vede Segoe UI):

```css
font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
    "Noto Sans", Helvetica, Arial, sans-serif;
```

## Immagini

Tutte le fotografie sono libere (pubblico dominio) da Wikimedia Commons:

- `panorama_neva.jpg` — panorama della Neva con i ponti (home)
- `ermitage.jpg` — scalinata del Nuovo Ermitage
- `peterhof.jpg` — la Grande Cascata
- `chiesa.jpg` — le cupole viste dal canale
- `attrazioni.jpg` — Fortezza di Pietro e Paolo
- `eventi.jpg` — Prospettiva Nevskij di notte
- `dormire.jpg` — Prospettiva Nevskij di giorno
- `contatti.jpg` — fiume Moika e canale Griboedov
- `borsch.jpg`, `pelmeni.jpg`, `blini.jpg` — i piatti tipici
- `logo.png` — logo del sito
- `favicon.ico` — icona del sito ricavata dallo stemma del logo (16, 32 e 48 px)

## Come vedere il sito

Il sito è pubblicato con GitHub Pages e si apre da qualsiasi browser
all'indirizzo https://eliseyrotar.github.io/TripRotarVisor/ senza installare nulla.

In alternativa si può scaricare questa repository e aprire `index.html`
in locale: funziona anche senza connessione, a parte le mappe se aggiunte.

## Note

Telefono ed email sono inventati per l'esercitazione. Gli hotel e i ristoranti
citati nella pagina "Dove dormire e mangiare" esistono davvero e i loro nomi
linkano ai siti ufficiali. L'ufficio turistico TripRotarVisor non esiste.
