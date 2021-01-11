# BayesianDecisionWeights

Decision Making Exam for Cognitive Science Masters.

## Project Description

Pipeline for experimental validation of the idea
that Prospect Theory's (PT) reverse S-shaped weighting function
is modulated by the affect of outcomes for risky decisions
(Rottenstreich & Hsee, 2001).

This pipeline is a suggestion for how their initial
(and convincing) findings can be tested more rigorously.

See the folder "Code" for code used in the project.
See the folder "Report" for the report submitted.
See the folder "Literature" for the literature that I build on.

# Project Overview

## Report

Contains the bibtex library used for the report,
alongside latex and pdf compilations of the report.

## Code

Figures which visualize the parameters of different
weighting functions are generated in the file
"0\_visualize\_paramters.Rmd".

Data is simulated in the file "1\_simulate\_data.Rmd".

The simulated data is sanity checked in the file
"2\_check\_simulated.Rmd".

Then the simulated data is modeled (i.e.
non-observed parameters are estimated) with
a (non)linear bayesian model in the file
"3\_toy\_model.Rmd".

Lastly, the file "4\_testing\_hypotheses.Rmd"
looks at the credibility intervals of the paramters
of interest for the three conditions studied.

## Figures

Figures generated in the .Rmd files in the code
folder are stored in the "figures" folder.
All figures from the assignment are there.

## Data

The fit of the bayesian model and the simulated data
are located in this folder.

## Literature

.pdf versions of the used literature is in the "Literature"
folder (with comments).

