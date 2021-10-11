# Presales

In Flowing le attività commerciali non sono ad appannaggio esclusivo del nostro reparto sales, ma in ogni fase della trattativa commerciale c’è sempre la presenza di un Surfer operativo che fa da spalla al commerciale per costruire a quattro mani la proposta migliore possibile. È dunque importante conoscere le caratteristiche di tutti i nostri servizi principali e delle forme contrattuali.
Tipologie di contratto

Quando parte un nuovo progetto utilizziamo tre tipologie di contratto: Soddisfatti o Rimborsati (SoR), Time and Materials (T&M) e a Corpo.

## Soddisfatti o Rimborsati

È la tipologia di contratto che più ci caratterizza e ci identifica. Puoi leggerne una versione semplificata su GitHub[^github]. *In a Nutshell*, il contratto SoR sancisce tra noi ed il nostro cliente, una modalità di lavoro basata sul valore e non sul tempo che il team impiega a produrre quel valore. Quando si lavora con un contratto SoR infatti il costo di una Iterazione[^iterazione] (settimanale o bi-settimanale) viene definito all’inizio del progetto e non è strettamente legato al tempo che il team lavora per il cliente durante l’iterazione.

Il fattore più caratteristico di questa tipologia di contratto è che il valore prodotto durante lo sprint deve essere ritenuto congruo dal cliente in base al costo dell’iterazione (e viene fatto nell’iteration Planning) e anche validato una volta consegnata la delivery dello sprint (viene fatto nell’iteration review). Il cliente può quindi non accettare l’iterazione se non incontra le sue aspettative. Quando succede il team ha l’onere di cercare di capire come mai quest’ultime sono state disattese, cercando di lavorare su vari aspetti della comunicazione con il cliente. Se il team crede che non ci siano le condizioni per lavorare con il cliente, perché magari non ha colto il funzionamento alla base del contratto SoR allora si procede con un Kill[^kill] e il progetto si conclude.

Il progetto va poi avanti di iterazione in iterazione, fino alla sua naturale conclusione.

### Principi

#### Skin in the game

Se guardassimo al solo bene di Flowing, il contratto SoR per noi sarebbe uno svantaggio. Per ogni iterazione mettiamo sul piatto infatti il fatto che potremmo lavorare gratis. Se guardiamo però al sistema Flowing/Cliente questo rischio viene mitigato dal fatto che il nostro Skin in the game è il più grande acceleratore verso un regime di fiducia — sano e duraturo — con il cliente. Mettendoci in gioco stiamo garantendo che faremo tutto il possibile per consegnare il valore pattuito. Questo atteggiamento, che all’inizio sembra spiazzare i clienti, dopo pochissimo tempo si trasforma in una macchina ben oleata.

Però, per poter funzionare, il SoR deve essere usato in condizioni in cui il team è in grado di fare promesse e rischiare il proprio lavoro. Se ci sono degli anti-pattern che non permettono al nostro team di lavorare in totale autonomia, spesso il SoR diventa difficoltoso da gestire. Sono alcuni esempi i progetti di team augmentation in cui dobbiamo lavorare a stretto contatto con il team cliente o quando il nostro lavoro è bloccato da un reparto del cliente, come ops o QA. In questi casi potrebbe essere più prudente utilizzare un contratto Time and Materials che ha meno vincoli per noi.

#### Centrato sul valore

Nella spiegazione che abbiamo fatto del SoR non si parla mai di “tempo” ma solo di “valore”. Questo perché definendo il costo di un’iterazione senza rendere palese il tempo ci permette di tenere tutte le conversazioni centrate su “Quanto valore porta” e non sul “Quanto ci mettiamo ad implementarlo”. Questo aspetto ha lo scopo di evitare discussioni (e ancoraggi) tipici di altre tipologie di contratto che rendono poi le discussioni difficoltose, poco fluide e soprattutto sterili.

#### Mappa/Territorio

La decisione di cosa fa parte di ogni singola iterazione viene fatta di volta in volta durante l’Iteration Planning. Questo permette al cliente di cambiare — anche radicalmente — il volto del progetto, non seguendo per forza il percorso stabilito in fase di Discovery. Ricorda, in un progetto software non bisogna mai confondere la mappa con il territorio. È giusto modificare il piano che abbiamo concordato con il cliente se le condizioni cambiano, ed il contratto SoR è il miglior strumento che abbiamo per farlo.

#### Decisionalità

Parlare di valore non di tempo ci dà un vantaggio strategico rispetto alla concorrenza. Possiamo decidere in autonomia il “come” portare valore al cliente. Possiamo infatti decidere come investire il tempo senza dover per forza accordarci con il cliente, dato che la discussione è sempre incentrata sull’outcome. Come organizzare il lavoro — ad esempio decide se fare pair o no — e la quantità e la modalità di testing sono tutte decisioni che spettano al team.

### Come Funziona

Eccoti una piccola guida pratica al SoR. Come vedi l’Iteration Meeting (diviso in Review e Planning) è una parte centrale del flusso. Fai riferimento al capitolo dedicato per approfondimenti.

1. Ogni iterazione inizia con un Iteration Planning in cui il team ed in cliente decidono quali sono le attività che verranno svolte all’interno di quell’iterazione.
2. Il Team Flowing lavora all’iterazione, facendo il possibile per portare a termine le attività.
3. Alla fine dello l’Iteration Review il cliente valida il lavoro fatto, decidendo se vuole pagare l’iterazione oppure no.
    1. Se il cliente dà un esito positivo l’iterazione verrà fatturata ed il progetto continua per l'iterazione successivo
    2. Se il cliente invece decide di non pagare l’iterazione, Flowing può decidere di continuare a lavorare con il cliente (non incassando l’iterazione) oppure concludere il progetto
4. Il progetto continua con questo flusso fino a che il progetto non si conclude in maniera “naturale”

{width: "75%"}
![Figura 2.1 - Flowchart del SoR](SOR.png)

## Time and Materials

Nei contratti di tipo Time and Materials, il cliente conosce il nostro costo a giornata. In questo caso quindi a differenza del SoR il tempo ha un fattore preponderante. Assicurati che nell’IM sia sempre ben chiaro il tempo investito e quindi il costo che il cliente si troverà ad affrontare. Questo ci permette di evitare sorprese in fase di fatturazione.

## A Corpo

Il contratto a corpo, quello dove prezzo e scope sono definiti a priori è una tipologia di contratto che cerchiamo di evitare perché:

Non permette cambi di rotta
Il rischio del fallimento è tutto a carico di Flowing

Detto questo, può succedere che per alcuni motivi decidiamo di lavorare con un contratto a corpo pur di prendere un cliente. Potrebbe essere un progetto piccolo con un cliente nuovo, dove quindi calibriamo bene costi e benefici. Oppure altri vincoli contrattuali come la partecipazione ad una gara.

Il team in questo caso deve stare attento fondamentalmente al budget e a gestire bene i cambi di rotta che — a prescindere da cosa c’è scritto sul contratto — arriveranno. Troverai una serie di consigli sul capitolo dedicato all’Iteration Meeting che anche in questo caso ha un ruolo fondamentale.

## Product Discovery

La Discovery (letteralmente tradotto: *scoperta*) è il primo passo del team Flowing verso le esigenze del cliente. Il primo incontro dove un team cross-funzionale dedica uno o più giorni a comprendere gli obiettivi del cliente, capire come validarli sui bisogni degli utenti e ipotizzare una roadmap da intraprendere. Queste informazioni sono appunto delle “scoperte” per il team ma anche per il cliente stesso. Il team tecnico e cross-funzionale infatti è in grado di portare il punto di vista delle diverse professionalità, dagli esperti di interazione utente, ingegneri del software e specialisti delle architetture. Tutte le competenze che possono stressare e/o individuare i principali road-block dell’idea del nostro cliente.
Ecco che la Discovery non ha solo il valore del suo outcome, ovvero il piano di azione. Ma il più grande valore è la consapevolezza che ha generato nel nostro cliente. E averlo fatto insieme ha gettato il primo seme verso un team unito (team Flowing e cliente) che ha un obiettivo comune. Motivo per cui la Discovery non è né un’analisi del problema, né un momento conoscitivo. E’ il primo lavoro che il team Flowing fa per il cliente: un lavoro di scoperta e consapevolezza.
Dalla Discovery possono emergere diverse attività in base al progetto e allo scenario. Potranno avviarsi attività sull’infrastruttura, spike tecnologici, attività di user research o un primo backlog di features da espletare che sarà poi suddiviso in rilasci con la granularità delle user stories e gestito con un approccio agile e iterativo.
Anche se la Discovery varia di volta in volta a seconda dello scenario ci sono quattro tipi di approcci che teniamo in questa fase:

**Discovery generica**
: un formato che prevede un’agenda esplorativa con un focus generico volto a stressare l’idea e i bisogni di business. Ha l’obiettivo di fare chiarezza, allineare cliente e team Flowing e sottolineare i punti di forza e le mancanze del progetto in base alle aspettative.

**Assessment infrastrutturale**
: una Discovery con focus prevalentemente sull’infrastruttura con l’obiettivo di portare alla luce gli interventi necessari per renderla adeguata alle esigenze.

**Architectural clash**
: un format con scope specifico per progetti o software in cui la scelta tecnologica diventa una scelta strategica.

**Software renovation sprint**
: una Discovery con un focus sullo stato del progetto volto a mappare lo stato dell’arte e individuare le attività principali per renderlo scalabile in modo efficace.

Tuttavia la Discovery non è solo il primo incontro. Discovery è anche un *“tag”* che adoperiamo per tutto un flusso di attività che vengono svolte anche durante il progetto, in modo iterativo o continuo. Il valore che il team Flowing eroga infatti non è solo nella “delivery” (attività di rilascio infrastrutture, codice e/o design) ma anche nelle attività di “learning” (analisi, ricerche utenti, spike, demo). Le fasi di learning si parallelizzano alle attività di delivery e impegnano il team a rinnovare la consapevolezza sulle evoluzioni del progetto. In questo modo si mantiene sempre la bussola sugli obiettivi di business e sui bisogni degli utenti evitando tutti gli antipattern classici di un processo di sviluppo asettico che causa il distorto obiettivo di espletamento del backlog fine a se stesso.

**Chiamiamo questo processo Continuous Discovery, più comunemente noto come Dual Track Agile.**

## Cross-Funzionalità

Quando stai costruendo una proposta insieme al commerciale, ricordati del resto delle Skill che Flowing può mettere a disposizione. Questo soprattutto quando ti viene chiesta una Skill specifica. Spesso problemi che sembrano di mero sviluppo si risolverebbero meglio con della UX, o con un lavoro sull’infrastruttura cloud. In questi frangenti ascolta la desiderata del cliente, ma sii pronto a fare una proposta diversa.

[^github]: <https://github.com/flowingis/money-back-guarantee-contract>
[^iterazione]: <https://www.agilealliance.org/glossary/iteration>
[^kill]: <https://www.flowing.it/blog/agile-planning-e-decisioni-keep-kill-transform/>