# Claw coloration in the fiddler crab Leptuca uruguayensis has no correlation with male quality 
Authors: Zackary A. Graham, Jônatas de Jesus Florentino, Samuel P. Smithers, João C. T. Menezes, José Eduardo de Carvalho, Alexandre V. Palaoro <br>
Contact about code, analyses, and claw photographs: alexandre.palaoro@gmail.com; alexandre.palaoro@ufpr.br
---

### This readme has been divided in three parts. First, we will talk about file structure, then the code, the dataset.

##### File structure:

We uploaded three different folders: "code", "data", and "figures". Each folder contain the files we used to run all analyses and the output files that came from the codes (the figures).
We are not uploading the claw photographs because they are too big. Github only allows uploading files up to 25 Mb. Our photos are larger than that because they are in RAW format. However, the photos are available for anyone that wants them. Just contact me and I can share them.
We are also uploading the Supplementary Material for those who do not have access to it.

##### Code:

The folder "code" contains: 
(i) the code required to run all the analyses we performed, both from the main manuscript and supplementary files; 
(ii) an RMarkDown file which contains all code;
(iii) the html of the RMarkDown file.

Thus, you can reproduce all documents we generated for this paper.

##### Data:

The folder "data" contains the data we used in our analyses. 
It is called day 2 because it is the second day of experiments. We used the first day to test our equipment and only used the data from the second day because they were more reliable.

The dataset contains the values of each individual of <i>Leptuca uruguayensis</i> we collected. All variables are contained in the same file. These data were used to run all analyses contained in the manuscript.

METADATA OF uca_data_true_reflectance_day2

In the columns we have the variables, in rows we have the individuals. 

COLUMN A: ID - the number we gave the individual fiddler crab <br>
COLUMN B: date.photographed - the date the individual was photographed <br>
COLUMN C: claw - claw length, measured from the tip of the fixed finger to the base of the manus where it meets the capurs. Unit: cm <br>
COLUMN D: carapace - carapace width, measured as the max distance between the edges of the branchial chambers when viewed from the dorsal side. Unit: cm <br>
COLUMN E: muscle - muscle mass, measured as the differenced between dry weight and dry weight after muscle was diggested. Please, see the paper for the description of how this was done. Unit: g <br>
COLUMN F: lipid - the lipid content measured (see the supplementary file for an accurate description of how we did this). Unit: micro-grams <br>
COLUMN G: lipid.percent - the amount of lipid relative to all the tissue measured. Unit: % <br>
COLUMN H: percent.red - red reflectance retrieven from the MICA toolbox. Please, see the paper for a descriptions of how this was done. Unit: % <br>
COLUMN I: percent.green - green reflectance retrieven from the MICA toolbox. Please, see the paper for a descriptions of how this was done. Unit: % <br>
COLUMN J: percent.blue - blue reflectance retrieven from the MICA toolbox. Please, see the paper for a descriptions of how this was done. Unit: % <br>

The code was run in R software v4.3.1.
Packages used:
ggtern v3.4.2
performance v0.10.4
parameters v0.21.4
betareg v3.1-4
lmtest v0.9-40
scales v1.2.1
ggplot2 v3.4.4


## Acknowledgment

A.V.P. was funded by Fundação de Amparo à Pesquisa do Estado de São Paulo (process no: 2016/22679-3). J.J.F. was funded through an undergraduate student scholarship for scientific research provided by Conselho Nacional de Desenvolvimento Científico e Tecnológico (CNPq, process no: 144202/2018-2). We wish to thank Rhea Eskew for helpful discussions. 
