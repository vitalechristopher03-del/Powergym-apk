POWER GYM - IMPORT FOTO CREA SCHEDA

Novità solo frontend Cloudflare:
- Caricando una foto della scheda, il sito prova a leggerla con OCR dal browser.
- Dopo la lettura crea automaticamente le righe della scheda.
- Per la scheda stile Olimpia/Team Marchello usa un template riconosciuto e crea Giorno A/B/C/D.
- Legge scadenza 'cambio' e prova a inserirla nel campo scadenza scheda.
- Se riconosce il nome cliente, lo inserisce nelle note e prova a selezionare il cliente esistente.
- Nessuna modifica a Manus, database o API.

Nota: serve connessione internet per caricare Tesseract.js dal CDN. Se l'OCR sbaglia, correggi il testo e premi Importa righe.
