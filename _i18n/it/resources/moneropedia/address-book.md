---
layout: moneropedia
entry: "Address Book"
tags: ["kovri"]
terms: ["rubrica", "rubrica indirizzi"]
summary: "Ti consente di visitare siti/servizi I2P di dominio .i2p"
---

### Le basi

Per poter visitare siti o usufruire di servizi @I2P con @Kovri, hai bisogno di una rubrica indirizzi. Una rubrica indirizzi ti consente di tradurre siti/servizi @I2P che utilizzano `.i2p` come [dominio di primo livello](https://it.wikipedia.org/wiki/Dominio_di_primo_livello) in un indirizzo che la rete @I2P possa riconoscere.

Senza una rubrica indirizzi saresti costretto/a ad utilizzare un [indirizzo base32](@base32-address) tutte le volte che vuoi visitare un sito o usufruire di un servizio @I2P - e non è proprio il massimo!

### Informazioni di dettaglio

Dal momento che non esistono [DNS](https://it.wikipedia.org/wiki/Domain_Name_System) sulla rete @I2P, neanche @Kovri utilizza DNS o alcun tipo di risoluzione di [host canonicamente unici](@canonically-unique-host). Al loro posto, @Kovri associa un [host localmente unico](@locally-unique-host) ad una @destinazione [indirizzo base64](@base64-address) in una @sottoscrizione. Una volta che sulla tua rubrica indirizzi viene registrata la @sottoscrizione, puoi risolvere il tuo sito con dominio `.i2p` preferito con una destinazione @I2P usabile.

### Creare una rubrica indirizzi

Di default, la tua installazione contiene una @sottoscrizione pubblica di default chiamata `hosts.txt` nel tua [directory dati](@data-directory). Quando @Kovri si avvia, carica questa sottoscrizione e preleva ogni altra sottoscrizione da te specificata. Una volta caricate le sottoscrizioni, la tua rubrica viene coerentemente popolata. Per conoscere maggiori dettagli su come getire le sottoscrizioni, vedi [qui](@sottoscrizione).

### Aggiornare la rubrica indirizzi

Attualmente esistono diversi modi per aggiornare la tua rubrica indirizzi:

1. Usa un @jump-service per inserire gli indirizzi I2P all'interno della tua rubrica indirizzi
2. Usa un @jump-service per copiare/incollare un indirizzo nella tua @sottoscrizione privata
3. Aggiungi/rimuovi manualmente elementi alla/dalla @sottoscrizione privata

**Nota: Kovri è in una fase di sviluppo non ancora avanzata. Nel futuro *esisteranno* modi più semplici per aggiornare la rubrica indirizzi**

### Rubrica indirizzi / Specifiche sul naming

Per dettagli sulle specifiche, visita la pagina [Nominativi e Rubrica](https://geti2p.net/it/docs/naming)
