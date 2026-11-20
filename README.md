# Code Lux

Scrivi un messaggio e la torcia del telefono lo lampeggia in codice Morse. Se la torcia non è disponibile lampeggia lo schermo; si possono aggiungere suono e vibrazione.

Funziona con Chrome su Android (serve il permesso alla fotocamera, usato solo per accendere il flash). Su iPhone di solito lampeggia lo schermo.

## A distanza
Un telefono può fare da **ricevitore**: preme «Avvia ricevitore» e trasmette da solo, uno dopo l'altro, i messaggi che arrivano sul suo canale. Chi apre il link del canale (`…/#c=nome-canale`, anche dal QR) può inviargli messaggi con «Invia al ricevitore».

I messaggi passano dal servizio gratuito [ntfy.sh](https://ntfy.sh) e restano lì al massimo 12 ore: chi conosce il nome del canale può leggerli e inviarne.

`qrcode.js` è [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) di Kazuhiko Arase (licenza MIT).
