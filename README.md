# E-commerce 
![image](https://github.com/user-attachments/assets/6ffe01f6-4ee3-4823-9f1e-62269a44d31a)

Le tecnologie utilizzate in questo E-commerce sono: 

HTML: Struttura di base della pagina web, includendo una tabella per visualizzare i prodotti (ricambi per stampanti), un'area per il carrello, e una sezione per il video. L'HTML include anche input e bottoni per interagire con il carrello.

CSS: Stile e design per la pagina, che usa il framework Materialize per una grafica responsive e moderna. Viene utilizzato anche uno sfondo personalizzato e uno stile per la tabella, i bottoni, e gli altri elementi.

JavaScript:

Gestione dei prodotti: Due classi, prodotto e prodottoC, sono usate per definire i prodotti e gli oggetti che vengono aggiunti al carrello.
Funzionalità di carrello: I prodotti vengono aggiunti al carrello tramite input numerici per la quantità, e il carrello si aggiorna in tempo reale. Viene calcolato anche il totale da pagare.
EmailJS: Il codice integra EmailJS per inviare una email con i dettagli del carrello a un indirizzo di destinazione (è necessario configurare EmailJS per questo).
Tabella dei prodotti: Una funzione popolata con un array di prodotti simula una lista di ricambi per stampanti. Ogni prodotto ha un nome, una marca, un identificativo, un prezzo e un'immagine.
Funzionalità interattive:

Aggiunta di un prodotto al carrello tramite un bottone.
Possibilità di rimuovere prodotti dal carrello.
Calcolo e visualizzazione del totale da pagare nel carrello.
Invio via email dei dettagli del carrello tramite un modulo di contatto.
