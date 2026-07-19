# Result Interpretation Report

## Network Pharmacology Analysis of Naringenin Metabolites Against Cervical Cancer

Cervical cancer (CC) is the second most common gynecological malignancy worldwide among women. Conventional treatments, such as radiotherapy and chemotherapy, have been effective in improving patient survival. Nevertheless, long-term administration is often accompanied by serious side effects that may reduce a patient's quality of life. Naringenin is a naturally occurring dihydro-flavonoid often found in numerous fruits and medical plants. It is known for its anti-tumor properties, and has been extensively utilized in Traditional Chinese Medicine (TCM) to help treat cancer including CC. However, the molecular targets and the mechanisms responsible for its anti-cervical cancer effects remain unclear (Zhou et al. 2004). Therefore, this study aims to identify the main target of naringenin and its potential mechanism against CC.
Naringenin ((2S)-5,7-dihydroxy-2-(4-hydroxyphenyl)-2,3-dihydrochromen-4-one) was identified from PubChem, and its potential targets were predicted using SwissTargetPrediction. Cervical cancer (CC)-associated genes were collected from the OMIM and GeneCards databases. The overlapping genes between the predicted naringenin target and CC-related genes were identified as relevant potential targets. A protein-protein interaction (PPI) network was constructed using the STRING database with a high-confidence interaction score (confidence ≥ 0.700). Subsequently, the result was visualized and analyzed using Cytoscape. Furthermore, functional enrichment analysis was done by using Gene Ontology (GO) and Kyoto Encyclopedia of Genes and Genomes (KEGG) pathway analyses of the potential targets using STRING (false discovery rate: medium). Finally, the compound-target network, PPI network, and enriched KEGG pathways were integrated into a single comprehensive network using the Merge Network feature in Cytoscape.

![Overlapping Genes](/Overlapping genes.png)
Figure 1. Identification of 86 overlapping genes between 17,860 CC-related genes and 97 naringenin targets.

A total of 86 overlapping genes were identified between 17,860 CC-related genes, and 97 predicted naringenin targets, representing the potential therapeutic targets of naringenin against CC. Eventhough the overlap constituted of only 0,5% of all CC-related genes, these included several well-established oncogenes and signaling molecules, such as PIK3CA, AKT1, MTOR, VEGFA, MET, SRC, MMP9, BCL2, and TERT, which are involved in tumor proliferation, apoptosis, angiogenesis, metastasis, and inflammatory responses. These findings suggest that naringenin potentially works through a multi-target mechanism to modulate multiple cancer-related signaling pathways.


Figure 2. Protein-protein interaction (PPI) network of the overlapping genes, resulted in 86 nodes and 176 edges.

Table 1. Topological analysis of the top 10 hub genes in the PPI network based on degree, betweeness centrality, ang closeness centrality.



Topological analysis of the PPI network (Figure 2 & Table 1) identified the top 10 hub genes based on degree, betweenness centrality, and closeness centrality. Among them, SRC, AKT1, PTGS2, and MMP9 displayed a degree equal to or greater than 30, whereas BCL2, PIK3CA, CYP19A1, MMP2, and APP exhibited comparatively lower topological values but remained important network components. These findings indicate that SRC, AKT1, PTGS2, MMP9, and ESR1 play as the core regulatory nodes of the PPI network and may serve as key molecular targets of the therapeutic effects of naringenin against CC.
	


Figure 3. Compound-target-pathway network illustrating the interactions among naringenin, overlapping targets, and enriched KEGG pathways.

The compound-target pathway network was constructed to visualize the relationships among naringenin, overlapping target genes, and significantly enriched KEGG pathways (Figure 3). The network demonstrates that naringenin interacts with multiple protein targets, each of which is associated with numerous biological pathways, highlighting its multi-target therapeutic characteristics. Several signaling pathways, including pathways in cancer, EGFR tyrosine kynase inhibitor resistance, PI3K-Akt signaling, MAPK signaling, TNF signaling, NF-kB signaling, apoptosis, proteoglycans in cancer, and human papillomavirus infection, were highly connected through shared target proteins. Among these, the hub genes SRC, AKT1, PTGS2, MMP9, ESR1, and PIK3CA, emerged as key regulatory nodes connecting multiple pathways, highlighting their important roles in mediating the anti-cervical cancer effects of naringenin. These findings strengthen the first suggestion of the naringenin mechanism of action.




Figure 4. Gene Ontology (GO, biological process and molecular process) and KEGG pathway enrichment analysis of the 86  overlapping genes.

Enrichment analysis (Figure 4) explained that the 86 overlapping targets were significantly enriched in biological processes related to epithelial cell migration, cellular stress response, and hypoxia, while molecular functions were primarily associated with protein kinase activity, nuclear receptor binding, and prostaglandin-endoperoxide synthase activity. Based on the KEGG pathway analysis, the 86 genes are significantly enriched in cancer-related pathways, including EGFR tyrosine kinase inhibitor resistance, endocrine resistance, proteoglycans in cancer, focal adhesion, VEGF signaling, and pathways in cancer. Overall, these findings reinforce the suggestion that naringenin may be involved in the signaling pathways and modulate the biological process in the tumor progression. These theoretical findings provide a theoretical basis for the future development of naringenin or new drugs for cervical cancer.

**Reference:**
Zhou J, Li H, Wu B, Zhu L, Huang Q, Guo Z, He Q, Wang L, Peng X & Guo T. 2024. Network Pharmacology Combined with Experimental Verification to Explore the Potential Mechanism of Naringenin in the Treatment of Cervical Cancer. Scientific Reports, 14 (1860). doi: https://doi.org/10.1038/s41598-024-52413-9.
