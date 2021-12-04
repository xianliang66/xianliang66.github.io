---
title: "GiantVM"
excerpt: "<br/><img src='/files/giantvm-arch.png'>"
collection: portfolio
---

A distributed hypervisor based on QEMU-KVM. It enables one VM to run on a cluster of physical machines. By leveraging distributed CPU, I/O, and memory (a.k.a, DSM), a uni ed x86 ISA is provided for the guest OS. Unmodi ed OSes such as Linux can thus utilize resources from a cluster. The experiments show that GiantVM can improve applications performance up to 3.4x compared to Spark.

---
title: "Falcon"
excerpt: "<br/><img src='/files/falcon-arch.png'>"
collection: portfolio
---

A timestamp-based self-invalidation cache coherence protocol for DSM. The traditional write-invalidation protocol may send useless invalidations to cached objects that have been evicted. Instead, the update requests in a self-invalidation protocol are always issued by objects that are not evicted. Falcon uses the logical lease to determine when to send such update requests. The lease is backed by per-operation logical timestamps, which reects the sequential consistency. The evaluation shows that the optimal protocol can improve the performance of a KV database by 27% and a graph processing application by 71.4%.

---
title: "Yanni"
excerpt: "<br/><img src='/files/yanni-arch.png'>"
collection: portfolio
---

A fast VM live migration system for data center load-balancing. A major problem for the VM live migration is its overwhelming network bandwidth consumption. Yanni addresses this by an empirical result that applications have read-only pages. Such pages are replicated at the destination before the migration, and the subsequent migration consumes little network bandwidth. Yanni also designed a dedicated compression algorithm to save the memory space of such read-only replica. The evalua- tion shows that Yanni reduces the network bandwidth use and the migration time by 69% and 83%, respectively, compared to VM live migration. The compression can achieve a space-saving of 83.6%.
