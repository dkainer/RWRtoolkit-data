# RWRtoolkit-data
Multiplex network (Rdata) objects for use with the [kb_djornl RWRtools KBase app.](https://github.com/kbaseapps/kb_djornl/)

## Multiplex Networks

### Comprehensive Network Multiplex (Default Multiplex Network)
| **Const** | Comprehensive_Network_AT_d0.5_v02.RData |
|:----------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.2 |
| **Description** | Contains the following network layers with unweighted edges and delta value = 0.5:<br />CoEvolution-DUO (DU) version 0.1 (AT-UU-DU-67-AA-01)<br />Coexpression Gene-Atlas (GA) version 0.3 (AT-UU-GA-01-AA-01)<br />Knockout Similarity (KS) version 0.3 (AT-UU-KS-00-AA-01)<br />PPI-6merged (PP) version 0.3 (AT-UU-PP-00-AA-01)<br />PEN-Diversity (PX) version 0.1 (AT-UU-PX-01-AA-01)<br />Predictive CG Methylation (PY) version 0.1 (AT-UU-PY-01-LF-01)<br />Regulation-ATRM (RE) version 0.3 (AT-UU-RE-00-AA-01)<br />Regulation-Plantregmap (RP) version 0.3 (AT-UU-RP-03-AA-01)<br />Metabolic-AraCyc (RX) version 0.3 (AT-UU-RX-00-AA-01) |



### Close to Phenotype Multiplex
| **Const** | Close_To_Phenotype_AT_d0.5_v01.RData |
|:----------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.1 |
| **Description** | Contains the following network layers with unweighted edges and delta value = 0.5:<br />Knockout Similarity (KS) version 0.3 (AT-UU-KS-00-AA-01)<br />PPI-6merged (PP) version 0.3 (AT-UU-PP-00-AA-01)<br />Metabolic-AraCyc (RX) version 0.3 (AT-UU-RX-00-AA-01) |



### Expression/Regulation Multiplex
| **Const** | Expression_Regulation_AT_d0.5_v01.RData |
|:----------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.1 |
| **Description** | Contains the following network layers with unweighted edges and delta value = 0.5:<br />Coexpression Gene-Atlas (GA) version 0.3 (AT-UU-GA-01-AA-01)<br />PEN-Diversity (PX) version 0.1 (AT-UU-PX-01-AA-01)<br />Regulation-ATRM (RE) version 0.3 (AT-UU-RE-00-AA-01) |



### GO Multiplex
| **Const** | GO_AT_d0.5_v01.RData |
|:----------------|:------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.1 |
| **Description** | Contains the following network layers with unweighted edges and delta value = 0.5:<br />GO semantic similarity (GO) version 0.4 (AT-UU-GO-05-AA-01) |



### High Confidence Multiplex
| **Const** | High_Confidence_AT_d0.5_v01.RData |
|:----------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.1 |
| **Description** | Contains the following network layers with unweighted edges and delta value = 0.5:<br />Knockout Similarity (KS) version 0.3 (AT-UU-KS-00-AA-01)<br />PPI-6merged (PP) version 0.3 (AT-UU-PP-00-AA-01)<br />Regulation-ATRM (RE) version 0.3 (AT-UU-RE-00-AA-01)<br />Metabolic-AraCyc (RX) version 0.3 (AT-UU-RX-00-AA-01) |



### Ontology Multiplex
| **Const** | Ontology_AT_d0.5_v01.RData |
|:----------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.1 |
| **Description** | Contains the following network layers with unweighted edges and delta value = 0.5:<br />GO semantic similarity (GO) version 0.4 (AT-UU-GO-05-AA-01)<br />Knockout Similarity (KS) version 0.3 (AT-UU-KS-00-AA-01) |



### Metabolic Multiplex
| **Const** | Metabolic_AT_d0.5_v01.RData |
|:----------------|:------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.1 |
| **Description** | Contains the following network layers with unweighted edges and delta value = 0.5:<br />Metabolic-AraCyc (RX) version 0.3 (AT-UU-RX-00-AA-01) |



### Predicted Regulation Multiplex
| **Const** | Predicted_Regulation_AT_d0.5_v02.RData |
|:----------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.2 |
| **Description** | Contains the following network layers with unweighted edges and delta value = 0.5:<br />Coexpression Gene-Atlas (GA) version 0.3 (AT-UU-GA-01-AA-01)<br />PEN-Diversity (PX) version 0.1 (AT-UU-PX-01-AA-01)<br />Regulation-Plantregmap (RP) version 0.3 (AT-UU-RP-03-AA-01)<br />Predictive CG Methylation (PY) version 0.1 (AT-UU-PY-01-LF-01) |



### Unknown Function Multiplex
| **Const** | Unknown_Function_AT_d0.5_v01.RData |
|:----------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.1 |
| **Description** | Contains the following network layers with unweighted edges and delta value = 0.5:<br />CoDomain (CD) version 0.3 (AT-UU-CD-00-AA-01)<br />CoEvolution-DUO (DU) version 0.1 (AT-UU-DU-67-AA-01)<br />PPI-6merged (PP) version 0.3 (AT-UU-PP-00-AA-01)<br />Metabolic-AraCyc (RX) version 0.3 (AT-UU-RX-00-AA-01) |



## Networks
Network files are located on the [kbase exascale_data repository](https://github.com/kbase/exascale_data/tree/main/prerelease/edge_data).

### CoDomain Network
| **Const** | AT-UU-CD-00-AA-01 |
|:---------------------------|:-------------------------------------------------------------------------------------------------------------|
| **Version** | 0.3 |
| **Description** | GeneA connects to GeneB if they share one or more common protein domains. Network was obtained from AraNet2. |
| **DOI** | https://doi.org/10.1093/nar/gku1053 |
| **# Edges** | 25,000 |
| **# Nodes** | 7,634 |
| **Processing information** | During to-spec processing no changes were made. |



### CoEvolution-DUO Network
| **Const** | AT-UU-DU-67-AA-01 |
|:---------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.1 |
| **Description** | GeneA connects to GeneB if a SNP in or near GeneA is correlated with a SNP in or near GeneB using the DUO metric. SNP data is from the full 1001 Genomes. SNPs were mapped to nearest genes (left/right) so that edges are all gene to gene. |
| **DOI** | https://doi.org/10.1101/2020.01.28.923730 |
| **# Edges** | 13,514 |
| **# Nodes** | 2,283 |
| **Processing information** | Edges between genes on the same chromosome (cis) were removed and edges with a DUO score < 0.67 were filtered out.|



### Coex Gene-Atlas Network
| **Const** | AT-UU-GA-01-AA-01 |
|:---------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.3 |
| **Description** | Coexpression network obtained from AtGenie.org. It uses expression array data from multiple tissues to calculate the correlation between genes. |
| **DOI** | https://doi.org/10.1111/nph.13557 |
| **# Edges** | 84,959 |
| **# Nodes** | 7,683 |
| **Processing information** | The network was already provided. It was thresholded as the top 1% of edges. During to-spec processing no changes were made. |



#### GO Network
| **Const** | AT-UU-GO-05-AA-01 |
|:---------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.4 |
| **Description** | GeneA connects to GeneB if the two genes have semantically similar GO terms (with a similarity score > 0). This network is used to evaluate other networks for functional biology content. |
| **DOI** | https://doi.org/10.1093/bioinformatics/btq064 |
| **# Edges** | 2,930,141 |
| **# Nodes** | 7,625 |
| **Processing information** | Edges are thresholded at similarity > 0.5. During to-spec processing no changes were made. V0.3 -> v0.4: used 0.5 thresholding instead of 0.3 to limit file size. |



### Knockout Similarity Network
| **Const** | AT-UU-KS-00-AA-01 |
|:---------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.3 |
| **Description** | GeneA connects to GeneB if the phenotypic effect of knocking out GeneA is similar to the phenotypic effect of knocking out GeneB. Similarity is based on Phenotype Ontology semantic similarity. |
| **DOI** | https://doi.org/10.1186/s13007-015-0053-y |
| **# Edges** | 94,952 |
| **# Nodes** | 1,841 |
| **Processing information** | This network was already provided in the paper. Edges with similarity score < 0.2 were culled. During to-spec processing no changes were made. |



### PPI-6merged Network
| **const** | AT-UU-PP-00-AA-01 |
|:---------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.3 |
| **Description** | GeneA connects to GeneB if their protein products have been shown to bind to interact with each other, typically through experimental evidence. The PPI-6merged network is the union of 6 different A.thaliana PPI networks: AraNet2 LC, AraNet2 HT, AraPPInet2 0.60, BIOGRID 4.3.194 physical, AtPIN, Mentha. These 6 were all relatively high scoring with GOintersect. StringDB provided a low score and therefore was not included |
| **DOI** | n/a |
| **# Edges** | 317,787 |
| **# Nodes** | 19,191 |
| **Processing information** | During to-spec processing no changes were made. |



### PEN-Diversity Network
| **Const** | AT-UU-PX-01-AA-01 |
|:---------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.1 |
| **Description** | GeneA connects to GeneB if the expression vector of GeneA is an important predictor of the expression vector of GeneB in an iRF model, where all other genes’ expression are included as covariates. The iRF model is an expansion on Random Forest, a feature selection model. |
| **DOI** | https://doi.org/10.1016/j.cell.2016.06.044 |
| **# Edges** | 97,819 |
| **# Nodes** | 17,907 |
| **Processing information** | 10,258 duplicate edges were removed (these edges are directed edges with different scores from A->B than B->A, in the unweighted version where all edges have scores of 1 these are duplicate edges and only one direction is maintained in the network). The top 0.1% of all edges were retained. |



### Predictive CG Methylation-1001 Epigenomes Network
| **Const** | AT-UU-PY-01-LF-01 |
|:---------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.1 |
| **Description** | GeneA connects to GeneB if the CG methylation vector of GeneA is an important predictor of the CG methylation vector of GeneB in an iRF model, where all other genes’ CG methylation states are included as covariates. The iRF model is an expansion on Random Forest, a feature selection model. |
| **DOI** | https://doi.org/10.1016/j.cell.2016.06.044 |
| **# Edges** | 76,027 |
| **# Nodes** | 13,314 |
| **Processing information** | 4,740 duplicate edges were removed (these edges are directed edges with different scores from A->B than B->A, in the unweighted version where all edges have scores of 1 these are duplicate edges and only one direction is maintained in the network). Only standard conditions were kept and methylation vectors with NAs were removed. The top 0.1% of all edges were retained. |



### Regulation-ATRM Network
| **Const** | AT-UU-RE-00-AA-01 |
|:---------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.3 |
| **Description** | GeneA connects to GeneB if GeneA is a Transcription Factor (TF) that is shown to interact with GeneB (which may or may not be a TF). This dataset contains literature mined and manually curated TF regulatory interactions for A.thaliana. Started from 1701 TFs from PlantTFDB 2.0 and retrieved 4663 TF-associated interactions. These were manually filtered (e.g. FPs, PPI interactions removed). They then added some from other sources. Final result is 1431 confirmed TF regulatory interactions, of which 637 are TF-TF. |
| **DOI** | https://doi.org/10.1093/molbev/msv058 |
| **# Edges** | 1,359 |
| **# Nodes** | 789 |
| **Processing information** | During to-spec processing, removed 25 self-loops and 47 duplicate edges. |



### Regulation-Plantregmap Network
| **const** | AT-UU-RP-03-AA-01 |
|:---------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.3 |
| **Description** | This network contains computationally predicted TF-Target relationships based on motifs, binding sites, ChipSeq data |
| **DOI** | https://doi.org/10.1093/nar/gkz1020 |
| **# Edges** | 167,851 |
| **# Nodes** | 16,014 |
| **Processing information** | Removed all Lit curated edges and then gave one point to each line of evidence (e.g. Motif, TFBS, ChipSeq) for an edge. Then summed them up to give an edge weight. Highest scoring regulatory edges have 5. We thresholded this network at score >=3. During to-spec processing, 29 self-loops and 48 duplicate edges were removed. |



### Metabolic-AraCyc Network
| **Const** | AT-UU-RX-00-AA-01 |
|:---------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version** | 0.3 |
| **Description** | GeneA connects to GeneB if they are both enzymatic and are linked by a common substrate or product. E.g. RXNA (GeneA) → Compound1 → RXNB (GeneB). Here GeneA connects to GeneB due to Compound1. |
| **DOI** | https://doi.org/10.1104/pp.102.017236 |
| **# Edges** | 21,524 |
| **# Nodes** | 2,857 |
| **Processing information** | All enzymatic reactions and associated genes (enzymes) and compounds were downloaded from AraCyc as smart tables, and transformed by custom R script to generate the appropriate network format linking gene to gene based on intermediary compounds.During to-spec processing, 24 non-standard nodes were removed (corresponding to 322 non-standard edges), and 3,243 duplicate edges were removed. |


