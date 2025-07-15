---
title: Educational Resources for Students
layout: page
permalink: /student-resources/
image:
  thumbnail: /resources/images/educational_resources.png
  path: /resources/images/educational_resources.png
---

# Educational Resources for Students

This page collects various websites that students may find helpful as they
learn topics associated with SIMCODES.

{% include toc %}

---
## 🔗 Useful Python Resources

- [Davit’s 3 day tutorial](https://dpotoyan.github.io/Statmech4ChemBio/labs/py-lab/intro.html)
  - Covers scientific and numerical python
- [Scientific Computing for Chemists](https://tinyurl.com/2sr92mkt) 
  - Has lots of python examples in the context of chem/bio data analysis and 
    modeling.
- [Think Python](https://allendowney.github.io/ThinkPython/)
  - Classic, short and well rounded book about python.
- [Software carpentry](https://software-carpentry.org/lessons/) 
  - Basics of Unix, git and python

---

## 🔗 Useful GitHub Resources

- [GitHub Docs - Getting Started](https://docs.github.com/en/get-started)
- [Git Handbook by GitHub](https://guides.github.com/introduction/git-handbook/)
- [GitHub Learning Lab](https://lab.github.com/)
- [Git Cheat Sheet (PDF)](https://tinyurl.com/45wstha2)

---

## 🔗 Useful Molecular Dynamics Resources

- [Best Practices for Molecular Simulations](https://tinyurl.com/4w3wv897)
- [openmm-tutorial-msbs](https://github.com/molmod/openmm-tutorial-msbs)  
- [OpenMM tutorials](https://openmm.github.io/openmm-cookbook/dev/tutorials.html)
  - If you want to use OpenMM in Colab copy these cells.
  - First Cell:
    -  ```.py
       !pip install -q condacolab
       import condacolab
       condacolab.install()
       ```
  - Second Cell.
    - ```.py
      %%capture
      !conda install -c conda-forge openmm mdtraj
      ```

---

## 🔗 Useful Machine Learning Resources

- [PyTorch Basics](https://pytorch.org/tutorials/)
- [Learn Pytorch step by step](https://tinyurl.com/mrxhhbfr)