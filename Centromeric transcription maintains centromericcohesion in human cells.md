#Centromeric transcription maintains centromeric cohesion in human cells
##introduction:
**centromere transcription（ including transcripts and ongoing transcription) function**: promote CENP-A deposition,bind all kinds of centromere Sproteins and regulate them,promote centromeric cohesion at early mitosis and proper chromosome segregation.

*[TFIIH]:transcriptional initiation factor*
*[α-amanitin]:a small cyclic peptide*
*[RNAP II]:RNA polymerase II*
*[CDK7]:It is an essential component of the transcription factor TFIIH*
*[Cdk9]:associate with P-TEFb, the positive transcription elongation factor*
**transcription inhibitor common for centromeric transcription:**
- RNAPII initiation inhibitors: triptolide and THZ1(CDK7 inhibitor)
inhibit the TFIIH, decreased the deposition of newly synthesized CENP-A in fruit fly and starfish cells

- RNAPII elongation inhibitors: α-amanitin  and flavopiridol(Cdk9 inhibitor):
 binds RNAP II and inhibits its elongation, induced a significant increase in centromeric cohesion defects and [anaphase lagging chromosomes](https://en.wikipedia.org/wiki/Anaphase_lag) in human cells.
*[CENP-B]:centromere protein B*
*[DB]:DNA-binding domain*
*[nocodazole]: synchronize the cell division cycle.And the cell do enter mitosis but cannot form metaphase spindles because microtubules (of which the spindles are made) cannot polymerise. The absence of microtubule attachment to kinetochores activates the spindle assembly checkpoint, causing the cell to arrest in prometaphase.*
**？treatment of human cell with triptolide did not yield the similar defect with α-amanitin**
**Probability：**
1. differential efficacies of inhibitors
2. inhibitor-induced phenotypes might not be a direct consequence, as these transcriptional inhibitors might suppress transcription globally.

**Solve**: specifically inactivate centromeric transcription without altering global gene transcription
eg: using CENP-B DB, target the transcriptional suppressor Kox1 specifically to centromeres, which decreased centromeric transcription and weakened centromeric cohesion.

**Summary:**
1. found that general transcriptional inhibitors exhibited distinct, even opposing, efficacies on the suppression of centromeric transcription:
- The inhibitor suppressing ongoing centromeric transcription weakened centromeric cohesion in mitotic cells
- the one increasing ongoing centromeric transcription strengthened centromeric cohesion.
2. CENP-B targeting system

##Results and discussion:

####Transcriptional inhibitors exhibit distinct, even opposing,efficacies on the suppression of ongoing α-satellite and gene transcription
*[α-satellite RNAs ]:stored in nucleoli*
*[EU]:https://en.wikipedia.org/wiki/5-Ethynyl-2'-deoxyuridine*
**experiment：** evaluate the efficacies of inhibitor
**analysis:**
#####result1 (α-amanitin and triptolide）：
1. figure 1C, log phase cell:

|inhibitor | nascent:GADPH/RPL30  |nascent:cetromeric|prove|
|:--|:--|:--|:--|
|α- amanitin |4h | 7h|suppresse centromeric transcription|
|Triptolide | 1h 20min      |4h and 7h：α-4 $\downarrow$；α-1 and α-13/21 $\uparrow$|not an effective inhibitor|

2. figure 1D, nocodazole-arrested mitotic cell:
- α-amanitin and triptolide had similar effects on centromeric transcription in nocodazole-arrested mitotic cells.
-Besides, α-amanitin at a low concentration of 5 µg/ml worked as effectively as at a high concentration of 50 µg/ml.
- Conlusion: α-amanitin, not triptolide, is a competent inhibitor to centromeric transcription.

#####Result2(flavopiridol and THZ1)：
1. Fig 1C/(FigS1 B/Fig S2A),log phase cell:

|inhibitor | gene transcription|cetromeric transcription|prove|
|:--|:--|:--|:--|
|flavopiridol|suppress |suppress centromeric transcription|suppress centromeric transcription|
| THZ1 | decrese slightly |increase| an enhancer for centromeric transcription similar results found in nontransformed RPE-1|

2. conclusion:
RNAPII elongation inhibitors: effectively suppress centromeric transcription
RNAPII initiation inhibitors: barely suppress centromeric
which suggested centromeric transcription might not require transcription initiation factors,unlike gene transcription.

#####Result3 (triptolide)
Fig.S1C
treatment of triptolide largely suppressed on-going transcription on the centromere of the X-chromosome in Drosophila S2 cells,but in human cell, it's not an effective inhibitor
**prove：** centromeric DNA sequences might be a key factor for the efficacy of triptolide in the suppression of centromeric transcription, as they are very divergent across species.

#### Treatment of α-amanitin, not triptolide, induces severe centromeric cohesion defects in mitotic cells
this paragraph mainly talks about how above inhibitors affects centromere function in human cell,we have known:
![](https://z3.ax1x.com/2021/10/21/5rgp7V.png)
experiment: not use flavopiridol,because it triggered a rapid escape from mitosis

**Result 1：**
for nocodazole-arrested Hela cell:
Fig 2A/Fig2 B
| DMSO   | α-amanitin    |triptolide|
| :------------- | :------------- |:----|
| defects in 30% cells       | defect in 70% cell     |defect in 32% cell|
*[Rpb1]:RNA polymerase II large subunit*
*[Rpb1-pSer2]:https://www.sigmaaldrich.com/US/en/product/SIGMA/SAB4200637*
*[4H8]:antibody*
*[H5]:antibody*
**prove:** These results may suggest that ==ongoing== centromeric transcription is required for maintaining centromeric cohesion

**Result2：**
1. cell with cohesion defects exhibited reduced Sgo1, total RNAPII (Rpb1, 4H8), and actively elongating RNAP II (Rpb1-pSer2, H5) :Fig. 2, A and E
2. quantification analysis confirm above things were reduced in α amanitin–treated cells，but DMSO-treated cells,triptolidetreated cells were either barely or slightly reduced: Fig. 2, C, D, and F
3. same results for nontransformed RPE-1 cells: Fig. 2, G–I

**conclusion:**

1. The inability of triptolide to inhibit ongoing centromeric transcription and weaken centromeric cohesion may explain why no obvious mitotic progression defects were observed in triptolide-treated cells
2. α-amanitin did not significantly reduce the amounts of total centromeric RNAs but induced severe centromeric cohesion defects,suggesting that centromeric cohesion is maintained largely by actively ongoing centromeric transcription: Fig. 1 C and Fig. 2, B and G
3. Treatment of triptolide did mildly decrease the total Sgo1 levels at centromeres but did not induce more severe centromeric cohesion defects. This is likely because the pool of Sgo1 that existed at inner-centromeres was sufficient to maintain centromeric cohesion, although total Sgo1 levels at centromeres were reduced.

**Result3：**
**mechanism exploration:** address if α-amanitin–induced cohesion defects were due to reduced cohesin subunits and cohesion regulators
**found：**
- Smc1, Sororin, Sgo1, and Bub1 levels was not decreased when treated
with α-amanitin, triptolide, flavopiridol, or THZ1 : Fig. S2 B
- α-amanitin and triptolide did not obviously change CENP-A levels at centromeres : Fig. S2, C and D

###Treatment of THZ1 strengthens centromeric cohesion
examine how treatment of THZ1(the enhancer of transcription)affected centromeric cohesion

**Result 1:** Fig. 3, A and B; and Fig. S2, E and F
**found:** increase Rpb1 and Rpb1-pSer2 levels at centromeres
**prove:** may explain why centromeric transcription was enhanced in the previous experiments:Fig. 1 C

**?** ectopic Rpb1, Rpb1-pSer2, and Sgo1 were also observed on chromosome arms in ∼50% of cells, whereas they were barely detected on chromosome arms in DMSO-treated cells.
**answer:** likely caused by gain of cohesion(because THZ1 promote cohesion). The phenotype of arm close is unlikely to be caused by decreased Wapl protein levels.(also because Wapl is negative regulator）Fig. 3 A; and Fig. S2, E and F
*[MG132]:metaphase-arrested*
*[Myc-CENP-B DB]:Myc is tag,and the antibody is anti-myc,so it doesn't bind endogenous CENP-B DB*
*[DB]:DNA binding domain*
*[arm close]:means cohesion in chromosome arm*
*[cohesion fatigue]:it's caused by lack of prophase pathway or separase which can't remove the sgo1.*
**Result2**:
**found:**
- Treatment of MG132 induced centromeric cohesion defects (cohesion fatigue) in ∼36% of DMSO-treated HeLa Tet-On cells,but the defects were significantly alleviated in THZ1-treated cells (∼11%):Fig. 3 C
- we found the distance between the the sistercentromere was shorter in THZ1-treated cells than in DMSO-treated cells: Fig. 3 D)

**prove:** increased centromeric transcription strengthens centromeric cohesion

**?**  triptolide did not strengthen centromeric cohesion, although it also induced a mild increase in transcription of some, but not all, of the tested centromeres.
**Answer:** the extent of triptolide-increased centromeric transcription was lower than that triggered by THZ1, triptolide treatment may not be sufficient to systematically promote cohesion: Fig. 1 C
:cat:
####Expression of CENP-B DB increases centromeric transcription and strengthens centromeric cohesion
**？** inhibitors provoked the issue of whether the observed phenomena are a direct consequence of centromeric transcription
**Solve：** novel approach to specifically manipulate centromeric transcription without affecting the rest of the genome.
**experiment 1：**
![](https://z3.ax1x.com/2021/10/22/5yHJDf.png)
1. construct and validate Myc-CENP-B DB is expressed in Doxycycline-inducible HeLa Tet-On stable cell：Fig. 3 E
2. confirm that Myc–CENP-B DB was specifically targeted to centromeres:Fig. 3 F /Fig. S2 H

**3.** examine if expression of Myc–CENP-B DB alters centromeric transcription by measuring the amounts of total centromeric RNAs

**found：** enhanced transcription at centromeres without significantly affecting gene transcription：Fig. 3 G
*[H3K4me2]:me2 means di-methylation,is an important epigenetic mark associated with active transcription at centromeres*
*[H3K9me3]:the heterochromatin mark,repression of satellite DNA regions*

**experiment 2：** To understand the mechanism underlying Myc–CENP-B DB-enhanced centromeric transcription, so examine the H3K4me2 levels at centromeres
**found:**
- H3K4me2 levels were increased at the tested centromeres but not at the tested pericentromeres and gene regions:Fig. 3 H
- expression of Myc–CENP-B DB decreased the levels of  H3K9me3 at centromeres
- expression of Myc–CENP-B DB also increased the Rpb1 and Rpb1-pSer2 levels at centromeres:Fig. 3, J and K; and Fig. S3, A and C

**conclusion:** Myc–CENP-B DB-enhanced centromeric transcription is likely attributed to the formation of more transcription-permissible chromatin
**?**  but the exact underlying mechanism still remains
unknown

**experiment 3:** because THZ1-induced transcription strengthens
centromeric cohesion, we wanted to know if Myc–CENP-B DB-enhanced centromeric transcription could do so as wel
**found:**
- ∼60% of control cells exhibited centromeric cohesion defects, expression of Myc–CENP-B DB in the two stable cell lines significantly alleviated centromeric cohesion defects (∼30%): Fig. 3 L.
- shortened the sister-centromere distance in stable Myc-CENP-B DB cell:Fig. 3, L and M

**prove:** ectopically increased centromeric transcription strengthens centromeric cohesion

**experiment4:** because expression of CENP-B DB might alter CENP-A dynamics and cause cohesion,so examined the CENP-A levels at centromeres in cells expressing CENP-B DB
**found:** no significant change: Fig. S2 I
**prove:** CENP-B DB-associated phenotypes might not be due to a significant change in CENP-A dynamics

**?** while has demonstrated that increased centromeric transcription by THZ1 and CENP-B DB enhances centromeric cohesion, the exact underlying mechanisms are unknown,It is also possible that these observed phenotypes might not be a direct consequence of altered centromeric transcription, as THZ1 treatment and CENP-B DB expression could directly affect cohesin dynamics in interphase.

####CENP-B DB-induced chromosome arm close depends on transcription
Expression of Myc–CENP-B DB also induced chromosome arm close, so to determine if it is because transcription
**experiment 1:** 4 h treated with inhibitor before harvest because it can
suppress gene transcription(means chromosome arm cohesion) but not centromeric transcription which allowed us to specifically assess the dependency of chromosome arm cohesion on transcription
**found:**
- the Rpb1 levels on both centromeres and chromosome arms were
significantly increased in the myc-CENP-B stable cells compared with control
cell：Fig. S3, A and D
**explain：** because Myc-CENP-B can promote transcription
- Treatment of α-amanitin or triptolide for 4 h either moderately or barely decreased Rpb1 levels at centromere:Fig. S3, A and C, but significantly reduced Rpb1 levels on chromosome arms:Fig. S3,A and D
**explain:** because 4h these two inhibitors only can inhibit transcription at gene transcription (centromere arm)
- treatment of α-amanitin or triptolide completely eliminated CENP-B DB-induced chromosome arm close: Fig. S3, A and B
**prove:** transcription on chromosome arms induced by CENP-B DB promotes chromosome arm cohesion

**PS:** we also found that THZ1-induced chromosome arm close also depends on transcription(证明方法和Myc-CENP-B DB一样)：Fig. S3, E and F
*[Bub1 kinase]:promote the localization of Sgo1,the detail can see review_sgo1*
*[comparable to]:相当于*
*[dominant-negative]:指当一个突变基因导入细胞后，不仅其表达的蛋白没有活性，而且该无活性蛋白还能抑制细胞内正常有活性的蛋白发挥功能*
**experiment 2:**  other possibilities that cause chromosome arm close
1. impair the localization of Bub1 kinase to kinetochores(causing Sgo1 not localized), which in turn leads to chromosome arm close and ectopic accumulation of Sgo1 on chromosome arms.
**found**: examined the Bub1 levels at kinetochores in Myc–CENP-B DB stable cells: Fig. S2, J and K, found that they were barely altered
 **conclusion:** excluding the possibility of Bub1 involvement

2. ectopic recruitment of Sgo1 onto chromosome arms by the retained RNAPII, as Sgo1 physically interacts with RNAPII
####CENP-B knockdown increases centromeric transcription and strengthens centromeric cohesion
CENP-B DB-induced centromeric transcription suggests that CENP-B might function as a suppressor for centromeric transcription.
**explain:** CENP-B DB bind DNA,but it doesn't function, CENP can't bind it to function as suppressor,so promote centromeric transcription.
**experiment:** examined centromeric RNAPII levels in CENP-B knockdown cells.
**result:**
- demonstrated the protein levels of CENP-B were significantly decreased by CENP-B siRNAs:Fig. 4 A and Fig. S3 G
**exp:** it means the knock down worked.
- CENP-B knockdown significantly increased Rpb1 and Rpb1-pSer2 levels at centromeres: Fig. 4, B and C; and Fig. S3, G and H
- The amounts of the tested centromeric transcripts were also increased:Fig. 4 D
- CENP-B knockdown significantly suppressed the centromeric cohesion defects caused by MG132 and also decreased the sister-centromere distance in cells exhibiting normal centromeric cohesion:Fig. 4, E and F
**exp:** CENP-B knockdown could suppress centromeric defects.

**conclusion:** centromeric transcription promotes centromeric cohesion
#### Targeting of the transcriptional suppressor Kox-1 with CENP-B DB to centromeres decreases centromeric transcription and impairs centromeric cohesion
tested if specific targeting of suppressor to centromeres with Myc–CENP-B DB could suppress centromeric transcription
**inhibitor selection:** Kox1,has been extensively used in CRISPR interference to suppress gene transcription
**experiment1:**
- the construction of fusion protein:
Myc–CENP-B DB-KRAB that contains Myc–CENP-B DB and the KRAB domain
(1–90) of Kox1: Fig. 5, A and B
- demonstrated that both Myc–CENP-B DB and Myc–CENP-B DB-KRAB were localized well to centromeres using immunostaining： Fig. 5 C

**result:** tested if this approach could specifically suppress transcription at centromeres:
- expression of Myc–CENP-B DB significantly increased the expression of tested α-satellite RNAs, whereas  expression of Myc–CENP-B DB-KRAB decreased them to levels ==comparable to those of control cells(vectors,because it's treated with MG132, it has cohesion fatigure)==: Fig. 5 D

**conclusion:** targeting the KRAB to centromeres using CENP-B DB is an
effective way to specifically suppress centromeric transcription

**?** the fusion protein CENP-B DB-KRAB did not decrease centromeric transcription to levels lower than the ones in control cells.
**answer:**
- insufficient expression of the fusion protein.
- this fusion protein might act in a dominant-negative manner.

**experiment2:**
 tested if this could weaken centromeric cohesion
**result:** expression of Myc–CENP-B DB largely suppressed the centromeric cohesion defects induced by MG132 in control cells, whereas expression of Myc–CENP-B DB-KRAB doesn't: Fig. 5, E and F
