Programmazione Concorrente A.A. 2024/2025
=============================================

Benvenuti al corso di Programmazione Concorrente per A.A. 2024/2025 del Corso di Laurea Magistrale in Ingegneria Informatica di Tor Vergata

Docente: `Romolo Marotta <https://romolomarotta.github.io>`_

News
----

* :ref:`n05-03-2025`
* :ref:`n04-03-2025`
* :ref:`n02-03-2025`

Per la lista completa degli aggiornamenti visita la sezione dedicata: :doc:`2025/news`

Obiettivi del corso
-------------------

L'obiettivo del corso è fornire allo studente competenze su tematiche di programmazione concorrente con particolare attenzione ai sistemi multicore.
Al termine del corso lo studente acquisirà le conoscenze e i concetti alla base di algoritmi concorrenti bloccanti e non, dei meccanismi di locking e delle memorie transazionali,
fondamentali ad affrontare sfide nell'ambito della programmazione concorrente su sistemi multicore/multiprocessore.

Prerequisiti
------------

Il corso presuppone una buona conoscenza di:
  
  * calcolatori elettronici
  * sistemi operativi
  * programmazione in linguaggio C


Orario delle lezioni
--------------------

=========  =============  =====
Giorno     Orario         Aula 
=========  =============  =====
Lunedì     14:00 - 16:00  B10
Mercoledì  14:00 - 16:00  B10
=========  =============  =====


.. warning::
   * La didattica sarà svolta esclusivamente in presenza.
   * La classe virtuale su Teams sarà utilizzata per condividere il materiale del corso e/o informazioni organizzative. 



Link ai contenuti del corso
---------------------------

- :doc:`Slides <2025/slides>`
- Teams (TBA)

..
 - `Teams <https://teams.microsoft.com/l/team/19%3aP9MxSHe2y0q9wpw9GJCsoFpsgnuKhN9ETf4DxOOIrw01%40thread.tacv2/conversations?groupId=749b9d4b-045a-4b4a-a67c-f49226de3c01&tenantId=ffb4df68-f464-458c-a546-00fb3af66f6a>`_
 - `SharePoint <https://uniroma3.sharepoint.com/sites/AA2223-SISTEMIOPERATIVI-20801961MAROTTA/Documenti%20Condivisi/General>`_
 - Stream
 - `Moodle <https://ingegneria.el.uniroma3.it/course/view.php?id=1395>`_
 - `GitHub  <https://github.com/SistemiOperativi>`_


Ricevimento
-----------

Contattare il docente alla seguente email **{cognome}@ing.uniroma2.it** e riportare il prefisso **[PC2425]** nell'oggetto.


Modalità d'esame
----------------

L'esame prevede 1 prova scritta.


Date
""""""""

* **I Appello** (Giugno)
  
  * TBD

* **II Appello** (Febbraio)

  * TBD



.. role:: removedtopic

Programma e testi
-----------------

* **Introduzione alla programmazione concorrente e preliminari.**  Richiami a tematiche di sincronizzazione.
* **Programmi concorrenti.** Speedup e relative leggi (Amdhal, Gustavson, Sun-Ni) - Richiami a concetti di safety e liveness
* **Correttezza.** Condizione di safety - Sequential consistency - Linearizability -Quiscient consistency.
* **Progresso.** Deadlock-freedom. Starvation-freedom. Progresso minimale e massimale. Wait-freedom. Lock-freedom. - Progresso dipendente ed indipendente dallo scheduler
* **Richiami di architetture shared memory.**  Core e cache - Memory model - Primitive atomiche
* **Algoritmi non-bloccanti (lock-free e wait-free).** Stack, Insiemi, Code di priorità, Registri.
* **Meccanismi di locking.** Richiami lamport (only R&W) e Primitive RMW. Implementazioni di lock basate su RMW. Cenni ad altri meccanismi di locking (barriere e condizioni).
* **Transactional Memory.**  Definizione,  Obstruction freedom, Opacity (cenni a TS1 e TS2). Software Transactional Memory (TinySTM). Hardware Transactional Memory (Intel TSX).
* **Aspetti avanzati - Implementazioni ed hardware**  NUMA-awareness in algoritmi non bloccanti e non.
* **Aspetti avanzati - Teoria.**  Consensus number and hierarchy. Costrutti universali.

:ref:`Libri di testo <books2025>`

.. disabled
 .. warning::

  :removedtopic:`topic` indica che i relativi contenuti sono stati esclusi dal programma 


.. toctree::
   :hidden:

   self
   2025/examples
   2025/questions
   2025/slides
   2025/lectures/index
   2025/exams
   2025/news
   2025/errata

..
   editions
   