# BenjaminShop - Sistema di Testing

## Descrizione
BenjaminShop è un progetto realizzato come parte del compito per la materia **TEP** (Tecnologie e Programmazione). Questo sistema di e-commerce include una simulazione di carrello e prodotto, con funzionalità di aggiunta, rimozione e calcolo del totale. Inoltre, il progetto include test avanzati realizzati con **Mocha** e **Chai** per assicurare il corretto funzionamento delle funzionalità.

### Funzionalità
- **Prodotto**: Creazione di oggetti `Prodotto` con validazioni su prezzo e applicazione di sconto.
- **Carrello**: Un oggetto `Carrello` che permette l'aggiunta di prodotti, il calcolo del totale, e l'applicazione di sconto globale.
- **Testing**: Test automatici usando **Mocha** e **Chai** per verificare il funzionamento delle classi `Prodotto` e `Carrello`.

## Come Usare

1. **Scarica il progetto**: 
   - Puoi scaricare il progetto completo tramite `git clone https://github.com/b3nj4m1no/testing.git` .
   
2. **Aggiungi il progetto alla tua cartella locale**: 
   - Estrai il contenuto del file ZIP nella tua cartella di lavoro.

3. **Apri il file index.html nel tuo browser**: 
   - Doppio click sul file `index.html` per aprire la pagina nel tuo browser. I test verranno eseguiti automaticamente grazie a Mocha.

4. **Visualizza i risultati dei test**: 
   - Nella pagina verranno mostrati i risultati dei test per le classi `Prodotto` e `Carrello`.

## Test
I test sono scritti utilizzando il framework **Mocha** per la struttura dei test e **Chai** per le asserzioni. I test coprono i seguenti scenari:
- Creazione e validazione dei prodotti.
- Aggiunta e rimozione dei prodotti nel carrello.
- Calcolo del totale del carrello.
- Applicazione di sconto globale sul carrello.
- Validazioni per input errati (prezzo negativo, quantità zero, sconto eccessivo).

## Licenza
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Questo progetto è stato creato a scopo educativo per la materia **TEP** e può essere utilizzato per scopi simili. Può essere liberamente modificato e distribuito con l'attribuzione appropriata.
---

### Creato da: **Benjamin**
