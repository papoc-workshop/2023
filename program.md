---
title: Program
---

PaPoC 2022 will take place on April 5th 2022. It is run in hybrid mode with both
in-person and remote speakers and attendees. All the times are given in CEST. If
speaking or attending remotely, please use [time zone
converter](https://www.timeanddate.com/worldclock/converter.html?iso=20220405T063000&p1=1264&p2=136&p3=179&p4=224&p5=248&p6=176&p7=240)
to find the times in your local time zone.

## Opening & Session 1: 08:30 to 09:45

* **Making CRDTs Byzantine Fault Tolerant**  
Martin Kleppmann (University of Cambridge)  
_08:30, 25m, in-person_  

* **Melda: A General Purpose Delta State JSON CRDT**  
Amos Brocco (University of Applied Sciences and Arts of Southern Switzerland)  
_08:55, 25m, in-person_  

* **Relaxed Paxos: Quorum intersection revisited (again)**  
Heidi Howard (University of Cambridge), Richard Mortier (University of Cambridge)  
_09:20, 25m, remote_  

## Session 2: 10:30 to 12:10

* **Marrying Replicated and Functional Data Structures**  
Vimala Soundarapandian (IIT Madras), Adharsh Kamath (NITK Surathkal), Kartik Nagar (IIT Madras), KC Sivaramakrishnan (IIT Madras)  
_10:30, 25m, remote_  

* **Merge What You Can, Fork What You Can’t: Managing Data Integrity in Local-First Software**  
Nicholas Schiefer (MIT), Geoffrey Litt (MIT), Daniel Jackson (MIT)  
_10:55, 25m, in-person_  

* **Geo-located data for better dynamic replication**  
Luis Silva (Universidade Nova de Lisboa), Frederico Aleixo (Universidade Nova de Lisboa), Albert Linde (Universidade Nova de Lisboa), João Leitão (Universidade Nova de Lisboa), Nuno Preguica  (Universidade Nova de Lisboa)  
_11:20, 25m, in-person_  

* **Distributed Access Control for Collaborative Applications using CRDTs**  
Pierre-Antoine Rault (INRIA), Claudia-Lavinia Ignat (INRIA), Olivier Perrin (Université de Lorraine)  
_11:45, 25m, in-person_  

## Session 3: 14:00 to 15:40

* **An Oblivious Observed-Reset Embeddable Replicated Counter**  
Matthew Weidner (Carnegie Mellon University), Paulo Sérgio Almeida (HASLab/INESC TEC and Universidade do Minho)    
_14:00, 25m, remote_  

* **Bilateral Anti-Entropy for Eventual Consistency**  
Rebecca Bilbro (Rotational Labs), Benjamin Bengfort (Rotational Labs), Pete Keleher (University of Maryland, College Park)  
_14:25, 25m, remote_  

* **Bolt-On Convergence in Replicated Data Types**   
Gowtham Kaki (University of Colorado Boulder), Prasanth Prahladan (University of Colorado Boulder), Nicholas Lewchenko (University of Colorado Boulder)   
_14:50, 25m, remote_  

* **Ordering Operations for Generic Replicated Data Types using Version Trees**  
Nazmus Saquib (University of California, Santa Barbara), Chandra Krintz (University of California, Santa Barbara), Rich Wolski (University of California, Santa Barbara)  
_15:15, 25m, remote_  

## Session 4: 16:30 to 18:30

### Invited Talk 1: Implementing Distributed ACID Transactions Without Atomic Clocks
**Karthik Ranganathan, CTO, YugaByte**  
_16:30, 60m, remote_  

#### Abstract

ACID transactions are a fundamental building block when developing
business-critical, user-facing applications. They simplify the complex task of
ensuring data integrity while supporting highly concurrent operations. While
they are taken for granted in monolithic SQL databases, most distributed DBs
would forsake them completely.

Fortunately, this is no longer the case. The trend started with Google Spanner,
which offered distributed transactions using GPS based atomic clocks - unheard
of in the database world before. Now, distributed transactions - without
requiring atomic clocks - are offered by distributed SQL databases. One such
example of a fully open source database offering this is YugabyteDB. Using the
example of YugabyteDB, this talk will explain how distributed ACID transactions
can be achieved without atomic clocks - without compromising on performance.

#### Bio

Karthik was one of the original database engineers at Facebook responsible for
building distributed databases including Cassandra and HBase. He is an Apache
HBase committer, and also an early contributor to Cassandra, before it was
open-sourced by Facebook. He is currently the co-founder and CTO of the company
behind YugabyteDB, a fully open-source distributed SQL database for building
cloud-native and geo-distributed applications.

### Invited Talk 2: A Programmable Cloud: CALM Foundations and Open Challenges
**Joseph M. Hellerstein, Professor, UC Berkeley**  
_17:30, 60m, remote_  

#### Abstract

The public cloud emerged a decade ago, yet distributed systems are still
programmed using models from sequential computing. All the traditional
challenges of distributed programming and data are still present in the cloud,
only they are now faced by the general population of software developers. Added
to these challenges are new desires for "serverless" computing, including
consumption-based pricing and autoscaling.
 
This talk will highlight principles for cloud programming that I have explored
with colleagues over the past decade, including the CALM Theorem and languages
like Dedalus and Bloom that encourage monotonic coordination-free consistency
via logic and lattices. The Anna "any-scale" KVS will be presented as a petri
dish for the potential of these ideas and many remaining challenges. 

I will conclude by overviewing new work in the Hydro project, which is aimed at
bringing research ideas to programmers in an practical, evolutionary fashion.
Key to our approach is a separation of distributed programs into a PACT of four
facets: Program semantics, Availablity, Consistency and Trust. We propose to
migrate developers gradually to PACT programming by lifting familiar code into
our more declarative level of abstraction. This agenda raises challenges across
multiple areas including language design, query optimization, transactions,
distributed consistency, compilers and program synthesis.

#### Bio 

Joe Hellerstein is the Jim Gray Professor of Computer Science at the University
of California, Berkeley. His research focuses on data-centric systems and the
way they drive computing. Hellerstein is an ACM Fellow, a Sloan Research Fellow
and the recipient of three ACM-SIGMOD Test of Time awards. In 2010, MIT's
Technology Review magazine included his work on cloud programming in their TR10
list of the 10 technologies "most likely to change our world". In addition to
his academic work, Hellerstein has been involved in a number of startup
companies including Trifacta, which brought academic research on data wrangling
to market.
