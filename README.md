# 🧬 Mutation Analysis of SARS-CoV-2 Genomes Using Clustal Omega, MEGA, and Python

## 1. Introduction
This project aims to analyze genomic mutations in multiple **SARS-CoV-2** sequences collected from different countries.  
By performing **multiple sequence alignment** and comparative analysis, we identified variations (mutations) that highlight how the virus evolves over time.

---

## 2. Tools and Methods

**Data Source:** SARS-CoV-2 genome sequences from [NCBI](https://www.ncbi.nlm.nih.gov/genbank/) / [GISAID](https://www.gisaid.org/)

**Tools Used:**
- 🧩 **Clustal Omega:** For multiple sequence alignment  
- 🔬 **MEGA:** For alignment visualization and mutation comparison  
- 🐍 **Python (pandas, matplotlib):** For mutation counting and visualization  

**Workflow:**
1. Downloaded genome sequences in **FASTA** format.  
2. Performed multiple sequence alignment using **Clustal Omega**.  
3. Imported the aligned file into **MEGA** for comparative analysis.  
4. Extracted mutation positions and processed the data in **Python**.  
5. Visualized mutation frequency and genomic distribution.  

---

## 3. Results

- **Total mutations detected:** 40,314  
- **Most frequently mutated regions:** Spike and ORF1ab genes  
- **Mutation type analysis:** Transitions (A↔G, C↔T) > Transversions  
- **Hotspot example:** Position 23,403 (Spike protein, D614G mutation)

**Visualizations:**
- 📊 Histogram of mutation counts across the genome  
- 🧠 Scatter plot showing mutation positions along the genome sequence  

---

## 4. Discussion
The large number of mutations (**40,314**) reflects the high variability of SARS-CoV-2.  
Most mutations occurred in functional regions like **Spike** and **ORF1ab**, which are known to influence infectivity and replication.  
**Transition mutations** were dominant, consistent with typical RNA virus evolution patterns.

---

## 5. Conclusion
This analysis successfully identified and visualized mutations in **SARS-CoV-2 genomes** using bioinformatics tools.  
The workflow demonstrates how simple computational steps — alignment, mutation detection, and Python-based analysis — can uncover meaningful biological insights about viral evolution.

---

## 6. References
- [Clustal Omega](https://www.ebi.ac.uk/Tools/msa/clustalo/)  
- [MEGA Software](https://www.megasoftware.net/)  
- [NCBI GenBank](https://www.ncbi.nlm.nih.gov/genbank/)  
- [GISAID](https://www.gisaid.org/)

---


