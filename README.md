##Introduction
A basic quantum chemical program written in python using the numpy and scipy libraries and is currently at the very beginnings. My time is tight as I try to balance this between my job and real-life so development may go slowly.

The basic HF part is complete, calculations can be carried out on all molecules and basis sets. It's a little slow at the moment and I need to work on making it faster. Currently this program fully supports RHF, UHF and MP2, next plans are to include reduced ERI time be taking advantage of molecule symmetry and then to implement more correlated methods such as DFT and CI. 

I'm basing this work on Attlia Szabo and Neil S. Ostlunds "Modern Quantum Chemistry: Introduction to Advanced Electronic Structure Theory" and David B. Cooks "Handbook of Computational Chemistry".

The tests section is very poor at the moment because it isn't worth my time will start adding more later.

Please see my GitHub pages http://chicheng45.github.io/Quantum_Chemistry/ for documentation and comparisons against other Qunatum Chemical Software Packages. 