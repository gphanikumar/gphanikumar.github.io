---
permalink: "/pfm"
title: Phasefield Modelling
layout: default
---
# Phasefield Modelling

## Code development

![3D dendrite](assets/images/pf3d1.png){:width="600px"}

The aspects currently being looked at are :
  * Use of CALPHAD approach to use realistic thermodynamic data
  * Effective computation using parallel processing and GPU computing using OpenCL.

![3D dendrite](assets/images/pf3d2.png){:width="600px"}

The work forms part of doctoral thesis of [P. Gerald Tennyson](students/gerald.html). Several models have been implemented over last few years by students as described below.

[Abhik N. Choudhury](students/abhik.html) implemented most of the eutectic models available in the literature as part of his work for his Dual Degree project.

[B.G. Chirranjeevi](students/chirranjeevi.html) implemented anisotropic free dendrite growth model and extended it to 3D solidification.


![Polycrystalline solidification](assets/images/aravind-poly1.png){:width="600px"}

[Aravind Krishnamurty](students/aravind.html) implemented a phase field model based on using the orientation as an order parameters for 2D simulation of solidification into polycrystalline microstructures. 

[Sanket](students/sanket.html) implemented a dry snow metamorphosis model to simulate microstructures of snow formation using a phase field model.

[Suryanaman](students/suryanaman.html) implemented the non-linear stability analysis of solidification to see the effect of amplitude of perturbation on the stability using Mathematica®. He also implemented asymptotic analysis in Mathematica® to retrieve Stefan's condition and Gibbs-Thomson condition from diffuse interface models.

## References
Please note that soft copies of publications are subject to copyright of the respective publishers.
   - MPI + OpenCL implementation of a phase-field method incorporating CALPHAD description of Gibbs energies on heterogeneous computing platforms  
P. Gerald Tennyson, G. M. Karthik, G. Phanikumar   
Computer Physics Communications, pp. 48-64, vol. 186 (2015)   
[DOI](http://dx.doi.org/10.1016/j.cpc.2014.09.014)
   - Computational modelling of dendritic to globular transition using an isothermal binary phase-field model   
P. Gerald Tennyson and G. Phanikumar   
Transactions of Indian Institute of Metals, Vol. 64, No.1-2, pp. 251-254, (2011)   
[URL](http://www.springerlink.com/content/w4180u34170m52w4/)
  - Experimental studies and phase field modeling of microstructure evolution during solidification with electromagnetic stirring   
P. Gerald Tennyson, P. Kumar, H. Lakshmi, G. Phanikumar, P. Dutta    
Transactions of the Non-ferrous Metals Society of China, vol. 20, supplement 3, pp. s774-s780 (2010)    
[DOI](http://dx.doi.org/10.1016/S1003-6326\(10\)60580-8) 

## Using MICRESS

We have also used [MICRESS](https://micress.rwth-aachen.de/) - The Microstructure Evolution Simulation Software from [Access e.V.](http://www.access.rwth-aachen.de/), Aachen, Germany. This software is coupled with [Thermo-Calc](https://www.thermocalc.com/) databases to simulate segregation in technical alloys.

## References

Rahul's HEA papers get listed here.
