---
layout: moneropedia
entry: "Address"
terms: ["address", "indirizzo", "indirizzi"]
summary: "o un alias, come donate.getmonero.org, or un set di 95 caratteri che inizia con un 4"
---

### Le basi

Quando invii dei Moneroj a qualcuno, hai bisogno solamente di un'informazione, e quest'informazione è il suo indirizzo Monero. Un indirizzo Monero *grezzo* è un set di 95 caratteri che inizia con un '4'. L'indirizzo per le donazioni alla comunità Monero, ad esempio, è <span class="long-term">44AFFq5kSiGBoZ4NMDwYtN18obc8AemS33DBLWs3H7otXft3XjrpDtQGv7SqSsaBYBb98uNbr2VBBEt7f2wfn3RVGQBEP3A</span>.

Dal momento che questi indirizzi sono lunghi e complessi, al loro posto incontrerai spesso degli indirizzi @OpenAlias. Ad esempio, le donazioni Monero possono essere inviate a <span class="long-term">donate@getmonero.org</span> o a <span class="long-term">donate.getmonero.org</span>.

Se vuoi ottenere un indirizzo @OpenAlias, puoi trovare ulteriori dettagli sulla [pagina di OpenAlias](/knowledge-base/openalias).

### Indirizzo integrato

Un indirizzo integrato è un indirizzo combinato con un @ID-Pagamento di 64 bit cifrato. Un indirizzo integrato grezzo è lungo 106 caratteri.

### Informazioni di dettaglio

L'indirizzo è proprio la concatenazione, in formato Base58, della [chiave di spesa](@spend-key) *pubblica* e la [chiave di visualizzazione](@view-key) *pubblica*, con prefisso il byte di rete (il numero 18 per Monero) e con suffisso i primi quattro byte dell'hash Keccac-256 dell'intera stringa (usata come checksum).
