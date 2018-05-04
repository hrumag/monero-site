---
layout: moneropedia
entry: "Base32 address"
tags: ["kovri"]
terms: ["Base32-address", "Base32-addresses"]
summary: "Hash codificato in Base32 di un indirizzo Base64"
---

### Le basi

Un indirizzo Base32 è una versione accorciata e codificata di un indirizzo @I2P. L'indirizzo Base32 è la prima parte in un hostname `.b32.i2p`.

Esempio:

`i35yftyyb22xhcvghmev46t5knefur5v66qzekkajatwfwhyklvq.b32.i2p`

dove

`i35yftyyb22xhcvghmev46t5knefur5v66qzekkajatwfwhyklvq` è l'indirizzo Base32.

### Informazioni di dettaglio

In sostanza un indirizzo Base32 è una rappresentazione di 52 caratteri [codificata Base32](https://en.wikipedia.org/wiki/Base32) dell'hash completo SHA-256 di un [indirizzo Base64](@base64-address) @I2P.

### Note

**Nota: `.b32` non è un sottodominio di `.i2p`**
