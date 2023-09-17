---
layout: page
permalink: /software
title: Software
description:
nav: true
---

I am committed to efficient software production: my software is available on
[GitHub](https://github.com/jermp).


#### **Data Structures**

Efficient C++ implementations of the following data structures (see also related publications).

- Compacted and Colored de Bruijn Graphs (WABI2023)
- K-Mer Dictionaries (ISMB2022, WABI2022, GBIO2023, ALGOMB2023)
- Minimal Perfect Hash Functions (SIGIR2021, ISMB2023, TKDE2023)
- Segment-Trees and Fenwick-Trees (SPE2021)
- Mutable Bitmaps with Rank/Select (INFOSYS2021)
- Compressed Bitmaps (DCC2021)
- Tries (SIGIR2017, TOIS2019, TKDE2021)
- Inverted Indexes (TOIS2017, TKDE2020, WSDM2019, SIGIR2020, CSUR2021)


[Fulgor](https://github.com/jermp/fulgor) --
A fast and compact k-mer index for large-scale matching and color queries.
<br />
Reference publications: WABI2023.

[LPHash](https://github.com/jermp/lphash) --
Fast and compact locality-preserving minimal perfect hashing for k-mer sets.
<br />
Reference publications: ISMB2023.

[SSHash](https://github.com/jermp/sshash) --
A compressed, weighted, associative, and exact dictionary for k-mers.
A membership-only version of SSHash is [SSHash-Lite](https://github.com/jermp/sshash-lite).
<br />
Reference publication: ISMB2022, WABI2022, GBIO2023, ALGOMB2023

[PTHash](https://github.com/jermp/pthash) --
Fast and compact minimal perfect hash functions.
<br />
Reference publications: SIGIR2021, TKDE2023.

[Mutable Rank and Select Queries](https://github.com/jermp/mutable_rank_select) --
Mutable bitmaps with support for Rank and Select queries.
<br />
Reference publication: INFOSYS2021.

[Prefix-Sum Queries](https://github.com/jermp/psds) --
A range of tree-shaped data structures for maintaining prefix-sums, including:
binary Segment-Tree (top-down and bottom-up),
b-ary Segment-Tree,
Fenwick-Tree,
b-ary Fenwick-Tree,
blocked Fenwick-Tree,
truncated Fenwick-Tree.
<br />
Reference publication: SPE2021.

[Query Auto-Completion](https://github.com/jermp/autocomplete) --
Efficienct and effective
autocompletion framework, based on forward/inverted indexes, succinct RMQ, and string dictionaries (Front-Coding and tries).
<br />
Reference publication: SIGIR2020.

[Inverted Indexes Benchmark](https://github.com/jermp/2i_bench) --
A benchmarking suite for inverted index data structures, featuring the following compressors:
Elias-Fano and partitioned Elias-Fano,
Opt-PFor-Delta,
Binary Interpolative,
QMX,
Simple,
Variable-Byte and Opt-VByte,
Gamma, Delta, Rice, Zeta,
DINT.
<br />
Reference publication: CSUR2021.

[Interpolative Coding](https://github.com/jermp/interpolative_coding) --
An efficient implementation of the Binary Interpolative Coding
algorithm.

[Sliced Indexes](https://github.com/jermp/s_indexes) --
Compressed bitmap indexes that support fast intersection and union.
<br />
Reference publication: DCC2021.

[DINT](https://github.com/jermp/dint) --
A Fast and compact dictionary-based decoder for inverted lists.
<br />
Reference publication: WSDM2019.

[Opt-VByte](https://github.com/jermp/opt_vbyte) --
Optimal partitioning of inverted lists compressed using binary vectors
and point-wise encoders, like Variable-Byte.
<br />
Reference publication: TKDE2020.

[Indexes for RDF](https://github.com/jermp/rdf_indexes) --
Trie-based indexes for semantic data like RDF triples.
<br />
Reference publication: TKDE2021.

[Tongrams](https://github.com/jermp/tongrams) --
Fast language model queries and [estimation](https://github.com/jermp/tongrams_estimation) in compressed space.
<br />
Reference publications: SIGIR2017, TOIS2019.

[Clustered Elias-Fano Indexes](https://github.com/jermp/clustered_elias_fano_indexes) --
Clustered Elias-Fano inverted indexes.
<br />
Reference publication: TOIS2017.

#### **Miscellanea**

C++ utilities that I used as sub-modules for larger projects.

[essentials](https://github.com/jermp/essentials) --
A C++ library providing essential core utilities for data structure design and benchmarking. More precisely:

- benchmarking facilities, including: messages displaying local time, configurable timer class, function to prevent code elision by compiler, simple creation and printing of json documents;
- functions to serialize-to and load-from disk data structures;
- functions to compute the number of bytes consumed by data structures;
- support for creating, removing, and iterate inside directories;
- transparent support for contiguous memory allocation.

[cmd_line_parser](https://github.com/jermp/cmd_line_parser) --
Command line parser for C++17. It offers all handy features in just 150 lines of code.

[mm_file](https://github.com/jermp/mm_file) --
A self-contained, header-only, implementation of memory-mapped files in C++ for both reading and writing.
