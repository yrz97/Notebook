###Results
####SET binds both Sgo1 and Sgo2
experiment ideas
*[ip]:immunoprecipitation*
*[IS]:immunostaining*
*[dispensable]:可有可无的*
*[NEB]:nuclear envelope breakdown*
1.find SET isoforms that can bind Sgo1 $\rightarrow$ SET α and β $\rightarrow$because these two isoforms has similiar  inhibition and localization,so has similar function, and they focused on SETα.
2.confirm Sgo1-SET binding:
- nocodazole-arrested :
using exogenous Myc-Sgo1 to ip endogenous SETα/β,PP2A usuccessfully:Fig 1A
  MG132-arrested: no difference:Fig.S1A
- further validate:using GFP-SET to ip Myc-Sgo1 in interphase and mitosis successfully
 ==!!== but unlucky,failed to detect the endogenous Sgo1–SET binding:suggesting that this binding might be weak or dynamic at early mitosis.
- in addition: using α-Sgo2 to ip SET successfully

####The SET-binding and cohesin-binding domains in Sgo1 are in
close proximity, but separable
1.try to find the region responsible for SET binding $\rightarrow$ using different length of GST-tagged Sgo1 N-terminal fragments to pull down His6-tagged
SET $\rightarrow$ the region 280–310 is the major domain required for SET
binding:Fig 1B
2.==??== find the region they determined is different from other studies(residue 1-40), it might be the application of different assays.
3.find the SET binding domain is close to cohesion binding domain$\rightarrow$ determine if the truncation of SET domain affect the Sgo1-cohesion binding,and vice versa:
- using GST-Sgo1(include these two regions) to pull down His6-SET or cohesin:find can bind both
- using GSTSgo1 ΔSET to pull down His6-SET or cohesin: find it can bind cohesion,not SET
- using GSTSgo1 Δcohesion to pull down His6-SET or cohesin : find it can bind SET,not cohesion
- further supported: using Myc-Sgo1 WT/ΔSET, ΔN, and ΔSET ΔN can ip Smc1 and PP2A at comparable level **in cell**
**conclusion:** these two domains can be separable from each other despite their proximity
4.evaluate the extent ==2== contribute to Sgo1-SET binding:
- using GFP-SET to only can ip Myc-Sgo1,not Myc-Sgo1 ΔSET and ΔSET ΔN:Fig 1E
- using Myc-Sgo1 ΔN and Myc-Sgo1 can ip GFP-SET successfully and extent similiar: Fig.1F
**conclusion:** 280–310 region in Sgo1 is the major binding
site for SET, and the 1–40 region of Sgo1 is dispensable for SET binding in cells.
####Sgo1 ΔSET mutants localize at centromeres and fully support
centromeric cohesion:
1.examine the cellular localization of Sgo1 ΔSET mutant:
- guess it's in the centromere: because sgo1 moving to kinetchore need C-terminal binding to pH2A, then need cohesion binding domain to bind cohesion in inner centromere, and ΔSET still have these two domain.
- to test this,
in RPE1 cell:
using IS, endogenous Sgo1 localized to centromere, after using siSgo1 treatment and expressing Sgo1 WT and ΔSET,we can see it still localized to centromere. Besides, they also WB mock /WT and ΔSET, they are expressed at similar levels, but from IS, the las two has stronger signal than endogenous:Fig iJ and H
in Hela cell: similar effectL Fig S1D
conclusion:the SET-binding domain in Sgo1 is dispensable for its centromeric localization during mitosis
2.guess SET-binding domain function: after si-Sgo1 treatment,the expression of exogenous Sgo1 and Sgo1-ΔSET has the similar effect,so this domain is not not important for its function of cohesion protection,because it stil resuced cohesion effect as WT: Fig 1I(ps:in the remaining ∼20% cells in which centromeric cohesion was not restored, the centromeric Sgo1 signals
were barely detectable,that is the transfection effect is not good)
###Identification of the domains in SET responsible for
Sgo1 binding
1.find the region in SET to bind Sgo1: previous studies demonstrated N-terminal(1-200) is the binding Sgo1 region in SET,and region 38–91 in SET-α,25–78 in SET-β adopts a helix structure to mediate SET dimerization $\rightarrow$ region(35-78) might also be involved in Sgo1 binding　$\rightarrow$　mutated many of the residues in this region that are not　involved in SET dimerization and tested their binding
2.using GST-Sgo1 (containing SET-binding domain) to pull down translated S35-radiolabeled SET WT or mutant proteins:Fig 2A
| E40K | E46K     |E50K|D56K|E60K|E64K|K68E|K72E
| :------------- | :------------- |:------------- |:------------- |:------------- |:------------- |:------------- |:------------- |
| mild       | mild       |mild       |completely|completely|completely|mild       |mild       |
because SET 3K(D56K, E60K,and E64K)completely lost its binding function$\rightarrow$focus on 3K
3.addition: some studies said SET can bind histone, test if this binding region can bind histone $\rightarrow$ none of these mutations affect binding: Fig S2B
4.construct 3K mutant,test its binding with Sgo1:
in virtro assay:
-  using GST-SET,not GST-SET 3K, pull down S35-radiolabeled Sgo1 successfully:Fig 2B
- similar result between SET and S35-radiolabeled Sgo2:Fig.2C
 in cell assay: using GFP-SET WT,not GFP-SET 3K to ip Myc-Sgo1 successfully:Fig 2D
**conclusion:** SET is a Shugoshin-binding protein, and it binds to Sgo1 through a region near its N-terminus(residues 38–72)
5.SET has been found to interact with PP2A, nucleosomes and form homodimers with itself,so test if 3K mutant influence binding with these.
- using GFP-SET 3K ip PP2A-Aα comparable to WT,but GFP-SET ΔC can't ip PP2A-Aα:Fig 2E.Besides,GFP-SET 3K can ip histone H3 comparable to WT: Fig 2F.
- using Myc-SET WT/3K to ip GFP-SET, which bound with GFP-SET
at a comparable level: Fig.2G
**conclusion:** the SET 3K mutant only exhibits binding defects to Sgo1 among all the tested binding partners,which is a separation-of-function mutant.
6.in addition, we further tested if SET ΔC is also a separation-of-function
mutant: this mutant not only lost its binding to PP2A: Fig. 2 E,but also exhibited reduced binding to Sgo1: Fig.S2 C.
### SET can disrupt the Sgo1–cohesin interaction in vitro and in cells
1. We speculated that SET and cohesin could compete with one another for binding Sgo1, because the SET and cohesin-binding domains in Sgo1 are in close proximity; Besides, because Cdk1 phosphorylation of Sgo1 at Thr346 significantly enhances the Sgo1–cohesin binding,inclusion of phospho-Sgo1 in this experiment would enable us to evaluate in more detail how SET competes with cohesin for Sgo1 binding
- in virtro:
using GST-Sgo1(phospho-Sgo1 or nonphospho-Sgo1) to pull down His6-SET or SA2/Scc:Fig 3A $\rightarrow$SET disrupted the Sgo1–cohesin binding in a dose-dependent manner regardless of the phosphorylation state of Sgo1 at T346

**?:** failed to observe a significant difference in resisting SET competition between mock teated and Cdk1-treated Sgo1

**answer:** Because we could not quantitatively measure how much Sgo1 was phosphorylated by Cdk1 in this in vitro experiment, the above result might be due to an outcome of low efficiency in Cdk1 phosphorylation.
- in cell:
1. using Sgo1 to ip coheison with or without GFP-SET$\rightarrow$ GFP-SET overexpression moderately reduced the Sgo1–
cohesin binding by more than twofold:Fig 3B and C.
2. to further confirm if the disruption of the Sgo1–cohesin interaction is mediated by SET binding to Sgo1$\rightarrow$ using Myc-Sgo1 to ip Smc1 with overexpressing GFP-SET WT and 3K$\rightarrow$Myc-Sgo1 bound more GFP-SET but less Smc1 in cells expressing GFPSET WT than vector control,expression of GFP-SET 3K barely affected the Myc-Sgo1-Smc1 binding but decreased its binding with Myc-Sgo1:Fig. 3, D and E
3. expressing GFP-SET at distinct levels and found that SET disrupted
the Sgo1–cohesin interaction in a dose-dependent manner(ps:this experiment can correspond to in virtro experiment):Fig 3F
4. as Cdk1-phosphorylated Sgo1 at Thr346 is essential for the Sgo1–cohesin interaction $\rightarrow$ examined Sgo1 phospho-Thr346 levels in cells overexpressing SET $\rightarrow$ found that Sgo1 phospho-Thr346 levels were comparable in mock cells and cells expressing GFP-SET WT or 3K: Fig. 3, D and G\rightarrow$ suggesting that the difference in the Sgo1–cohesin binding observed above is unlikely due to changes in phospho-Thr346 levels．
５．Besides,no significant difference was detected in Sgo1–PP2A interactions in GFP-SET WT and 3K cells:Fig 3D

**conclusion:**:SET binding to Sgo1 can, at least moderately, inhibit the Sgo1–cohesin interaction
### Chromosome segregation is delayed in cells expressing Sgo1 ΔSET or depleted of SET
1.It has been shown that delayed cohesion resolution can postpone chromosome segregation$\rightarrow$ as SET binding to Sgo1 might inhibit the Sgo1–cohesin interaction, so monitored chromosome segregation in Mock,si-separase and si-SET-$\rightarrow$ these three spent duration of 17 min from NEB to metaphase, but as for the duration from metaphase to chromosome segeration, they experience 14min,30 min and 23.1 min respectively:Fig. 4, A and B; and Fig. S3 A
**conclusion**: SET functions to promote timely chromosome segregation during mitosis
2.to further explore the importance of the SET-Sgo1 binding in
chromosome segregation, we examined mitotic progression in Sgo1 ΔSET cells $\rightarrow$ cells stably expressing Sgo1 WT or ΔSET were transfected with plasmids after Sgo1 si-RNAs$\rightarrow$ Mock cells progressed from
NEB to metaphase with an average duration of 16.3 min, and Sgo1 depletion arrested the cells in prometaphase with an average duration of 200 min:Fig. 4, C and D; and Fig. S3 B$\rightarrow$ Expression of Sgo1 WT or ΔSET significantly
rescued the prometaphase arrest caused by Sgo1 depletion in ∼80% of cells: Fig 1I$\rightarrow$ The cells expressing with Sgo1 WT or ΔSET progressed
from NEB to metaphase exhibited no significant difference compared with Mock cells: Fig S3 B,but the cell expressing Sgo1 ΔSET were delayed in chromosome segregation compared with the cells expressing Sgo1 WT: Fig 4C and D.
**??**:In the remaining 20% of cells, no obvious rescue was observed.
answer: As low or no expression of Sgo1 WT or ΔSET was observed in ∼20% cells
**conclusion:** SET and the SET-Sgo1 binding may promote chromosome segregation via disrupting the Sgo1–cohesin interaction.

**however**:, we cannot completely rule out the possibility that the delayed chromosome segregation might be caused by other mitotic defects induced by SET depletion or expression of Sgo1 ΔSET, such as subtle kinetochore-microtubule attachment defects
3.further attempted to confirm the importance of the SETS-go1 binding in chromosome segregation using the Sgo1-binding mutant SET 3K




































































1.Figure 1A
-vector is no Myc-Sgo1,so it can't show any proteins.
-6.5% input is without beads,so it can show every proteins.
above is as control.
2.Figure 1B
interphase in the most left means vector
aH3-pS10 is histone modification in mitosis:https://www.bioscience.co.uk/product~940143
