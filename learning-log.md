# 🧠 Learning Log: Galaxy Genomics Pathway

This log captures my reflections, learnings, and challenges as I go through the Galaxy training materials.

---

## 📅 Week of July 7–13, 2025

**Tutorial Completed**: A short introduction to Galaxy  
**Key Concepts Learned**:
- Navigating Galaxy’s user interface
- Importing data and viewing histories
- Running tools and examining outputs

**Tools Used**: Upload tool, cut tool, history manager  
**Challenges**:
- Initially confused between histories and datasets
- Took time to understand  various tools 
- Took time to understand data linking in workflows

**Tutorial Completed**: Galaxy Basics for Genomics  
**Key Concepts Learned**:
- Counting and Sorting SNPs
- Visual interpretation of read quality
- Workflow creation with paired-end data

**Tools Used**: BEDtools, Datamash,  Sort , FastQC
**Challenges**:
- Took time to understand exons and SNPs and its parameters
- Understanding trimming parameters
- Slow loading of history panel

**Tutorial Completed**: Mapping 
**Key Concepts Learned**:
- Mapping the reads of an experiment to a reference genome
- Align paired-end reads to the mouse reference genome using Bowtie2
- Convert and sort alignment files with Samtools
- Index BAM files for quick access in visualization or downstream tasks
- Visualize aligned reads using IGV
  
**Tools Used**: Samtools, Bowtie2,  IGV ,  JBrowse
**Challenges**:
- Took time to select the correct reference genome (mm10) in the tool interface took some extra care.
- Double-checked that my input files were properly paired and labeled.
- Loading BAM files into IGV required ensuring the .bai index file was correctly generated.

**Tutorial Completed**: Genome Assembly 
**Key Concepts Learned**:
- Principles of de novo genome assembly using short-read data (de Bruijn graph strategy via Velvet) 
- Download and import raw sequencing reads (paired-end FASTQ) and reference FASTA into Galaxy 
- Assess read quality and characteristics with FastQC and MultiQC (e.g., read length, coverage, quality scores, GC content, adapter/remove contaminants)
- Decide on the optimal k‑mer size based on read length and coverage
- Run Velvet (velveth + velvetg) to assemble reads into contigs; use interleaved paired-end input mode 
- Evaluate assembly quality: collect statistics on contigs (e.g. N50, total length, number of contigs) Galaxy Training Network

**Tools Used**: FastQC, MultiQC, Velvet (velveth + velvetg) on Galaxy platform
**Challenges**:
- Choosing appropriate k‑mer size without over-fragmenting or over-merging contigs
- Ensuring sufficient coverage and read quality metrics were acceptable before assembly
- Interpreting assembly statistics 
- Managing Galaxy history structure and dataset naming so outputs remain clear and traceable
  
---




