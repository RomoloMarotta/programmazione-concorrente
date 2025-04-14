09/04/2025 - Strutture dati concorrenti: Set (approfondimenti) e Priority Queue
-------------------------------------------------------------------------------

* Set
    * Harris + Search index
        * Resizable hash table
        * Skip list NUMASK

* Lock-free Priority Queue
    * Richiami
        * Heap
        * Calendar Queue  
    * Linearizable (Sundell and Tsigats)
    * Lazy deletion
        * Timestamping (Lothan and Shavit)
        * Marked prefix (Linden and Johosson)
    * Adaptive (Marotta and Ianni and Pellegrini and Quaglia)



Altre Fonti
"""""""""""""""""""""""

* Resizable hash table: `Split-ordered lists: Lock-free extensible hash tables <https://dl.acm.org/doi/10.1145/1147954.1147958>`_
* `NUMASK: High Performance Scalable Skip List for NUMA <https://drops.dagstuhl.de/storage/00lipics/lipics-vol121-disc2018/LIPIcs.DISC.2018.18/LIPIcs.DISC.2018.18.pdf>`_
* Priority Queue by Sundell et al: `Fast and lock-free concurrent priority queues for multi-thread systems <https://ieeexplore.ieee.org/document/1213189>`_
* Priority Queue by Lothan et al: `Skiplist-based concurrent priority queues <https://ieeexplore.ieee.org/document/845994>`_
* Priority Queue by Linden et al: `A Skiplist-Based Concurrent Priority Queue with Minimal Memory Contention <https://link.springer.com/chapter/10.1007/978-3-319-03850-6_15>`_
* Priority Queue by Marotta et al: 
  * `A Lock-Free O(1) Event Pool and its Application to Share-Everything PDES Platforms <https://dl.acm.org/doi/abs/10.1109/DS-RT.2016.33>`_
  * `A conflict-resilient lock-free calendar queue for scalable share-everything PDES platforms <https://dl.acm.org/doi/10.1145/3064911.3064926>`_
  * `A Conflict-Resilient Lock-Free Linearizable Calendar Queue <https://dl.acm.org/doi/10.1145/3635163>`_



-----------------------------------------------------------------------------------


07/04/2025 - Strutture dati concorrenti: Set Hashtable e Skip list
-----------------------------------------------------------------------

* Hashtable
* Skip list

Altre fonti
"""""""""""""""""""""""

* `High performance dynamic lock-free hash tables and list-based sets <https://dl.acm.org/doi/10.1145/564870.564881>`_
* `Skip lists: a probabilistic alternative to balanced trees <https://dl.acm.org/doi/10.1145/78973.78977>`_
* `Practical Lock-Feedom. Section 4.3.3  <https://www.cl.cam.ac.uk/techreports/UCAM-CL-TR-579.pdf>`_

