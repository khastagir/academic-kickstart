---
title:
linktitle: Sistemi di Elaborazione
toc: true
type: docs
draft: false
date: 2020-04-03
menu:
  courses:
    parent: Teaching
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---

# Sistemi di Elaborazione
#### Anno Accademico 2019/20
---

## Informazioni generali
* Corso di laurea del [Corpo Tecnico del Genio della Marina](http://www.marina.difesa.it/il-tuo-futuro-e-il-mare/formazione-in-marina/accademia_navale/studio/piano_studi/Pagine/default.aspx), Specializzazione [Armi Navali](http://www.marina.difesa.it/il-tuo-futuro-e-il-mare/formazione-in-marina/accademia_navale/studio/piano_studi/Pagine/armi_navali.aspx), dell' [Accademia Navale di Livorno](http://www.marina.difesa.it/Pagine/default.aspx)
* Responsabile: [Nicola Tonellotto](http://tonellotto.github.io)
* Codocente: [Franco Maria Nardini](http://hpc.isti.cnr.it/~nardini)
* CFU: 6
* Periodo: Primo semestre
* Lingua: Italiano

## Orario delle lezioni
* Giovedì: 8:35 -- 11:10 (Lab. Microonde)
* Sabato: 10:25 -- 13:10 (Aula 3)

## Ricevimento studenti
* Dopo le lezioni o tramite appuntamento email

## Obiettivi formativi
Gli obiettivi formativi del corso sono di fornire conoscenze legate all’architettura degli elaboratori con un approccio sistemistico. Il corso è concepito in due moduli. Nel primo modulo si presenta una trattazione del sistema calcolatore nel suo complesso, si introduce il repertorio delle istruzioni e i vari sottosistemi: processore, memoria e input/output. Durante le lezioni saranno discussi esempi concreti dei vari sottosistemi, analizzando le architettura x86 (standard per calcolatori processori general-purpose) e ARM (standard per calcolatori embedded). Nel secondo modulo si introduce lo standard de-facto dei sistemi operativi moderni (UNIX) con un taglio pratico. Si illustra come i vari sottosistemi visti nel primo modulo sono resi disponibili e usabili attraverso astrazioni di più alto livello tipiche del sistema operativo stesso. Questo secondo modulo include un corso pratico di programmazione su piattaforma UNIX.

## Prerequisiti

* Conoscenza di base del C/C++
* Strutture dati e algoritmi di base
* Concetti di sistemi operativi

## Argomenti di massima

* Livelli di astrazione
* Prestazioni di un calcolatore
* ISA e assembler MIPS
* Aritmetica degli elaboratori
* Schemi per sommatori e moltiplicatori hardware
* Floating point
* Schema a blocchi di CPU a ciclo singolo
* Pipeline e prestazioni
* Schema a blocchi di CPU in pipeline
* Eccezioni e interruzioni
* Gerarchie di memoria
* Memorie cache
* Memoria virtuale
* Strutturazione di Unix
* System/Library call
* User/System/CPU time e misurazioni di tempo
* Processi
* Unbuffered I/O
* Anatomia dello Unix File System
* Layout di memoria in Unix
* Comunicazioni inter-processo

## Modalità di esame

Prova orale, composta da una prima parte sul modulo "Programmazione Avanzata in Ambiente UNIX" da compilare in forma scritta e da discutere con la commissione d'esame, seguita da una seconda parte sul modulo "Architetture degli Elaboratori" da discutere con la commissione d'esame.

## Libri di testo

* [**Struttura e progetto dei calcolatori**](https://www.amazon.it/Struttura-progetto-calcolatori-Contenuto-elettronicamente/dp/8808352021)<br>
di David A. Patterson e John L. Hennessy, edito da Zanichelli (quarta edizione italiana)

* [**Advanced Programming in the UNIX environment**](https://www.amazon.it/Advanced-Programming-Environment-Richard-Stevens/dp/0321637739/ref=dp_ob_title_bk)<br>
di W. Richard Stevens e Stephen A. Rago, edito da Addison-Wesley (terza edizione inglese)

## Programma delle lezioni

Vedi [qui](https://unimap.unipi.it/registri/dettregistriNEW.php?re=3301056::::&ri=50325).

## Materiale didattico

* Architetture degli Elaboratori {{% staticref "files/siselab_slides.pdf" "newtab" %}}{{< icon name="file-pdf" pack="fas" >}}{{% /staticref %}}
* Programmazione Avanzata in Ambiente UNIX [{{< icon name="external-link-alt" pack="fas" >}}](http://hpc.isti.cnr.it/~nardini/siselab_anl/)
