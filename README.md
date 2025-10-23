
# UbuntuWear – Mockup e-commerce (HTML/CSS/JS)

Questo pacchetto contiene:
- `index.html` – homepage con sezioni, dark-mode, header con effetto scroll, pagina “Le Sarte” con filtri e lightbox.
- `shop.html` – pagina Shop con filtri (tessuto, area, sarta), ordinamento e impaginazione (client-side).
- `product.html` – pagina Prodotto con varianti (colore, quantità) e galleria (lightbox condivisa).
- `assets/sarte/*.jpg` – segnaposto locali per ritratti delle sarte (SVG salvati come .jpg).
- `assets/products/*.jpg` – segnaposto locali per foto prodotto.

## Come usare
Apri `index.html` in un browser. I link nel menu portano a `shop.html` e alle sezioni interne. Per vedere la pagina prodotto, usa il pulsante “Vedi” nelle card dello shop.

## Sostituzione immagini
Sostituisci i file in `assets/sarte/` e `assets/products/` con le foto reali (reportage). Mantieni gli stessi nomi file per non dover modificare il codice.

## Licenze e diritti di immagine
Le immagini dei segnaposto sono generate e libere. Per immagini reali (ritratti), assicurati di avere i diritti di utilizzo (consenso dei soggetti + licenza compatibile).

## Personalizzazioni rapide
- Colori brand: modifica le variabili CSS in `:root` (`--brand`, `--accent`).  
- Testi/CTA: cerca le classi `.headline`, `.subhead`, `.button` nei file HTML.  
- Prodotti e impaginazione: cambia `PER_PAGE` e l’array `PRODUCTS` in `shop.html`.
