


# HEPMC Package (2.06.09)


HepMC - a C++ Event Record for Monte Carlo Generators
Authors: Matt Dobbs, University of Victoria and Jorgen Beck Hansen, CERN
Additional Authors: Lynn Garren, Fermilab
Refer to: https://savannah.cern.ch/projects/hepmc/ for online documentation.
and: M. Dobbs and J.B. Hansen, 
"The HepMC C++ Monte Carlo Event Record for High Energy Physics", 
Computer Physics Communications, Vol. 134 (2001) 41-46, [ATL-SOFT-2000-001].

Copyright (C) 2000 by Matt Dobbs, University of Victoria and Jorgen Beck Hansen, CERN
The HepMC Event Record Package is the intellectual property of
the package authors. Anyone may copy and distribute this package freely.



## Installation

```bash
mkdir .bin && .bin
git clone https://github.com/jodafons/hepmc.git && cd hepmc
./configure --with-momentum=MEV --with-length=CM
make -j4
export HEPMC_LIBRARY=~/.bin/HepMC/build/lib
# For MacOS or LD_LIBRARY_PATH for Unix
export DYLD_LIBRARY_PATH=$DYLD_LIBRARY_PATH:$HEPMC_LIBRARY
```

## Homepage:

http://home.thep.lu.se/~torbjorn/Pythia.html


## Download:
http://lcgapp.cern.ch/project/simu/HepMC/download/HepMC-2.06.09.tar.gz

