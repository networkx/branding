# NetworkX

## Summary

NetworkX is a Python package for the creation, manipulation, and study of the
structure, dynamics, and functions of complex networks.
NetworkX provides intuitive data structures for describing networks (or graphs)
with the flexibility to support a wide range of relational data.
The library also provides an extensive set of tools including standard graph
algorithms; network structure and analysis measures; and utilities for
creating a wide variety of graphs, either from existing data or with
well-known generation methods.
The library is written in pure Python, with an emphasis on readable,
well-documented, and thoroughly-tested code.
Graph and network analysis are ubiquitous with applications spanning many
domains: from mathematics and theoretical computer science to astronomy,
linguistics, biology, social science, and beyond.
NetworkX is the fundamental package for network analysis in the scientific
Python ecosystem, supporting exploration and applications across all domains.

## Use Cases / Applications

NOTE: these are pretty generic - having some more specific examples would be
good.

 - Analysis of social networks such as Twitter, Facebook, or YouTube; including
   community detection, information flow, and suggestion and recommendation
   algorithms.
 - Biology and public health: from protein folding to contact tracing.
 - Computer science and information theory - many fundamental data structures
   and algorithms are described in terms of graphs, from tree structures and
   information codings to search and path finding algorithms.

Other ideas from perusal of dependents on GitHub:
 - AI/ML/neural networks
   * [netket](https://github.com/netket/netket)
   * [Deep graph library (DGL)](https://github.com/dmlc/dgl)
   * [Maze RL framework](https://github.com/enlite-ai/maze)
   * [allen act (embodied AI)](https://github.com/allenai/allenact)
   * [evalml (automl framework)](https://github.com/alteryx/evalml)
   * [CompilerGym (RL for compiler optimzations from FB)](https://github.com/facebookresearch/CompilerGym)
   * [open_spiel - RL for games](https://github.com/deepmind/open_spiel)
   * [cogDL (DL with graphs)](https://github.com/THUDM/cogdl)
   * [AWS autogluon](https://github.com/awslabs/autogluon)
 - neuroscience
   * [neurokernel (fruitfly brain models)](https://github.com/neurokernel/neurokernel)
 - Geospatial analysis
   * [spopt](https://github.com/pysal/spopt)
 - microbiology
   * [biotite](https://github.com/biotite-dev/biotite)
 - Quantum computing
   * [Qiskit](https://github.com/Qiskit/qiskit-ignis)
 - Genomics
   * [RagTag](https://github.com/malonge/RagTag)
   * [GenomeWorks](https://github.com/clara-parabricks/GenomeWorks)
 - Data visualization
   * [dtale (flask project for pandas viz)](https://github.com/man-group/dtale)
 - NLP
   * [hanlp](https://github.com/hankcs/HanLP)
   * [haystack](https://github.com/deepset-ai/haystack)

## Planned Features

 - Improved interoperability with other scientific Python libraries. This
   includes tighter integration with foundational packages like NumPy, SciPy,
   and Matplotlib for improved performance, as well as domain-specific
   libraries in which network analysis plays a central role (e.g. Geopandas).

 - Increased selection of algorithms, including Louvain community detection,
   VF2++ subgraph isomorphism, and heuristic-based approaches for solving the
   traveling salesman problem.

 - More flexible graph generators to improve scalability and better support
   non-NetworkX-specific data structures.

## Project needs

 - Graph visualization performance and scalability | 2000 hours
 - Exploring interface with other computation backends | 2000 hours
 - Community manager (part time) | 250 hours / year
