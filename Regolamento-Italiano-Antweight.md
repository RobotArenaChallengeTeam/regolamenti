# ﻿Regolamento italiano Antweight - Regole costruttori
Il seguente documento regola la costruzione dei robot, il formato dell’evento e le procedure a cui i partecipanti si devono attenere per partecipare alle competizioni Antweight in Italia. In quanto competizione di robot da combattimento distruttivi, in questo documento sono compresi tutti i requisiti di sicurezza obbligatori da seguire per la costruzione e l’utilizzo dei robot durante l’evento. La categoria di competizione del presente regolamento è già nota come Antweight 150g in ambito europeo o come Fairyweight in USA.

Chiunque in italia puó utilizzare questo regolamento per i propri eventi purché sia: o linkato direttamente in cima al documento dell'evento in questione, o copiato integralmente, oppure allegato integralmente in formato pdf. Possono essere apportate modifiche menzionando i vari punti del regolamento e riscrivendoli nel proprio documento. Dovranno inoltre essere inserite nel documento dell'evento una descrizione dell'arena, del formato, dei criteri di giudizio scelti qualora diversi da quelli di battlebots e la durata degli incontri.

## Riferimento regole internazionali
Questo documento riprende il regolamento Antweight World Series (https://www.robotwars101.org/ants/rules.htm) con la sola modifica sostanziale nel punto 2b) Antweight 101.6mm -> 100mm, attuata per rendere un robot costruito per questo evento valido anche per eventi a livello europeo o intercontinentale. Per qualsiasi eccezione e approfondimento rimandiamo quindi al regolamento AWS, che verrà utilizzato dai giudici come riferimento in caso di situazioni particolari.
## 1) Definizioni
* Roller: un robot che per muoversi usa ruote o sistemi di movimento capaci di rotazioni intere a contatto con il terreno. (Es: ruote e cingoli.)
* NON-Roller: qualsiasi robot non incluso nella categoria Roller. (Es: Walker, Shuffler, Bristle Drive, Gyro-Walkers, Hovercraft.)
* Flyer: robot che si può mantenere in volo, questa tipologia di robot non é permessa.
* Clusterbot: un robot composto da più parti separate.
* Robot modulare: progettato con la possibilità di montare diverse parti (armi, forche, paratie,...) a seconda dell’avversario da affrontare.
* Arena: l’area all’interno della quale i robot possono combattere, chiusa su tutti i lati e sul soffitto.
* Pit o botole: zone sul piano dell’arena o lungo i suoi bordi in cui i robot potrebbero cadere.
* Safety Link: una parte rimovibile di un circuito elettrico del robot che chiude il circuito solo una volta inserita, o due connettori esposti che possono essere manualmente separati.

## 2) Regole per i robot
### Peso
A. Usando una bilancia con una precisione di +-0.01g il limite di peso della categoria è 150.0g per i Roller e 225.0g per i NON-Roller (si consiglia i costruttori di arrivare ad un peso massimo di 149.5g o 224.5g per mettere in conto eventuali differenze nella calibrazione delle bilance, o in alternativa prevedere facili alleggerimenti di 1g per compensare tali variazioni).
  1. Un Clusterbot deve rientrare nei limiti di peso sommando i pesi di tutte le sue parti. In caso di robot modulari il limite di peso viene misurato nella configurazione più pesante.
  2. Oltre al robot anche eventuali copie pre-assemblate di backup verranno pesate preventivamente. In caso di modifiche/riparazioni durante il torneo il peso verrà nuovamente misurato e dovrà sempre essere sotto il peso massimo di categoria.
### Dimensioni
B. Il robot deve entrare completamente in un cubo con lati di 100mm, anche sfruttando la diagonale o posizioni inclinate.
  1. Tutte le parti di un Clusterbot devono entrare completamente in un singolo cubo.
  2. Il robot potrà essere in grado di espandersi oltre il volume del cubo solo se questa espansione è attivata da controllo remoto dopo l’inizio del combattimento (Es: NON con estensioni per gravità.)
  3. Se l’espansione di una parte di un Clusterbot é attivata da un’altra delle parti, entrambe devono cominciare posizionate così come rientrano nel cubo, altrimenti sono libere di cominciare come diversi robot affiancati.
### Elettronica
C. Interruttore generale: il robot deve essere dotato di un interruttore o safety link in grado di scollegare l’alimentazione da tutta l’elettronica che sia accessibile dall’esterno a mano.
  1. Power led: il robot deve esser dotato di un indicatore luminoso che sia sempre acceso o al massimo lampeggiante quando il robot è alimentato, e possa essere completamente spento solo utilizzando l’interruttore generale.

D. Frequenze ammesse: il radiocomando può utilizzare le seguenti frequenze: 27 MHz, 40MHz, 418 MHz, 433-434 MHz, 868 MHz e 2.45 GHz purché seguendo tutte le corrispondenti regolamentazioni.

E. Interruttore remoto: le armi del robot devono avere la possibilità di essere disattivate da remoto e disattivarsi automaticamente in caso di failsafe.

F. Failsafe: il robot deve arrestarsi completamente quando la trasmittente è spenta o in caso di perdita di segnale.

### Armi
G. Tipi di armi non concesse:
* colla o superfici adesive
* fluidi pericolosi o sversamento di fluidi
* armi con scopo di inceppare l’avversario
* fiamme ed esplosivi
* armi rotative che possono frammentarsi invece che rompersi
* RF jamming, sistemi di interferenza radio
* taser o sistemi che usano l'elettricità come arma
* induzioni o sistemi magnetici (NB: sono concessi solenoidi come attuatori)

H. Limiti di pressione: ogni sistema che utilizzi liquidi o gas sotto pressione per attuatori è limitato a 7bar.

I. Proiettili: le armi non possono essere progettate per staccarsi completamente dal robot, ma possono essere parzialmente separate purché connesse da un filo di non più di 90cm. il filo non può essere usato come arma di inceppamento.

J. Parti acuminate o taglienti: tutte le parti acuminate o taglienti del robot dovranno avere delle coperture protettive e chiaramente distinguibili mentre non in arena.

K. Batterie: le batterie non potranno contenere acidi o elettroliti liquidi e sono limitate ad un massimo di 24v come tensione misurata da cariche.

## 3) Arena
* L’arena da combattimento è un volume chiuso per evitare la fuoriuscita di pezzi e detriti, come materiale per la costruzioni di lati trasparenti dovrá essere usato policarbonato con uno spessore minimo di 4mm per motivi di sicureza. I robot combatteranno su una superficie piana, nella quale possono essere piazzate botolo o hazards. É caldamente consigliato che all'evento sia presente una Test Box nella zona Pit, un cubo anche inferiore ai 50cm di lato con pareti in legno ed una faccia trasparente per poter accendere il proprio robot e testarlo in sicurezza durante i controlli pre-torneo o dopo le riparazioni, o che in sua vece sia possibile utilizzare l'arena.
* **Per maggiori dettagli sulle specifiche dell'arena consultare il documento fornito dall'organizzatore del singolo evento che linka questo regolamento**

## 4) Combattimenti
Il formato consigliato per gli eventi é un tabellone a Doppia Eliminazione, che garantisce ad ogni robot un minimo di due combattimenti, più un’eventuale Royal Rumble a fine giornata a cui possono partecipare in contemporanea tutti i robot ancora funzionanti. Consigliamo quindi di portare ricambi almeno per poter affrontare un secondo combattimento durante il torneo principale. Ma è fortemente consigliato portare svariati ricambi per poter garantire il funzionamento del robot con il procedere del tabellone.
* Ogni combattimento ha la durata massima consigliata di 3 minuti, durante la quale i robot hanno l’obiettivo di incapacitare l’avversario.
* Passato il tempo limite senza incapacitamenti, o in caso di incapacitamenti simultanei, una giuria di 3 giudici decide l’esito del combattimento secondo i criteri di giudizio consigliati di BattleBots: Danno, Aggressività e Controllo. (https://battlebots.com/wp-content/uploads/2021/06/Judges-Guide-Rev.2021.0.pdf)
* **per il reale formato del tabellone, la reale durata massima dei combattimenti, ed i critetri di giudizio scelti consultare il documento fornito dall'organizzatore del singolo evento che linka questo regolamento**
* Al temine di un combattimento, in caso di resa o in caso l’arbitro chiami una pausa, i robot dovranno immediatamente cessare qualsiasi funzione ed andare in uno stato di failsafe.
* Un robot che cade all’interno di una botola o fuoriesce dai limiti dell'arena qualora possibile si considera immediatamente incapacitato.
* Regola dell’aggressore: in caso in cui più robot cadano all’interno della botola insieme, ed é chiaro chi ha compiuto l’azione di spinta, quel robot verrà giudicato vincitore.
* Un robot si considera immobile quando non più in grado di traslare o ruotare, sia se ciò avvenga per danni sia se il robot risulta incastrato in arena o in bilico.
* Un robot si considera incapacitato quando immobile per più di 10 secondi, qualsiasi contatto con l’avversario durante il conto alla rovescia corrispondente riavvia il conteggio da 10
* Un robot si considera incapacitato se la sua batteria fuoriesce dal telaio o risulta eccessivamente esposta.
* Durante un combattimento, un pilota può arrendersi dicendo STOP e bussando su una parete dell’arena, in quel caso il suo robot viene immediatamente dichiarato incapacitato.
* Un robot che non ingaggia contro un avversario mobile ma non in grado di traslare in arena viene penalizzato nella criterio di giudizio Aggressività.
* I robot possono afferrare o tenere l’avversario contro le pareti dell’arena per un massimo di 10 secondi. Dopo lo scadere di questo conteggio sono obbligati a rilasciare l’avversario. In caso di mancata separazione l’incontro viene messo in pausa ed i robot separati manualmente. Mantenere la presa fino allo scadere del countdown influenza positivamente il criterio di giudizio Controllo.
* In caso di robot incastrati tra loro, dopo 10 secondi (o prima se entrambi i piloti dichiarano di essere incastrati) il combattimento viene messo in pausa ed i robot separati manualmente. Se i pezzi responsabili dell’incastro devono essere rimossi per effettuare la separazione non potranno essere rimontati sul robot prima della ripresa dell’incontro.
* Durante qualsiasi pausa durante un combattimento non è concesso sistemare o modificare i robot.

link utili per le comunitá di costruttori di robot in italia:
[Discord](https://discord.com/invite/zKuerqs6EP)

## Altro
Revisione principale del regolamento a cura di Robot Arena Challenge,il regolamento qui presente é sotto licenza MIT, per qualsia chiarimento contattare:

rac@studio5t.com
[Instagram](https://www.instagram.com/robotarenachallenge/)
[YouTube](https://www.youtube.com/channel/UCQnjBZ0KMxlHL-30ejunIVA)
[Facebook](https://www.facebook.com/RobotArenaChallenge)

<div align="center">
<img src="/immagini/loghi/Logo-RAC-trasparente.png" alt="logo" width="200"/>
</div>
