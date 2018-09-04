---
title: Past, present and future of an economic network
date: 2018-09-04
tags:
    - Agent
---

## 📖 Passato
Il progetto Agent nasce *ufficialmente* durante l’estate 2017, nei giorni del summercamp di FairCoop in Jura (Svizzera).   
Diverse persone metterebbero in dubbio questa notizia, tanto quanto l’esistenza stessa di Bernini, che di fatto ha smesso di comparire - da un po' - nelle chat di telegram (ora mi trovate come @ivanminutillo).  
Ad oggi, lo sviluppo di Agent ha richiesto 509,4 ore di lavoro pagate in faircoin ( ben più del doppio se contiamo quelle volontarie, sempre contando solo le mie), 364 commit su github, divisi tra i vari repository e 31 issue aperte e 26 chiuse.  
Il lavoro su Agent ha permesso al tempo stesso di creare una [component library open source](kit.opencoopecosystem.net) in React ed una [wiki](doc.opencoopecosystem.net) che racconta la visione e i  componenti principali di un’infrastruttura economica decentralizzata, aperta e basata su vocabolari e protocolli condivisi.

Fin da subito, Agent ha saputo contare su un gruppo fidato di persone a fargli da famiglia.   
FairCoop ha degli individui rari al suo interno e alcuni di loro si sono presi carico - armati di pazienza, esperienza e intelligenza - del nuovo arrivato, aiutandolo ad evolvere e migliorare giorno dopo giorno.   
Il processo di co-creazione e sviluppo di Agent è stato emozionante, snervante e formativo.  
Avere la possibilità di collaborare quotidianamente con Lynn & Bob è una fortuna.   
Mi hanno aiutato a mettere in discussione il pragmatismo classico dello scrivere software secondo le metodologie più in voga, unendo la visione politica e sociale a quella tecnica.  
Per non parlare del lato umano e della dedizione che mostrano giorno dopo giorno, nel portare avanti la visione e lo sviluppo di un'infrastruttura che possa supportare nuovi e ancora sconosciuti sistemi economici. Sempre cercando di non imporre idee assolute, ma supportando quasi in ogni linea di codice idee alternative a quelle del capitalismo odierno (vi consiglio di approfondire il loro lavoro direttamente [sul loro sito](https://mikorizal.org)).
Lo sviluppo di Agent si basa su un assioma preciso:
Il software viene scritto solo in funzione di supporto ad una necessità concreta esposta da una comunità.  
Ogni features è implementata in base alle necessità della comunità che lo adotta e le priorità sono decise in assemblee e revisionate mese per mese.  
Così durante il 2018, Agent si è evoluto in base alle necessità di Open Coop Work, il primo gruppo ad utilizzarlo.     
Open Coop Work (OCW) è una cooperativa nata per organizzare il lavoro interno di FairCoop.   
All’interno di OCW sono presenti 5 aree divise per tematiche (Tech, Communication, Common Management, Welcome, Circular Economy). 
Ognuna di queste, attraverso assemblee, stabilisce mensilmente il lavoro da fare. 
OCW è un network aperto e chiunque può partecipare in una o più aree e contribuire a portare a termine dei lavori. 
Sempre mensilmente OCW valida il lavoro di ogni partecipante e distribuisce un compenso, secondo un protocollo deciso in assemblea.

Il flusso appena narrato, è in linea di massima anche ciò che ad oggi il software permette di fare. 
> In breve Agent facilita la creazione e distribuzione di valore all'interno di un ecosistema decentralizzato ed orizzontale.

1. Permette di creare piani di lavoro e ad ogni partecipante di inserire il proprio contributo. Ogni piano può contenere processi creati da un unico gruppo o  gruppi diversi, creando una contaminazione di abilità e visioni.

![](https://i.imgur.com/cCPQEN4.jpg)


2. Permette di avere una visione generale degli eventi che accadono nei gruppi di cui l'utente fa parte, dei piani aperti o conclusi e delle risorse disponibili.

![](https://i.imgur.com/bs3zH5g.jpg)

3. Permette di validare, secondo un protocollo ben definito, il lavoro svolto da ogni individuo, per poi effettuare la distribuzione del budget mensile.

![](https://i.imgur.com/xyTeHOB.jpg)


## 🚀 Presente
Nodi locali, centri culturali e altri gruppi esterni all’ecosistema FairCoop stanno testando l’adozione di Agent.
Il valore aggiunto per le loro necessità, oltre l'organizzazione del flusso di lavoro, è la possibilità di tracciare risorse, che possono essere prodotte o utilizzate durante piani di lavoro, oppure scambiate tra altri gruppi del network, favorendo la creazione di una rete di economia circolare.

![](https://i.imgur.com/HIPlNNY.jpg)

Un'altra feature chiave è il wallet, che permette di gestire crypto e monete sociali in modo facile e trasparente, all’interno di gruppi.

![](https://i.imgur.com/G6XMrUb.jpg)

Queste features sono attualmente in lavorazione, e occuperanno buona parte dello sviluppo di fine 2018. 


## 🛸 Futuro
Il futuro di Agent è decentralizzato e non si chiamerà Agent.
Il 2018 è stato pieno di discussioni e ricerche, avvenute all'interno di chat e communità diverse, che infine hanno portato alla scelta di [ActivityPub](https://www.w3.org/TR/activitypub/#Overview), come protocollo su cui implementare la prima versione di un software economico distribuito, estendendo il suo vocabolario (ActivityStream) attraverso quello di [ValueFlows](https://valueflo.ws).
Il futuro, in versione embrionale, è già su GIT e si chiama [Pub Of The Commons](https://gitlab.com/OpenCoop/CommonsPub). Un fork di [Pleroma](https://git.pleroma.social/pleroma/pleroma/), ad opera di [Mayel](https://mayel.space/), nato per creare un server ActivityPub generico, sul quale costruiremo il nostro network economico.  
**Il futuro è agent-centric.**   
Ogni persona avrà la sua istanza, e potrà federarsi con altri partecipanti, siano essi altri individui, gruppi o bot, mantenendo pieno controllo dei propri dati.
Il software terrà traccia di tutti gli eventi creati all’interno dei vari network, come una sorta di dashboard personale. 
Questa dashboard permetterà all'utente di compiere ogni tipo di attività: sia essa sociale, economica o politica, attraverso una pletora di applicazioni che implementeranno protocolli e vocabolari compatibili, contribuendo a formare un ecosistema aperto cooperativo.
Il software potrà (dovrà) essere forkato e adattato a seconda delle necessità di ogni persona/gruppo, favorendo la sperimentazione di modelli politici ed/o economici specifici.
La scelta di ActivityPub come protocollo per l’infrastruttura decentralizzata è anch’essa una scelta politica, oltre che tecnica.
Ma i motivi tecnici e politici della scelta di ActivityPub saranno materiale per un altro articolo.
Tanto quanto il prossimo nome di Agent e la sua identità visuale.
Tanto quanto le strategie di finanziamento, la roadmap e il business plan per i prossimi 3 anni.

Il punto rimane però sempre lo stesso. 
Creare strumenti a partire da una chiara visione politica: di partecipazione piuttosto che di rappresentanza, per facilitare nuovi modelli di organizzazione sociale ed economica alternativi al modello capitalista.

🎂 Buon primo anno di vita Agent, o Kamasi, o come ti chiamerai... e tanti auguri a noi!
