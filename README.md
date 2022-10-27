# Meta-analysis_OA

## Major importance of the workflow description
-------------------------------------------------
+ The important data files in this meta-analysing was using clark_paper_data.csv, meta-data_ocean_meta.csv, OA_activitydat_20190302_BIOL3207.csv. 
+ These three data was converted and put together into one dataset which is called as ocean_meta_data.csv data file.
+ The rmd was then rendered into html as well as uploaded to the GitHub desktop and then after collaborating the data can be cloned and reproduced.

## meta-data - column description and details in the ocean_meta_data.csv data file. 
------------------------------------------------------------------------------------
in this table/ tibble the important columns will be only described (the necessary ones for the meta analysis)
Name of the Column - Description
+ Study 
+ Year (online) - the online was chosen first as the online publication date year was first before the printed year date (year measured) 
+ Species - Species name: acantho = Acanthochromis; Ambon = Pomacentrus amboinensis; Chromis = Chromis atripectoralis; Humbug = Dascyllus aruanus; Lemon = Pomacentrus moluccensis	
+ Life stage - the stages of the fishes there were 
+ ctrl.n - number of samples in the control treatment
+ ctrl.mean - the mean of the acticity in controlled treatment
+ ctrl.sd - the standard deviation of the acticity in controlled treatment
+ oa.n - number of samples in the elevated CO2 treatment
+ oa.mean - the mean of the acticity in elevated CO2 treatment
+ oa.sd - the standard deviation of the acticity in elevated CO2 treatment

+ effect.size - gives information about the relationship between the variables 
+ sampling.variance - the spread of the values that are around the expected values

## file structure (content)
----------------------------
i) Statistical Analysis and Interpretation 
+ This section will contain getting the summary (m, n and sd) from the first file and then put into a table. 
+ Then the file 2 was binded together with the summary table (it was made sure that the species were re-worded) 
+ Then the combined table was then was inserted into the 3rd file. This was for the meta-analysis. Funnel plot, forest plot (orchard plot), time-lag plot, meta-analytic model using the rma.mv function and the escalc function was used. 
+ Then this was setup in a public GitHub Repository (where the link is also attached) 
[https://github.com/Han3207/Meta-analysis_OA.git]
