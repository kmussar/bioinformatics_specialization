# bioinformatics_specialization
Files in association with the Genomic Data Science Specialization from Johns Hopkins. 
https://www.coursera.org/specializations/genomic-data-science

There are 8 courses in this specialization including: 
## 1. Introduction to Genomic Technologies
This course is an introduction to the basic biology of modern genomics and the experimental tools that are used to measure it. It covers the Central Dogma of Molecular Biology and how next-generation sequencing can be used to measure DNA, RNA, and epigenetic patterns. Additionally, it touches on the key concepts in computing and data science that are needed to understand how data from next-generation sequencing experiments are generated and analyzed.

## 2. Genomic Data Science with Galaxy
This course is an introduction to Galaxy and how to use it for genomic analysis. First, we learned about Galaxy's user interface, what workflows are and how to use them, and how to upload, annotate, share, and publish data. Then, we worked with example data to evalute sequence quality and perform ChIP-sequence analysis with MACS. We learned about TopHat and its use in RNA-seq analysis, mapping, assembly, and differential expression. Our final assignment was to create a Galaxy workflow to identify polymophic sites in 3 individuals, provided three sets of paired reads (raw reads from an Illumina sequencer). We provided a short write-up explaining our results as well as the number of specific types of variants as well as the genes with the largest number of polymorphic sites.    

## 3. Python for Genomic Data Science
This course focuses on the Python programming language and tools within python that will be useful for genomic data science. Specifically, it covers data structures, string methods, loops, functions, modules, packages, loading data, and the biopython package. 
#### My Notebooks: 
* 'Working_with_Galaxy_Course_Project_Supplemental_Code.ipynb' 

## 4. Algorithms for DNA Sequencing
This has been the most interesting course! Finally, I dove into into computational methods -- algorithms and data structures -- for analyzing DNA sequencing data. This course began by covering string methods to manipulate DNA sequences, how to downloading and parse genomes and how to analyze reads by position. Then we learned different methods for read alignment and global and local assembly. Specific topics covered include Naive exact matching, Boyer-Moore, hash tables for indexing, hamming and edit distance, the pigeonhole principle, the first and second laws of assembly, overlap graphs, shortest common superstring, and De Brijn graphs and Eulerian walks. 

#### My Notebooks: 
* 'parsing_sequencing_reads.ipynb'
> Find motifs within sequences - their position and the number of times they occur. Also, find motifs within the reverse complement of the sequence and the reverse complement of the motif within the original sequence. Find motoifs in a sequence allowing for a given number of mismatches. And lastly, determine if there are any positions along the read with lower quality on average than other positions. This would indicate an error with the sequencer.
* 'alignment and assembly'
> Write a function to perform local alignment, specifically to determine the edit distance between the best match of a pattern and reference genome. Also, write a function to make an overlap graph of exact matches between reads. Report the number of pairs found between reads and the number of reads with outgoing edges.

# Upcoming Courses still to complete: 
## 5. Command Line Tools for Genomic Data Science
Introduces to the commands that you need to manage and analyze directories, files, and large sets of genomic data. This is the fourth course in the Genomic Big Data Science Specialization from Johns Hopkins University.

## 6. Bioconductor for Genomic Data Science
Learn to use tools from the Bioconductor project to perform analysis of genomic data. This is the fifth course in the Genomic Big Data Specialization from Johns Hopkins University.

## 7. Bioconductor for Genomic Data Science
Learn to use tools from the Bioconductor project to perform analysis of genomic data. This is the fifth course in the Genomic Big Data Specialization from Johns Hopkins University.

## 8. Bioconductor for Genomic Data Science
Learn to use tools from the Bioconductor project to perform analysis of genomic data. This is the fifth course in the Genomic Big Data Specialization from Johns Hopkins University.
