# MODEL1111070003: Bordbar2011_MultiTissueType_MetabolicNetwork

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1111070003.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1111070003.git@20140916`

## Usage

Importing the model package.

`import MODEL1111070003 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**A multi-tissue type genome-scale metabolic network for analysis of whole-body systems physiology.**   
Bordbar A, Feist AM, Usaite-Black R, Woodcock J, Palsson BO, Famili I. _BMC
Syst Biol._ 2011 Oct 31;5(1):180.
[22041191](http://www.ncbi.nlm.nih.gov/pubmed/22041191) ,  
**Abstract:**   
ABSTRACT: BACKGROUND: Genome-scale metabolic reconstructions provide a
biologically meaningful mechanistic basis for the genotype-phenotype
relationship. The global human metabolic network, termed Recon 1, has recently
been reconstructed allowing the systems analysis of human metabolic physiology
and pathology. Utilizing high-throughput data, Recon 1 has recently been
tailored to different cells and tissues, including the liver, kidney, brain,
and alveolar macrophage. These models have shown utility in the study of
systems medicine. However, no integrated analysis between human tissues has
been done. RESULTS: To describe tissue-specific functions, Recon 1 was
tailored to describe metabolism in three human cells: adipocytes, hepatocytes,
and myocytes. These cell-specific networks were manually curated and validated
based on known cellular metabolic functions. To study intercellular
interactions, a novel multi-tissue type modeling approach was developed to
integrate the metabolic functions for the three cell types, and subsequently
used to simulate known integrated metabolic cycles. In addition, the multi-
tissue model was used to study diabetes: a pathology with systemic properties.
High-throughput data was integrated with the network to determine differential
metabolic activity between obese and type II obese gastric bypass patients in
a whole-body context. CONCLUSION: The multi-tissue type modeling approach
presented provides a platform to study integrated metabolic states. As more
cell and tissue-specific models are released, it is critical to develop a
framework in which to study their interdependencies.

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


