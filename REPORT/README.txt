Alessandro Rodeghero VR474699
Lorenzo Tabarelli VR477605

#############################################################

INSTALLATION AND PROJECT FOCUS
-Readme.md
-PROJECT FOCUS - ADVERSARIAL POMCP.pdf

Readme.md is divided in two parts:
the first one explains how to install and run the software.
the second one is a description of the software's structure.

PROJECT FOCUS - ADVERSARIAL POMCP.pdf describes the focus of this project.

##############################################################

TESTS ANALYSIS
-TEST
-IMGS
-ACCURACIES
-ANALYSIS.pdf

TEST is a directory containing the python notebook used to
run all the tests we've done.

-- !python3 jacobian_pomcp_custom.py 190 64_32_32_32 0.2 800 0.5 20 40 0.3 1 --
-- where the parameters are:
---initial train size
---nn_architecture
---dropout
---number of training epochs
---lambda
---max rho
---k
---validation split
---directory where the models are saved

IMGS is a directory containing the plots.

ACCURACIES is a directory containing the tests outputs in 
which are reported the accuracies for each configuration tested:
*30 tests with default configuration
*141 tests with custom configurations
*40 tests with random augmentation
*18 tests with jacobian augmentation(with validation)
*229 total tests

ANALYSIS.pdf reports various tests that we have done with 
plots and observations.


