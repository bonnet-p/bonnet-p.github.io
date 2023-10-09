## Project Topics @ DIKU (Fall 2023)

### Local NVMe Storage in DuckDB

DuckDB (duckdb.org) is an in-process SQL OLAP database management system.
It has been designed for portability, so it relies on the Posix abstraction to access
the local file system. In this project, the goal is to revisit access to local storage
assuming that NVMe SSDs are used. The idea is to rely on a modern I/O interface and
storage allocation abstraction that exploit the latest NVMe features.

### Local NVMe Storage in Adios

ADIOS2 is a high-performance I/O framework (https://adios2.readthedocs.io/).
It has been designed for parallel file systems on top the Posix abstraction.
Modern HPC clusters (e.g., Frontier at Oak Ridge) rely on local NVMe SSDs for burst buffers.
A previous project implemented an NVMe transport beneath the existing storage engine.
In this project, the goal is to revisit the design of the storage engine
to leverage the feaatures of the underlying NVMe transport. 

### Computational Storagei (Delilah) in Daphne

Delilah (https://github.com/delilah-csp) is a computational storage platfom that enables the offload of eBPF
program from a host onto computational storage. We have experimented with Delilah
in the context of a relational system. In this project, the goal is to experiment
with Delilah in the context of the Daphne system (https://daphne-eu.eu/), 
an Integrated Data Analysis Pipelines for Large-Scale Data Management, HPC and Machine Learning.

### On-Path and Off-Path Computational Storage

Delilah (https://github.com/delilah-csp) is a computational storage platfom that enables the offload of eBPF
programs. The architecture of Delilah is on-path, i.e., it is run on a PCIe card that is
located between the host and SSDs. In this project, the goal is to experiment with Delilah 
with an off-path architecture, where PCIe card and SSDs are endpoints under the same PCIe root complex
using peer-to-peer DMA to transfer data efficiently.

### RISC-V Based Computational Storage

Delilah (https://github.com/delilah-csp) is a computational storage platfom that enables the offload of eBPF.
The current version of Delilah is implemented on a Xilinx MPSoc composed of FPGA and ARM cores.
In this project, the goal is to explore how RISC-V processors should be customized to fit
the needs of a computational storage processor.


