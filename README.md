# NASA-Research
RNA Seq steps + DGEA + GSEA + ORA


# Abstract

## Transcriptomic Adaptation of Arabidopsis thaliana to Spaceflight Under Light Conditions
### Introduction & Context

Spaceflight exposes plants to microgravity, radiation, and altered light cues, reshaping molecular and physiological processes essential for growth and stress adaptation. Understanding responses is critical for sustainable life-support in extraterrestrial habitats.  Arabidopsis thaliana shows broad transcriptional reprogramming in microgravity, often via ABA-mediated stress pathways. The combined influence of spaceflight and light on gene expression remains underexplored. This study investigates transcriptomic responses under light using NASA OSD-678.

### Methods

RNA-seq data from 36 samples across three genotypes (Col-0, Ws, phyD mutant) under spaceflight and ground control conditions were analyzed using Python pipelines. After filtering low-expression and low-variance genes, 14,157 genes were retained. PCA revealed clear separation between spaceflight and ground controls. Differential expression via DESeq2 identified significant genes (padj < 0.05, |log₂FC| ≥ 2). ORA of these DEGs was performed in ShinyGO using all gene sets, including GO terms and KEGG pathways. GSEA was conducted on the full ranked gene list to assess pathway-level trends.

### Results

We identified 133 significant DEGs. Downregulated genes (RD20, KIN1, LTI30, LEA4-5) were enriched for ABA and abiotic stress responses, suggesting suppressed dehydration and oxidative stress signaling. Upregulated genes (bHLH38, AT2G14247, AIR1,) were associated with iron homeostasis, redox regulation, and nutrient transport. ORA highlighted “GODA ABA HORMONE UP” and “HEINRICH HIGH-LIGHT SALT-TREATMENT UP.” GSEA revealed enrichment in photosynthesis (photosystem I & II, thylakoid membranes), phenylpropanoid biosynthesis, secondary metabolite production, and detoxification, supporting metabolic remodeling and stress adaptation under light-exposed spaceflight.

### Significance

Under light-exposed spaceflight, Arabidopsis attenuates ABA-mediated stress signaling while enhancing redox, nutrient, photosynthetic, and secondary metabolite pathways. ORA and GSEA indicate transcriptional changes affect stress responses, energy metabolism, and cell wall or photomorphogenic processes, reflecting an adaptive mechanism that recalibrates stress perception, resource allocation, and photosynthetic efficiency to maintain homeostasis under microgravity and altered light.

###Keywords: Arabidopsis thaliana, microgravity, photomorphogenesis, transcriptomics, differential gene expression









[nasaposter.pdf](https://github.com/user-attachments/files/31727339/nasaposter.pdf)


