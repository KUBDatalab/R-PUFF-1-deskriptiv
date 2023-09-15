---
title: "Datasæt"
---

Det er ikke let at lære om statistik uden eksepler på data. 

I dette kursus bruger vi et udvalg af følgende datasæt. Ikke alle tages i 
brug, men her er de.


### BETACAR
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


### BLOOD.doc

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


### BONEDEN.DOC
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

### BOTOX
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

### Breast


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



###  Corneal

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


### DIABETES

Variable                      Column                      Code
ID                                 1-6
mon_a1c 	  	 8-9			Month A1c
day_a1c              	11-12                          Day A1c
yr_a1c                         14-15                          Yr A1c 
age_yrs                       17-20			Age in years	     
gly_a1c                       22-28                           Hemoglobin A1c                                     
ht_cm                          30-34                           Height in cm    missing=999.9        
wt_kg			36-39 	   		Weight in kg


### EAR


Variable      Column         Description               Format or Code
-------------------------------------------------------------------------
 Id             1-3          ID
 Clear           5           Clearance by 14 days     1=yes/0=no
 Antibo          7           Antibiotic               1=CEF/2=AMO
 Age             9           Age                      1=<2 yrs/2=2-5 yrs/
                                                      3=6+ yrs
 Ear            11           Ear                      1=1st ear/2=2nd ear
------------------------------------------------------------------------


### EFF

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


###  ENDOCRIN

 Variable      COLUMN       LABEL
  Subject        1          SUBJECT #
  Replicat       3          REPLICATE #
  Estrone       5-8         ESTRONE
  Estradol     10-13        ESTRADIOL
  Androste     15-18        ANDROSTENEDIONE
  Testost      20-23        TESTOSTERONE


Estradl.doc


Variable	Column		Code	

Id		5-8			Identification number
Estradl		12-16			Estradiol
Ethnic		18			Ethnicity 0=African-American;  1=Caucasian
Entage		20-21			Age
Numchild	24			Parity, number of children  9=missing
Agefbo		26-27			Age at 1st birth (=0 if numchild=0)  99=missing
Anykids	29			any children  1=yes;  0=no   9=missing
Agemenar	32-35			age at menarche   99=missing
BMI		37-43			Body Mass Index
WHR		46-49			waist-hip ratio


### ESTROGEN DOC

Variable    COLUMN                LABEL

Id           1-2                   ID
std_typ       4                    STUDY TYPE
                                     1=0.625MG VS PLACEBO
                                     2=1.25MG VS PLACEBO
                                     3=1.25MG VS 0.625MG
period        6                    PERIOD
trtgrp        8                    TREATMENT
                                     1=PLACEBO
                                     2=0.625MG
                                     3=1.25MG
sysd1r1     10-12                 SYSTOLIC BP DAY 1 READING 1
                                     MISSING=999
diasd1r1    14-16                 DIASTOLIC BP DAY 1 READING 1
                                     MISSING=999
sysd1r2     18-20                 SYSTOLIC BP DAY 1 READING 2
                                     MISSING=999
diasd1r2    22-24                 DIASTOLIC BP DAY 1 READING 2
                                     MISSING=999
sysd1r3     26-28                 SYSTOLIC BP  DAY 1 READING 3
                                     MISSING=999
diasd1r3    30-32                 DIASTOLIC BP DAY 1 READING 3
                                     MISSING=999
sysd2r1     34-36                 SYSTOLIC BP DAY 2 READING 1
                                     MISSING=999
diasd2r1    38-40                 DIASTOLIC BP DAY 2 READING 1
sysd2r2     42-44                 SYSTOLIC BP DAY 2 READING 2
diasd2r2    46-48                 DIASTOLIC BP DAY 2 READING 2
sysd2r3     50-52                 SYSTOLIC BP DAY 2 READING 3
diasd2r3    54-56                 DIASTOLIC BP DAY 2 READING 3
sysd3r1     58-60                 SYSTOLIC BP DAY 3 READING 1
diasd3r1    62-64                 DIASTOLIC BP DAY 3 READING 1
sysd3r2     66-68                 SYSTOLIC BP DAY 3 READING 2
diasd3r2    70-72                 DIASTOLIC BP DAY 3 READING 2
sysd3r3     74-76                 SYSTOLIC BP DAY 3 READING 3
diasd3r3    78-80                 DIASTOLIC BP DAY 3 READING 3


FEV.DOC

Variable      Column       Description           Format or Code
----------------------------------------------------------
 Id            1-5         ID number
 Age           7-8         Age (yrs)
 FEV          10-15        FEV (liters)           X.XXXX
 Hgt          17-20        Height (inches)        XX.X
 Sex           22          Sex                    0=female/1=male
 Smoke         24          Smoking Status         0=non-current smoker/
                                                  1=current smoker
----------------------------------------------------------


Field.doc

Variable    Column	Description

id                 1-6            ID
group            8              group (1=RHO/2=RPGR)
 age              11-14        age at visit  (XX.X in years)
 gender          16            gender (1=m/2=f)  Note: all RPGR individuals have to be male 
 dtvisit          18-27	  date of visit (month/day/year)
 folowup       29-34	  time from 1st visit in years
 totfldod       36-43	  total field area right eye (OD) in degrees²
 totfldos        45-52	  total field area left eye (OS) in degrees²

Heart.doc  

Variable	column		code
_______________________________________________________________________________________
Diagnosis	1-2		Y1=normal
				Y2=atrial septal defect without pulmonary stenosis or pulmonary hypertension
				Y3=ventricular septal defect with valvular pulmonary stenosis
				Y4=isolated pulmonary hypertension
				Y5=transposed great vessels
				Y6=ventricular septal defect without pulmonary hypertension
				Y7=ventricular septal defect with pulmonary hypertension
Prevalence	5-9		Prevalence
X1		12-15 		age 1-20 years old
X2		18-21		age>20 years old
X3		24-27		mild cyanosis
X4		30-33		easy fatigue
X5		36-39		chest pain
X6		42-45		repeated respiratory infections
X7		48-51		EKG axis more than 110


### HORMONE

Variable       Column      Description/Code
---------------------------------------------------------------------------
ID               4-5       ID
Bilsecpr         9-14      Biliary secretion-pre      
Bilphpr         18-23      Biliary pH-pre             
Pansecpr        26-32      Pancreatic secretion-pre   
Panphpr         37-41      Pancreatic pH-pre          
Dose            46-50      Dose 
Bilsecpt        53-59      Biliary secretion-post     
Bilphpt         64-68      Biliary pH-post            
Pansecpt        70-75      Pancreatic secretion-post  
Panphpt         79-84      Pancreatic pH-post 
Hormone          90        Hormone 1=SAL/2=APP/3=CCK/4=SEC/5=VIP
--------------------------------------------------------------------------


Hosiptal.doc

Variable       Column     Label

   Id           1-2           id no.

   Dur_stay     4-5           Duration of hospital stay

   Age          7-8           Age

   Sex          10            Sex  1=male/2=female

   Temp        12-15          First temperature following admission

   WBC         17-18          First WBC(x1000) following admission

   Antibio      20            Received antibiotic 1=yes/2=no

   Bact_cul     22            Received bacterial culture 1=yes/2=no

   Service      24            Service 1=med/2=surg.



### INFANTBP
-------------------------------------------------------------------------
Variable        Column         Format    Description
-------------------------------------------------------------------------
Salt Taste Variables
-------------------------------------------------------------------------
 ID              2-4
 Mn_sbp          7-11            xx.xx   Mean SBP 99.99=missing
 Mn_dbp         13-17            xx.xx   Mean DBP 99.99=missing
 MSB1slt        19-24           xxx.xx   MSB-trial 1* water
 MSB2slt        26-31           xxx.xx   MSB-trial 2 water
 MSB3slt        33-38           xxx.xx   MSB-trial 3 0.1 molar salt + water
 MSB4slt        40-45           xxx.xx   MSB-trial 4 0.1 molar salt + water
 MSB5slt        47-52           xxx.xx   MSB-trial 5 water
 MSB6slt        54-59           xxx.xx   MSB-trial 6 water
 MSB7slt        61-66           xxx.xx   MSB-trial 7 0.3 molar salt + water
 MSB8slt        68-73           xxx.xx   MSB-trial 8 0.3 molar salt + water
 MSB9slt        75-80           xxx.xx   MSB-trial 9 water
 MSB10slt       82-87           xxx.xx   MSB-trial 10 water

Sugar Taste Variables
--------------------------------------------------------------------------
 MSB1sug        89-94           xxx.xx   MSB-trial 1 non-nutritive sucking
 MSB2sug        96-101          xxx.xx   MSB-trial 2 water
 MSB3sug       103-108          xxx.xx   MSB-trial 3 5% sucrose + water
 MSB4sug       110-115          xxx.xx   MSB-trial 4 15% sucrose + water
 MSB5sug       117-122          xxx.xx   MSB-trial 5 non-nutritive sucking
--------------------------------------------------------------------------
* for MSB data 999.99 is a missing value; 0 indicates the baby did not suck.


   LEAD.DOC

VARIABLE  COLUMN    DESCRIPTION
 id        1-3      IDENTIFICATION NUMBER

 area       5       AREA - RESIDENCE ON AUG'72
                       1=0-1 MILES FROM SMELTER
                       2=1-2.5 MILES
                       3=2.5-4.1 MILES

 ageyrs    7-11      AGE in years xx.xx 

 sex        13       SEX  1=MALE  2=FEMALE

       IQ TEST RESULTS

 iqv_inf   15-16      INF - INFORMATION SUBTEST IN WISC AND WPPSI

 iqv_comp  18-19      COMP - COMPREHENSION SUBTEST IN WISC AND WPPSI

 iqv_ar    21-22      AR - ARITHMETIC SUBTEST IN WISC AND WPPSI

 iqv_ds    24-25      DS - DIGIT SPAN SUBTEST(WISC) AND SENTENCE
                           COMPLETION(WPPSI)

 iqv_raw   27-28      V/RAW - RAW SCORE/VERBAL IQ 

 iqp_pc    30-31      PC - PICTURE COMPLETION SUBTEST IN WISC AND WPPSI

 iqp_bd    33-34      BD - BLOCK DESIGN SUBTEST IN WISC AND WPPSI

 iqp_oa    36-37      OA - OBJECT ASSEMBLY SUBTEST(WISC), ANIMAL HOUSE
                           SUBTEST(WPPSI)

 iqp_cod   39-40      COD - CODING SUBTEST(WISC), GEOMETRIC DESIGN
                            SUBTEST(WPPSI)

 iqp_raw   42-43      P/RAW - RAW SCORE/PERFORMANCE IQ (TOTAL OF SCORES
                              PC, BD, OA, & COD)

 hh_index  45-46      HH/INDEX - HOLLINGSHEAD INDEX OF SOCIAL STATUS

 iqv       48-50      IQV - VERBAL IQ

 iqp       52-54      IQP - PERFORMANCE IQ

 iqf       56-58      IQF - FULL SCALE IQ (NOT SUM OR AVERAGE OF IQV D IQP)

 iq_type    60        TYPE OF IQ TEST   1=WISC  2=WPPSI
                       (WISC USUALLY GIVEN TO CHILDREN GE 5 YRS 1 MONTH OF AGE               
                        WPPSI USUALLY GIVEN TO CHILDREN LE 5YRS OF AGE)

 lead_grp   62        GROUP - BLOOD LEAD LEVEL GROUP

                         1=BLOOD LEAD LEVELS BELOW 40 MICROGRAMS/100ML IN
                                BOTH 1972 & 1973 (control group)
                           2=BLOOD LEAD LEVELS GREATER THAN OR EQUAL TO
                                40 MICROGRAMS/100ML
                                IN BOTH 72 & 73 OR A LEVEL GREATER THAN OR
                                EQUAL TO 40
                                IN 73 ALONE (3 CASES ONLY) (currently exposed 
                                 Group)
                           3=BLOOD LEAD LEVELS GREATER THAN OR EQUAL TO
                                40 MICROGRAMS/100ML
                                IN 72 AND LESS THAN 40 IN 73
                                 (previously exposed group)

 Group       64          1=control group; 2=exposed group
 
 ld72      66-67      LD72 - BLOOD LEAD VALUES (MICROGRAMS/100ML) IN72
                              MISSING=99

 ld73      69-70      LD73 - BLOOD LEAD VALUES (MICROGRAMS/100ML) IN 73

 fst2yrs    72        FST2YRS - DID CHILD LIVE FOR 1ST 2 YRS WITHIN
                              1 MILE OF SMELTER  1=YES  2=NO

 totyrs    74-75      TOTYRS - TOTAL NUMBER OF YEARS SPENT WITHIN
                              4.1 MILES OF SMELTER


       SYMPTOM DATA (AS REPORTED BY PARENTS)

 pica       77         PICA   1=YES  2=NO

 colic      79         COLIC  1=YES  2=NO

 clumsi     81         CLUMSINESS  1=YES  2=NO

 irrit      83         IRRITABILITY  1=YES  2=NO

 convul     85         CONVULSIONS  1=YES  2=NO

      CONTAIN NEUROLOGICAL TEST DATA
       
 _2plat_r  87-88       # OF TAPS FOR RIGHT HAND IN THE 2-PLATE TAPPING
                              TEST  (#TAPS IN ONE 10 SECOND TRIAL)
                              MISSING=99

 _2plat_l  90-91       # OF TAPS FOR LEFT HAND IN THE 2-PLATE TAPPING TEST
                                (#TAPS IN ONE 10 SECOND TRIAL)
                              MISSING=99

 visrea_r  93-94       VISUAL REACTION TIME RIGHT HAND (MILLISECONDS)
                              MISSING=99

 visrea_l  96-97       VISUAL REATION TIME LEFT HAND (MILLISECONDS)
                              MISSING=99

 audrea_r  99-100      AUDITORY REACTION TIME RIGHT HAND (MILLISECONDS)
                              MISSING=99

 audrea_l  102-103     AUDITORY REACTION TIME LEFT HAND (MILLISECONDS)
                              MISSING=99

 fwt_r    105-106      FINGER-WRIST TAPPING TEST RIGHT HAND
                              (# TAPS IN ONE 10 SECOND TRIAL)
                              MISSING=99

 fwt_l    108-109      FINGER-WRIST TAPPING TEST LEFT HAND
                              (#TAPS IN ONE 10 SECOND TRIAL)
                              MISSING=99

 hyperact  111-112    WWPS - WERRY-WEISS-PETERS SCALE FOR HYPERACTIVITY
                              0=NO ACTIVITY . . . . 4=SEVERLY HYPERACTIVE
                              (AS REPORTED BY PARENTS)
                              MISSING=99

 maxfwt     114-115      Finger-wrist tapping test in dominant hand(max of              
                         fwt_r,fwt_l)


{% include links.md %}

