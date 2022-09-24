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

Rileggendo o consultando una tabella potrebbe essere difficile comprenderne al volo le dimensioni. EDICO ci riporterà il numero di righe e colonne contenute in una tabella richiamando la funzione "Mostra dimensioni".
Per attivarla procediamo come segue:

1. Posizionamo il cursore sulla tabella
2. Premiamo Alt+F11

![Tabella 3 per 4](https://user-images.githubusercontent.com/16359799/192101447-48aaf079-55d9-45b2-aae9-e2b46c1f583f.png)

Edico ci riporterà che la tabella è una 3 per 4.

In alternativa è anche possibile richiamare la funzione "Mostra dimensioni" dal menu Azioni.

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

Provate l'inserimento con l'editor bidmensionale o l'editor bidimensionale in celle per comprendere le differenze fra i due strumenti anche in fase di inserimento e spostamento fra le celle.

![image](https://user-images.githubusercontent.com/16359799/192101141-c548e1a9-0adb-4dbc-85e9-49f975461d65.png)

Per l'esempio già scritto fare riferimento all'Esempio 3 del file allegato.

A partire dall'editor bidimensionale è anche possibile spostarsi rapidamente alla tabella precedente o successiva. Se, ad esempio stiamo valutando i profitti di marzo e vogliamo compararli coi profitti di febbraio, possiamo spostarci alla tabella precedente semplicemente premendo Pagina Su o scegliendo "tabella precedente" dal menu "Vai a".

![Vai a pagina precedente](https://user-images.githubusercontent.com/16359799/192101307-7c3d8caf-9a66-40bf-bfa8-01de359a721c.png)

Si può naturalmente effettuare l'operazione inversa premendo Pagina Giù o selezionando la relativa voce dal menu "Vai a".

## Le matrici

Proprio come le tabelle, EDICO ci permette di gestire in modo del tutto analogo le matrici. Richiamando l'esempio precedente, supponiamo voler calcolare, per ciascun periodo, la differenza fra i due profitti.

Impostiamo quindi due matrici A e B, di cui la prima conterrà i dati di febbraio mentre la seconda conterrà i dati di marzo.

Avremo quindi che

$$
A=\left(\begin{array}{ccc}
10000 & 9000 & 8500 \\
3400 & 2300 & 4000
\end{array}\right)
$$

$$
B=\left(\begin{array}{ccc}
9800 & 9300 & 8100 \\
3400 & 2400 & 4400
\end{array}\right)
$$

Vogliamo quindi scrivere le matrici A e B in EDICO.

E' possibile inserire una matrice in tre modi distinti
* Premendo CTRL+ALT+M ;
* Dal menu Inserisci, scegliendo Matrice;
* Premendo F5 e scegliendo matrice

Scegliamo il modo a noi più congeniale.
Creiamo quindi una semplice matrice 2 per 3 in modo del tutto simile a come abbiamo fatto in precedenza per le tabelle:
![creazione matrice](https://user-images.githubusercontent.com/16359799/192102547-6e7fe497-a262-4800-95ba-d2ffe40ce660.png)

In modo del tutto simile alle tabelle ci troveremo di fronte ad una serie di marcatori:
* matrice
* Nuova colonna
* Nuova colonna
* Nuova riga
* Nuova colonna
* Nuova colonna
* fine matrice 

Proprio come nel caso delle tabelle è possibile utilizzare l'editor bidimensionale e l'editor bidimensionale in celle per gestire la matrice.
Procedo quindi nello scrivere le due matrici A e B.

Ecco mentre sto scrivendo $A$:
![scrivo la matrice A](https://user-images.githubusercontent.com/16359799/192102838-34a30ca5-dcc3-46df-9adf-65e413fb3610.png)

Copiamo anche $B$ e dovremmo ora avere un qualcosa di simile a ciò che appare in figura:
![esempio](https://user-images.githubusercontent.com/16359799/192102998-3f58dfb6-ca6a-4d87-9a3c-bd6d75f63a41.png)
Per l'esempio già scritto fare riferimento all'Esempio 4 del file allegato.

A questo punto, applicando le regole delle matrici, possiamo calcolare la matrice:

$$C = A - B$$

## Operazioni con le matrici
Per effettuare la sottrazione fra le due matrici possiamo usare l'editor bidimensionale. 

In questo caso andiamo a definire una nuova matrice $C$ sempre di dimensioni 2 per 3.
![esempio](https://user-images.githubusercontent.com/16359799/192103181-452f9082-971c-495c-be95-134ee09aa033.png)
Ci portiamo quindi all'interno della matrice e apriamo l'editor bidimensionale con F11:

Aiutandoci con le funzioni Pagina su e Pagina giù andiamo a copiare i vari elementi per impostare la sottrazione termine a termine.
![scrivendo la matrice C](https://user-images.githubusercontent.com/16359799/192103695-1a3e7e62-8903-4d2e-a3a0-ab655eb29bf8.png)
Chiudiamo l'editor bidimensionale confermando con Invio.

Per andare alla matrice C già scritta fare riferimento all'esempio 5 del file allegato.

Ora possiamo duplicare la riga con Control+d che, in questo caso duplicherà la riga dell'editor lineare e quindi l'intera matrice.

![le due righe duplicate](https://user-images.githubusercontent.com/16359799/192103895-f700b55f-cc73-490b-9822-295a1a3163d9.png)

Quindi possiamo entrare nuovamente nell'editor bidimensionale con F11 e svolgere le sottrazioni aiutandoci con la calcolatrice.

* Possiamo selezionare i singoli elementi della matrice (le singole sottrazioni) con F12
* Possiamo calcolarne il risultato e salvarlo negli appunti con Shift+F9
* Infine possiamo incollarlo con Control+V
![image](https://user-images.githubusercontent.com/16359799/192103932-3a95dfd1-21c4-478a-969b-e59f279de856.png)

Otteniamo quindi la matrice calcolata 
$$$$
C=\left(\begin{array}{ccc}
-200 & 300 & -400 \\
0 & 100 & 400
\end{array}\right)
$$

Per andare allo svolgimento del calcolo fare riferimento all'esempio 6 del file allegato.




