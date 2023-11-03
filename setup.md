---
title: Setup
---
## Setup

> ## Hvor skal jeg installere R og RStudio?
>
> Installer på din egen computer. Installation på Onedrive og andre drev i skyen vil virke. Men du vil ikke kunne installere de
> biblioteker og udvidelser du har brug for.
>
{: .caution}


**R** og **RStudio** er to forskellige programmer. R er det 
egentlige programmeringssprog, der bruges til den statistiske
analyse og visualisering. Men R i sig selv er ikke rart at 
arbejde med. Derfor bruger vi R gennem RStudio, der er et 
mere grafisk baseret interface, kaldet et "Integrated Development
Enviroment (IDE). RStudio gør det ikke nødvendigvis let at 
bruge R. Men det gør det lettere.

R skal installeres før du installerer RStudio. Det sikrer at 
RStudio kan finde R på din computer. Når du har installeret begge
programmer, nøjes du med at køre RStudio - programmet sørger selv
for at starte R op.

Efter du har installeret begge programmer, anbefalder vi kraftigt
at det første du installerer er **`tidyverse`** pakken.
Det gøres inde fra RStudio. **`tidyverse`** pakken er en 
samling af kraftfulde data science værktøjer. Du 
kan læse meget mere på [**`tidyverse`** websitet](https://tidyverse.tidyverse.org).

Følg instruktionerne herunder for det styresystem du har på 
din computer, og installer efterfølgende **`tidyverse`**.

### Windows

#### Hvis du allerede har R og RStudio installeret

* Åben RStudio, og klik på "Help" > "Check for updates". Hvis der
er kommet en ny version, så afslut RStudio og installer den
seneste version som beskrevet herunder.
* For at tjekke hvilken version R du har installeret, start
RStudio og det første der dukker op på "konsollen" fortæller
hvilken version af R du har installeret. Alternativt kan du
køre `sessionInfo()`, der også vil vise hvilken version af R
du har. Gå til [CRAN websitet](https://cran.r-project.org/bin/windows/base/) og tjek
om der er en nyere version. Hvis der er, download og installer den.

#### Hvis du ikke har R og Rstudio installeret

* Download R fra
   [CRAN websitet](http://cran.r-project.org/bin/windows/base/release.htm).
* Kør den `.exe` fil der bliver downloaded.
* Gå til [RStudio download siden](https://www.rstudio.com/products/rstudio/download/#download).
* Under *Installers* vælg **RStudio x.yy.zzz - Windows.
  Vista/7/8/10** (hvor x, y, og z repræsenterer version numre).
* Dobbeltklik på filen for at installere den.
* Når installationen er færdig, åbner du RStudio for at sikre at alt virker og du ikke får fejlbeskeder.


### macOS

#### Hvis du allerede har R og RStudio installeret

* Åben RStudio, og klik på "Help" > "Check for updates". Hvis der
er kommet en ny version, så afslut RStudio og installer den
seneste version som beskrevet herunder.
* For at tjekke hvilken version R du har installeret, start
RStudio og det første der dukker op på "konsollen" fortæller
hvilken version af R du har installeret. Alternativt kan du
køre `sessionInfo()`, der også vil vise hvilken version af R
du har. 
* Gå til [CRAN websitet](https://cran.r-project.org/bin/macosx/) og tjek om der er en nyere version tilgængelig. Hvis der er, så  download og installler den. 


#### Hvis du ikke har R og Rstudio installeret

* Download R fra
  [CRAN websitet](http://cran.r-project.org/bin/macosx/).
* Vælg `.pkg` filen for den nyeste R version.
* Dobbeltklik på den downloaded fil for at installere R.
* Det er en god ide også at installere [XQuartz](https://www.xquartz.org/) (der bruges af visse pakker).
* Gå til [RStudio download siden](https://www.rstudio.com/products/rstudio/download/#download).
* Under *Installers* vælg **RStudio x.yy.zzz - Mac OS X 10.6+ (64-bit)**
  (hvor x, y, and z repræsenterer version numre).
* Dobbeltklik på filen for at installere RStudio.
* Når installationen er færdig, åbner du RStudio for at sikre at alt virker og du ikke får fejlbeskeder.


### For alle

Installer **tidyverse** pakken ved at køre denne kommando i 
"console" i RStudio:

install.packages("tidyverse")



{% include links.md %}
