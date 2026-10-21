# Gas Sales Energia – Pagina AR

Esperienza in Realtà Aumentata (MindAR + A-Frame) per la pagina pubblicitaria "Il tuo punto fermo in un mondo in movimento".

## Pubblicazione su GitHub Pages
1. Crea un nuovo repository su GitHub (es. `gassales-ar`), **pubblico**.
2. Carica **tutto il contenuto** di questa cartella (index.html, .nojekyll, cartelle `assets/` e `libs/`) nella radice del repository.
3. Settings → Pages → Source: *Deploy from a branch* → Branch `main` / `(root)` → Save.
4. Dopo 1-2 minuti la pagina è online su `https://TUO-UTENTE.github.io/gassales-ar/`.
5. Genera il QR code con quell'indirizzo (HTTPS obbligatorio per la fotocamera: GitHub Pages lo fornisce già).

## Prova
- Telefono: apri il link → "Avvia AR" → consenti la fotocamera → inquadra tutta la pagina.
- PC senza fotocamera: aggiungi `?preview` all'indirizzo per vedere l'anteprima 3D (trascina per ruotare).

## Contenuti AR e link
| Elemento | Link |
|---|---|
| Logo Gas Sales Energia | https://www.gassalesenergia.it/ |
| Luce | https://www.gassalesenergia.it/offerte-luce/ |
| Gas | https://www.gassalesenergia.it/offerte-gas/ |
| Efficienza energetica | https://www.gassalesenergia.it/selosopagomeno/ |
| Sostenibilità | https://www.gassalesenergia.it/sostenibilita/ |
| Gas Sales Bluenergy (volley) | https://www.gassalespiacenza.it/ |
| Sportelli (sopra il QR) | https://www.gassalesenergia.it/sportelli/ |

Palazzo Gotico 3D (`gotico.glb`, compressione Draco) sopra la foto del palazzo; globo che ruota (`terra.mp4`, con riserva `terra.webm`) sul cerchio blu con la scritta sopra; linee luminose animate dal globo ai loghi.

## Modifiche rapide
Posizioni, dimensioni e link sono nel blocco CONFIGURAZIONE all'inizio dello script in `index.html` (coordinate in pixel della foto target 1102×1880).
Se cambi la grafica della pagina stampata, ricompila `assets/targets.mind` con il MindAR Image Targets Compiler.

## Note iOS / Android
- iPhone: usare Safari (iOS 14.3+). Android: Chrome.
- Nei browser interni di Instagram/Facebook/WhatsApp la fotocamera può essere bloccata: la pagina mostra un avviso per aprirla in Safari/Chrome.
- Le librerie sono incluse in `libs/` (nessuna dipendenza da CDN esterni).
