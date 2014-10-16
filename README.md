# BIOMD0000000344: Hsp70Model

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000344.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000344.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000344 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
** Modelling the Role of the Hsp70/Hsp90 System in the Maintenance of Protein Homeostasis **   
Proctor CJ, Lorimer IAJ _PLoS ONE_2011; 6(7): e22038. [doi:10.1371/journal.pon
e.0022038](http://www.plosone.org/article/info%3Adoi%2F10.1371%2Fjournal.pone.
0022038),  
**Abstract:**   
Neurodegeneration is an age-related disorder which is characterised by the
accumulation of aggregated protein and neuronal cell death. There are many
different neurodegenerative diseases which are classified according to the
specific proteins involved and the regions of the brain which are affected.
Despite individual differences, there are common mechanisms at the sub-
cellular level leading to loss of protein homeostasis. The two central systems
in protein homeostasis are the chaperone system, which promotes correct
protein folding, and the cellular proteolytic system, which degrades misfolded
or damaged proteins. Since these systems and their interactions are very
complex, we use mathematical modelling to aid understanding of the processes
involved. The model developed in this study focuses on the role of Hsp70
(IPR00103) and Hsp90 (IPR001404) chaperones in preventing both protein
aggregation and cell death. Simulations were performed under three different
conditions: no stress; transient stress due to an increase in reactive oxygen
species; and high stress due to sustained increases in reactive oxygen
species. The model predicts that protein homeostasis can be maintained during
short periods of stress. However, under long periods of stress, the chaperone
system becomes overwhelmed and the probability of cell death pathways being
activated increases. Simulations were also run in which cell death mediated by
the JNK (P45983) and p38 (Q16539) pathways was inhibited. The model predicts
that inhibiting either or both of these pathways may delay cell death but does
not stop the aggregation process and that eventually cells die due to
aggregated protein inhibiting proteasomal function. This problem can be
overcome if the sequestration of aggregated protein into inclusion bodies is
enhanced. This model predicts responses to reactive oxygen species-mediated
stress that are consistent with currently available experimental data. The
model can be used to assess specific interventions to reduce cell death due to
impaired protein homeostasis.

**Note:**

Simulations were performed under three different conditions: 1) normal
condition (no stress), 2) moderate stress due to an increase in reactive
oxygen species (ROS) i.e. ROS levels were increased by a factor of 4 at
time=4hours for a period of 1 hour (not 2 hours as mentioned in the figure 5
legend of the reference publication. This is a typo in the paper and is
clarified by the author) and 3) high stress due to sustained increase in
reactive oxygen species (ROS) (here ROS increases with time).

The model that corresponds to the normal condition is submitted as a main
model in the BioModels Database. The other two models, that corresponds to the
moderate stress conditions and high stress conditions are available in SBML
format as supporting files [go to Curation tab].

Supplementary figures S3 (normal condition), S4 (moderate stress condition)
and S6 (high stress condition) are reproduced here.


