---
layout: default
---

## News

- **@DIKU students**: Please check the following [project topics](projects.md) for MSc or BSc thesis 

## Bio

Philippe Bonnet is professor at DIKU, the computer science department of the University
of Copenhagen. 

He is an experimental computer scientist with a background in
database systems. For thirty years, he has explored the design, implementation,
and evaluation of database systems in the context of successive generations of computer
classes, including wireless sensor networks, computer clusters and most recently
computational storage. 
Philippe has a track record of successful research projects under DARPA, NSF (while a research associate 
at Cornell University), EU and Danish funding (at DIKU and ITU).

Philippe is an expert on storage system
software. In this area, he contributed to the uFlip Benchmark, the Linux multiqueue block
layer, the Linux framework for Open-Channel SSDs, the OX architecture for computational
storage, the xNVMe library and Delilah, a prototype for eBPF offload on
computational storage.
Philippe was involved in the development of sensor networks in the early 2000s with
the Cougar project at Cornell, and the Hogthrob and Mana projects at U.Copenhagen. 
Philippe is co-author of a book on database tuning together with Dennis Shasha.

Philippe joined DIKU in 2001 as assistant professor in the Distlab group.
He was faculty at the IT University from 2009 to 2023, and he is now back at DIKU.
Before Denmark, Philippe worked as software engineer at ECRC in Munich, Germany
from 1993 to 1996, as a PhD student at GIE Dyade in Grenoble, France, and
as a postdoc and later research associate at Cornell University, NY, USA from 1999 to 2001.
In this period, Philippe had the priviledge to work under the supervision of Stephane Bressan at ECRC,
Anthony Tomasic at Dyade and Praveen Seshadri at Cornell. 

Philippe is a trustee of the VLDB Endowment and currently chairs the ACM EIG on Reproducibility
and Replicability.

## PhD Students

### Students

[Kasper Hjort Berthelsen](https://www.linkedin.com/in/kasperhjortberthelsen/?originalSubdomain=dk) (ITU, 2024) &nbsp; &nbsp;
[Morten Tychsen Clausen](https://pure.itu.dk/da/persons/morten-tychsen-clausen) (ITU, 2024)&nbsp; &nbsp;
[Niclas Hedam](https://www.linkedin.com/in/hedam/?originalSubdomain=dk) (ITU, 2024) &nbsp; &nbsp;


### Graduates 

[Matias Bjørling](https://www.linkedin.com/in/matiasbjoerling/?originalSubdomain=dk) (ITU, 2015) &nbsp; &nbsp;
[Marcus Chang](https://www.linkedin.com/in/marcus-chang-7293056/) (DIKU, 2009) &nbsp; &nbsp;
[Niv Dayan](https://www.linkedin.com/in/niv-dayan-26636663/?originalSubdomain=ca) (ITU, 2015) &nbsp; &nbsp;
[Jonathan Furst](https://www.linkedin.com/in/jofu87/) (ITU, 2016) &nbsp; &nbsp;
[Javier Gonzalez](https://www.linkedin.com/in/javigon/?locale=en_US) (ITU, 2015) &nbsp; &nbsp;
[Joel Granados](https://www.linkedin.com/in/joelgranados/?originalSubdomain=dk) (ITU, 2013) &nbsp; &nbsp;
[Aslak Johansen](http://www.linkedin.com/pub/aslak-johansen/8/90b/554) (ITU, 2014) &nbsp; &nbsp;
[Martin Leopold](https://www.linkedin.com/in/martin-leopold-9444222/?originalSubdomain=dk) (DIKU, 2007) &nbsp; &nbsp;
[Ivan Luiz Picoli](https://www.linkedin.com/in/ivan-luiz-picoli-b34672105/?originalSubdomain=dk) (ITU, 2019) 

## Research

Many of the research questions I study are motivated by three recent trends that drive the 
evolution of computer systems:
1. The performance of modern storage hardware has triggered a 
necessary redesign of the storage software stack.
2. The diversification of workloads driven by artificial 
intelligence and big data, combined with the limits reached by central processing units has propelled 
the emergence of specialized hardware to deliver top performance at an acceptable energy cost. 
3. Data movement bottlenecks in traditional, processor-centric architectures have led to the
development of data-centric architectures, where processing is moved to where data is stored.

My research is based on the hypothesis that solid-state drives
that are programmed and
specialized together with database management systems minimize data movement and improve performances.
This hypothesis is based on our early work on th
performance characteristics of SSDs and on the integration of SSDs in Linux. This work
demonstrated the limitations of layered system design with generic SSD firmware.
The idea is that databases and SSDs should be co-designed.

Currently, my research focuses on:
- **Computational storage**, that makes it possible to execute functions 
on compute resources within the storage system as a result of I/Os issued by a host. 
I lead the computational storage work package in the Horizon Europe Daphne project. 
- **Co-designed SSDs**. A longer term effort is to make it possible to program and specialize SSDs that can then 
be integrated in the context of composable database management systems.
- **Scientific data management at extreme scale**. I am also interested in exploring 
how computational storage could benefit scientific applications.  
Our hypothesis is that computational storage devices efficiently support error-controlled, progressive, and adaptable retrieval of scientific data at extreme scale.
- **Reproducibility and Replicability**. Finally, a complementary line of work focuses on 
reproducibility and replicability in the context of computational storage and co-designed SSDs.
More generally, I am interested in teaching experimental design to computer science students
and studying how policies within institutions or at national level
can favor the replicability of experimental research. 

## Service

- Chair of ACM EIGREP, the ACM's Emerging Interest Group on Reproducibility and Replicability.
- Co-founder and steering committee member of the Danish Reproducibility Network 
- Trustee of the VLDB Endowment



