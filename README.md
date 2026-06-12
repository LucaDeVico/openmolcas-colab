# openmolcas-colab
A container for OpenMolcas binaries compiled inside a Colab environment.

The idea is to have two Colab notebooks:

Notebook 1 will be used by me to compile OpenMolcas (long and tedious) inside Colab, with all the necessary frills and options. I will be running this notebook to produce the binaries and ancillary files necessary to run OpenMolcas inside a notebook. These files will be tar-zipped and uploaded to this repository. Notebook 1 does not need to be made public.

Notebook 2 will be made public. It will contain a call to quickly wget the tarball, unzip it, and use it. There will be a way to create a basic input for OpenMolcas, run it, and visualize the output. For the latter, hopefully, there will be the possibility to visualize geometric coordinates, possibly molecular orbitals, and an extract of the main results, along with the ability to download the full set of output files.

There is also the molecular and orbital viewer from the OPAL suite, which is integrated into Notebook 2.
