POWER GYM - FIX PNG APK

Correzioni lato sito:
- Anteprima PNG ora si apre dentro il sito, non come immagine grezza.
- Aggiunto pulsante Torna indietro in alto a sinistra nella schermata PNG.
- Scarica PNG ora usa più fallback: File System Access, bridge Android opzionale, data URL/download, apertura immagine.
- Condividi PNG resta disponibile ed è consigliato su APK.

Nota APK importante:
Se nell'APK il pulsante Scarica PNG non salva ancora, Manus deve aggiungere nel progetto Android WebView un DownloadListener e/o un bridge JavaScript:
window.Android.downloadBase64Image(dataUrl, filename)
che salva il file PNG nella cartella Download o Galleria.
