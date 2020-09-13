---
layout: project
color: "#64bd78"
logo: NSF IIS-2008295
---

<div class="callout">
Query Optimizaton for Data Intensive Applications
</div>

Modern database management systems (DBMSs) employ sophisticated query optimization techniques that enable the generation of efficient execution plans for queries over very large data sets. A variety of other applications also process large data sets, but cannot leverage database-style query optimization for their code. In this project, an open-source programming language compiler will be enhanced with database-style query optimization capabilities. Data-intensive parts of ordinary programs will be executed in chunks using different execution plans. Based on feedback from earlier chunks, alternative plans might be used for later chunks. The compiler could be used for a variety of data-intensive applications, allowing all of them to benefit from this class of performance optimizations.

Existing query optimization techniques for in-memory processing are limited in several ways: (a) they are not extensively used outside relational database management systems; (b) they are limited to a handful of relational operators, and do not cover access patterns or dynamically-defined functions found in other data-analysis scenarios; (c) they treat the underlying compiler as a black-box, with unpredictable performance depending on which compiler is used with which compiler settings; (d) they often bake-in design choices that may be appropriate for usage within a particular DBMS, but not for more general cases. This project directly addresses these challenges by optimizing data-analysis style queries expressed as tight loops in a conventional imperative programming language. This project will extend an open-source compiler (GraalVM/Truffle) with both known and novel optimization techniques that will automatically be applied whenever the compiler identifies that a loop is time-consuming. Integration into the compiler allows many applications to efficiently process large data sets. The system will support dynamic queries involving user-defined functions and arbitrary access patterns. Database-style and compiler optimizations will co-exist in one system, eliminating some of the mismatches that happen when the compiler is used as a black-box by a DBMS. The system will tune a variety of run-time execution parameters automatically, with minimal guidance from the programmer. The extended compiler will be validated by developing an interactive data exploration application that will allow users to dynamically specify and analyze a variety of large in-memory datasets.



## Principal Investigators

* <a href="http://www.cs.columbia.edu/~kar">Kenneth Ross</a>, Columbia University
* <a href="http://www.cs.columbia.edu/~ewu">Eugene Wu</a>, Columbia University 

## Open Source Software

## Galleries and Tutorials

