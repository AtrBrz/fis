# Wheat Flour Products Manufacturing Risk Assessment

This repository contains the MATLAB models serving as a replication package for the submitted paper reported at the end of this file. This repository also contains additional material for the above-mentioned paper.

## Context
<!-- @Atrin: here a breif summary of the scope and the context of the paper (no more than 4 lines) --> 
The goal of this research is to create an intelligent system to assess the manufacturing system’s level of risk for wheat flour products. Five Fuzzy Inference Systems (FISs) are arranged in two layers of the model to assess the risk associated with a system that produces wheat flour products.Four FISs evaluate risks based on FMEA criteria (Occurrence, Severity, and Detectability) with expert input. The
outputs, covering Physical, Chemical, Biological, and Environmental Failures, are then integrated for overall system ranking.in the second layer all risks is the input of the model and the output shows the final risk in the manufacturing system based on integration of all IF-THEN rules.
<!-- @Atrin: describe the content of the folders --> 
* *[replication/edcc](replication/edcc/README.md)*: replication package for a scientific paper submitted to KES 2024.
  first folder related to all figures and diagrams( Membership functions, rule viewer, surface viewer,..)
  and the second one related to the fis file including all details and information of my work and IF-THEN rules.

## Additional Material
<!-- @Atrin: put some description of the figures and the figures as well -->
-figure Chemical Risk.Occurence shows the fuzzy model for chemical risk. the model consists of 3 inputs which are occurence, severity and detectability and the output of model is chemical risk the implication method is Min and the aggregation method is Max and the defuzzification is centroid.
-figure chemical_surface shows the surface viewer of chemical risk. when the occurence and detectability are very small, the chemical risk is minor and when the occurence and detectability are very high the chemical risk is important.  
-figure environmental_rule shows the rule viewer of environmental risk it means that for example when occurence is 65 percent and severity 70 and detectability is 60 percent the environmental risk is 70 percent. 
-figure final risk shows the mamdani fuzzy model based on 4 different risks input( Physical, Biological, Chemical, Environmental) and the output shows the final risk in the system.the defuzzification is centroid and implication is min and (and, or) methode is min-max.
-figure finalrisk_rule shows the Matlab’s rule viewer and final risk level in manufacturing system that is 22.5 percent based on 4 input. the level of first risk(physical risk) is 60.1 percent and second input is biological risk that is 76.3 percent and environmental risk is 71.3 percent.The output of this model is a final risk of the system in 5 different ranges from 0 to 100 %. the final risk from 0% to 19% shows poor situation, from 20% to 39% shows fair situation, from 40% to 59% shows average situation, from 60% to 79% shows good situation and from 80% to 100% shows excellent situation(Low-risk level) which means the great manufacturing systems.so our case study is in the fair situation.


In the following figure, the Membership function of the Final Risk is reported.
![Membership function for the final risk](./images/finalriskmembership.jpg)


## Replication Package
<!-- @Atrin: describe here the instructions on how to replicate the work (how to run the models) --> 
in this work, we used matlab software to create the intelligent model system to assess the manufacturing system’s level of risk. Five Fuzzy Inference Systems (FISs) are arranged in two layers of the model to assess the risk associated with a system that produces wheat flour products.Four FISs evaluate risks based on FMEA criteria (Occurrence, Severity, and Detectability) with expert input. The
outputs, covering Physical, Chemical, Biological, and Environmental Failures, are then integrated for overall system ranking.in the second layer all risks is the input of the model and the output shows the final risk in the manufacturing system based on integration of all IF-THEN rules.


## License
The software is licensed according to the GNU General Public License v3.0 (see License file).

## People
* Atrin Barzegar - Università della Campania "Luigi Vanvitelli" (Italy)

## Credits
This software is build using Matlab R2023a, licensed to Universita' della Campania "Luigi Vanvitelli". The tools use the Fuzzy Logic Toolbox v.3.1.

## References
The figures and the replication package refer to the paper "Fuzzy Inference System for Risk Assessment of Wheat Flour Product Manufacturing Systems", submitted to the 28th International Conference on Knowledge-Based and Intelligent Information & Engineering Systems (KES 2024).

