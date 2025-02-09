# TNIC

TNIC is a trusted NIC architecture on top of hardware accelarators that aims to provide a secure trusted networking API for building trustworthy distributed systems while keeping the trusted computed base (TCB) minimal and veriable.

We build TNIC on top of SmartNICs, i.e., specifically we built our prototype on top of Alveo U280 from Xilinx. 
We evaluated TNIC compared to other TEEs (SGX, AMD-SEV) as root-of-trust for networked systems. 
We applied it to four applications (more info in the paper!) and we conducted a security analysis of TNIC system operations to proof that is verifiable.


You can find more details in our [ASPLOS'25 paper](TBA).


## Artifact

TNIC is available in the following repositories:

[TNIC-hw](https://github.com/TUM-DSE/TNIC-hw.git) which contains the hardware implementation of TNIC.

[TNIC-sw](https://github.com/TUM-DSE/TNIC-sw.git) which contains the codebases of TNIC applications.

[TNIC-proofs](https://github.com/TUM-DSE/TNIC-proofs.git) which contains the security proofs of TNIC system operations.


## Full paper 

This repository also contains [the full version of the paper](./TNIC_ASPLOS_25_full.pdf) presenting (2) formally verified proofs for the TNIC security protocols and (2) the implementation details of four distributed systems using TNIC.

