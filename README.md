# BIOMD0000000083: Model_1

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000083.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000083.git@20140916`


# Model Notes


This is model is according to the paper_Toward a detailed computational model
for the mammalian circadian clock_

In this model interlocked negative and positive regulation of Per,Cry,Bmal
,REV-ERBalpha genes are all involved.The model is actually robust so the
initial conditions are unimportant.We gave every entity zero as initial
value,and start the graph at time=132h.

The simulation results in figure 8B can be reproduced by roadRunner online and
Copasi. We use a ceiling function to simulate the day-light cycle.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


