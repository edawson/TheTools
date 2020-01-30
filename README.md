# TheTools
A semi-curated list of genomegraph tools!

## Background
Historically, genomes (especially reference genomes) have been represented as linear strings. 
There are many reasons for this decision. Strings enable a simple coordinate system, much like the
monotonically increasing addresses of a well-designed street. The use of strings also forces a
haploid representation, meaning that there is only one expected allele at any position. These two
qualities make comparison of genomes simple: bijective maps can describe the relationship between
two reference genomes or a new genome's contigs and the reference. Algorithms operating on strings
are also generally of favorable complexity (often $O(l)$, where $l$ is the length of the string).
By the era of genomic sequencing, a significant body of research already existed on string-based algorithms, meaning that many approaches could be adapted to genomic research, avoiding the need
to create new algorithms.

While linearity reduces the cognitive and algorithmic overhead it masks significant amounts
of genomic complexity. Genomes are often multiploid (i.e., they have multiple copies of homologous
chromosomes, which may possess individual variations). 

Graph genomes are data structures which represent the genomic sequences of organisms
using nodes (or "vertices") and edges (or "links"). Such data structures have come into broad
use in the 2010s, though the use of graphs in genomes goes back many decades, particularly in genome assembly (see *Graphical pangenomics*, Erik Garrison, 2019 for a historical account). The primary advantages of graphs are that they
allow the representation of complex sequences, variation, repetitive structures, and annotations
within the same data structure as the backing reference.

Many implementations of graph genomes have arisen. We have attempted to catalog some of them
below, though this should not be considered a comprehensive list. We have separated the
available tools into several categories, primarily by their intended purpose or graph representation.
## Types of graphs
### deBruijn Graphs
### Sequence Graphs
### Variation Graphs

## DNA sequence graph representations
### HiSat2
### vg, odgi, and the vgteam
### Seven Bridges Genomics
### Bifrost graphs
### minigraph
## Graph construction algorithms
### vg construct
### seqwish
### svaha2
## Graph-based genotypers
## Graph visualization
### Bandage
## RNA Analysis

## Tools for improving graph representations (FORGe)

## Heng Li

## Durbin

