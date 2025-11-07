# P-Delta Analysis

## What is it?
- In normal analysis, geometry of structure don't change when applying forces. 
- So Internal forces are computed using original geometry.
- But in reality, when structure deflects, loads act on deformed shape, producing secondary moment and increased stresses.
- This is called `P-Delta` effect $M = P \times \Delta$ , here P = Axial load acting on structure and Delta = Lateral displacement
- P-Delta Analysis is extremely important in case of tall buildings where there is large amount of lateral drift  or structure with slender columns or frames or structure with high flexibility
- seismic or wind-loaded buildings are also affected by this.

## Types of P-Delta effects
- GLobal P-Delta effect
  - Overall lateral sway of the entire structure
  - for example wind load on tall building
- Local P-Delta effect
  - Local bending of individual members
  - Column bending between floors

## How Modern software deals with it?
- All the modern software like ETABS, SAP2000 and STAAD Pro supports P-Delta analysis.
- This software first runs first order analysis and then calculates additional movements using deflections.
