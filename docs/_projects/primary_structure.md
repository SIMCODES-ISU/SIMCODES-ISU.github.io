---
title: Determining Primary Structure
image:
  path: /projects/images/primary.png
  thumbnail: /projects/images/primary.png
  width: 50% # Reduce the display size to 50% of the container
  height: auto
  alt: "A protein being decomposed into a list of amino acids."
tags: ["2026"]
---

Mentors: Ryan Richard

The input to most computational chemistry packages is Cartesian coordinates of
a molecule (i.e., the location of each atom in three-dimensional space). For
example the Cartesian coordinates of a water dimer are (units are Angstroms, 
i.e., one tenth of a nanometer):

```
H -1.958940 -0.032063  0.725554
H -0.607485  0.010955  0.056172
O -1.538963  0.004548 -0.117331
H  1.727607  0.762122 -0.351887
H  1.704312 -0.747744 -0.399151
O  1.430776 -0.003706  0.113495
```

However, when we study proteins we typically are more interested in the primary
sequence of the system, i.e., the names, and order, of the amino acids 
comprising the protein. By visualizing the protein, chemists can manually assign
amino acid labels, but this is tedious and error-prone for large proteins (which
often have hundreds to thousands of amino acids). Ideally we would like to have
a program do this for us.

Given the connectivity of a protein (which atoms are bonded to which other 
atoms), identifying amino acids becomes what is called a "sub-graph search," 
i.e., the problem becomes to determine whether the protein contains a set of
atoms with a particular bonding arrangement. While we typically think of
proteins as being comprised of 20 different amino acids, the reality is each
amino acid can adopt multiple configurational isomers, significantly 
complicating the search.

This project seeks to develop a tool which is capable of reliably determining
the primary structure of a protein.