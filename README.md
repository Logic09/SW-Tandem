# SW-Tandem
SW-Tandem: A Efficient Tool for Large-Scale Peptide Sequencing

SW-Tandem is implemented in C++. We assume that reader is familiar with C++ to some extent and is able to run C++ programs. Considering that some users do not have access to the Sunway TaihuLight supercomputer, we have offered a MPI version of Sunway TaihuLight.

#Availability

#5.1 Sunway TaihuLight with SW26010

Installation and Requirements

CPU | SW2610 processor

Processor Node | 4 CGs (4 MPEs and 256 CPEs)

OS | Sunway Raise OS 2.0.5 (based on Linux)

Instruction | Sunway-64 Instruction Set

Compile language | C, C++, Fortran

Parallel programming interface | MPI 3.0, OpenMP 3.1, OpenACC 2.0


Usage:
eg: bsub –I –b –q queue_name –n 1 –cgsp 64 –share_size 4096 –host_stack 128 ./swtandem input-path output-path


#5.2 MPI Cluster
Installation and Requirements
We assume that readers are familiar with MPI to some extent and are able to run MPI programs. We recommend at least 8GB of memory for workflows involving standard tryptic digestions.
Usage:
eg: mpirun -np <number of processes> -f servers ./swtandemmpi input-path output-path<program arguments>  
