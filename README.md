<p align="center">
<img src="https://i.imgur.com/pBuUepf.jpg" width=450>
</p>

Pyrho is a real-space DFT code written in Python. It is *not* built to be super-fast or scalable-
instead, it is built to be super-readable.

In the last few decades, thousands of Ph.D.'s have been given to hard-working theoreticians who solved
complex scientific problems using density functional theory (DFT) codes that they don't really
understand. Pyrho exists to make the "under-the hood" foundation for most DFT codes accessible to
those of us who aren't brave enough to dive into the source code of research grade DFT software packages.

There's a tutorial notebook (`tutorial.ipynb`) to guide you through the process of building Pyrho from scratch
(starting with the 1D Schroedinger equation). This notebook is based on interactive lectures given by Prof.
Joerg Neugebauer.

To be as nimble and powerful as possible, Pyrho makes heavy use of numerical recipes and routines in
the `numpy` and `scipy` libraries. These are really the only requirements.

[//]: # (For the sake of familiarity, Pyrho interfaces with structure objects from the atomic simulation
environment ase and pymatgen)

[//]: # (Please reach out if you have any questions, or if you're interested in hosting a Pyrho workshop for
DFT beginners at your school/institute!)

Happy calculating!

# Installing Pyrho

[//]: # (## conda)
[//]: # (```)
[//]: # (conda install -c conda-forge pyrho)
[//]: # (```)

## git
```
git clone https://github.com/ashtonmv/pyrho.git
pip install -r pyrho/requirements.txt
```

## testing with mybinder
[Run the tutorial notebook on a remote docker instance here](https://mybinder.org/v2/gh/ashtonmv/pyrho/master)
