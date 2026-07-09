---
title: Boeing 737 MAX MCAS
pov: ""
draft: 1
---

# Boeing 737 MAX MCAS

La Parte V deve sporcare le mani.

Fin qui il corridoio è stato descritto come dispositivo: filtro, riduttore di overflow, cecità della verifica, cattura della critica, resistenza illeggibile. Ma un dispositivo teorico che non regge davanti a un caso concreto è solo arredamento concettuale. Elegante, magari. Sempre arredamento. Il Boeing 737 MAX serve a questo: non come esempio emotivo, non come tragedia da usare per fare peso retorico, ma come stress-test. Se il corridoio autorizzato significa qualcosa, deve spiegare perché una catena piena di ingegneri, regolatori, procedure, simulazioni, manuali, certificazioni e piloti abbia potuto produrre una cucitura così fragile e insieme così difficile da imputare prima che cedesse.

La risposta facile è: MCAS.

È anche la risposta sbagliata, o almeno troppo piccola.

Il Maneuvering Characteristics Augmentation System era il punto visibile della rottura. Un sistema automatico, legato all'angolo d'attacco, capace di comandare stabilizzatore nose-down in certe condizioni. Dopo Lion Air 610, il 29 ottobre 2018, e Ethiopian Airlines 302, il 10 marzo 2019, quella sigla è diventata quasi un personaggio: MCAS il colpevole, MCAS il software killer, MCAS il bug. Capisco la tentazione. Una sigla concentra. Una sigla sta bene nei titoli. Una sigla sembra dare al dolore un indirizzo.

Ma il corridoio non lavora solo producendo un colpevole. Lavora anche producendo il tipo di colpevole che possiamo vedere.

Il MAX non nasce nel vuoto tecnico. Nasce dentro una pressione commerciale precisa: costruire un nuovo aereo abbastanza nuovo da competere, abbastanza vecchio da non costringere compagnie e piloti a pagare un nuovo addestramento pesante. I nuovi motori LEAP, più grandi e montati più avanti e più in alto, cambiano la dinamica dell'aereo in certi inviluppi. MCAS entra come cucitura: non un grande annuncio di trasformazione, ma un'aggiunta che aiuta l'aereo a comportarsi, almeno nella grammatica certificativa, come una continuità del 737 precedente. Già qui il caso smette di essere un incidente software. È una cucitura tra aerodinamica, mercato, certificazione e addestramento.

Una cucitura non è neutra. Decide dove passa la tensione.

Il punto brutale è che MCAS, nella sua configurazione originale, poteva affidarsi all'input di un solo sensore di angle of attack. Se quel sensore mentiva, il sistema poteva credere a una condizione aerodinamica che non c'era e spingere il muso in basso. Non era solo un difetto locale. Era una scelta di architettura che concedeva a un segnale singolo un'autorità sproporzionata dentro una scena ad alta velocità, alto carico cognitivo e bassa tolleranza all'ambiguità. Il sensore non doveva convincere un foro robusto. Doveva parlare nel formato giusto al circuito giusto.

Questo è il corridoio in forma ingegneristica: non passa ciò che è vero, passa ciò che il circuito è autorizzato a trattare come input valido.

Dopo i disastri, il NTSB formulò il punto senza poesia, quindi meglio: le analisi di sicurezza avevano assunto un certo riconoscimento e una certa risposta da parte dei piloti, ma gli equipaggi reali si trovarono davanti a molteplici allarmi e indicazioni contemporanee. Robert Sumwalt disse che c'era un gap tra le assunzioni usate per certificare il MAX e l'esperienza reale degli equipaggi.[^boeing-ntsb] È una frase quasi perfetta per questo libro, e purtroppo non l'ho inventata io. Il gap non era fuori dal sistema. Era dentro l'immagine autorizzata del pilota.

Il pilota certificativo era leggibile.

Il pilota reale era sovraccarico.

Questa differenza è il centro del caso. Il pilota nel modello riconosce, interpreta, reagisce. Il pilota nella cabina reale riceve stick shaker, warning, valori discordanti, trim che si muove, quota, velocità, comunicazioni, memoria procedurale, sorpresa, secondi che spariscono. La certificazione non aveva eliminato l'umano. Lo aveva formalizzato. L'umano era lì, ma come funzione prevista. Doveva assorbire la deviazione secondo il tempo e la forma che il modello gli concedeva. Quando non lo fece, non perché fosse astrattamente incapace ma perché la scena reale era diversa dalla scena modellata, il corridoio mostrò la sua ferocia più elegante: aveva lasciato spazio all'uomo solo dove l'uomo era già stato semplificato.

Qui il caso Boeing non ripete il Capitolo 4. Lo specifica.

Il loop chiuso diceva: il sistema elimina l'occasione della verifica. Il caso MCAS mostra come quell'occasione venga eliminata prima, in strati separati, senza che nessuno debba dichiarare “chiudiamo il foro”. Non serve un cattivo con il sigaro. Basta che ogni strato abbia una ragione locale per non riaprire la cucitura intera.

Lo strato commerciale vuole continuità: stesso type rating, addestramento contenuto, nessun simulatore se possibile, promessa di transizione liscia. Lo strato ingegneristico vuole compensare una caratteristica di handling senza trasformare l'aereo in un nuovo oggetto amministrativo. Lo strato documentale vuole descrivere il cambiamento come abbastanza piccolo da restare gestibile. Lo strato regolatorio, anche quando non è corrotto nel senso da romanzo, lavora dentro deleghe, fiducia, asimmetria informativa, pressione di calendario, competenza dispersa. Lo strato di cockpit riceve alla fine una superficie in cui la cucitura è stata resa opaca proprio perché ogni passaggio precedente l'ha trattata come locale.

Responsabilità stratificata non significa responsabilità evaporata.

È il contrario. Significa che il foro deve essere progettato per risalire gli strati. Se resta nello strato sbagliato, produce solo capri espiatori ordinati. Il pilota come ultimo responsabile operativo. L'ingegnere come tecnico che ha valutato una funzione. Il certificatore come burocrate che ha approvato una modifica. Il manager come pressione generica. Boeing come azienda. FAA come regolatore. Ognuno visibile a pezzi, la cucitura intera invisibile finché non cade l'aereo.

Il corridoio ama questa forma di imputabilità a pezzi. Non perché assolve tutti, ma perché rende quasi impossibile contestare il disegno prima dell'evento catastrofico. Ogni obiezione deve entrare dal proprio ingresso: sicurezza del software qui, training là, manuale più avanti, sensor redundancy in un altro ufficio, human factors in una nota, market pressure come rumore di fondo che non ha casella tecnica. Se dici: il problema è la combinazione, rischi di sembrare vago. Se dici: il problema è la cucitura, il corridoio ti chiede quale modulo intendi.

E la cucitura non ha mai un modulo solo.

Il Joint Authorities Technical Review, dopo, vide molte cose che prima erano rimaste troppo distribuite: MCAS non valutato come funzione integrata con sufficiente trasparenza; FAA non pienamente informata dell'espansione della funzione; documentazione e comunicazione inadeguate; bisogno di aggiornare il modo in cui si assumono riconoscimento e tempi di risposta dei piloti. La House Committee investigation aggiunse il lato politico-industriale: pressione sui costi e sui tempi, debolezze dell'ODA, scelte di training che minimizzavano il valore dell'addestramento e inibivano soluzioni tecniche più robuste.[^boeing-jatr-house] Non sono dettagli da appendice. Sono la mappa della cucitura.

La domanda allora non è: perché nessuno ha visto MCAS?

Qualcuno vedeva pezzi di MCAS. Qualcuno sapeva abbastanza per scrivere, abbastanza per approvare, abbastanza per addestrare o non addestrare, abbastanza per documentare o omettere. La domanda corretta è più sgradevole: quale foro avrebbe costretto quei pezzi a diventare una sola cosa imputabile prima del disastro?

Un foro decente avrebbe fatto almeno quattro lavori.

Primo: avrebbe trattato MCAS come funzione integrata, non come somma di cambi locali. Non “questo software modifica un comportamento in certe condizioni”, ma “questa cucitura collega sensori, stabilizzatore, manuali, training, aspettative sul pilota e promessa commerciale di continuità”. Sembra una frase lunga. Lo è. Le cose importanti spesso sono lunghe perché il potere preferisce i campi corti.

Secondo: avrebbe reso contestabile l'assunzione sul pilota. Non il pilota ideale, non il pilota come componente educata del modello, ma il pilota in cabina con allarmi multipli e tempo compresso. Qui il punto non è insultare la simulazione. La simulazione serve. Il punto è impedire che la simulazione diventi un corridoio dove può entrare solo l'umano già compatibile con l'ipotesi. Se la sicurezza dipende dalla risposta umana, allora la scena umana deve essere parte della sicurezza, non una nota morale a fine catena.

Terzo: avrebbe dato potere di arresto a segnali scomodi. Non basta che un rischio sia scritto da qualche parte. Il Capitolo 4 lo chiamava residuo: l'allarme che aspetta un archeologo. Nel MAX il residuo assume molte forme: informazioni tecniche non promosse, manuali che non raccontano abbastanza, training costruito attorno alla continuità, classificazioni che mantengono piccola una funzione diventata grande. Un foro vero non archivia questi attriti come documentazione. Li aggancia a una leva: finché questa cucitura non è spiegata intera, non passa.

Quarto: avrebbe reso costosa la continuità fittizia. Questo è il punto meno tecnico e più politico. La promessa “non serve nuovo addestramento” non è solo una scelta commerciale. È una decisione epistemica: dice che la differenza introdotta non merita una nuova forma di attenzione. Quando quella promessa diventa dominante, ogni modifica tende a presentarsi come non-modifica. Il corridoio non cancella la novità. La traveste da eredità.

Il significante ereditato torna qui con il rumore dei motori.

“737” non è solo un modello. È un carrier di fiducia, procedure, familiarità, type rating, mercato, calendario. Il MAX eredita quel significante e insieme lo modifica. Questa è una posizione pericolosa: abbastanza nuovo da richiedere cuciture, abbastanza vecchio da volerle nascondere. Il corridoio autorizzato funziona benissimo in questi casi perché non deve vietare la differenza; deve farla transitare come continuità.

La tragedia sta anche lì: nella differenza costretta a indossare la maschera della stessa cosa.

Non c'è bisogno di trasformare Boeing in mostro metafisico. Sarebbe comodo, e la comodità è quasi sempre un pessimo strumento investigativo. Le aziende fanno pressioni, proteggono margini, vendono continuità, minimizzano attriti; i regolatori delegano, inseguono complessità, si fidano di pezzi di processo; gli ingegneri lavorano dentro vincoli; i piloti ereditano l'ultima versione della scena. Il punto non è dire che tutti sono ugualmente colpevoli. Questa è un'altra maniera di non accusare nessuno. Il punto è dire che la responsabilità, quando è stratificata, deve avere una forma capace di restare stratificata senza dissolversi.

Serve un'imputabilità della cucitura.

Una cucitura è imputabile quando puoi chiedere: chi ha deciso che un solo sensore bastava per questa autorità? Chi ha deciso che questa funzione restava abbastanza piccola da non cambiare training e manuali? Chi ha potuto contestare quella decisione senza perdere contro calendario e costo? Chi aveva il dovere di guardare la combinazione invece del componente? Quale informazione avrebbe fermato la certificazione, non solo arricchito il fascicolo? Dove stava il freno?

La domanda del freno ritorna perché è volgare e precisa. Nel MAX il freno non poteva stare solo nella cabina, negli ultimi secondi, sulle spalle di due persone che scoprivano la cucitura mentre l'aereo la usava contro di loro. Un freno messo lì è già una colpa travestita da controllo. Il freno doveva stare a monte: nel momento in cui la funzione cresceva; nel momento in cui l'autorità del sensore restava singola; nel momento in cui l'omissione dal manuale diventava conveniente; nel momento in cui “non serve simulatore” smetteva di essere una conclusione tecnica e diventava il corridoio dentro cui tutte le altre conclusioni dovevano passare.

Questa è la lezione più dura del caso MCAS: il foro tardivo può essere eccellente e restare tardivo.

Dopo i disastri, i report hanno visto. Hanno nominato. Hanno corretto. La messa a terra globale del MAX, le modifiche al software, l'uso di due sensori, gli aggiornamenti di training, le revisioni della certificazione: tutto questo conta. Non c'è nessun onore nel disprezzare la riparazione. Ma una riparazione postuma non falsifica la tesi del corridoio; la conferma nel suo punto più freddo. Il sistema ha prodotto conoscenza quando il prezzo era già stato pagato da 346 persone.

Il corridoio non è l'assenza di verifica. È spesso verifica dopo irreversibilità.

Ecco perché il caso Boeing deve aprire la Parte V. Non perché sia il caso più nuovo, né il più elegante. È quasi troppo noto, ormai, quindi rischia di diventare un'icona smussata. Ma proprio per questo serve rimetterlo nella sua forma dura: non un bug, non una catena di mele marce, non una generica “complessità”. Una cucitura autorizzata che ha fatto passare continuità dove c'era differenza, semplicità dove c'era carico, documentazione dove serviva foro, risposta umana dove serviva tempo reale di comprensione.

Il corridoio ha chiesto al pilota di essere l'ultimo sensore morale del sistema.

Poi gli ha tolto la scena in cui quel sensore poteva funzionare.

Questa non è automazione contro umanità. È peggio, quindi più reale: automazione che conserva l'umano come firma finale di una scelta che altri strati hanno già reso quasi non contestabile. Il pilota resta nel loop abbastanza da portare responsabilità, non abbastanza da riaprire il modello. È lo stesso trucco visto altrove: il soggetto presente come terminale d'imputazione, non come testimone capace di ferire il circuito.

Un corridoio meno indecente avrebbe dovuto fare una cosa semplice e difficile: rallentare dove il mercato voleva continuità, esporre dove la documentazione voleva compressione, integrare dove la procedura voleva separare, ascoltare il disturbo prima che diventasse relitto.

Non lo ha fatto.

E quando un aereo cade, anche la teoria deve smettere di parlare in punta di piedi. Il corridoio autorizzato uccide quando riesce a trasformare la cucitura intera in una serie di passaggi localmente accettabili. Nessun passaggio, preso da solo, porta tutto il peso. Tutti insieme portano l'aereo giù.

La post-mortem può ricostruire la sequenza. Il foro vivo doveva interromperla.

[^boeing-ntsb]: National Transportation Safety Board, *Safety Recommendation Report ASR-19-01*, 2019, sulla distanza tra assunzioni di safety assessment e risposta effettiva degli equipaggi davanti ad allarmi multipli.

[^boeing-jatr-house]: Joint Authorities Technical Review, *Boeing 737 MAX Flight Control System: Observations, Findings, and Recommendations*, 2019; U.S. House Committee on Transportation and Infrastructure, *The Design, Development & Certification of the Boeing 737 MAX*, 2020.
