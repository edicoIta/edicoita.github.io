# Tabelle e matrici, le strutture bidimensionali
* * *

![Tabelle e matrici](https://user-images.githubusercontent.com/16359799/192094768-6ef3a876-8ed8-4c39-adbe-a2b6e8f650a9.png)


Le tabelle e le matrici sono particolari elementi con struttura a griglia, formate da colonne e da righe.

Le tabelle vengono utilizzate per incolonnare dati o testo in modo ordinato.

Solitamente le tabelle usano graficamente dei bordi per separare i singoli elementi (celle) contenuti. Così vi saranno dei bordi verticali (colonne) e dei bordi orizzontali (righe). Il contenuto di ciascuna cella viene presentato all'interno di questi bordi.

Le matrici sono dei tipi particolari di tabelle che, graficamente, non presentano un bordo. In matematica, in particolare in algebra lineare, una matrice è una tabella ordinata di elementi.

EDICO permette di lavorare con tabelle e matrici.

Proprio perché queste strutture si espandono su più righe e colonne sono chiamati elementi bidimensionali: dove la prima dimensione sono le righe e la seconda dimensione le colonne.

## L'uso delle tabelle

E' possibile inserire una tabella in tre modi distinti
* Premendo CTRL+ALT+T ;
* Dal menu Inserisci, scegliendo Tabella;
* Premendo F5 e scegliendo tabella


In qualunque caso, dando INVIO ci verrà chiesto di specificare un dimensionamento della tabella (numero di righe e numero di coloone).

Possiamo scrivere il valore con la tastiera. Per spostarci fra un campo di testo e l'altro possiamo usare il tasto TAB.

Nell'esempio vediamo un caso in cui impostiamo una tabella con 3 righe e 4 colonne:

![Esempio](https://user-images.githubusercontent.com/16359799/192092735-1409d9a2-7fed-45c2-aa28-9fadb18cc42c.png)

Il cursore verrà riportato nell'editor lineare.

Prendiamoci il tempo di esplorare ciò che abbiamo creato. Sul nostro display braille o Scorrendo con le freccette troviamo una serie di marcatori come:
* inizio tabella  
* Nuova colonna  
* Nuova colonna  
* Nuova colonna  
* Nuova riga  
* Nuova colonna  
* Nuova colonna  
* Nuova colonna  
* Nuova riga  
* Nuova colonna  
* Nuova colonna  
* Nuova colonna  
* fine tabella 

Fra questi marcatori possiamo andare a inserire manualmente il contenuto della nostra tabella. Ad esempio se vogliamo riempire la prima riga con:

| Profitto | Nord | Centro | Sud |


lo possiamo fare andando a scrivere "Profitto" fra il marcatore di inizio tabella e il primo marcatore di nuova colonna, e a seguire centro e sud.
Per vedere l'esempio svolto fare riferimento all'Esempio 1 del file allegato.

![image](https://user-images.githubusercontent.com/16359799/192093181-7a6c9bbb-2b83-46e7-9a49-f711609af245.png)

Se questa modalità è comoda quando abbiamo a che fare con tabelle piccole, che magari riusciamo a leggere interamente in modo lineare nel display braille, diventa poco pratica e di difficile gestione quando i dati cominciano a essere molti.
Se già cominciassimo a riempire le altre righe della tabella in questo modo, sarebbe molto facile perdere l'orientamento.

Per questo motivo EDICO mette a disposizione l'editor bidimensionale.

## Editor Bidimensionale

Come nel caso delle strutture didattiche delle operazioni questo è disponibile in due modi: Editor Bidimensionale e Editor Bidimensionale in celle.

Manteniamo posizionato il cursore all'interno della nostra tabella e premiamo F10:
![Editor bidimensionale](https://user-images.githubusercontent.com/16359799/192093733-303a2ee5-9652-4197-8a69-cea62507556a.png)

Viene così aperto l'editor bidimensionale.

Nel display braille visualizzeremo l'intera riga della tabella, con i marcatori di nuova colonna.
Per spostarci alla seconda riga premiamo Freccia giù.
Sul display braille, a inizio riga, leggeremo sempre anche la coordinata della riga in cui siamo. Ad esempio, la prima riga comparirà come:

Riga1 edt Profitto. Nord. Centro. Sud.

La sintesi vocale leggerà l'intera riga della tabella scandendola lettera per lettera.

Questo tipo di Editor è molto comodo per chi lavora in braille se si desidera avere a disposizione sul display l'intera riga della tabella.

L'editor bidimensionale appare in una finestra di dialogo che contiene:
* Una barra dei menu
* Tanti campi di testo uno per ogni riga della tabella (nel nostro caso 3 campi di testo)
* Un pulsante Aggiorna attivabile anche premendo semplicmenente INVIO.

Ci si può spostare fra i vari controlli premendo TAB. Ci si può spostare fra le varie righe anche usando le frecce su e giù.

Quando abbiamo concluso premiamo ESC per chiudere l'editor bidimensionale senza salvare le modifiche e tornare nel documento.

L'editor bidimensionale in celle è simile all'editor bidimensionale. A differenza di quest'ultimo però, mostrerà sul display braille e leggerà in sintesi vocale una singola cella della tabella alla volta.
Manteniamo posizionato il cursore all'interno della nostra tabella e premiamo Shift+F11.
![Editor bidimensionale in celle](https://user-images.githubusercontent.com/16359799/192093749-b17b6bf3-26fc-4e34-a7a5-6e6fbc81bc39.png)

Come si può notare, in questo caso la sintesi vocale leggerà solo la cella della tabella su cui abbiamo posizionato il cursore. Anche il display braille mostrerà il contenuto di una singola cella.

Sul display braille, prima del contenuto, possiamo leggere le coordinate. Così, ad esempio, leggeremo:

c1 1    profitto

premiamo TAB e troviamo

c1 2    nord 

premiamo TAB e troviamo

c1 3    centro

eccetera

La finestra di dialogo è del tutto simile a quella dell'editor bidimensionale in righe. La barra dei menu in entrambi i casi consente di inserire simboli grazie al menu Inserisci.
E' poi possibile aggiungere e rimuovere righe e colonne dal menu Modifica, Selezionare delle porzioni della tabella dal menu Seleziona e richiamare la calcolatrice dal menu Strumenti.

Una funzione interessante viene messa a disposizione dal menu Azioni che permette di passare al volo fra l'editor bidimensionale e l'editor bidimensionale in celle.

Prendetevi del tempo per esplorare le varie opzioni presenti. 
Al termine potete completare l'esercizio aggiungendo due righe alla tabella copiando quella qui sotto:

| Profitto | Nord | Centro | Sud |
| --- | --- | --- | --- |
| TV | 10000€ | 9000€ | 8500€ |
| Radio | 3400€ | 2300€ | 4000€ |

![Esempio](https://user-images.githubusercontent.com/16359799/192100537-bb2e3ec9-0c29-4f28-aa8e-33ee07aa09c7.png)

La tabella in questo caso rappresenta una informazione. In questo caso i profitti di un negozio di elettronica nel mese di Febbraio. Possiamo completare l'esercizio aggiungendo un testo che descrive la tabella. Ad esempio: 

Profitto febbraio (euro) 

![Esempio](https://user-images.githubusercontent.com/16359799/192100666-40addced-357d-4031-985b-9530be29b42b.png)

Per vedere l'esempio svolto fare riferimento all'Esempio 2 del file allegato.

Proviamo ora ad aggiungere una ulteriore tabella, ad esempio con i profitti del mese di marzo. Copiare questa tabella preceduta dal testo 

Profitto marzo (euro)

| Profitto | Nord | Centro | Sud |
| --- | --- | --- | --- |
| TV | 9800€ | 9300€ | 8100€ |
| Radio | 3400€ | 2400€ | 4400€ |

