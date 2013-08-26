Papers that have had more or less influence on Rust, or which one might want to consult for inspiration or to understand Rust's background.

## Type system

* [Region based memory management in Cyclone](http://209.68.42.137/ucsd-pages/Courses/cse227.w03/handouts/cyclone-regions.pdf)
* [Traits: composable units of behavior](http://scg.unibe.ch/archive/papers/Scha03aTraits.pdf)

## Concurrency

* [Singularity: rethinking the software stack](https://research.microsoft.com/pubs/69431/osr2007_rethinkingsoftwarestack.pdf)
* [Language support for fast and reliable message passing in singularity OS](https://research.microsoft.com/pubs/67482/singsharp.pdf)
* [Scheduling multithreaded computations by work stealing](http://supertech.csail.mit.edu/papers/steal.pdf)
* [Thread scheduling for multiprogramming multiprocessors](http://www.eecis.udel.edu/%7Ecavazos/cisc879-spring2008/papers/arora98thread.pdf)
* [The data locality of work stealing](http://www.aladdin.cs.cmu.edu/papers/pdfs/y2000/locality_spaa00.pdf)
* [Dynamic circular work stealing deque](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.170.1097&rep=rep1&type=pdf) - The legendary Chase/Lev deque
* [Work-first and help-first scheduling policies for async-finish task parallelism](http://www.cs.rice.edu/%7Eyguo/pubs/PID824943.pdf) - More general than fully-strict work stealing
* [A Java fork/join calamity](http://www.coopsoft.com/ar/CalamityArticle.html) - critique of Java's fork/join library, particularly its application of work stealing to non-strict computation
* [Scheduling techniques for concurrent systems](http://www.ece.rutgers.edu/%7Eparashar/Classes/ece572-papers/05/ps-ousterhout.pdf)
* [Contention aware scheduling](http://www.ece.rutgers.edu/%7Eparashar/Classes/ece572-papers/05/ps-ousterhout.pdf)
* [Balanced work stealing for time-sharing multicores](http://www.cse.ohio-state.edu/hpcs/WWW/HTML/publications/papers/TR-12-1.pdf)
* [Three layer cake](http://www.upcrc.illinois.edu/workshops/paraplop10/papers/paraplop10_submission_8.pdf)
* [Non-blocking steal-half work queues](http://www.cs.bgu.ac.il/%7Ehendlerd/papers/p280-hendler.pdf)
* [Reagents: expressing and composing fine-grained concurrency](http://www.mpi-sws.org/~turon/reagents.pdf)

## Other

* [Crash-only software](https://www.usenix.org/legacy/events/hotos03/tech/full_papers/candea/candea.pdf)

## Papers *about* Rust

* [GPU programming in Rust](http://www.cs.indiana.edu/~eholk/papers/hips2013.pdf)
* [Parallel closures: a new twist on an old idea](https://www.usenix.org/conference/hotpar12/parallel-closures-new-twist-old-idea) - not exactly about rust, but by nmatsakis
