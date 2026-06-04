POWER GYM - FIX CARICAMENTO AREA CLIENTE

Correzione:
- Aggiunto timeout alle chiamate backend Manus.
- Se clientApp.getWorkout non risponde, non resta più bloccato su "Caricamento".
- Mostra un messaggio chiaro e pulsante Riprova.

Se compare "Il backend non risponde", Manus deve controllare clientApp.getWorkout per quel clientId.
