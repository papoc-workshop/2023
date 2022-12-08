---
title: Call for Papers
---
# Call for Papers

Consistency is one of the fundamental issues of distributed computing. Beyond
the well-known tension between Consistency, Availability, and
Partition-tolerance, as captured by the CAP theorem, many nuanced consistency
models and algorithms have been developed for different purposes. These
consistency models have subtly different behaviour in practice, which translates
to difficult choices between fault tolerance, performance, and programmability.
The issues and trade-offs are particularly vexing at scale, with a large number
of processes or large shared databases, and in the presence of high latency and
failure-prone networks, such as edge computing and peer-to-peer networks.

Since its inception in 2014, the PaPoC workshop series has brought together
researchers and practitioners who seek to develop better techniques and a better
understanding of consistency in distributed systems. We welcome contributions
from a wide range of backgrounds: system development, distributed algorithms,
concurrency, fault tolerance, databases, programming languages, blockchain, and
verification. While there is no one universally best solution, we believe that
by bringing together these perspectives, we can develop techniques that provide
useful guarantees to applications, that are usable by application developers,
and that satisfy real-world scalability, performance, and reliability
requirements.

The workshop is looking for contributions on the following, and associated,
topics:
* Design principles, correctness conditions, and programming patterns for
  scalable distributed data management systems.
* Techniques for relaxed consistency models: session guarantees, causal
  consistency, operational transformation, conflict-free replicated data types
  (CRDTs), monotonic programming, state merging, operation commutativity, etc.
* Data consistency in geo-replicated, peer-to-peer, and edge networks.
* Techniques for scaling and improving the performance of strongly consistent
  systems (e.g., Paxos-based, state machine replication, shared-log consensus,
  blockchains).
* How to expose consistency vs performance and scalability trade-offs in the
  programming model, and how to help developers choose.
* How to support composed operations spanning multiple objects (transactions,
  sagas, workflows).
* Reasoning, analysis and verification of application programs using storage
  systems with weak consistency models.
* Formal methods for verifying safety and progress of distributed applications
  and systems
* Strengthening the guarantees beyond consistency: fault tolerance, security,
  ensuring invariants are preserved, bounding metadata size, and controlling
  divergence.

## Details on submissions

The PaPoC workshop invites short papers up to 6 pages (including references)
discussing original contributions, experience reports, or work in progress
reports (supported by initial validations). We also accept longer proposals,
under the understanding that PC members are only expected to read the first six
pages. Submissions do not need to be anonymised.

Authors of accepted papers will have the opportunity to choose whether they want
their papers published in ACM Digital Library (along with papers from other
EuroSys workshops). In any case, accepted papers will be made available to
participants of the workshop. At least one author of each accepted submission is
expected to present their work at the workshop, and to be available for
discussions.

## How to submit your work

Submissions should be made [via HotCRP](https://papoc22.hotcrp.com/).

All submissions should be written in English and provided in PDF format. We
suggest that you use the [ACM template for LaTeX or MS
Word](https://www.acm.org/publications/proceedings-template), but this is not
required.

If using the LaTeX template, please use the following document class (which
matches the [format used by EuroSys](https://github.com/papoc-workshop/2022)):

    \documentclass[sigplan,review]{acmart}

In case of any questions, please contact the Program Chairs at
[papoc22@hotcrp.com](mailto:papoc22@hotcrp.com).

## Important Dates

| Submission deadline   | January 27, 2022 |
|---|---|
| Notification date     | February 17, 2022 |
| Camera-Ready deadline | March 3, 2022 |
| Workshop              | April 5, 2022 |

All deadline times are 23:59 hrs
[AoE](https://www.timeanddate.com/time/zones/aoe).
