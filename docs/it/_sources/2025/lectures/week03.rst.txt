19/03/2025 - Stack parte 2
-----------------------------------------------------------------------

* Stack
  
  * treiber, elimination stack

* Microbenchmark
  * rand
  * lrand48_r



Riferimenti libro di testo
""""""""""""""""""""""""""
* [:ref:`t1 <books2025>`] Sezione  11.2, 11.3

Altre fonti
"""""""""""""""""""""""

* Elimination stack: `A Scalable Lock-free Stack Algorithm <https://dl.acm.org/doi/10.1145/1007912.1007944>`_
* `rand <https://man7.org/linux/man-pages/man3/rand.3.html>`_
* `lrand48_r <https://man7.org/linux/man-pages/man3/drand48_r.3.html>`_
* `GCC Thread Local Storage <https://gcc.gnu.org/onlinedocs/gcc/Thread-Local.html>`_



17/03/2025 - Introduzione a strutture dati concorrenti - Stack parte 1
-----------------------------------------------------------------------

* Utilizzo di perf
* Stack
  * seriale, concorrente (pthread spinlock e mutex), treiber




Riferimenti libro di testo
""""""""""""""""""""""""""
* [:ref:`t1 <books2025>`] Sezione  11.1, 11.2

Altre fonti
"""""""""""""""""""""""

* perf:
  * `Perfwiki <https://perfwiki.github.io/main/>`_
  * `Linux man <https://man7.org/linux/man-pages/man1/perf.1.html>`_

* Read Modify Write: `Efficient synchronization of multiprocessors with shared memory <https://dl.acm.org/doi/10.1145/48022.48024>`_
* Compare and swap: `__sync built-in <https://gcc.gnu.org/onlinedocs/gcc-14.2.0/gcc/_005f_005fsync-Builtins.html>`_
* Treiber stack: `Systems Programming: Coping With Parallelism <https://dominoweb.draco.res.ibm.com/reports/rj5118.pdf>`_

