```markdown
# CS159-T: A History of Parallel Processing in Bioinformatics

**David Warshawsky**  
Computer Science Department  
San Jose State University  
San Jose, CA 95192  
408-924-1000  
david.warshawsky@sjsu.edu  

## Abstract
Parallel processing is revolutionizing the field of bioinformatics by enabling large-scale collection and analysis of biological data. This paper provides a comprehensive history of parallel processing in bioinformatics, from founding methods to modern high-performance computing. It discusses the major challenges faced in the parallel processing of bioinformatics data, including data collection, preprocessing, and load balancing. Major tools that leverage parallel processing and their effects on sequence analysis are highlighted, offering an in-depth perspective on the role of parallel processing in advancing the field of bioinformatics.

## Introduction
Parallel processing plays a crucial role in bioinformatics, helping to record and analyze biological data to get sequences. The paper discusses Frederick Sanger's pioneering method for sequencing nucleotides, which is the foundation of modern genetics. The process of splitting DNA strands, adding primers, and using DNA polymerase to create complementary strands is explained. The use of fluorescently labeled dideoxynucleotides for precise sequencing is highlighted, along with the concept of next-generation sequencing for entire genomes.

## Parallel Processing in Hardware
Parallel processing is essential not only in bioinformatics software but also in hardware for collecting raw data. Automated Capillary Electrophoresis and Cycle Sequencing are examples of technologies that use parallel processing for DNA analysis. 

### Automated Capillary Electrophoresis
This technology analyzes DNA fragments using fluorescently labeled nucleotides. It involves capillaries in buffer trays, a laser light source, and a CCD (charge-coupled device) for detecting fluorescent signals. The process of pushing DNA fragments through capillaries with electrical force and recording the light signals to determine nucleotide sequences is detailed.

### Cycle Sequencing
Cycle sequencing amplifies DNA fragments for sequencing. The process uses PCR (Polymerase Chain Reaction) to bind primers to DNA regions of interest. Different fluorescent dideoxynucleotides are used to terminate DNA synthesis at specific points, creating fragments of varying lengths for analysis.

## Parallel Processing in Software
Parallel processing in bioinformatics software involves splitting sequences for analysis using multiple CPUs or cores. Python is a standard tool for this due to its simplicity and high-level abstraction. Tools like BioPython are used for analyzing nucleotide percentages and ratios.

### High-Performance Computing (HPC)
HPC is critical for assembling genomes of unsequenced organisms, a task known as De Novo Assembly. This process involves mapping algorithms to find overlapping sections in fragmented sequences and building decision trees for alignment.

### Parallelized Data Preprocessing
Tools like FASTQC are used for identifying repeated sequence data and preprocessing raw sequences. The methods of parallelization, including instruction-level and data-level parallelization, are discussed. Dynamic programming methods keep track of compared parts, saving time and improving efficiency.

## Summary/Conclusion
Bioinformatics requires large-scale data collection and analysis to sequence genomes. Proper analysis involves parallelized hardware for accurate identification and software for processing nucleotide sequences. Unique identifiers and ratios ensure accurate results and prevent contamination. HPCs with dedicated resources prevent race conditions and deadlock during computationally expensive tasks.

## References
1. Agilent Technologies. Femto Pulse 12-Capillary Array [Online image]. [Accessed: Apr. 23, 2023].
2. Galaxy Team. 2018. Galaxy: a comprehensive approach for supporting accessible, reproducible, and transparent computational research in the life sciences. Commun. ACM 61, 8 (August 2018), 48–54.
3. Gauthier, J., Vincent, A.T., Charette, S.J., & Derome, N. (2018). A brief history of bioinformatics. Briefings in Bioinformatics, 21(6), 1-9.
4. Lee, W. "BIOL CS 123B: Bioinformatics II" [website]. San Jose State University, accessed April 22, 2023.
5. Promega Corporation. 2019. What Is Capillary Electrophoresis? [Video].
6. Thermo Fisher Scientific. (n.d.). Sequencing Reaction for Sanger Sequencing. Retrieved April 22, 2023.
7. Wesley, L. CS 123A Bioinformatics I. San José State University. Fall 2022.
```
