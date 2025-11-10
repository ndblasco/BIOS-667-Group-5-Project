# This is the repository for Group 5's Final Project for BIOS 667. 

### RQ: Does treatment have a significant effect on TWSTRS score over time, adjusting for age and sex?  
Data obtained from http://hbiostat.org/data courtesy of the Vanderbilt University Department of Biostatistics  

This dataset in from Table 6.9 of Statistical Methods for the Analysis of Repeated Measurements by Charles S. Davis, pp. 161-163 (Springer, 2002). These data are from a multicenter, randomized controlled trial of botulinum toxin type B (BotB) in patients with cervical dystonia from nine U.S. sites.  
* Randomized to placebo (N=36), 5000 units of BotB (N=36), 10,000 units of BotB (N=37)
* Response variable: total score on Toronto Western Spasmodic Torticollis Rating Scale (TWSTRS), measuring severity, pain, and disability of cervical dystonia (high scores mean more impairment)
* TWSTRS measured at baseline (week 0) and weeks 2, 4, 8, 12, 16 after treatment began
* treat = 1,2,3 is 10000 U, 5000 U, Placebo respectively
* sex=1 is female, sex=2 is male

**To read dta file into R:**  
library(haven)  
df <- read_dta("cdystonia.dta")  

**Workload Split:**  
* Intro/Methods: Lauren  
* Modeling and corresponding Results section:  
  * GLM: Nathalie  
  * GEE: Lily
  * GLMM: Sirui
* Discussion/Conclusion: Yihao

