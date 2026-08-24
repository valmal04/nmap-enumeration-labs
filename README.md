# nmap-enumeration-labs

## Descrizione

Questa repository raccoglie tre laboratori pratici dedicati alla **network enumeration** con Nmap, svolti in ambienti differenti.

L'obiettivo dei laboratori è stato acquisire familiarità con le principali tecniche di ricognizione ed enumerazione di rete, analizzando host, porte, servizi e relative versioni.

## Laboratori

### 1. Enumerazione della rete domestica

Laboratorio di enumerazione eseguito all'interno di una rete domestica, con l'obiettivo di individuare gli host presenti e analizzare i servizi esposti.

**Contenuti:**
- Report completo del laboratorio in formato PDF
- Script contenente i comandi Nmap utilizzati

[Visualizza il laboratorio →](./home-network/)

### 2. Enumerazione di Metasploitable 2

Laboratorio di enumerazione eseguito su Metasploitable 2, una macchina virtuale intenzionalmente vulnerabile utilizzata per attività di formazione e sicurezza informatica.

**Contenuti:**
- Report completo del laboratorio in formato PDF
- Script contenente i comandi Nmap utilizzati

[Visualizza il laboratorio →](./metasploitable2/)

### 3. Full Port Scan

Laboratorio dedicato alla scansione completa delle porte TCP tramite l'opzione `-p-` di Nmap, utilizzata per analizzare l'intero intervallo di porte da 1 a 65535.

**Contenuti:**
- Report completo del laboratorio in formato PDF
- Script contenente i comandi Nmap utilizzati

[Visualizza il laboratorio →](./full-port-scan/)

## Strumenti utilizzati

- Nmap
- Terminale Linux
- Metasploitable 2

## Obiettivi

I laboratori sono stati realizzati per esercitarsi su:

- individuazione degli host attivi;
- scansione delle porte;
- identificazione dei servizi;
- rilevamento delle versioni dei servizi;
- raccolta e analisi delle informazioni disponibili tramite Nmap;
- interpretazione dei risultati delle scansioni.

## Note

1. Le attività documentate in questa repository sono state eseguite esclusivamente su sistemi e reti di proprietà o su ambienti predisposti per attività di laboratorio e formazione.

2. Ogni comando e output riportato nei documenti è tratto direttamente dalla registrazione integrale della sessione terminale, effettuata tramite il comando `script`, e disponibile come log grezzo nelle rispettive cartelle. Questo permette a chiunque di verificare direttamente i comandi eseguiti e i relativi risultati.
