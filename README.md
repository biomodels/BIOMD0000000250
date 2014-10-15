# BIOMD0000000250: Model_1

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000250.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000250.git@20140916`


# Model Notes


This mechanistic model describes the activation of immediate early genes such
as cFos after EGF or heregulin (HRG) stimulation of the MAPK pathway.
Phosphorylated cFos is a key transcription factor triggering downstream
cascades of cell fate determination. The model can explain how the switch-like
response of p-cFos emerges from the spatiotemporal dynamics. This mechanistic
model comprises the explicit reaction kinetics of the signal transduction
pathway, the transcriptional and the posttranslational feedback and
feedforward loops. In the below article, two different mechanistic models have
been studied, the first one based on previously known interactions but failing
to account for the experimental data and the second one including additional
interactions which were discovered and confirmed by new experiments. The
mechanistic model encoded here is the second one, the extended and at the time
of creation most complete model of cell fate decision making in response to
different doses of EGF or HRG stimulation. The encoded parameter set
corresponds to 10mM HRG stimulation as shown in Fig.1 of the article. The
Supplementary Methods of the article provide further parameter sets that allow
simulations for different ligands and different doses. A corresponding core
model is available from http://www.ebi.ac.uk/biomodels/ as MODEL1003170000.

**Ligand-specific c-Fos expression emerges from the spatiotemporal control of ErbB network dynamics.**   
Takashi Nakakuki(1), Marc R. Birtwistle(2,3,4), Yuko Saeki(1,5), Noriko
Yumoto(1,5), Kaori Ide(1), Takeshi Nagashima(1,5), Lutz Brusch(6), Babatunde
A. Ogunnaike(3), Mariko Hatakeyama(1,5), and Boris N. Kholodenko(2,4); Cell
_In Press, online 20 May 2010_ , doi:
[10.1016/j.cell.2010.03.054](http://doi.dx.org/10.1016/j.cell.2010.03.054 )  
(1) RIKEN Advanced Science Institute, Computational Systems Biology Research
Group, Advanced Computational Sciences Department, 1-7-22 Tsurumi-ku,
Yokohama, Kanagawa, 230-0045, Japan  
(2) Systems Biology Ireland, University College Dublin, Belfield, Dublin 4,
Ireland  
(3) University of Delaware, Department of Chemical Engineering, 150 Academy
St., Newark, DE 19716, USA  
(4) Thomas Jefferson University, Department of Pathology, Anatomy, and Cell
Biology, 1020 Locust Street, Philadelphia, PA 19107, USA  
(5) RIKEN Research Center for Allergy and Immunology, Laboratory for Cellular
Systems Modeling, 1-7-22 Tsurumi-ku, Yokohama, 230-0045, Japan  
(6) Dresden University of Technology, Center for Information Services and High
Performance Computing, 01062 Dresden, Germany


