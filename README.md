# SW-Tandem
SW-Tandem: A Efficient Tool for Large-Scale Peptide Sequencing

SW-Tandem is a C++ program designed to accelerate large-scale database searching based peptide sequencing. We assume that reader is familiar with C++ to some extent and is able to run C++ programs.

Installation and Requirements
CPU | SW2610 processor
Processor Node | 4 CGs (4 MPEs and 256 CPEs)
OS | Sunway Raise OS 2.0.5 (based on Linux)
Instruction | Sunway-64 Instruction Set
Compile language | C, C++, Fortran
Parallel programming interface | MPI 3.0, OpenMP 3.1, OpenACC 2.0

Usage:
eg: bsub –I –b –q queue_name –n 1 –cgsp 64 –share_size 4096 –host_stack 128 ./swtandem input-path output-path
