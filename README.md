# DFT-derived Force Field Parameters

## Description

+ DFT-derived force field parameters for CO<sub>2</sub>, H<sub>2</sub>O, and
 CH<sub>4</sub> in M-MOF-74 (M = Mg, Mn, Fe, Co, Ni, Zn) can be found under
 *forcefield/*
+ Minimized M-MOF-74 structures used for all calculations in the paper can be
 located in *structures/*
+ Molecule .def field files used in combination with DFT-derived force field
 can be located in *molecules/*

## Comments
The input .def files can be used as-is for simulations in COTA or RASPA.

Because the standard exponential-6 form approaches negative infinity as the
 distance approaches zero, it is recommended to use a 'hacked' Buckingham
 potential (one which is set to an arbitrarily large, positive value at very
 short distances) so as to avoid atomic overlap during MC simulations. This
 should not be a problem in MD simulations if the system is initialized
 properly, and the standard Buckingham functional form should be adequate.

## Reference
Mercado, R.; Vlaisavljevich, B.; Lin, L.-C.; Lee, K.; Lee, Y.; Mason, J. A.;
 Xiao, D. J.; Gonzalez, M. I.; Kapelewski, M. T.; Neaton, J. B.; Smit, B.
 *J. Phys. Chem. C*, **2016**, *120* (23), 12590–12604.
DOI: [10.1021/acs.jpcc.6b03393](http://dx.doi.org/10.1021/acs.jpcc.6b03393)

## Link 
https://github.com/rociomer/DFT-derived-force-field

