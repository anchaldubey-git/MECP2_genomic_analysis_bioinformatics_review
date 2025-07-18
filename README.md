# MECP2 GENOMIC ANALYSIS: BIOINFORMATICS
Comparative analysis of the MECP2 protein across species to explore its evolutionary conservation and clinical significance in Rett Syndrome. Includes sequence retrieval, BLASTp analysis, MSA, conservation scoring, and phylogenetic tree construction using tools like UniProt, BLAST, ClustalW, Jalview, and MEGA.
This project aims to investigate the **evolutionary conservation** of the MECP2 protein, a gene critical to **neurodevelopment** and strongly linked to **Rett Syndrome**. By performing **sequence alignment, similarity search, conservation scoring**, and **phylogenetic analysis**, we explore how MECP2 varies across species and what that reveals about its functional importance.


---

## 📊 Tools Used

- **UniProt** – Sequence retrieval
- **NCBI BLASTp** – Protein sequence comparison
- **ClustalW / Clustal Omega** – Multiple sequence alignment
- **Jalview** – Visualization and conservation scoring
- **MEGA** – Phylogenetic tree construction
- **Python (Matplotlib)** – Identity plotting 

---

## 📚 References

- Amir RE, et al. *Rett syndrome is caused by mutations in X-linked MECP2.* Nat Genet. 1999. [PMID: 10508514](https://pubmed.ncbi.nlm.nih.gov/10508514/)
- Lyst MJ, Bird A. *Rett syndrome: a complex disorder with simple roots.* Nat Rev Genet. 2015. [PMID: 28229398](https://pubmed.ncbi.nlm.nih.gov/28229398/)

---


## 📌 Overview

- **Gene Studied:** MECP2 (*Methyl-CpG-binding protein 2*)
- **Relevance:** Loss-of-function mutations in MECP2 are the primary cause of **Rett Syndrome**, a severe neurodevelopmental disorder.
- **Goal:** To compare the MECP2 protein sequence in **Homo sapiens**, **Pan paniscus**, **Gorilla gorilla**, and **Mus musculus** to analyze conservation and evolutionary relationships.

---

## 🧪 Workflow Summary

### 1. **Sequence Retrieval**
- Protein sequences of MECP2 were retrieved from **UniProt** for the four species listed above.

### 2. **BLASTp Analysis**
- Performed using **Human MECP2** as the query.
- Observed % identity:
  - Bonobo: **100%**
  - Gorilla: **100%**
  - Mouse: **95.27%**
- All sequences showed **100% query coverage** and **E-value of 0**.

### 3. **Multiple Sequence Alignment (MSA)**
- Conducted using **ClustalW**.
- Visualized in **Jalview**.
- High conservation observed, especially in functionally important domains.
- Mouse showed slight divergence, mostly in less conserved regions.

### 4. **Conservation Score Analysis**
- Jalview conservation bar and consensus sequence showed **strong residue-level conservation**, particularly in the **MBD** and **TRD** domains of MECP2.

### 5. **Phylogenetic Tree Construction**
- Tree generated in **MEGA** using the Neighbor-Joining method.
- Human, Gorilla, and Bonobo clustered closely, supporting their evolutionary proximity.
- Mouse formed a separate clade, reflecting greater divergence in MECP2.

---

## 🧠 Clinical Relevance

**MECP2** regulates gene expression by binding to methylated DNA and recruiting transcriptional repressors. It is essential for **neuronal development and synaptic function**. Mutations in MECP2 disrupt this process, leading to **Rett Syndrome** — characterized by developmental regression, motor dysfunction, and intellectual disability.  
The strong conservation of MECP2 across species underscores its **biological significance**, and comparative analysis may aid in refining animal models and guiding therapeutic strategies.

---

## 👩‍🔬 Author

**Anchal Dubey**  
MSc Biotechnology  
This project was developed as part of a bioinformatics learning module on comparative gene analysis.
---


## 📁 Project Structure
<pre> MECP2_Comparative_Analysis/ ├── data/ │ ├── mecp2_human.fasta │ ├── mecp2_panpaniscus.fasta │ ├── mecp2_gorilla.fasta │ └── mecp2_mouse.fasta │ ├── results/ │ ├── blast/ │ │ └── blastp_results.txt │ ├── msa_alignment.aln │ ├── msa_conservation.png │ └── phylogenetic_tree.png │ ├── identity_plot.py └── README.md </pre>


