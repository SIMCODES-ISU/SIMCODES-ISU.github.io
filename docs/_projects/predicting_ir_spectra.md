---
title: Predicting IR Spectra
image:
  path: /projects/images/ir_spectra.png
  thumbnail: /projects/images/ir_spectra.png
  width: 50% # Reduce the display size to 50% of the container
  height: auto
  alt: "A scientist looking at an IR spectra on a computer."
tags: ["2026"]
---

Mentors: Theresa Windus and Qi Li

In Chemistry infrared (IR) spectra are an important tool for understanding
chemical structure. This is because IR spectra serve as a sort of "molecular
fingerprint," i.e., each molecule has a unique IR spectrum. In turn, chemists 
can tell what molecules are present in a compound based on the IR spectra of the 
compound. Furthermore, this "fingerprint" becomes distorted depending on the 
chemical environment of the molecules allowing chemists to deduce how molecules 
in the compound are interacting.

Chemists interested in using IR spectra to monitor reactions involving peptides
face a dilemma. Chemical systems involving peptides involve many unique
components, and many unique interactions among those components. In turn, the IR
spectra of these systems become difficult to understand with chemical
intuition alone. In such a scenario, chemists would ideally turn to theory for
help, but the cost of computing an IR spectra scales rapidly with system size
making such computations prohibitive.

This project seeks to use machine learning to predict the IR spectra of a target
peptide or protein given its  molecular structure. To do this we will build up 
an intuition about the IR spectra of individual amino acids, and interactions
among amino acids, that enables us to predict the target system's IR spectra.
