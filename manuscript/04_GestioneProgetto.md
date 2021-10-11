# Gestione Progetto

La regola aurea è di mantenere alta la comunicazione e la condivisione con il cliente in modo da sentirsi parte di un unico team che genera valore. I riti che Flowing mette in campo sono momenti da schedulare a calendario per creare uno spazio protetto di discussione e confronto, ma da soli potrebbero non bastare. Non importa che strumento usi (quello proposto da Flowing o quello proposto dal cliente), l’importante è avere un canale di comunicazione aperto e vivo per evitare che un dubbio o un fraintendimento portino il progetto sulla cattiva strada.

## Iteration Meeting

L'Iteration Meeting è il cuore di Our Flow, un momento quasi solenne che ogni progetto a prescindere dalla tipologia di contratto deve avere. Si tiene, solitamente, una volta a settimana e le attività vengono tracciate tramite una Kanban Board, di solito una board Trello. Nella Figura 4.1 vedi la versione più semplice di Kanban che si può implementare con un Backlog, la lista di attività nell’iterazione e le attività da far accettare al Product Owner.

{width: "75%"}
![Figura 4.1 - Kanban Board](kanban.png)

L'Iteration Meeting è diviso in due fasi principali, Iteration Review ed Iteration Planning. 

### Iteration Review

in questa prima fase lo scopo è quello di farsi validare dal PO il lavoro fatto durante l'iterazione. È importante, per evitare fraintendimenti, che ogni task portato a termine sia validato dal PO. Se questa fase viene svolta in maniera superficiale infatti, può accadere che arrivino dei rework anche dopo settimane. Rendendo poi la pianificazione particolarmente difficoltosa.
Sicuramente alcune funzionalità sono pronte prima della review, per cui ha senso condividerlo con il cliente anche prima del rito: vale sempre la regola di ricevere un feedback il prima possibile, così anche da tenere la review snella. L’iteration Review rappresenta la fine formale dell’iterazione corrente.

### Iteration Planning

Una volta messa in sicurezza l'iterazione attuale, è il momento di pianificare la prossima iterazione. Soprattutto nelle prime settimane è importante calibrare bene il contenuto dell’iterazione. È infatti tenere a mente due aspetti contemporaneamente. Da una parte nelle prime fasi è importante instaurare il regime di fiducia e consegnare valore (anche più del dovuto) è un ottimo modo per arrivarci. Però è ugualmente importante educare il cliente alla gestione del compromesso e al fatto che non tutto è fattibile subito. 

Una tecnica che può essere utile è quella di inserire i task nell’iterazione e rendere chiaro che alcuni task saranno must-have mentre degli altri saranno dei nice-to-have.

L’iteration Planning rappresenta il momento formale in cui l'iterazione ha inizio.

### Tips & Tricks

#### Be prepared 

L'Iteration Meeting è un momento importante e come tale va "preparato". Con il team potete organizzare anche un pre-iteration per pianificare l'incontro, fare una prevalidazione dei task conclusi e ragionare sui vari scenari possibile e soprattutto arrivare preparati all'incontro con delle proposte per il cliente. La preparazione può anche essere asincrona, se credi che un pre-incontro in call sia eccessivo. Ma l'importante è che l'IM non sia improvvisato rischiando di dover prendere decisioni al volo senza dare la possibilità al team di sincronizzarsi.

La stessa cosa vale per la review: se devi mostrare una demo fai in modo di averla testata in precedenza e che sia tutto pronto per fare vedere il flusso da validare. Se ci sono piccoli problemi da risolvere, fai capire al cliente che ne hai già preso coscienza e che li risolverai quanto prima.

#### Non solo Kanban

Sappiamo tutti che un buon utilizzo della Kanban è fondamentale per ottimizzare il flusso delle attività. Ma spesso non è abbastanza, soprattutto in fasi concitate come la vicinanza ad una deadline. In questi momenti cerca di creare un rapporto positivo basato sull'empatia e sull'ascolto attivo. Spesso infatti, i conflitti che nascono all'interno di un progetto derivano da incomprensioni o paure del PO.

#### Rendi palesi i vincoli

Se il team ha un vincolo forte di budget o di deadline, alla fine di ogni IM discuti di questi vincoli. Se hai un budget di iterazioni da concludere, alla fine di ogni IM rendi palese a che punto sei del progetto e del consumo di ore. Questo eviterà delle brutte sorprese, e aiuterà il team ad affrontare subito i problemi.

#### Rendi le informazioni "visuali"

Sembrerà banale, ma un'immagine vale più di mille parole. Se pensi possa essere d'aiuto, utilizza dei grafici o altri strumenti visuali che ti aiutino a tenere traccia dell'avanzamento del progetto. Ad esempio puoi usare un Burndown Chart di Figura 4.2 per mostrare l'avanzamento dei lavori.

{width: "75%"}
![Figura 4.2 - Burndown Chart by PabloStraub, CC0, via Wikimedia Commons](chart.png)

### Come il contratto può incidere sull'IM?

Le discussioni da tenere durante l'IM variano a seconda della tipologia di contratto.

#### Soddisfatti o Rimborsati

In questo caso nel contratto non è definito lo scope up-front. È importante quindi abilitare e abituare il PO a esercitare il suo potere di poter cambiare rotta qualora sia utile per l'andamento del progetto. La negoziazione, che è comunque una parte integrante di ogni IM, ha un ruolo particolarmente importante nei contratti SoR. Mai e per nessun motivo la discussione va spostata sul tempo, ma solo sul valore che il cliente da alle storie e quindi sul fatto che ci sia un fit tra quello che possiamo effettivamente consegnare e quello che il cliente è disposto a pagare per i task.

Evitare di parlare del tempo durante gli IM è indispensabile per evitare che ci sia un effetto ancoraggio e trovarsi poi a dover giustificare se un task a richiesto più o meno tempo di quello accennato durante un IM.

#### Contratto a Corpo

Al contrario del contratto SoR il contratto a corpo ha lo scope definito. Le feature da realizzare sono specificate all'interno del contratto e quindi una modifica sostanziale dello scope richiede un cambiamento anche contrattuale. Se questa cosa capita durante la vita del progetto - ed è una cosa sana - avverti il commerciale che fa parte del tuo team. Potrebbe essere anche un'occasione per fare un transform e rendere palese al cliente i limiti del contratto a corpo. Il fatto che lo scope ed il budget siano fissi fa sì che in ogni IM di un contratto a corpo ci sia un piccolo recap che faccia capire al cliente a che punto del progetto siamo e quanto budget è stato consumato. In questo modo criticità possono essere affrontate il prima possibile senza aspettare la fine del contratto.

Ad esempio, nel caso in cui ci sia un ritardo, lo si può recuperare limando lo scope di alcune attività spezzando i task in parti più piccole e mettendo quelle meno utili in fondo nel backlog, rendendoli dei nice-to-have. Se poi il ritardo viene recuperato allora quelle feature possono essere recuperate nelle fasi finali del progetto.

#### Time and materials

In questo caso il costo dell'iterazione non è fisso ma dipende dall'effort che effettivamente il team è riuscito ad erogare per il cliente in quella settimana. Qualora ci siano dei cambi di rotta, puoi usare i consigli che trovi nella sezione del contratto SoR. Se invece devi gestire un budget finito o una deadline puoi usare la stessa tecnica del contratto a corpo. Rendi esplicito l'avanzamento.

In ogni caso però, dato che in questo caso la variabile che incide sulla fatturazione è il tempo, ad ogni IM rendi esplicito quanto il team ha lavorato per il cliente in quella iterazione. Questo ti permetterà di evitare fraintendimenti all'arrivo delle fatture.

## Kick-off (primo IM)

Il primo IM - a cui diamo il nome di Kick-off - è un po’ particolare. Non può, per ovvie ragioni, contenere la parte di Iteration Review. Ma ci sono un paio di cose da tenere a mente in questa prima fase.

#### Fai Presentare il Team

Ricorda di presentarti e di presentare tutto il team, alla discovery potrebbe aver partecipato solo una parte del team. Se puoi apri la telecamera e fatti vedere dal cliente renderai le presentazioni più "umane". Chiedi inoltre di far presentare tutti le persone del team cliente che parteciperanno agli IM e fatti spiegare quale è il loro ruolo. Se noti infatti che ci sono persone diverse da quelle che sono emerse durante la discovery o che il mappa di potere sembra essere diversa rendilo palese. Questo può evitare fraintendimenti futuri su chi deve fare cosa durante il proseguo del progetto.

#### Presenta Our Flow

Può sembrarti banale, ma prenditi del tempo per spiegare come si svolgeranno gli Iteration Meeting. Spiega soprattutto qual è il ruolo e la responsabilità che ha il PO nell'accettare formalmente quanto consegnato ad ogni iterazione, soprattutto in un contratto SoR.

## Quanto dura un’iterazione?

Non esiste una formula matematica per calcolare la durata ottimale di un’iterazione. Tuttavia abbiamo riscontrato negli anni in maniera empirica che iterazioni della durata di una settimana si sposano bene con il resto di Our Flow. Perché possiamo dirlo? Consideriamo alcuni elementi.

Come hai avuto modo di vedere, in Flowing è fondamentale ricercare continuamente feedback. A ogni IM il PO è tenuto da contratto a dare feedback al team revisionando ed eventualmente approvando “ufficialmente” quanto sviluppato. Avere IM vicini tra loro ci permette di evitare l’accumulo di troppe feature non approvate: se qualcosa non va nel lavoro svolto lo rileviamo al più dopo qualche giorno e lo mettiamo a posto! In questo modo evitiamo rilavorazioni corpose e di conseguenza riduciamo lo spreco. Questo aspetto assume una particolare rilevanza all’avvio dei progetti, quando il livello d'incertezza è molto alto ed è necessario instaurare un regime di fiducia con il cliente.

Mantenere l’iterazione corta ci aiuta inoltre a stimare e pianificare meglio il lavoro. Cosa ti viene più facile: pianificare una vacanza di una settimana o un viaggio di un mese? Lo stesso vale per i progetti: pianificare il lavoro di una settimana è sicuramente più facile che quello di un mese. Inoltre, a causa del hard-easy effect, in qualità di esseri umani tendiamo di fronte alla complessità ad essere ottimisti e di conseguenza sopravvalutiamo le chances di cavarcela con poco. Quando facciamo le stime tendiamo quindi a stimare più o meno correttamente i task piccoli, mentre tendiamo a sottostimare i task più complessi. L’iterazione di una settimana ci impone di ragionare su task della durata al più di qualche giorno e di conseguenza ci permette di fare delle stime più accurate, di pianificare meglio il lavoro e di fare una negoziazione dello scope più efficace.

Nei contratti SoR, la durata dell’iterazione ha anche implicazioni di natura economica. Come ben sai questo contratto prevede che alla fine dell’Iteration Review il cliente validi il lavoro fatto, decidendo se vuole pagare l’iterazione o meno. Ovviamente più è lunga l’iterazione, maggiore sarebbe la perdita in caso di esito negativo: perdere un’iterazione da € 7.000 potrebbe essere un problema, ma è sicuramente un problema minore di quanto potrebbe esserlo qualora valesse € 14.000 o peggio ancora € 21.000! Vista la relazione lineare tra la durata dell’iterazione e il suo costo, vi è una relazione lineare anche tra la durata dell’iterazione è il rischio assunto dal team. Iterazioni più corte minimizzano questo rischio!

È sempre sbagliato avere iterazioni della durata superiore a una settimana? No, non possiamo essere dogmatici sulla durata ottimale delle iterazioni. Alcuni progetti sono piuttosto peculiari e di conseguenza l’iterazione di una settimana potrebbe risultare limitante o addirittura controproducente. Ad esempio in un progetto di pura ricerca UX il team potrebbe aver bisogno di più settimane per produrre dei deliverable da sottoporre alla review del PO. In altri contesti l’iterazione potrebbe addirittura durare meno di una settimana. Ad esempio, uno dei nostri team in passato ha lavorato a un progetto in cui c’era molta incertezza su ciò che andava fatto, con al tempo stesso una scadenza vincolante e stretta. In virtù di queste condizioni il team ha optato per impostare una durata dell’iterazione di soli due giorni! 

Nella maggior parte dei casi comunque l’iterazione di una settimana ci aiuta a ricevere feedback costantemente, stimare e pianificare meglio il lavoro e a ridurre il rischio. 

L’iterazione settimanale tuttavia non sostituisce la visione a medio-lungo termine del progetto. Per raggiungere un obiettivo potrebbero essere necessarie più iterazioni. Ogni iterazione rappresenta quindi un passo in avanti verso il raggiungimento di un obiettivo del progetto. É fondamentale pertanto definire di concerto col PO l’obiettivo (o gli obiettivi) da raggiungere nel giro di 4/6 iterazioni, così da avere una visione a grandi linee di più ampio respiro.

## Siamo tutti PM (o perchè non c’è un PM)

Una cosa che salta all'occhio nell'organizzazione del lavoro dei team Flowing è la mancanza di figure di PM dedicate. Questo perché crediamo che ogni persona del team debba essere un PM, o più in generale crediamo che sia importante che la responsabilità di far sì che il progetto proceda senza intoppi debba essere condivisa da tutto il team. Questo aiuta a non creare colli di bottiglia o inefficienze perché tutto il team sente sua la responsabilità di far andare le cose per il verso giusto.

Può capitare che nel team emerga una figura che in qualche modo tenga più degli altri le fila del progetto, e succede soprattutto per tre motivi.

1. **Il cliente lo richiede espressamente**: i nostri clienti spesso hanno strutture gerarchiche molto rigide e questo si riflette anche nella collaborazione con noi chiedendo di sapere chi è il "referente di progetto". In questo caso spesso viene indicata la persona che è nel team da più tempo, chi può dedicare più effort possibile al progetto in quel momento o la persona più senior.

2. **Nasce spontaneamente**: nella gestione del progetto mettiamo molto rapporto umano, ed è quindi possibile che emerga naturalmente una persona che il cliente sente in qualche modo "più vicina" o la più adatta con la quale confrontarsi. Questa è una cosa del tutto naturale che non va combattuta ma che può anzi essere utile in situazioni di stress di progetto.

3. **Il team ne sente l’esigenza**: in situazione un po’ critiche come clienti con dinamiche complesse o non perfettamente allineato al nostro modo di lavorare, il team stesso può sentire l’esigenza di eleggere un proprio membro come “referente di progetto” permettendo al resto del gruppo di concentrarsi sulla delivery per un periodo più o meno lungo. Se nel team nessuno sente di avere le caratteristiche per poter tenere le redini del progetto, il team può richiedere aiuto al planning.

In entrambi i casi però è utile ricordare che la responsabilità della gestione del progetto è sempre e comunque condivisa da tutti i membri del team. Quindi se ti ritrovi ad essere la persona di riferimento del cliente ricorda sempre che tutto deve comunque funzionare senza di te. Se il cliente ti da delle informazioni o degli spunti, ricordati sempre di riportarle al team in maniera condivisa. Se per un qualche motivo non puoi lavorare al progetto - ferie o per motivi di planning - le informazioni sull'andamento del progetto devono sempre essere disponibili a tutti. In questo modo non creerai un collo di bottiglia.

Come puoi leggere, non siamo contrari al ruolo di PM, ma all’esistenza di un titolo di PM e al fatto che sia una figura scollegata dall’operatività del team.

## Controllo di gestione

In Flowing ogni team è auto-organizzato. Questo non significa che “ogni team fa come vuole”. Significa che in Flowing è chiaro quando un team è sano e quando il progetto è in carreggiata. Poiché la vision ci porta ad affrontare situazioni complesse è normale che nella quotidianità si verifichino delle criticità. In Flowing vogliamo accogliere il cambiamento e diventare bravi nel reagire ad esso. Per noi è molto più importante saper raddrizzare situazioni che cercare di pianificarle perfette.
Con controllo di gestione si intende quindi la capacità di avere sotto controllo:

**Serenità del team**
: è importante da monitorare per salvaguardare le performance dei surfer e la loro serenità operativa. Progetti frustranti generano persone scontente e persone scontente causano negatività nell’ambiente e nelle discussioni. E’ importante avere la sensibilità di cogliere i segnali delle persone del proprio team. Il confronto e il feedback sono solo i due strumenti più immediati. Una retrospettiva periodica può aiutare ad avere un quadro delle sensazioni dei componenti del team.



**Scadenze/roadmap**:
: Le scadenze e il progresso sulla delivery sono la nostra principale responsabilità verso le aspettative del cliente. Averle chiare è necessario al team per decidere bene e assumersi le responsabilità giuste. Indipendentemente dal tipo di progetto e contratto avere la percezione del progresso e dello stato dell’arte è indispensabile per una buona pianificazione.


**Redditività del progetto**
: La redditività del progetto è un dato fondamentale oltre che metrica decisiva nell’ecosistema Flowing. Un progetto tecnicamente perfetto diventa fallimentare se non si sostiene economicamente. E’ importante che il team conosca la redditività del progetto e per farlo sono necessarie le informazioni di ingaggio contrattuale e l’effort utilizzato da tutto il team. L’ingaggio contrattuale contiene le informazioni sulla tariffa, sull’eventuale monte giornate a disposizione o sul costo dell’iterazione. Il tempo speso dai surfer su quel progetto è recuperabile dal software di time tracking. Incontrando questi due dati è possibile ottenere le informazioni di redditività di ogni progetto indipendentemente dal tipo di contratto. Se la redditività è inferiore alle aspettative si consiglia di invocare un confronto nel rito di planning.

**Qualità del rapporto col cliente**
: La qualità del rapporto col cliente va salvaguardato perché catalizzatore di tutti i punti precedenti. Un buon rapporto col cliente contribuisce alla serenità del team, permette una più semplice negoziazione e discussione sulle aspettative e sulle scadenze e velocizza il raggiungimento del regime di fiducia che si ripercuote positivamente sul planning del progetto e quindi sulla redditività. Salvaguardare un buon rapporto richiede la stessa sensibilità dei rapporti sociali in generale. Volendo dare degli spunti potremmo sintetizzare con: ascolto, propositività, calibrazione nelle conversazioni, empatia verso la posizione/problematiche del nostro referente. A queste possiamo aggiungere la capacità di trasmettere al cliente:
* concetti che potrebbero essere a lui nuovi (senza farlo sentire inappropriato) 
* il concetto di team inteso come gruppo di lavoro che opera insieme in funzione di un obiettivo, scardinando la classica visione di cliente/fornitore dove gli interessi personali diventano disfunzionali al progetto.

## Come gestire il SoR quando…

> **Qual è il modo giusto per raccontare il SoR ad un cliente abituato ad altri tipi di contratto?**
È difficile rispondere a questa domanda in poche righe. Prima di tutto è importante capire il contesto e chi sono gli interlocutori per meglio calibrare lo storytelling. E’ necessario investire molto tempo a spiegare cosa significa secondo noi sviluppare un software; spesso viene semplificato con “ti dico cosa voglio, me lo stimi e lo fai”, il contratto è una conseguenza di questo pensiero - quindi tendenzialmente, a corpo. Una delle frasi chiave è “il software è un processo di learning” che spesso fa riflettere l’interlocutore. Spesso poi una discovery fa emergere ambiguità che non fanno che confermare questo pensiero, per partire con una discovery è un ottimo primo step.
Si può far leva sulla condivisione del rischio che nelle altre tipologie di contratto è sbilanciata da una parte o dall’altra.
Ricorda sempre che nel tuo team ci sono anche i sales che possono aiutarti nel racconto a referenti del cliente di più alto profilo con i quali non ti interfacci quotidianamente.

> **Quali sono i concetti chiave da ripetere ossessivamente?**
* capire che lo sviluppo è un processo di learning
* consegna di valore vs allocazione di giornate
* iterazioni brevi e costanti

> **Quali sono gli errori da non fare e che rischiano di trasformare il SoR in un’altra cosa?**
* parlare di tempo invece che di valore durante la negoziazione
* quando veniamo meno al prezzo fisso dell’iterazione (riduzione di effort concordato con il cliente, allungamento dell’iterazione)
* non avere un feedback chiaro e scritto del PO contestualmente alla fine dell’iterazione
* non avere un PO in grado di decidere se accettare o meno l’iterazione (in quel caso bisogna capire chi ha questa responsabilità e farlo partecipare agli IM)

> **Come gestisco il fatto che il cliente si basa già su un framework agile (tipo Scrum)?**

Di base, l’approccio agile di Flowing e il contratto SoR non sono in contrasto con altri framework, anzi, si potrebbe sfruttare l’approccio del cliente (se davvero usa Scrum e non solo a parole) come boost per massimizzare il valore rilasciato.
Il cliente potrebbe imponerre riti come standup, review, planing, retrospective. L’aspetto che va chiarito è che il team Flowing non è a disposizione full time (non siamo body rental) e che quindi potrebbe non essere presente a tutti i riti con tutti i membri del team. Per il resto non ci sono grosse differenze se non che quello che per Flowing è un Iteration Meeting, per un cliente con Scrum è splittato in più riti (review e planning).
Potrebbero sorgere problemi qualora il cliente imponga sprint troppo lunghi (1 mese) o se il team Flowing non è autonomo nel portare avanti i propri obiettivi, come quando si dipende da risorse interne al cliente che sono organizzate con logiche diverse. Se non si riesce a trovare un modo di far convivere il SoR con l’organizzazione interna del cliente si potrebbe decidere anche di non usare un SoR, ma altri tipologie di contratto.

> **Come gestisco il fatto che il cliente lavora su sprint più lunghi di 1 settimana?**
Come puoi aver letto nel paragrafo “Quanto dura un’iterazione?” cerchiamo sempre di avere iterazioni di una settimana. Quando questo non è possibile devi tenere in considerazione i rischi che come Flowing stiamo incamerando. Considera che in un’iterazione più lunga abbiamo più skin in the game, perché stiamo promettendo il lavoro di due settimane piuttosto che di una. Quindi in questi casi il team deve fare particolarmente attenzione nel pianificare l’iterazione tenendo a mente questo rischio.

> **Ed è un problema se a gestire questi riti è il cliente e non Flowing (cioè, il pallino del gioco non è il nostro)?**
L’importante non è chi modera i vari riti, ma come viene portata avanti la fase di negoziazione in modo da condividere un output che massimizzi il valore e non una mera lista di funzionalità o di pezzi di codice. Ricorda, il tutto si basa sul valore rilasciato e il valore rilasciato non è “quanto codice ho scritto”.

> **Cosa devo rispondere ad un cliente che continua a chiedermi “ma per questo quanto ci vuole”?**
Prima di tutto bisogna capire che necessità copre l’esigenza di avere una stima e, di solito, avuta questa risposta, diventa più semplice formulare una risposta che non comprenda una stima in tempo.
Inoltre va ricordato al cliente che una stima in tempo non è mai una previsione affidabile perchè non tiene conto di altri fattori, come il fatto che una card potrebbe essere fumosa (magari servono delle spike per capire meglio) o il fatto che il team deve apprendere dei concetti di dominio che ancora non conosce.
Pesare una card quindi non significa dare un tempo di esecuzione, ma definire un punteggio che aiuta al cliente e al team quali sono le attività più grandi e fumose.

> **Come gestisco il fatto che in alcuni periodi il team non è al completo (per ferie, per emergenze o per altre attività Flowing)?**
La cosa migliore è fare in modo che il team, in fase di negoziazione, sia in grado di calibrarsi per garantire ugualmente un valore adeguato (es i membri del team presenti riescono a sopperire la mancanza degli assenti). E’ indice di serietà, che il cliente in genere apprezza, anticipare le problematiche e sapersi organizzare di conseguenza.	 
Se questo non fosse possibile si può ragionare su
* verificare al planning chi altro può aiutare il team nella fase critica
* concordare con il cliente una riduzione del valore generato nell’iterazione che verrà recuperato nelle prossime (meglio nelle precedenti)
* prevedere un allungamento dell’iterazione a 2 settimane ritardando il delivery concordato

> **Cosa fare nel caso in cui nell'iterazione sono entrati nuovi task da fare (non prevedibili) e il cliente non vuole eliminare le storie ancora da fare per fargli posto?**

Di base è una richiesta che non può essere accettata. Se il cliente vuole aggiungere un nuovo task deve scegliere cosa far cadere dalla torre. Siamo pronti al cambiamento e dobbiamo saper accogliere le richieste se questo porta ad aumentare il valore rilasciato.
Se il cliente non è disposto a togliere qualcosa, in via del tutto eccezionale, si può accettare la richiesta chiarendo che si tratta di un’eccezione, che non possiamo promettere di completare il task per il prossimo IM e che questo può incidere su tutta la promessa fatta allo scorso IM, cioè “proveremo a fare il meglio possibile, ma non promettiamo nulla”

> **Come devo “vendermi” l’output se non ho raggiunto gli obiettivi concordati? Potrebbero essere sorti problemi di qualsiasi natura, anche non imputabili al cliente (ho avuto la febbre) per cui la storia che sto portando avanti non è completa e il team non riesce a sopperire alla mia mancanza.**

Se il team si rende conto di non essere in grado di consegnare il valore concordato per motivi non imputabili al cliente dovrà, in primis, avere cura di condividere con il cliente questa problematica, per evitare sorprese negative che non sono mai ben accette.
Poi, al successivo IM si verifica cosa manca e si condivide un piano per completare il lavoro nell’iterazione successiva, che sarà quindi un po’ più carica del solito.
In un regime di fiducia, questo basta per proseguire.
Se il cliente contesta l’iterazione per una piccola mancanza, probabilmente il regime di fiducia è venuto meno e il problema è più grande del mancato completamento di un task.

> **Cosa succede se il cliente mi contesta l’iterazione?**

Il SoR prevede la possibilità che il cliente contesti un’iterazione. Questo può avvenire se il valore consegnato è molto distante dall’aspettativa. E’ importante quindi capire la causa di questa ambiguità nel modo che il team ritiene più opportuno (retrospettiva?).
Si deciderà poi insieme al cliente la strada da seguire: continuare a lavorare insieme cercando di migliorare ad ogni iterazione o interrompere la collaborazione.

> **Come trattare le attività “time consuming” che non producono un valore facilmente raccontabile senza scendere nel concetto di “tempo”?**

Ci possono essere vari pattern. 
Immaginando che queste attività siano in backlog e quindi visibili in anticipo rispetto all’esecuzione, il team si può preparare facendo “cassa” cercando di spendere il meno possibile nelle iterazioni precedenti per avere un margine di manovra quando arriverà il momento dell’attività time consuming.
Quelle invece che sono sia time-consuming che corpose potrebbero essere gestite facendo capire che occupano “tempo” senza specificare quanto. Se poi il problema persiste per i processi del cliente vedo tre strade:
* Si risolve in retrospettiva modificando il processo e indicando che il nostro team sta sottoperformando
* Si accetta che è così e a quel punto tutte le iterazioni saranno molto conservative lato flowing per accogliere le attività time-consuming
* le attività time-consuming si mettono in un contratto separato diverso dal SoR

Di base se il team deve fare qualcosa per il progetto, significa che sta portando valore.
Ad esempio, se scrivi un documento che nessuno leggerà, lo fai presente. Se te lo fanno fare ugualmente la tracci come attività e la pesi nell’iterazione come fosse una user story.
Un backlog non ha solo storie fine all’utente, ma anche fine al PO, al team, agli stackeholder… alla “politica” potrei pure dire.
Tutto quello che il team fa per agevolare, migliorare, supportare il PO/cliente - si paga, e il valore va fatto percepire.

> **Cosa fare quando il cliente propone di spingere per le prossime N iterazioni per poi andare più blandi?**

In questo caso dipende dal numero di iterazioni coinvolte nel boost richiesto. Se sono un paio di settimane è fisiologico ed è completamente gestibile dal team, anzi cogli l’occasione di rimarcare che è proprio grazie a questo contratto che si può ottenere questa flessibilità. Se invece il tempo è superiore alle 2 settimane è consigliabile l’intervento di un commerciale per rivedere il contratto e aumentare il costo dell’iterazione. Se il periodo è medio-lungo infatti diventa poi molto difficile per il team recuperare l’effort speso in più, diventando quindi molto rischioso per noi.

> **Come vanno trattate le attività di consulenza all'interno di un'iterazione? (Non ci si riferisce ad un "consiglio" a spot, ma un'attività dove è richiesto dell'effort significativo)**

Se si tratta di un’attività di coaching “spot” o di una consulenza tecnica o architetturale specifica può essere trattata nell’iterazione sottolineando che il valore di una consulenza è in genere maggiore di un’attività di sviluppo.
Se le attività diventano importanti si può suggerire una discovery o un altro format in grado di soddisfare l’esigenza del cliente e portare l’attività in altri contratti ad hoc (corpo o T&M)


