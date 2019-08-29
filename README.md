# CS 6930: Independent Study

## Verified Systems

This graduate independent study examines recent research results in verified systems, with specific focus on verified operating and distributed systems software (e.g., CertiKOS, seL4, Verdi, etc.). The independent study is structured as a graduate seminar: weekly readings together with paper reviews and periodic assignments in which students build and extend existing verified systems. As a final project, students will either implement their own verified system (of moderate complexity) or extend an existing verified system in a nontrivial way. 

## Grade Breakdown

| Component| Percentage |
|----------|------------|
| Weekly readings + paper reviews | 30% |
| Assignments | 30% |
| Final Project | 40% |

## Paper Reviews

In addition to scheduled assignments, students are required to post reviews of each week's assigned reading. 

Post reviews to the [Piazza page](piazza.com/ohio/fall2019/cs6930) using the appropriate tag (e.g., *w2* for week 2's review).

Reviews should include at least the following sections: 

* Summary: What's the paper about?
* Contributions: What's the value of this paper to the research community?
* Pros: What's good about this paper wrt. content, stylistically, or otherwise?
* Cons: What's bad?

## Final Projects

Students are required to complete a significant final project (40%) that either extends an existing verified system in an interesting way or implements a verified system from scratch (target and scope to be agreed upon in consulation with the instructor). Students will document their final projects in short technical reports (Week 13). Students will present their final projects in the final two weeks of the semester.  

## Course Schedule 

| Week | Topic | Reading | Assignment Due |
|------|-------|---------|----------------|
| Week 1 | Intro to the course | | |
| Week 2 | seL4 | [Comprehensive formal verification of an OS microkernel](http://ts.data61.csiro.au/publications/nicta_full_text/7371.pdf) | |
| Week 3 | CertiKOS | [CertiKOS: An Extensible Architecture for Building Certified Concurrent {OS} Kernels](https://www.usenix.org/system/files/conference/osdi16/osdi16-gu.pdf) | |
| Week 4 | Side channels in seL4 | [Can we prove time protection?](http://ts.data61.csiro.au/publications/csiro_full_text//Heiser_KM_19.pdf) | [Assignment 1](https://github.com/OUPL/VerifiedSystems/blob/master/Assignment1.md) |
| Week 5 | TLA+ | [Euclid Writes an Algorithm: A Fairytale](http://lamport.azurewebsites.net/pubs/euclid.pdf) | Final Project Check-in #1 |
| Week 6 | Paxos | [The Part-Time Parliament](http://lamport.azurewebsites.net/pubs/lamport-paxos.pdf) | |
| Week 7 | Byzantine Paxos in TLA+ | [Byzantizing Paxos by Refinement](http://lamport.azurewebsites.net/pubs/web-byzpaxos.pdf) | |
| Week 8 | Verdi | [Verdi: A Framework for Implementing and Verifying Distributed Systems](https://verdi.uwplse.org/verdi.pdf) | |
| Week 9 | Verdi-style Paxos | [Planning for Change in a Formal Verification of the Raft Consensus Protocol](https://verdi.uwplse.org/raft-proof.pdf) | [Assignment 2](https://github.com/OUPL/VerifiedSystems/blob/master/Assignment2.md) |
| Week 10 | Verified web / crypto | [Everest: Towards a Verified, Drop-in Replacement of HTTPS](http://drops.dagstuhl.de/opus/volltexte/2017/7119/pdf/LIPIcs-SNAPL-2017-1.pdf) | Final Project Check-in #2 |
| Week 11 | Verified web / crypto cont. | [Formally Verified Cryptographic Web Applications in WebAssembly](https://eprint.iacr.org/2019/542.pdf) | |
| Week 12 | Verified blockchains | [Mechanising Blockchain Consensus](http://discovery.ucl.ac.uk/10038868/1/toychain-accepted.pdf) | [Assignment 3](https://github.com/OUPL/VerifiedSystems/blob/master/Assignment3.md) |
| Week 13 | Slack week | No reading | Final Project Reports |
| Week 14 | Final projects presentations #1 | Read others' final project reports | Review others' reports |
| Week 15 | Final projects presentations #2 | No reading | |
