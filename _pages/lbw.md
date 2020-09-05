---
permalink: "/lbw"
title: Laser Welding of Dissimilar Metals 
layout: default
---
# Laser Welding of Dissimilar Metals

This work was done as a part of my Ph.D. at the Indian Institute of Science, Bangalore.

Recent advances in the manufacturing processes using laser have led to increased use of advanced and dissimilar materials. Laser welding is a versatile technique with chemically pure heat source and a good control over power level to join extremely thin as well as very thick plates.

There is a lot of literature available on joining of similar metals/alloys. Not much, however, is known about dissimilar metal joining, which promises an important role in future.

![LBW schematic](assets/images/weldsch.jpg){:width="400px"}


Figure on the right shows a schematic of Laser Welding Setup : Butt weld with gaussian heat source applied symmetric about the centerline on the top

## Issues in Dissimilar Welding

Butt Welding of similar metals/alloys with the heat source placed symmetrical about the centerline on the top would usually lead to microstructural features that are well documented. Weld pool solidification takes place by continuous growth of base metal grains leading to columnar grains with a weld-centerline or equiaxed grains at the centre of the weld. The shape of the weld pool is symmetric about the centerline.

However, during welding of dissimilar metals, there are many interesting features that are not completely understood. Physical properties of the two metals being very different from each other lead to complexities in weld pool shape, solidification microstructure and segregation patterns.


![Welding of similar alloys](assets/images/weld2.jpg){:width="300px"} | ![Welding of dissimilar metals / alloys](assets/images/weld3.jpg){:width="300px"}
Welding of similar metals/alloys | Welding of dissimilar metals/alloys 

## Experimental Studies

The focus was on characterization and modeling aspects. Optical microscopy, Scanning Electron Microscopy, EDS and Transmission Electron Microscopy are used to characterize the microstructure. The welding experiments are done in collaboration with laser processing group of Technical University of Clausthal.

Systems studied were Copper-Nickel and Iron-Copper. Pure metals were chosen for simplicity and ease in fundamental understanding. Iron-copper system has solid state immiscibility and liquid miscibility. Copper and nickel have different physical properties but have complete miscibility in solid and liquid states and provide an ideal system for a detailed analysis.

![CuNi spot weld, top view](assets/images/cuni.jpg){:width="400px"}


## Computational Modelling of Laser Welding of Dissimilar Metals

A computational modelling of the transport phenomena that take place during laser welding of dissimilar metals of was developed using control volume formulation. Since the process is inherently three dimensional in nature, a 3D transient model was developed to calculate conservation of mass, momentum, enthalpy and composition. The model uses Patankar's SIMPLER algorithm. The program is written in Fortran 90. Visualization is done using Matlab and Tecplot. The computational facilities are provided by Supercomputer Education and Research Centre, Indian Institute of Science. 

![Thermal and velocity field](assets/images/dmw.jpg){:width="400px"}


## References 
Please Note that the soft copies of the papers are subject to copyright restrictions of the respective publishers.

  - Characterization of continuous CO2 laser welded Fe-Cu dissimilar couple   
Gandham Phanikumar, Sambandam Manjini, Pradip Dutta, Jyotirmoy Mazumder and Kamanio Chattopadhyay    
Metallurgical and Materials Transactions Vol.36A, August, pp. 2137-2147 (2005)  
[DOI](http://dx.doi.org/10.1007/s11661-003-0021-4)
  - Continuous welding of Cu-Ni dissimilar couple    
G. Phanikumar, P. Dutta and K. Chattopadhyay   
Science and Technology of Welding and Joining, Vol. 10, No. 2, pp. 158-166(9) April (2005)   
[DOI](http://dx.doi.org/10.1179/174329305X36043)
  - Computational modelling of laser welding of Cu-Ni dissimilar couple   
Gandham Phanikumar, Pradip Dutta and Kamanio Chattopadhyay    
Metallurgical and Materials Transactions B, Vol. 35B, Iss. April, pp. 339-350 (2004)    
[DOI](http://dx.doi.org/10.1007/s11661-005-0334-6)
  - Microstructural development of dissimilar weldments: case of MIG welding of Cu with Fe filler    
S. Kumar, G. Phanikumar, P. Dutta and K. Chattopadhyay    
Journal of Materials Science, Vol. 37, No. 11, pp. 2345-2349 (2002)    
[DOI](http://dx.doi.org/doi:10.1023/A:1015306408611)
  - Modelling of transport phenomena in laser welding of dissimilar metals    
G. Phanikumar, K. Chattopadhyay and P. Dutta    
International Journal of Numerical Methods in Heat and Fluid Flow, Vol. 11, No. 2, pp. 156-171 (2001)   
[URL](http://www.emeraldinsight.com/rpsv/cgi-bin/linker?reqidx=/cw/mcb/09615539/v11n2/s4/p156.idx&lkey=-1601331056&rkey=71801791)
  - Supercomputing Applications in Materials Engineering    
G. Phanikumar, Pradip Dutta and K. Chattopadhyay    
Current Science, Vol. 78, No. 7(April 10), pp. 847-849 (2000)    
[URL](http://www.iisc.ernet.in/currsci/apr102000/surveys3.pdf)
  - Solidification microstructures in laser welding of dissimilar metals    
G. Phanikumar, P. Dutta and K. Chattopadhyay    
International conference on solidification science and processing, Ed., B.K. Dhindaw, B.S. Murty, S. Sen, Science Publishers, Inc., Enfield, USA, pp 155-162 (2001)   
  - Laser processing of dissimilar metals    
G. Phanikumar, P. Dutta and K. Chattopadhyay    
Proc. Int. Symposium on Materials Ageing and Life Management (ISOMALM), Oct. 3-6, 2000, IGCAR, Kalpakkam,   
(Eds.) Baldev Raj, K.Bhanu Sankara Rao, T.Jayakumar, and R.K.Dayal, Allied Publishers Ltd., Chennai, India, (2000)
  - Dissimilar Metal Welding of Copper-Nickel Couple by Continuous Wave CO2 Laser    
Dutta, P., Phanikumar, G., Pardeshi, R., Mazumder, J., and Chattopadhayay, K.    
Trends in Welding Research (ISBN: 0-87170-627-X), Proceedings of the 5th international conference, ASM International, Ohio, USA, pp 461-466 (1999)    
  - Numerical Simulation of Laser Welding of Dissimilar Metals    
G. Phanikumar, K. Chattopadhyay, and P. Dutta    
Mathematical Modelling of Weld Phenomena V, Institute of Materials, London, pp 885-896 (2000) 

