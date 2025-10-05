# takeover-request-dataset
This dataset contains anonymized experimental data collected from a driving simulator study conducted at Seoul National University.
The study examined how hazard type (behavioral vs. environmental) and takeover request (ToR) explanation type (action-only, precursor-only, hazard-only, precursor + hazard) jointly influence drivers’ cognitive and behavioral responses during conditionally automated driving (SAE Level 3).

## Experimental Overview
**Design:** 4 (Explanation Type) × 2 (Hazard Type) within-subjects design  

**Hazard Types:**  
- Behavioral Prediction (BP)  
- Environmental Prediction (EP)  
*(Based on Crundall’s hazard taxonomy distinguishing driver reasoning demands.)*  

**Explanation Types:**  
- E1: Action-only  
- E2: Precursor-only  
- E3: Hazard-only  
- E4: Precursor + Hazard  

**Participants:** 12 licensed drivers (normal or corrected-to-normal vision/hearing)  
**Simulator:** Forum 8 UC WinRoad ver. 10  
**Task:** Participants engaged in non-driving-related smartphone tasks during automated driving and responded to system-issued takeover requests.  
**Takeover timing:** ToR issued at 6,000 m with a 7 s takeover lead time and 10 s time-to-collision.  

**File format:** CSV (UTF-8 encoded)  
Each participant contributed 8 rows (4 explanation × 2 hazard conditions), totaling 96 rows.
