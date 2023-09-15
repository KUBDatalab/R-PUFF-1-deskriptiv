---
title: "Datasæt"
---

Det er ikke let at lære om statistik uden eksepler på data. 

I dette kursus bruger vi et udvalg af følgende datasæt. Ikke alle tages i 
brug, men her er de.


BETACAR
---------------------------------------------------------------------
Variable            Column        Description/Code
---------------------------------------------------------------------
Prepar    		     1          Preparation 1=SOL/2=ROCHE/3=BASF-30/4=BASF-60
Id                   3-4          Subject #
Base1lvl    	   6-8          1st Baseline Level 
Base2lvl 		  10-12         2nd Baseline Level 
Wk6lvl 	        14-16         Week 6 Level
Wk8lvl	        18-20         Week 8 Level 
Wk10lvl		  22-24         Week 10 Level	
Wk12lvl	        26-28         Week 12 Level 
---------------------------------------------------------------------


BLOOD.doc

Variable                 Column                    Description
__________________________________________________________________
Id                             1-6                              ID
matchid                   8-13                            Matched ID
case                          15                               Case/control  1=case/ 0=control
curpmh                     17                               Current PMH use  1=yes / 0=no
ageblood                 19-20                           Age at blood draw
estradol                   22-23                           Estradiol
estrone                    25-27                           Estrone  missing=999
testost                     29-31                           Testosterone  missing=999
prolactn                  34-38                           Prolactin   xx.xx  missing=99.99


BONEDEN.DOC
---------------------------------------------------------------------
Variable    Column       Code
---------------------------------------------------------------------
ID           2-8
Age          9-11        Age (yrs)
zyg         12-14        1=mz 2=dz

    Twin 1  Lighter Smoking Twin

ht1         15-19        Height (cm)
wt1         20-24        Weight (kg)
tea1        25-29        Tea  (cups/week)
cof1        30-34        Coffee  (cups/week)
alc1        35-39        Alcohol  (drinks/week)
cur1        40-44        Current Smoking (cigarettes/day)
men1        45-49        Menopause Status (0=pre/1=post/2=unknown hysterectomy)
pyr1        50-55        Pack-years smoking
ls1         56-61        Lumbar spine (g/cm**2)
fn1         62-67        Femoral neck (g/cm**2)
fs1         68-73        Femoral shaft (g/cm**2)

      Twin 2  Heavier Smoking Twin

ht2         74-78        Height (cm)
wt2         79-83        Weight (kg)
tea2        84-88        Tea  (cups/week)
cof2        89-93        Coffee  (cups/week)
alc2        94-98        Alcohol  (drinks/week)
cur2        99-103       Current Smoking (cigarettes/day)
men2       104-108       Menopause Status (0=pre/1=post/2=unknown hysterectomy)
pyr2       109-114       Pack-years smoking
ls2        115-120       Lumbar spine (g/cm**2)
fn2        121-126       Femoral neck (g/cm**2)
fs2        127-132       Femoral shaft (g/cm**2)
---------------------------------------------------------------------

BOTOX.DOC
---------------------------------------------------------------------
Variable    Column       Code
---------------------------------------------------------------------
ID           1-3
group         5          1=TL/2=Placebo/3=Botox
pain0        6-9         pain score month 0  missing=999
pain05      10-13        pain score month 0.5  missing=999
pain1       14-17        pain score month 1  missing=999
pain2       18-21        pain score month 2  mising=999
pain3       22-25        pain score month 3  missing=999
pain4       26-29        pain score month 4  missing=999
pain5       30-33        pain score month 5  missing=999
pain6       34-37        pain score month 6  missing=999
pain7       38-41        pain score month 7  missing=999
pain8       42-45        pain score month 8  missing=999
pain9       46-49        pain score month 9  missing=999
pain10      50-53        pain score month 10  missing=999
pain11      54-57        pain score month 11  missing=999
pain12      58-61        pain score month 12  missing=999
pain13      62-65        pain score month 13  missing=999
pain14      66-69        pain score month 14  missing=999
pain15      70-73        pain score month 15  missing=999
pain16      74-77        pain score month 16  missing=999
pain17      78-81        pain score month 17  missing=999
---------------------------------------------------------------------

Breast.doc

variable    column    Description
Id           1-6      ID
case          8       case   1=case, 0=control
age          10-11    age
agemenar     13-14    age at menarche
agemenop     16-17    age at menopause
afb          19-20    age at first birth  98=nullip
parity       22-23    parity
bbd           25      Benign Breast disease  1=yes/0=no
famhx         27      family history breast cancer  1=yes/0=no
bmi          30-34    BMI (kg/m**2)
hgt          37-38    Height (inches)
alcohol      40-45    Alcohol use (grams/day)
pmh           47      PMH status  2=never user/3=current user
dur3         49-51    Duration of Estrogen use  (months)
dur4         53-55    Duration of Estrogen + progesterone use  (months)
csmk          57      Current Smoker 1=yes/0=no
psmk          59      Past smoker  1=yes/0=no
foluptm      61-64    Months of follow up Note: Some subjects provided no  
                      follow up after the 1990 questionnaire: foluptm=0 for
                      these people



  Corneal.doc

Variable   Column      Variable label
  id        2-3        ID
  tr         5         Treatment   1=M   2=G  3=P          
  c1        8-9        Central  visit 1                    
  s1       12-13       Superior visit 1                    
  i1       16-17       Inferior Visit 1                    
  t1       20-21       Temporal visit 1                    
  n1       24-25       Nasal Visit 1                       
  c2       28-29       Central Visit 2(day 7)              
  s2       32-33       Superior Visit 2                    
  i2       36-37       Inferior Visit 2                    
  t2       40-42       Temporal Visit 2                    
  n2       44-45       Nasal Visit 2                       
  c3       48-49       Central Visit 3(day 14)  missing=99             
  s3       52-53       Superior Visit 3  missing=99                  
  i3       56-57       Inferior Visit 3  missing=99                  
  t3       60-61       Temporal Visit 3  missing=99                  
  n3       64-65       Nasal Visit 3     missing=99   


DIABETES .DOC

Variable                      Column                      Code
ID                                 1-6
mon_a1c 	  	 8-9			Month A1c
day_a1c              	11-12                          Day A1c
yr_a1c                         14-15                          Yr A1c 
age_yrs                       17-20			Age in years	     
gly_a1c                       22-28                           Hemoglobin A1c                                     
ht_cm                          30-34                           Height in cm    missing=999.9        
wt_kg			36-39 	   		Weight in kg


EAR.DOC

Variable      Column         Description               Format or Code
-------------------------------------------------------------------------
 Id             1-3          ID
 Clear           5           Clearance by 14 days     1=yes/0=no
 Antibo          7           Antibiotic               1=CEF/2=AMO
 Age             9           Age                      1=<2 yrs/2=2-5 yrs/
                                                      3=6+ yrs
 Ear            11           Ear                      1=1st ear/2=2nd ear
------------------------------------------------------------------------


EFF.DOC

Variable             Column         Description/Code
---------------------------------------------------------------------------
Name                   1-8          Study name
Id                    10-11         Study Number 
Endpnt                 13           Endpoint  1=efficacy   
Antibio                15           Antibiotic                  
                                    1=Amikacin/2=Gentamicin/3=Netilmicin/
                                    4=Sisomycin/5=Tobramycin
Samp_sz               17-19         Sample Size 
Cured                 21-23         Number Cured 
---------------------------------------------------------------------------




{% include links.md %}

