<<<<<<< HEAD
[//]: # (This section starts with a 2nd level heading and get embedded in the result QA report at https://github.com/sPHENIX-Collaboration/QA-gallery/tree/QA-tracking-high-occupancy)

## Tracking QA at high occupancy

High occupancy tracking QA consists full tracker + reconstruction of events with 76 $\pi^+$, and 76 $\pi^-$ in a $\Delta\eta \times \Delta\phi = 0.5 \times 0.5$ window. In this small window, we would like to emulate the occupancy for 0-10% AuAu 200 GeV $\delta N_{Ch}/\delta\eta = 609$ [DOI: 10.1103/PhysRevC.83.024913]. Beyond this window, six more high $p_T>60$ GeV$/c$ pions are added to help constraint 3D vertex. 

Please note the calorimeters are disabled to improve execution speed, which also removed some of the correlated albedo background for the tracker. 

The source code of the macro can be found at https://github.com/sPHENIX-Collaboration/macros/tree/QA-tracking-high-occupancy or [comparing it to the master branch](https://github.com/sPHENIX-Collaboration/macros/compare/QA-tracking-high-occupancy?expand=1).
=======
[//]: # (This section starts with a 2nd level heading and get embedded in the result QA report at https://github.com/sPHENIX-Collaboration/QA-gallery/tree/QA-tracking-low-occupancy)

## Tracking QA at low occupancy

Low occupancy tracking QA concists full tracker + reconstruction of events with 20 $\pi^+$,  20 $\pi^-$ and one $\Upsilon(1S) \rightarrow e^+ e^-$. Please note the calorimeters are disabled to improve execution speed, which also removed some of the correlated albedo background for the tracker. 

The source code of the macro can be found at https://github.com/sPHENIX-Collaboration/macros/tree/QA-tracking-low-occupancy or [comparing it to the master branch](https://github.com/sPHENIX-Collaboration/macros/compare/QA-tracking-low-occupancy?expand=1).
>>>>>>> 15cad80c69c611809e5db1a4c1e6105061aa91a8
