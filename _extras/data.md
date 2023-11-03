---
title: "Datasæt"
---

Det er ikke let at lære om statistik uden eksepler på data. 

I dette kursus bruger vi et udvalg af følgende datasæt. Ikke alle tages i 
brug, men her er de.


### BETACAR

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/BETACAR.csv)


|Variable    |          Description/Code
|------------|---------------------------------------------------------
|Prepar      |  Preparation 1=SOL/2=ROCHE/3=BASF-30/4=BASF-60
|Id          |      Subject #
|Base1lvl    |   1st Baseline Level 
|Base2lvl    | 2nd Baseline Level 
|Wk6lvl      |    Week 6 Level
|Wk8lvl      |     Week 8 Level 
|Wk10lvl     | Week 10 Level	
|Wk12lvl     |      Week 12 Level 


### BLOOD

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/BLOOD.csv)

|Variable                  |          Description
|----------------|----------------------------
|Id                     |                       ID
|matchid         |                 Matched ID
|case            |                      Case/control  1=case/ 0=control
|curpmh          |                   Current PMH use  1=yes / 0=no
|ageblood                   |                Age at blood draw
|estradol                 |                  Estradiol
|estrone                  |                  Estrone  missing=999
|testost                 |                   Testosterone  missing=999
|prolactn                  |                 Prolactin   xx.xx  missing=99.99


### BONEDEN

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/BONEDEN.csv)


|Variable  |  Column   |      Code
|----------|------------|-----------------------------------------------
|ID        |   2-8     |
|Age       |   9-11    |    Age (yrs)
|zyg       |  12-14    |    1=mz 2=dz

Twin 1  Lighter Smoking Twin

|Variable |      Code
|---------|-----------------------------------------------
|ht1      |     Height (cm)
|wt1      |     Weight (kg)
|tea1     |     Tea  (cups/week)
|cof1     |     Coffee  (cups/week)
|alc1     |     Alcohol  (drinks/week)
|cur1     |     Current Smoking (cigarettes/day)
|men1     |     Menopause Status (0=pre/1=post/2=unknown hysterectomy)
|pyr1     |     Pack-years smoking
|ls1      |     Lumbar spine (g/cm**2)
|fn1      |     Femoral neck (g/cm**2)
|fs1      |     Femoral shaft (g/cm**2)

Twin 2  Heavier Smoking Twin

|Variable  |      Code
|----------|-----------------------------------------------------------
|ht2       |         Height (cm)
|wt2       |         Weight (kg)
|tea2      |         Tea  (cups/week)
|cof2      |         Coffee  (cups/week)
|alc2      |         Alcohol  (drinks/week)
|cur2      |         Current Smoking (cigarettes/day)
|men2      |         Menopause Status (0=pre/1=post/2=unknown hysterectomy)
|pyr2      |         Pack-years smoking
|ls2       |         Lumbar spine (g/cm**2)
|fn2       |         Femoral neck (g/cm**2)
|fs2       |         Femoral shaft (g/cm**2)



### BOTOX

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/BOTOX.csv)


|Variable    |       Code
|------------|---------------------------------------------------------
|ID          |
|group       |           1=TL/2=Placebo/3=Botox
|pain0       |         pain score month 0  missing=999
|pain05      |        pain score month 0.5  missing=999
|pain1       |        pain score month 1  missing=999
|pain2       |        pain score month 2  mising=999
|pain3       |        pain score month 3  missing=999
|pain4       |        pain score month 4  missing=999
|pain5       |        pain score month 5  missing=999
|pain6       |        pain score month 6  missing=999
|pain7       |        pain score month 7  missing=999
|pain8       |        pain score month 8  missing=999
|pain9       |        pain score month 9  missing=999
|pain10      |        pain score month 10  missing=999
|pain11      |        pain score month 11  missing=999
|pain12      |        pain score month 12  missing=999
|pain13      |        pain score month 13  missing=999
|pain14      |        pain score month 14  missing=999
|pain15      |        pain score month 15  missing=999
|pain16      |        pain score month 16  missing=999
|pain17      |        pain score month 17  missing=999

### Breast
[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/Breast.csv)


|variable     |     Description |
|-------------|-----------------------------------------|
|Id           |        ID |
|case         |       case   1=case, 0=control  |
|age          |          age  |
|agemenar     |       age at menarche |
|agemenop     |       age at menopause  |
|afb          |          age at first birth  98=nullip  |
|parity       |        parity |
|bbd          |        Benign Breast disease  1=yes/0=no  |
|famhx        |        family history breast cancer  1=yes/0=no |
|bmi          |          BMI (kg/m**2)  |
|hgt          |          Height (inches)  |
|alcohol      |        Alcohol use (grams/day)  |
|pmh          |        PMH status  2=never user/3=current user  |
|dur3         |          Duration of Estrogen use  (months) |
|dur4         |          Duration of Estrogen + progesterone use  (months)  |
|csmk         |        Current Smoker 1=yes/0=no  |
|psmk         |        Past smoker  1=yes/0=no  |
|foluptm      |        Months of follow up Note: Some subjects provided no    |
|              |        follow up after the 1990 questionnaire: foluptm=0 for |
|              |        these people  |



###  Corneal

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/Corneal.csv)


|Variable   |        Variable label|
|-----------|-------------------------------|
|  id       |    ID|
|  tr       |      Treatment   1=M   2=G  3=P          |
|  c1       |        Central  visit 1                    |
|  s1       |         Superior visit 1                    |
|  i1       |         Inferior Visit 1                    |
|  t1       |         Temporal visit 1                    |
|  n1       |         Nasal Visit 1                       |
|  c2       |         Central Visit 2(day 7)              |
|  s2       |         Superior Visit 2                    |
|  i2       |         Inferior Visit 2                    |
|  t2       |         Temporal Visit 2                    |
|  n2       |         Nasal Visit 2                       |
|  c3       |         Central Visit 3(day 14)  missing=99             |
|  s3       |         Superior Visit 3  missing=99                  |
|  i3       |         Inferior Visit 3  missing=99                  |
|  t3       |         Temporal Visit 3  missing=99                  |
|  n3       |         Nasal Visit 3     missing=99   |


### DIABETES

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/DIABETES.csv)


|Variable     |                                       Code|
|-----------|----------------------------------------------|
|ID                 |     |
|mon_a1c 	  	| 			Month |
|day_a1c        |                    Day A1c|
|yr_a1c         |                          Yr  |
|age_yrs        |			Age in years	|
|gly_a1c        |                     Hemoglobin A1c                                     |
|ht_cm            |                                         Height in cm    missing=999.9
|wt_kg			 	 |  		Weight in 


### EAR

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/EAR.csv)


|Variable      |         Description               |Format or Code|
|--------------|-----------------------------------------------------------|
|Id           |            ID                         ||
| Clear        |              Clearance by 14 days   |  1=yes/0=no|
| Antibo       |              Antibiotic             |  1=CEF/2=AMO|
| Age          |              Age                    |  1=<2 yrs/2=2-5 yrs/|
|              |                                     |   3=6+ yrs|
| Ear          |             Ear                     | 1=1st ear/2=2nd ear|



### EFF

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/EFF.csv)


|Variable           |           Description/Code|
|--------------|-------------------------------------------------------------|
|Name                   |         Study name|
|Id                       |      Study Number |
|Endpnt               |             Endpoint  1=efficacy   |
|Antibio              |             Antibiotic                  |
|                           |         1=Amikacin/2=Gentamicin/3=Netilmicin/|
|                           |         4=Sisomycin/5=Tobramycin|
|Samp_sz              |          Sample Size |
|Cured                  |        Number Cured |



###  ENDOCRIN

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/ENDOCRIN.csv)


| Variable          |   LABEL|
|--------------|-------------------------- |
|  Subject          |        SUBJECT #|
|  Replicat       |          REPLICATE #|
|  Estrone          |      ESTRONE|
|  Estradol       |      ESTRADIOL|
|  Androste       |      ANDROSTENEDIONE|
|  Testost          |    TESTOSTERONE|


### Estradl

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/Estradl.csv)


|Variable|			Code	|
|--------|-----------------------------------------------------|
|Id					  | Identification number|
|Estradl	|				Estradiol|
|Ethnic		|			Ethnicity 0=African-American;  1=Caucasian|
|Entage		|			Age|
|Numchild|				Parity, number of children  9=missing|
|Agefbo		|			Age at 1st birth (=0 if numchild=0)  99=missing|
|Anykids	|			any children  1=yes;  0=no   9=missing|
|Agemenar|				age at menarche   99=missing|
|BMI					|Body Mass Index|
|WHR					|waist-hip ratio|


### ESTROGEN

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/ESTROGEN.csv)


|Variable |                   LABEL|
|---------|------------------------------------------|
|Id             |                 ID|
|std_typ    |                       STUDY TYPE|
|                 |                    1=0.625MG VS PLACEBO|
|                 |                    2=1.25MG VS PLACEBO|
|                 |                    3=1.25MG VS 0.625MG|
|period     |                       PERIOD|
|trtgrp     |                       TREATMENT|
|                 |                    1=PLACEBO|
|                 |                    2=0.625MG|
|                 |                    3=1.25MG|
|sysd1r1    |                  SYSTOLIC BP DAY 1 READING 1|
|                 |                    MISSING=999|
|diasd1r1 |                    DIASTOLIC BP DAY 1 READING 1|
|                 |                    MISSING=999|
|sysd1r2    |                  SYSTOLIC BP DAY 1 READING 2|
|                 |                    MISSING=999|
|diasd1r2 |                    DIASTOLIC BP DAY 1 READING 2|
|                 |                    MISSING=999|
|sysd1r3    |                  SYSTOLIC BP  DAY 1 READING 3|
|                 |                    MISSING=999|
|diasd1r3 |                    DIASTOLIC BP DAY 1 READING 3|
|                 |                    MISSING=999|
|sysd2r1    |                  SYSTOLIC BP DAY 2 READING 1|
|                 |                    MISSING=999|
|diasd2r1 |                    DIASTOLIC BP DAY 2 READING 1|
|sysd2r2    |                  SYSTOLIC BP DAY 2 READING 2|
|diasd2r2 |                    DIASTOLIC BP DAY 2 READING 2|
|sysd2r3    |                  SYSTOLIC BP DAY 2 READING 3|
|diasd2r3 |                    DIASTOLIC BP DAY 2 READING 3|
|sysd3r1    |                  SYSTOLIC BP DAY 3 READING 1|
|diasd3r1 |                    DIASTOLIC BP DAY 3 READING 1|
|sysd3r2    |                  SYSTOLIC BP DAY 3 READING 2|
|diasd3r2 |                    DIASTOLIC BP DAY 3 READING 2|
|sysd3r3    |                  SYSTOLIC BP DAY 3 READING 3|
|diasd3r3 |                    DIASTOLIC BP DAY 3 READING 3|


### FEV

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/FEV.csv)

|Variable |     Description     |      Format or Code
|---------|---------------------|----------------------------
| Id      |    ID number        |
| Age     |    Age (yrs)        |
| FEV     |    FEV (liters)     |      X.XXXX
| Hgt     |    Height (inches)  |      XX.X
| Sex     |    Sex              |      0=female/1=male
| Smoke   |    Smoking Status   |      0=non-current smoker/1=current smoker



### Field
[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/Field.csv)

|Variable   |	Description
|-----------|--------------
|id          |  ID
|group        |              group (1=RHO/2=RPGR)
|age           |        age at visit  (XX.X in years)
|gender       |            gender (1=m/2=f)  Note: all RPGR individuals have to be male 
|dtvisit      |	  date of visit (month/day/year)
|folowup      |	  time from 1st visit in years
|totfldod     |	  total field area right eye (OD) in degrees²
|totfldos     |	  total field area left eye (OS) in degrees²

### Heart
[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/Heart.csv)
|Variable	|code
|---------|--------
|Diagnosis	|		Y1=normal
				Y2=atrial septal defect without pulmonary stenosis or pulmonary hypertension
				Y3=ventricular septal defect with valvular pulmonary stenosis
				Y4=isolated pulmonary hypertension
				Y5=transposed great vessels
				Y6=ventricular septal defect without pulmonary hypertension
				Y7=ventricular septal defect with pulmonary hypertension
|Prevalence |		Prevalence
|X1		| 		age 1-20 years old
|X2		|		age>20 years old
|X3		|		mild cyanosis
|X4		|		easy fatigue
|X5		|		chest pain
|X6		|		repeated respiratory infections
|X7		|		EKG axis more than 110


### HORMONE
[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/HORMONE.csv)

|Variable       |      Description/Code
|---------------|------------------------------------------------------------
|ID             |       ID
|Bilsecpr       |      Biliary secretion-pre      
|Bilphpr        |      Biliary pH-pre             
|Pansecpr       |       Pancreatic secretion-pre   
|Panphpr        |      Pancreatic pH-pre          
|Dose           |      Dose 
|Bilsecpt       |      Biliary secretion-post     
|Bilphpt        |      Biliary pH-post            
|Pansecpt       | Pancreatic secretion-post  
|Panphpt        |       Pancreatic pH-post 
|Hormone        |        Hormone 1=SAL/2=APP/3=CCK/4=SEC/5=VIP


### Hosiptal

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/Hospital.csv)


|Variable   |            Label
|------------| ---------------
|   Id           |  id no.
|   Dur_stay     |           Duration of hospital stay
|   Age         |           Age
|   Sex         |            Sex  1=male/2=female
|   Temp        |          First temperature following admission
|   WBC         |          First WBC(x1000) following admission
|   Antibio      |            Received antibiotic 1=yes/2=no
|   Bact_cul     |            Received bacterial culture 1=yes/2=no
|   Service      |            Service 1=med/2=surg.



### INFANTBP

[Download](https://raw.githubusercontent.com/KUBDatalab/R-PUFF-1-deskriptiv/main/data/INFANTBP.csv)

Salt Taste Variables

|Variable   |              Format |   Description|
|----------|-----------------------|---------------------------------------|
| ID              |                | |
| Mn_sbp      |                xx.xx|   Mean SBP 99.99=missing|
| Mn_dbp      |               xx.xx |  Mean DBP 99.99=missing|
| MSB1slt   |                xxx.xx |  MSB-trial 1* water|
| MSB2slt   |                xxx.xx |  MSB-trial 2 water|
| MSB3slt   |                xxx.xx |  MSB-trial 3 0.1 molar salt + water|
| MSB4slt   |                xxx.xx |  MSB-trial 4 0.1 molar salt + water|
| MSB5slt   |                xxx.xx |  MSB-trial 5 water|
| MSB6slt   |                xxx.xx |  MSB-trial 6 water|
| MSB7slt   |                xxx.xx |  MSB-trial 7 0.3 molar salt + water|
| MSB8slt   |                xxx.xx |  MSB-trial 8 0.3 molar salt + water|
| MSB9slt   |                xxx.xx |  MSB-trial 9 water|
| MSB10slt  |                xxx.xx |  MSB-trial 10 water|

Sugar Taste Variables

|Variable     |            Format |   Description|
|-----------|--------------|-----------------------------------------------|
| MSB1sug     |              xxx.xx|   MSB-trial 1 non-nutritive sucking|
| MSB2sug     |             xxx.xx  | MSB-trial 2 water|
| MSB3sug     |            xxx.xx |  MSB-trial 3 5% sucrose + water|
| MSB4sug     |            xxx.xx |  MSB-trial 4 15% sucrose + water|
| MSB5sug     |            xxx.xx |  MSB-trial 5 non-nutritive sucking|


* for MSB data 999.99 is a missing value; 0 indicates the baby did not suck.


### LEAD

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


### MICE

|Variable   column      Description 
| Id         1-2         ID
| Group       4          GROUP 1=RP  2=NORMAL
| Trtgrp      6          TREATMENT GROUP
                         A=LIGHT
                         B=DIM
                         C=DARK
| Age        8-9         AGE (days)
| B_amp     13-14        B AMP  9999=missing
| A_amp     16-19        A AMP  9999=missing  


### NEPHRO

Variable         Column      Description/Code
---------------------------------------------------------------------------
name               1-8       Study name
id                10-11      Study number
Endpnt             13        Endpoint  2=nephrotoxicity
Antibio            15        Antibiotic 1=Amikacin/2=Gentamicin/3=Netilmicin/
                                   4=Sisomycin/5=Tobramycin
Samp_sz           17-19      Sample size 
Side_eff          21-23      Number with side effects 
---------------------------------------------------------------------------


### NIFED

Variable    Column       Description            Code
-----------------------------------------------------------------------------
Id           1-2         ID
trtgrp        4          Treatment group        N=nifedipine/P=placebo
bashrtrt     6-8         Baseline heart rate*   beats/min
lv1hrtrt    10-12        Level 1 heart rate+    beats/min
lv2hrtrt    14-16        Level 2 heart rate     beats/min
lv3hrtrt    18-20        Level 3 heart rate     beats/min
bassys      22-24        Baseline systolic bp*  mm Hg
lv1sys      26-28        Level 1 systolic bp    mm Hg
lv2sys      30-32        Level 2 systolic bp    mm Hg
lv3sys      34-36        Level 3 systolic bp    mm Hg
-----------------------------------------------------------------------------
* Immediately prior to randomization.
+ Highest heart rate and systolic blood pressure at baseline and each level of
  therapy respectively.
Values of 999 indicates that either
(a) the patient withdrew from the study prior to entering this level of therapy
(b) the patient achieved pain relief prior to reaching this level or therapy,
(c) the patient encountered this level of therapy, but this particular piece
       of data was missing.

### OTO

Variable         Column       Description/Code
---------------------------------------------------------------------------
Name               1-8        Study Name
Id                10-11       Study Number 
Endpnt             13         Endpoint 1=efficacy/2=nephrotoxicity/3=ototoxicity
Antibio            15         Antibiotic 1=Amikacin/2=Gentamicin/3=Netilmicin/
                                   4=Sisomycin/5=Tobramycin
Samp_sz           17-19       Sample Size
Side_eff          21-23       Number with side effect 
---------------------------------------------------------------------------

### PIRIFORM

Variable                      Column                                    Code

ID                                1-6
piriform                        8                                             Piriformis Syndrome  1=Negative,  2=Positive
sex                              10                                            Sex  1=Male,  2=Female
age                             12-14                                       Age
maxchg                       16-21                                      Max change between tibia and peroneal


### SEXRAT

Variable          Column
--------------------------------------
nm_chld+            1         Number of children
sx_1                3         Sex of 1st born
sx_2                5         Sex of 2nd born
sx_3                7         Sex of 3rd born
sx_4                9         sex of 4th born
sx_5                11        sex of 5th born 
sexchldn*           13-17     Sex of all children  
num_fam**           19-22     Number of families
--------------------------------------
+ For families with 5+ children, the sex of the first 5 children are listed.
The number of children is given as 5 for such families.
* The sex of successive births is given. Thus, MMMF means that the first
three children were males and the fourth child was a female. There were 484
such families.
** Number of families with specific gender contribution of children


### SMOKE

Variable      Columns         Code
-----------------------------------------------------
ID              1-3           ID number 
Age             4-5           age 
Gender           6            Gender        1=male/2=female
Cig_day         7-8           Cigarettes/day      
CO              9-11          Carbon monoxide (CO) (X 10) missing=999	   
Min_last       12-15          Minutes elapsed since last cigarette missing=9999  
LogCOadj       16-19          Log CO Adj * (X 1000)  missing=9999
Day_abs        20-22          Days abstinent  Those abstinent less than 1 day
                                    were given a value of zero.
--------------------------------------------------------------------
* This variable represents adjusted carbon monoxide (CO) values. CO values
were adjusted for minutes elapsed since last cigarette smoked using the formula
Log 10 CO (Adjusted) = Log 10 CO - (-0.000638) X (Min - 80), where Min is the
number of minutes elapsed since the last cigarette smoked.  


### SWISS

Variable      Column       Codes
-----------------------------------------------------------
 ID             1-4         ID             

 age (yrs)      6-7         age (yrs)      

 group           9          Group    1=High NAPAP, 2=Low NAPAP, 3 = control

 creat_68      12-15   x.xx Serum Creatinine 1968 (mg/dL) 9.99=missing 

 creat_69      18-21   x.xx Serum Creatinine 1969 (mg/dL) 9.99=missing 

 creat_70      24-27   x.xx Serum Creatinine 1970 (mg/dL) 9.99=missing 

 creat_71      30-33   x.xx Serum Creatinine 1971 (mg/dL) 9.99=missing 

 creat_72      36-39   x.xx Serum Creatinine 1972 (mg/dL) 9.99=missing 

 creat_75      42-45   x.xx Serum Creatinine 1975 (mg/dL) 9.99=missing 

 creat_78      48-51   x.xx Serum Creatinine 1978 (mg/dL) 9.99=missing
---------------------------------------------------------------


### TEAR

Variable                      Column                                    Code

ID                                1-2
od3bas1                       3-9                                           OD 3sec baseline 1               
od3bas2                       10-16                                       OD 3 sec baseline 2     
od3im1                        17-23                                       OD 3 sec immediately post 1
od3im2                        24-30                                       OD 3 sec immediately post 2         
od3pst51		31-37				OD 3 sec 5min post 1
od3pst52		38-44				OD 3 sec 5min post 2
od3pt101		45-51				OD 3 sec 10min post 1
od3pt102		52-58				OD 3 sec 10min post 2
od3pt151		59-65				OD 3 sec 15min post 1
od3pt152		66-72				OD 3 sec 15min post 2 
os3bas1                        73-79                                      OS 3sec baseline 1               
os3bas2                        80-86                                      OS 3 sec baseline 2     
os3im1                         87-93                                      OS 3 sec immediately post 1
os3im2                         94-100                                    OS 3 sec immediately post 2         
os3pst51		101-107	 		OS 3 sec 5min post 1
os3pst52		108-114			OS 3 sec 5min post 2
os3pt101		115-121			OS 3 sec 10min post 1
os3pt102		122-128			OS 3 sec 10min post 2
os3pt151		129-135			OS 3 sec 15min post 1
os3pt152		136-142			OS 3 sec 15min post 2
od6bas1                       143-149                                  OD 6 sec baseline 1               
od6bas2                       150-156                                  OD 6 sec baseline 2     
od6im1                        157-163                                  OD 6 sec immediately post 1
od6im2                        164-170                                  OD 6 sec immediately post 2         
od6pst51		171-177			OD 6 sec 5min post 1
od6pst52		178-184			OD 6 sec 5min post 2
od6pt101		185-191			OD 6 sec 10min post 1
od6pt102		192-198			OD 6 sec 10min post 2
od6pt151		199-205			OD 6 sec 15min post 1
od6pt152		206-212 			OD 6 sec 15min post 2 
os6bas1                       213-219                                   OS 6 sec baseline 1               
os6bas2                       220-226                                   OS 6 sec baseline 2     
os6im1                        227-233                                   OS 6 sec immediately post 1
os6im2                        234-240                                   OS 6 sec immediately post 2         
os6pst51		241-247	 		OS 6 sec 5min post 1
os6pst52		248-254			OS 6 sec 5min post 2
os6pt101		255-261			OS 6 sec 10min post 1
os6pt102		262-268			OS 6 sec 10min post 2
os6pt151		269-275			OS 6 sec 15min post 1
os6pt152		276-282			OS 6 sec 15min post 2
od10bas1                     283-289                                  OD 10 sec baseline 1               
od10bas2                     290-296                                  OD 10 sec baseline 2     
od10im1                      297-303                                  OD 10 sec immediately post 1
od10im2                      304-310                                  OD 10 sec immediately post 2         
od10ps51		311-317			OD 10 sec 5min post 1
od10ps52		318-324			OD 10 sec 5min post 2
od10p101		325-331			OD 10 sec 10min post 1
od10p102		332-338			OD 10 sec 10min post 2
od10p151		339-345			OD 10 sec 15min post 1
od10p152		346-352 			OD 10 sec 15min post 2 
os10bas1                     353-359                                   OS 10 sec baseline 1               
os10bas2                     360-366                                   OS 10 sec baseline 2     
os10im1                      367-373                                   OS 10 sec immediately post 1
os10im2                      374-380                                   OS 10 sec immediately post 2         
os10ps51		381-387	 		OS 10 sec 5min post 1
os10ps52		388-394			OS 10 sec 5min post 2
os10p101		395-401			OS 10 sec 10min post 1
os10p102		402-408			OS 10 sec 10min post 2
os10p151		409-415			OS 10 sec 15min post 1
os10p152		416-422			OS 10 sec 15min post 2

### TEMPERAT

Variable    COLUMN       LABEL
Date         1-6         DATE (MDY)
Out_temp     8-10        OUTSIDE TEMERATURE  Degrees Fahrenheit
Room        12-13        ROOM LOCATION
In_temp     15-18        INSIDE TEMPERATURE  Degrees Fahrenheit
Cor_fac       20         CORRECTION FACTOR ADDED (1=YES 0=NO)
Typ_wea       22         TYPE OF WEATHER
                          1=SUNNY
                          2=PARTLY CLOUDY
                          3=CLOUDY
                          4=RAINY
                          5=FOGGY
                          9=MISSING

### TENNIS1

VARIABLE  Column       VARIABLE NAME
-------------------------------------------------------
Id         3-5         ID

Age        8-9         AGE    99=MISSING

Sex         12         SEX   1=MALE / 2=FEMALE

Num_epis    15         NUMBER OF EPISODES OF TENNIS ELBOW 9=MISSING	                      

Typ_last    18         TYPE OF RACQUET USED DURING LAST EPISODE
                        1=CONVENTIONAL SIZE
                        2=MID-SIZE
                        3=OVER-SIZE
                        9=MISSING

Wgt_last     21        WEIGHT OF RACQUET USED DURING LAST EPISODE
                        1=HEAVY
                        2=MEDIUM
                        3=LIGHT
                        4=DON'T KNOW
                        9=MISSING

Mat_last     24        MATERIAL OF RACQUET USED DURING LAST EPISODE
                        1=WOOD
                        2=ALUMINUM
                        3=FIBERGLASS AND COMPOSITE
                        4=GRAPHITE
                        5=STEEL
                        6=COMPOSITE
                        7=OTHER
                        9=MISSING
 
 Str_last     27       STRING TYPE OF RACQUET USED DURING LAST EPISODE
                        1=NYLON
                        2=GUT
                        3=DON'T KNOW
                        9=MISSING

Typ_curr       30      TYPE OF RACQUET USED CURRENTLY
                         1=CONVENTIONAL SIZE
                         2=MID-SIZE
                         3=OVER-SIZE
                         9=MISSING

 Wgt_curr      33      WEIGHT OF RACQUET USED CURRENTLY   
                        1=HEAVY
                        2=MEDIUM
                        3=LIGHT
                        4=DON'T KNOW
                        9=MISSING

Mat_curr       36      MATERIAL OF RACQUET USED CURRENTLY
                        1=WOOD
                        2=ALUMINUM
                        3=FIBERGLASS AND COMPOSITE
                        4=GRAPHITE
                        5=STEEL
                        6=COMPOSITE
                        7=OTHER
                        9=MISSING
 
Str_curr       39     STRING TYPE OF RACQUET USED CURRENTLY
                       1=NYLON
                       2=GUT
                       3=DON'T KNOW
                       9=MISSING

### TENNIS2

VARIABLE   Column  PERIOD*  VARIABLE NAME
----------------------------------------------------------------------------------
id         3-5                ID

age        8-9                AGE

sex         12                SEX
                               1 = MALE
                               2 = FEMALE
                               9 = MISSING

drg_ord     15                DRUG ORDER
                               1 = MOTRIN-PLACEBO
                               2 = PLACEBO-MOTRIN

painmx_2    18        2       DURING STUDY PERIOD, PAIN DURING MAXIMUM ACTIVITY VS
                                BAESLINE
                               1 = WORST
                               2 = UNCHANGED
                               3 = SLIGHTLY IMPROVED (25%)
                               4 = MODERATELY IMPROVED (50%)
                               5 = MOSTLY IMPROVED (75%)
                               6 = COMPLETELY IMPROVED
                               9 = MISSING

pain12_2    21        2       WITHIN 12 HOURS FOLLOWING MAXIMAL ACTIVITY, COMPARED TO                               
                              SAME PERIOD AT BASELINE  (SAME CODE AS painmx_2)

painav_2    24        2       DURING THE AVERAGE DAY OF STUDY PERIOD PAIN VS. BASELINE
                             (SAME CODE AS painmx_2)  

painov_2    27        2       OVERALL IMPRESSION OF DRUG EFFICACY VS. BASELINE		                        (SAME CODE AS painmx_2)

painmx_3    30        3       DURING STUDY PERIOD, PAIN DURING MAXIMUM ACTIVITY VS  
                               BASELINE   (SAME CODE AS painmx_2)

pain12_3    33        3       WITHIN 12 HOURS FOLLOWING MAXIMAL ACTIVITY, COMPARED TO                    
                              SAME PERIOD AT BASELINE   (SAME CODE AS painmx_2)

painav_3    36        3       DURING THE AVERAGE DAY OF STUDY PERIOD PAIN VS BASELINE
                              (SAME CODE AS painmx_2)

painov_3    39        3       OVERALL IMPRESSION OF DRUG EFFICACY VS BASELINE
                              (SAME CODE AS painmx_2)

painmx_4    42        4       DURING STUDY PERIOD, PAIN DURING MAXIMUM ACTIVITY VS  
                               BASELINE   (SAME CODE AS painmx_2)

pain12_4    45        4       WITHIN 12 HOURS FOLLOWING MAXIMAL ACTIVITY, COMPARED TO  
                              SAME PERIOD AT BASELINE  (SAME CODE AS painmx_2)

painav_4    48        4       DURING THE AVERAGE DAY OF STUDY PERIOD PAIN VS BASELINE
                               (SAME CODE AS painmx_2)

painov_4    51        4       OVERALL IMPRESSION OF DRUG EFFICACY VS BASELINE
                              (SAME CODE AS painmx_2)
----------------------------------------------------------------------------------
* PERIOD 2 = PAIN SCORES AFTER THE FIRST ACTIVE DRUG PERIOD COMPARED WITH BASELINE
  
  PERIOD 3 = PAIN SCORES AFTER THE WASHOUT PERIOD COMPARED WITH BASELINE

  PERIOD 4 = PAIN SCORES AFTER THE SECOND ACTIVE DRUG PERIOD COMPARED WITH BASELINE



### VALID

|Variable     |        Description             |Format or Code
|-------------|-----------------------------------|-----------
|Id           |          ID number                |
|sfat_dr       |         Saturated fat-DR        |   XXXXX.XX
|sfat_ffq     |         Saturated fat-FFQ        |  XXXXX.XX
|tfat_dr      |         Total fat-DR             |  XXXXX.XX
|tfat_ffq     |         Total fat-FFQ            |  XXXXX.XX
|alco_dr      |         Alcohol consumption-DR   |  XXXXX.XX
|alco_ffq     |         Alcohol consumption-FFQ  |  XXXXX.XX
|cal_dr       |         Total calories-DR        | XXXXXX.XX
|cal_ffq      |         Total calories-FFQ       | XXXXXX.XX



{% include links.md %}

