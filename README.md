# BIOMD0000000532: MODEL1407300000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000532.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000532.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000532 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Vazquez2014 - Chemical inhibition from amyloid protein aggregation kinetics

This model is described in the article:

[Modeling of chemical inhibition from amyloid protein aggregation
kinetics.](http://identifiers.org/pubmed/24572069)

Vázquez JA.

BMC Pharmacol Toxicol 2014; 15(1): 9

Abstract:

BACKGROUNDS: The process of amyloid proteins aggregation causes several human
neuropathologies. In some cases, e.g. fibrillar deposits of insulin, the
problems are generated in the processes of production and purification of
protein and in the pump devices or injectable preparations for diabetics.
Experimental kinetics and adequate modelling of chemical inhibition from
amyloid aggregation are of practical importance in order to study the viable
processing, formulation and storage as well as to predict and optimize the
best conditions to reduce the effect of protein nucleation. RESULTS: In this
manuscript, experimental data of insulin, A?42 amyloid protein and
apomyoglobin fibrillation from recent bibliography were selected to evaluate
the capability of a bivariate sigmoid equation to model them. The mathematical
functions (logistic combined with Weibull equation) were used in
reparameterized form and the effect of inhibitor concentrations on kinetic
parameters from logistic equation were perfectly defined and explained. The
surfaces of data were accurately described by proposed model and the presented
analysis characterized the inhibitory influence on the protein aggregation by
several chemicals. Discrimination between true and apparent inhibitors was
also confirmed by the bivariate equation. EGCG for insulin (working at
pH?=?7.4/T?=?37°C) and taiwaniaflavone for A?42 were the compounds studied
that shown the greatest inhibition capacity. CONCLUSIONS: An accurate, simple
and effective model to investigate the inhibition of chemicals on amyloid
protein aggregation has been developed. The equation could be useful for the
clear quantification of inhibitor potential of chemicals and rigorous
comparison among them.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000532](http://identifiers.org/biomodels.db/BIOMD0000000532).

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024).

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


