
# Differential Gene Expression Analysis, Interpretation, and Functional Characterization


@Slack: @Sanzida 


# Link
Github rep for stage 2:

R code: https://github.com/sanzidaanee/hackbio-biocoding-internship/blob/main/Stage2/Code/transcriptomics.Rmd

Video post:


# Introduction

Differential expression analysis is a fundamental technique used to identify changes in gene expression between different biological conditions like healthy or diseased situations. By analyzing the RNA-seq data can identify the up and down-regulated genes that respond to specific conditions or treatments and can be used as a potential biomarker for early detection of cancer [1].


# Dataset
This is a processed RNAseq dataset with quantitated gene expression data from an RNA-seq experiment, that contains an experiment between a diseased cell line and diseased cell lines treated with compounds. 

## Link:

# Results and Visualization

## Differentially Expressed Genes (DEGs)

DEGs were identified using a t-statistical test, setting a significance level of 1%. The log2 fold change (FC) was calculated with cutoff 1 and >1 for upregulation and < -1 for downregulation.
From this analysis, 1 upregulated genes and 4 downregulated genes were extracted from a raw extracted dataset.

A volcano plot was created to visualize these results, showing how highly differentially genes were expressed based on fold changes and p values. So, the volcano plot would show genes up-regulated on the right side, while those down-regulated in the cancer state appear on the left side.

![000018](https://github.com/user-attachments/assets/04a502cc-4b71-4841-9fe6-30b474d34c6f)


Figure 1: Volcano plot of low-grade gliomas (LGG) dataset visualizes gene expression data. X-axis shows log2-fold change and Y-axis shows adjusted p-value. Red points indicate upregulated and blue dots indicate downregulated genes.

# Gene Function

The selected upregulated and downregulated genes based on the cut-off values of log fold change and p-value, are annotated from the GeneCards database to identify their functions [2].

# Gene Function

The selected upregulated and downregulated genes based on the cut-off values of log fold change and p-value, are annotated from the GeneCards database to identify their functions.

## Upregulated gene

## EMILIN2

EMILIN2 (Elastin Microfibril Interfacer 2) is a Protein Coding gene. Diseases associated with EMILIN2 include Lichen Nitidus and Epidermolytic Acanthoma. Among its related pathways are Elastic fiber formation and Extracellular matrix organization. 

Gene Ontology (GO) annotations related to this gene include extracellular matrix constituent conferring elasticity. An important paralog of this gene is EMILIN1.

### Molecular function for EMILIN2 Gene 


This gene is responsible for anchoring smooth muscle cells to elastic fibers and may be involved not only in the formation of the elastic fiber but also in the processes that regulate vessel assembly and have cell adhesive capacity [3].

## Downregulated gene

## TBX5 Gene 


TBX5 (T-Box Transcription Factor 5) is a Protein Coding gene. Diseases associated with TBX5 include Holt-Oram Syndrome and Atrial Septal Defect 1. Among its related pathways are Gene expression (Transcription) and Cardiac conduction [2].

Gene Ontology (GO) annotations related to this gene include DNA-binding transcription factor activity and transcription factor binding. An important paralog of this gene is TBX4 [2].


### Molecular function for TBX5 Gene 

-  DNA-binding protein that regulates the transcription of several genes and is involved in heart development and limb pattern formation [4].
-  Binds to the core DNA motif of NPPA promoter [5]

### Molecular function for TBX5 Gene according to GENATLAS

#### Biochemistry:

- murine T-box gene Tbx5 (T, brachyury) homolog, putative transcription factor, likely expressed in developing limb bud and heart in mice [6]. 

- It is also involved in developmental regulation, pairing with TBX3, a homolog to Drosophila optomotor-blind gene (omb), involved in the optic lobe and wing development [6].

## IFITM1 gene

IFITM1 (Interferon Induced Transmembrane Protein 1) is a Protein Coding gene. Diseases associated with IFITM1 include Influenza and West Nile Virus [7]. Among its related pathways are Cytokine Signaling in Immune system and Antiviral mechanism by IFN-stimulated genes [8]. 


Gene Ontology (GO) annotations related to this gene include obsolete signal transducer activity, downstream of the receptor. An important paralog of this gene is IFITM3 [2].


### Molecular function for IFITM1 Gene 

- IFN-induced antiviral protein inhibits the entry of viruses to the host cell cytoplasm, permitting endocytosis, but preventing subsequent viral fusion and release of viral contents into the cytosol.
- Active against multiple viruses, including influenza A virus, SARS coronaviruses (SARS-CoV and SARS-CoV-2), Marburg virus (MARV), Ebola virus (EBOV), Dengue virus (DNV), West Nile virus (WNV), human immunodeficiency virus type 1 (HIV-1) and hepatitis C virus (HCV) [9].
- Can inhibit: influenza virus hemagglutinin protein-mediated viral entry, MARV and EBOV GP1,2-mediated viral entry, and SARS-CoV and SARS-CoV-2 S protein-mediated viral entry.
- Also implicated in cell adhesion and control of cell growth and migration [10].
- Inhibits SARS-CoV-2 S protein-mediated syncytia formation [11].
- Plays a key role in the antiproliferative action of IFN-gamma either by inhibiting the ERK activation or by arresting cell growth in G1 phase in a p53-dependent manner [2].
- Acts as a positive regulator of osteoblast differentiation [2.
- In hepatocytes, IFITM proteins act in a coordinated manner to restrict HCV infection by targeting the endocytosed HCV virion for lysosomal degradation [9].
- IFITM2 and IFITM3 display anti-HCV activity that may complement the anti-HCV activity of IFITM1 by inhibiting the late stages of HCV entry, possibly in a coordinated manner by trapping the virion in the endosomal pathway and targeting it for degradation at the lysosome  [9].


## LAMA2 Gene

LAMA2 (Laminin Subunit Alpha 2) is a Protein Coding gene. Diseases associated with LAMA2 include Muscular Dystrophy, Congenital Merosin-Deficient, 1A and Muscular Dystrophy, Limb-Girdle, Autosomal Recessive 23 [7]. Among its related pathways are Integrin Pathway and ERK Signaling [8].

Gene Ontology (GO) annotations related to this gene include signaling receptor binding and structural molecule activity. An important paralog of this gene is LAMA1.


### Molecular function for LAMA2 Gene 

- Binding to cells via a high-affinity receptor, laminin is thought to mediate the attachment, migration, and organization of cells into tissues during embryonic development by interacting with other extracellular matrix components [3].

### Molecular function for LAMA2 Gene according to GENATLAS

#### Biochemistry:

laminin, alpha 2 polypeptide, component of cutaneous basement membrane zone binding to alpha dystroglycan,and coreceptor of mycobacterium leprae with alpha dystroglycan, heterotrimerizing (laminin 12) with laminin beta 1 and gamma 3 LAMA2 [6].


## CAV2 Gene

CAV2 (Caveolin 2) is a Protein Coding gene. Diseases associated with CAV2 include Heart Lymphoma and Developmental And Epileptic Encephalopathy 69 [7].  Among its related pathways are ESR-mediated signaling and the Development EGFR signaling pathway [8].

Gene Ontology (GO) annotations related to this gene include protein homodimerization activity and D1 dopamine receptor binding. An important paralog of this gene is CAV1.


### Molecular function for CAV2 Gene 

- May act as a scaffolding protein within caveolar membranes interact directly with G-protein alpha subunits and can functionally regulate their activity [3].
- Acts as an accessory protein in conjunction with CAV1 in targeting lipid rafts and driving caveolae formation [3]. 
- The Ser-36 phosphorylated form has a role in modulating mitosis in endothelial cells.
- Positive regulator of cellular mitogenesis of the MAPK signaling pathway [3]. 
- Required for the insulin-stimulated nuclear translocation and activation of MAPK1 and STAT3, and the subsequent regulation of cell cycle progression (By similarity) [12]. 

### Molecular function for CAV2 Gene according to GENATLAS

#### Biochemistry:

- Caveolin is a major component of the inner surface of caveolae,small invaginations of the plasma membrane,expressed in brain endothelial and astroglial cells, forming a stable hetero-oligomeric complex with CAV1,involved in essential cellular functions,including signal transduction,lipid metabolism,cellular growth control and apoptosis CAV2 [6]. 

# References

1. Wang, Z., Gerstein, M., & Snyder, M. (2009). RNA-Seq: a revolutionary tool for transcriptomics. Nature reviews genetics, 10(1), 57-63.
2. https://www.genecards.org/
3. ttps://www.uniprot.org/uniprotkb/Q9BXX0/entry#function
4. Zhang, X. L., Qiu, X. B., Yuan, F., Wang, J., Zhao, C. M., Li, R. G., ... & Yang, Y. Q. (2015). TBX5 loss-of-function mutation contributes to familial dilated cardiomyopathy. Biochemical and Biophysical Research Communications, 459(1), 166-171.
5. Pradhan, L., Gopal, S., Li, S., Ashur, S., Suryanarayanan, S., Kasahara, H., & Nam, H. J. (2016). Intermolecular interactions of cardiac transcription factors NKX2. 5 and TBX5. Biochemistry, 55(12), 1702-1710.
6. http://genatlas.medecine.univ-paris5.fr/fiche.php?n=2676
7. https://www.malacards.org/card/
8. https://pathcards.genecards.org/card/antiviral_mechanism_by_ifn-stimulated_genes
9. Narayana, S. K., Helbig, K. J., McCartney, E. M., Eyre, N. S., Bull, R. A., Eltahla, A., ... & Beard, M. R. (2015). The interferon-induced transmembrane proteins, IFITM1, IFITM2, and IFITM3 inhibit hepatitis C virus entry. Journal of Biological Chemistry, 290(43), 25946-25959.
10. Shi, G., Kenney, A. D., Kudryashova, E., Zani, A., Zhang, L., Lai, K. K., ... & Yount, J. S. (2021). Opposing activities of IFITM proteins in SARS‐CoV‐2 infection. The EMBO journal, 40(3), e106501.
11. Buchrieser, J., Dufloo, J., Hubert, M., Monel, B., Planas, D., Rajah, M. M., ... & Schwartz, O. (2020). Syncytia formation by SARS‐CoV‐2‐infected cells. The EMBO journal, 39(23), e106267.
12. https://www.uniprot.org/uniprotkb/P51636/entry#function




















