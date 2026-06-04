POWER GYM - JWT PULITO

Correzioni:
- Il selettore esercizi non dipende più da clientApp.getExercises.
- Le immagini esercizi vengono prese dai file locali del sito.
- Ogni cliente ha il pulsante "Crea scheda".
- Dopo il salvataggio scheda, puoi copiare il messaggio da inviare al cliente.
- L'area cliente usa gli esercizi locali per mostrare immagini e nomi.
- Il backend Manus serve solo per login admin, clienti e salvataggio schede.

Nota:
Se la creazione cliente dà ancora errore, il problema è nell'endpoint adminToken.clients.create del backend.
