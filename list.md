
A list of Dafny projects:

## IronClad/IronFleet

[IronClad](https://github.com/microsoft/Ironclad), started 2015, this is probably the first and largest project in Dafny. The main features are: 
* proof of a distributed system (and lots of examples of simpler ones), 
* Math libraries, 
* temporal logic libraries, 
* refinement proofs.

Approx 30000 Loc.

Distributed systems, Paxos-based replicated state machine library (IronRSL) and a lease-based sharded key-value store (IronKV). The project contains a lot of Math libraries, temporal logics operators. Was recently updated to work with Dafny 3.0.0
Related papers: 
 * [IronFleet: Proving Practical Distributed Systems Correct](https://www.microsoft.com/en-us/research/publication/ironfleet-proving-practical-distributed-systems-correct/), SOSP, 2015.
 * [IronFleet: Proving Safety and Liveness of Practical Distributed Systems](https://www.microsoft.com/en-us/research/publication/ironfleet-proving-safety-liveness-practical-distributed-systems/), CACM, vol 50, 2017

## CloudMake 

[Formalizing and Verifying a Modern Build Language](https://www.researchgate.net/publication/290355122_Formalizing_and_Verifying_a_Modern_Build_Language/citations#fullTextFileContent)

I could not find a github repository for this project.
The papers report approx 2500 Loc.

Resources:
 
* [Formalizing and Verifying a Modern Build Language](https://www.researchgate.net/publication/290355122_Formalizing_and_Verifying_a_Modern_Build_Language/citations#fullTextFileContent), FM 2014.

## FreeRTOS in Dafny

[FreeRTOS is a popular real-time and embedded operating system](https://www.semanticscholar.org/paper/Program-Verification-of-FreeRTOS-using-Microsoft-Matias/8ec3ff1f3c7dc12fee0df727c8a55548aff95a7e)

I could not find a repository with the code. 

Resources:

* [Program Verification of FreeRTOS using Microsoft Dafny](https://www.semanticscholar.org/paper/Program-Verification-of-FreeRTOS-using-Microsoft-Matias/8ec3ff1f3c7dc12fee0df727c8a55548aff95a7e)
* [Program Verification of FreeRTOS using Microsoft Dafny. MsC Thesis](https://core.ac.uk/reader/216946486)

## ExpressOS
This [repository](https://github.com/ExpressOS/expressos) holds the kernel of ExpressOS. The project also holds the instructions of building and using ExpressOS.

Resources:

* [Verifying Security Invariants in ExpressOS](http://madhu.cs.illinois.edu/asplos13.pdf), ASPLOS 2013.


## DPLL
 [Verification of DPLL](https://github.com/andricicezar/sat-solver-dafny)
 Verification of the DPLL algorithm at the core of SAT solvers.

 Related papers:

 * [Verifying the DPLL Algorithm in Dafny](https://arxiv.org/abs/1909.01743), FROM 2019.

## Deposit Smart Contract 

[Deposit Smart Contract](https://github.com/ConsenSys/deposit-sc-dafny), 2020.
This project provides a complete proof of the Deposit Smart Contract algorithms used in the Beacon Chain (Eth2.0). 
Contains: tree library, some `seq` helpers, proofs of memory safety (using `:autocontracts`). 

Approx. 3500 Loc.

Related papers:
* [blog post](https://consensys.net/blog/research-development/20039/)
* [Verification of the Incremental Merkle Tree Algorithm with Dafny](https://arxiv.org/abs/2105.06009)
* Extended Abstract version forthcoming in FM'21.

## Verification of the Beacon Chain Phase 0

[Formal verification of Eth2.0 specs](https://github.com/ConsenSys/eth2.0-dafny) 

The objective of this project is to write a formal specification of the Eth2.0 specification in the verification-aware programming language Dafny.

Approx. 6500 Loc.

Resources:

* [Experience report](https://arxiv.org/abs/2110.12909)
* [blog post](https://consensys.net/blog/developers/formally-verifying-the-ethereum-2-0-phase-0-specifications/)







