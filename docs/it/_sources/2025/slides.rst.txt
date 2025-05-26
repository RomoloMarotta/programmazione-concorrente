Slides e Testi
==============

In questa sezione potete scaricare le slide delle lezioni.


* `01 - Introduzione    </programmazione-concorrente/slides/01-PC-intro-web-25-03-05.pdf>`_.      Pubblicato il 04/03/25. Aggiornato il 05/03/25.
* `02 - Proprietà       </programmazione-concorrente/slides/02-PC-properties-web-25-03-25.pdf>`_. Pubblicato il 04/03/25. Aggiornato il 25/03/25.
* `03 - Strutture dati  </programmazione-concorrente/slides/03-PC-concurrent-ds-25-05-05.pdf>`_.  Pubblicato il 19/03/25. Aggiornato il 05/05/25.
* `04 - Locking         </programmazione-concorrente/slides/04-PC-locks.pdf>`_.  Pubblicato il 26/05/25.
* `05 - Transactinal Memory         </programmazione-concorrente/slides/05-PC-tm.pdf>`_.  Pubblicato il 26/05/25.

.. _books2025:

Testi consigliati
"""""""""""""""""

* [t1] The Art of Multiprocessor Programming - Maurice Herlihy, Nir Shavit, Victor Luchangco, Michael Spear - Morgan Kaufmann (seconda edizione).
* [t2] Shared-Memory Synchronization - Michael L. Scott - Springer Cham.


Documentazione
""""""""""""""

* `POSIX <https://pubs.opengroup.org/onlinepubs/9699919799>`_
* `Linux <https://man7.org/linux/man-pages/>`_
* `gcc sync builtins <https://gcc.gnu.org/onlinedocs/gcc/_005f_005fsync-Builtins.html#g_t_005f_005fsync-Builtins>`_

..
    * `Microsoft C docs on literals <https://docs.microsoft.com/cpp/c-language/c-integer-constants>`_
    * `GCC Thread Local Storage <https://gcc.gnu.org/onlinedocs/gcc/Thread-Local.html>`_
    * `Linux Kernel <https://www.kernel.org/doc/html/latest/>`_
    * `mode_t <https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/sys_stat.h.html>`_
    * `ramdisk <https://www.kernel.org/doc/html/latest/admin-guide/blockdev/ramdisk.html>`_
    * `ramfs <https://wiki.debian.org/ramfs>`_
    * `tmpfs <https://www.kernel.org/doc/html/latest/filesystems/tmpfs.html>`_
  
    * `objdump <https://man7.org/linux/man-pages/man1/objdump.1.html>`_
    * `/etc/passwd <https://man7.org/linux/man-pages/man5/passwd.5.html>`_
    * `/etc/group <https://man7.org/linux/man-pages/man5/group.5.html>`_
    * `/etc/shadow <https://man7.org/linux/man-pages/man5/shadow.5.html>`_
    * `Bash redirection <https://www.gnu.org/software/bash/manual/html_node/Redirections.html>`_


Altro materiale
"""""""""""""""

* Introduzione
    * `The free lunch is over by Herb Sutter <http://www.gotw.ca/publications/concurrency-ddj.htm>`_
    * `Welcome to the jungle by Herb Sutter <https://herbsutter.com/welcome-to-the-jungle>`_
    * `50 Years of Microprocessor Trend Data by K. Rupp <https://github.com/karlrupp/microprocessor-trend-data>`_
* Proprietà
    * Scalabilità
        * `Another view on parallel speedup <https://dl.acm.org/doi/10.5555/110382.110450>`_
        * `Legge di Amdahl Sezione 4 Eq. 11 <https://dl.acm.org/doi/pdf/10.5555/110382.110450>`_
    * Correttezza:
        * Sequential consistency: `How to make a multiprocessor computer that correctly executes multiprocess programs <https://ieeexplore.ieee.org/document/1675439>`_
        * `Linearizability: a correctness condition for concurrent objects <https://dl.acm.org/doi/10.1145/78969.78972>`_
        * Serializability: `The Serializability of Concurrent Database Updates <https://dl.acm.org/doi/10.1145/322154.322158>`_
    * Progresso:
        * `On the nature of progress <https://link.springer.com/chapter/10.1007/978-3-642-25873-2_22>`_
* Strutture dati concorrenti
    * Stack
        * Treiber stack: `Systems Programming: Coping With Parallelism <https://dominoweb.draco.res.ibm.com/reports/rj5118.pdf>`_
        * Elimination stack: `A Scalable Lock-free Stack Algorithm <https://dl.acm.org/doi/10.1145/1007912.1007944>`_
    * Set
        * `A Lazy Concurrent List-Based Set Algorithm <https://link.springer.com/chapter/10.1007/11795490_3>`_
        * `A Pragmatic Implementation of Non-blocking Linked-Lists <https://link.springer.com/chapter/10.1007/3-540-45414-4_21>`_
        * `High performance dynamic lock-free hash tables and list-based sets <https://dl.acm.org/doi/10.1145/564870.564881>`_
        * Resizable hash table: `Split-ordered lists: Lock-free extensible hash tables <https://dl.acm.org/doi/10.1145/1147954.1147958>`_
        * `Practical Lock-Feedom. Section 4.3.3  <https://www.cl.cam.ac.uk/techreports/UCAM-CL-TR-579.pdf>`_
        * `Skip lists: a probabilistic alternative to balanced trees <https://dl.acm.org/doi/10.1145/78973.78977>`_
        * `NUMASK: High Performance Scalable Skip List for NUMA <https://drops.dagstuhl.de/storage/00lipics/lipics-vol121-disc2018/LIPIcs.DISC.2018.18/LIPIcs.DISC.2018.18.pdf>`_
    * Priority Queue:
        * Sundell et al: `Fast and lock-free concurrent priority queues for multi-thread systems <https://ieeexplore.ieee.org/document/1213189>`_
        * Lothan et al: `Skiplist-based concurrent priority queues <https://ieeexplore.ieee.org/document/845994>`_
        * Linden et al: `A Skiplist-Based Concurrent Priority Queue with Minimal Memory Contention <https://link.springer.com/chapter/10.1007/978-3-319-03850-6_15>`_
        * Marotta et al: 
            * `A Lock-Free O(1) Event Pool and its Application to Share-Everything PDES Platforms <https://dl.acm.org/doi/abs/10.1109/DS-RT.2016.33>`_
            * `A conflict-resilient lock-free calendar queue for scalable share-everything PDES platforms <https://dl.acm.org/doi/10.1145/3064911.3064926>`_
            * `A Conflict-Resilient Lock-Free Linearizable Calendar Queue <https://dl.acm.org/doi/10.1145/3635163>`_
    * FIFO Queue
        * `Simple, fast, and practical non-blocking and blocking concurrent queue algorithms <https://dl.acm.org/doi/10.1145/248052.2481061>`_
        * `A methodology for creating fast wait-free data structures <https://dl.acm.org/doi/10.1145/2370036.2145835>`_
    * Wait-free Multiple-Reader Single-Writer Register
        * `Multiword atomic read/write registers on multiprocessor systems <https://dl.acm.org/doi/10.1145/1412228.1455262>`_
        * `A Wait-Free Multi-word Atomic (1,N) Register for Large-Scale Data Sharing on Multi-core Machines <https://ieeexplore.ieee.org/document/8048930>`_
* Lock
    *  Ibridi:
        * Mutexee: `Unlocking Energy <https://www.usenix.org/conference/atc16/technical-sessions/presentation/falsafi>`_
        * `Malthusian Locks <https://dl.acm.org/doi/10.1145/3064176.3064203>`_









..
    * `glibc source code <https://sourceware.org/git/?p=glibc.git;a=summary>`_
    * `Linux Kernel Source Code <https://elixir.bootlin.com/>`_
    * `Introduction to Operating Systems <https://pages.cs.wisc.edu/~remzi/OSTEP/intro.pdf>`_
    * `GCC and Make Compiling, Linking and Building C/C++ Applications <https://www3.ntu.edu.sg/home/ehchua/programming/cpp/gcc_make.html>`_
    * `Bakery algorithm <http://lamport.azurewebsites.net/pubs/bakery.pdf>`_
    * `Complete Fair Scheduler <https://www.kernel.org/doc/html/latest/scheduler/sched-design-CFS.html>`_
    * `Hard Disk <https://pages.cs.wisc.edu/~remzi/OSFEP/file-disks.pdf>`_
    * `Solid State Drives - Data Reliability and Lifetime <https://www.csee.umbc.edu/~squire/images/ssd1.pdf>`_
    * `Filesystem Hierarchy Standard <https://refspecs.linuxfoundation.org/FHS_3.0/fhs-3.0.pdf>`_
    * `objdump <https://man7.org/linux/man-pages/man1/objdump.1.html>`_
    * `readelf <https://man7.org/linux/man-pages/man1/readelf.1.html>`_
    * `gdb <https://man7.org/linux/man-pages/man1/gdb.1.html>`_
       
