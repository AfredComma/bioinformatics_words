# Bioinformatics word explain

We can view the page on [bionformatics_words](https://afredcomma.github.io/bioinformatics_words) .

## Sample Type

### cfDNA
    from https://en.wikipedia.org/wiki/Circulating_free_DNA

Circulating free DNA (cfDNA) are degraded DNA fragments released to the blood plasma. cfDNA can be used to describe various forms of DNA freely circulating the bloodstream, including circulating tumor DNA (ctDNA) and cell-free fetal DNA (cffDNA). Elevated levels of cfDNA are observed in cancer, especially in advanced disease.[1] There is evidence that cfDNA becomes increasingly frequent in circulation with the onset of age.[2] cfDNA has been shown to be a useful biomarker for a multitude of ailments other than cancer and fetal medicine. This includes but is not limited to trauma, sepsis, aseptic inflammation, myocardial infarction, stroke, transplantation, diabetes, and sickle cell disease.[3] cfDNA is mostly a double-stranded extracellular molecule of DNA, consisting of small fragments (70 to 200 bp) and larger fragments (21 kb).[4] and has been recognized as an accurate marker for the diagnosis of prostate cancer and breast cancer.[5]


## Sample transport


### one
    from https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6345613/
Sample stability is an especially important consideration for the sequencing of RNA, which is labile and vulnerable to degradation by host and environmental RNase enzymes, but stability is also a factor for DNA as well. To minimize the possibility of nucleic acid degradation, the use of chemical DNA or RNA stabilizers at the time of sample collection may be considered. Formalin-fixed paraffin-embedded (FFPE) samples are also associated with nucleic acid degradation when they are allowed to stay unfixed for prolonged periods, and degradation is also enhanced by age and formalin-associated chemical modifications of RNA (48). When frozen, DNA and RNA remain relatively intact; however, multiple freeze–thaw steps during sample aliquoting and processing may result in nucleic acid degradation that is partly due to the release of endogenous nucleases (49).

## Sequencing quality control

### method one
    from https://galaxyproject.github.io/training-material/topics/sequence-analysis/tutorials/quality-control/tutorial.html
To estimate sequence quality along all sequences, we now use FastQC. It is an open-source tool that provides a simple way to quality control raw sequence data. It provides a modular set of analyses which you can use to give a quick impression of whether your data has any problems of which you should be aware before doing any further analysis.

## Raw reads preprocessing

### sequenced adapters
    from biostar https://www.biostars.org/p/145032/
both PCR primers and sequence adaptors are artificial DNA oligonucleotides, generally of known sequence. The first are used to prime DNA replication reactions. Those used to amplify specific DNA sequences in vitro are called PCR primers. Sequence adaptors are any kind of short DNA sequence serving the scope of fishing a (generally unknown) DNA sequence of interest for various purposes; they are used in a variety of techniques, and sometimes can take part in a DNA replication step (e.g. in a 5'RACE). Depending on experimental protocols and following bioinformatics, both PCR primers and sequence adaptors can end up in raw sequence reads (for instance, this may occur if you are sequencing a DNA library).

### Low-complexity region    
    from wiki https://en.wikipedia.org/wiki/BLAST
"Low-complexity region" means a region of a sequence composed of few kinds of elements. These regions might give high scores that confuse the program to find the actual significant sequences in the database, so they should be filtered out. The regions will be marked with an X (protein sequences) or N (nucleic acid sequences) and then be ignored by the BLAST program. To filter out the low-complexity regions, the SEG program is used for protein sequences and the program DUST is used for DNA sequences. On the other hand, the program XNU is used to mask off the tandem repeats in protein sequences.

    from https://www.nature.com/articles/s41598-017-18695-y
Regions within sequences that are composed of a lower diversity of residues (nucleotides or amino acids) compared to other areas can be defined as low complexity regions (LCRs).

### Contig
    from http://staden.sourceforge.net/contig.html
In order to make it easier to talk about our data gained by the shotgun method of sequencing we have invented the word "contig". A contig is a set of gel readings that are related to one another by overlap of their sequences. All gel readings belong to one and only one contig, and each contig contains at least one gel reading. The gel readings in a contig can be summed to form a contiguous consensus sequence and the length of this sequence is the length of the contig.


## Match
    from wiki https://en.wikipedia.org/wiki/K-mer
In bioinformatics, k-mers are subsequences of length {\displaystyle k} k contained within a biological sequence. Primarily used within the context of computational genomics and sequence analysis, in which k-mers are composed of nucleotides (i.e. A, T, G, and C), k-mers are capitalized upon to assemble DNA sequences,[1] improve heterologous gene expression,[2][3] identify species in metagenomic samples,[4] and create attenuated vaccines.[5] 


## Database

### greengene
    from https://aem.asm.org/content/72/7/5069
A 16S rRNA gene database (http://greengenes.lbl.gov) addresses limitations of public repositories by providing chimera screening, standard alignment, and taxonomic classification using multiple published taxonomies.

### UNITE 
    from https://academic.oup.com/nar/article/47/D1/D259/5146189
UNITE (https://unite.ut.ee/) is a web-based database and sequence management environment for the molecular identification of fungi.

### NT database
    from https://www.ncbi.nlm.nih.gov/nucleotide?cmd=search
The Nucleotide database is a collection of sequences from several sources, including GenBank, RefSeq, TPA and PDB. Genome, gene and transcript sequence data provide the foundation for biomedical research and discovery.

    from https://ccb.jhu.edu/software/centrifuge/manual.shtml
NCBI BLAST's nt database contains all spliced non-redundant coding sequences from multiplpe databases, inferred from genommic sequences. Traditionally used with BLAST, a download of the FASTA is provided on the NCBI homepage. 


### NR database
    from http://www.matrixscience.com/help/seq_db_setup_nr.html
The nr database is compiled by the NCBI (National Center for Biotechnology Information) as a protein database for Blast searches. It contains non-identical sequences from GenBank CDS translations, PDB, Swiss-Prot, PIR, and PRF. The strengths of nr are that it is comprehensive and frequently updated.

## Bioinformatical tools(Match)
### bowtie2
    from http://bowtie-bio.sourceforge.net/bowtie2/index.shtml

Bowtie 2 is an ultrafast and memory-efficient tool for aligning sequencing reads to long reference sequences. It is particularly good at aligning reads of about 50 up to 100s or 1,000s of characters, and particularly good at aligning to relatively long (e.g. mammalian) genomes. Bowtie 2 indexes the genome with an FM Index to keep its memory footprint small: for the human genome, its memory footprint is typically around 3.2 GB. Bowtie 2 supports gapped, local, and paired-end alignment modes.

### BWA
    from http://bio-bwa.sourceforge.net/
BWA is a software package for mapping low-divergent sequences against a large reference genome, such as the human genome. It consists of three algorithms: BWA-backtrack, BWA-SW and BWA-MEM. The first algorithm is designed for Illumina sequence reads up to 100bp, while the rest two for longer sequences ranged from 70bp to 1Mbp. BWA-MEM and BWA-SW share similar features such as long-read support and split alignment, but BWA-MEM, which is the latest, is generally recommended for high-quality queries as it is faster and more accurate. BWA-MEM also has better performance than BWA-backtrack for 70-100bp Illumina reads.

### SNAP
    from http://snap.cs.berkeley.edu
SNAP is a new sequence aligner that is 3-20x faster and just as accurate as existing tools like BWA-mem, Bowtie2 and Novoalign. It runs on commodity x86 processors, and supports a rich error model that lets it cheaply match reads with more differences from the reference than other tools. This gives SNAP up to 2x lower error rates than existing tools (in some cases) and lets it match larger mutations that they may miss. SNAP also natively reads BAM, FASTQ, or gzipped FASTQ, and natively writes SAM or BAM, with built-in sorting, duplicate marking, and BAM indexing.

### Kraken
    from https://ccb.jhu.edu/software/kraken/
Kraken is a system for assigning taxonomic labels to short DNA sequences, usually obtained through metagenomic studies. Previous attempts by other bioinformatics software to accomplish this task have often used sequence alignment or machine learning techniques that were quite slow, leading to the development of less sensitive but much faster abundance estimation programs. Kraken aims to achieve high sensitivity and high speed by utilizing exact alignments of k-mers and a novel classification algorithm.

### CLARK
    from http://clark.cs.ucr.edu
We present CLARK, a method based on a supervised sequence classification using discriminative k-mers. Considering two distinct specific classification problems (see the article for details), namely (1) the taxonomic classification of metagenomic reads to known bacterial genomes, and (2) the assignment of BAC clones and transcript to chromosome arms/centromeres (in the absence of a finished assembly for the reference genome), CLARK outperforms in classification speed and precision the best state-of-the-art methods. 

### MetaOthello
    from https://www.ncbi.nlm.nih.gov/pubmed/29036588
We introduce MetaOthello, a probabilistic hashing classifier for metagenomic sequencing reads. The algorithm employs a novel data structure, called l-Othello, to support efficient querying of a taxon using its k-mer signatures. MetaOthello is an order-of-magnitude faster than the current state-of-the-art algorithms Kraken and Clark, and requires only one-third of the RAM. In comparison to Kaiju, a metagenomic classification tool using protein sequences instead of genomic sequences, MetaOthello is three times faster and exhibits 20-30% higher classification sensitivity. We report comparative analyses of both scalability and accuracy using a number of simulated and empirical datasets.

### MetaMaps
    from https://github.com/DiltheyLab/MetaMaps
MetaMaps is tool specifically developed for the analysis of long-read (PacBio/Oxford Nanopore) metagenomic datasets.
It simultaenously carries out read assignment and sample composition estimation.
It is faster than classical exact alignment-based approaches, and its output is more information-rich than that of kmer-spectra-based methods. For example, each MetaMaps alignment comes with an approximate alignment location, an estimated alignment identity and a mapping quality.
The approximate mapping algorithm employed by MetaMaps is based on MashMap. MetaMaps adds a mapping quality model and EM-based estimation of sample composition.

## Bioinformatical tools(assembly)
### MEGAHIT
    from https://github.com/voutcn/megahit
MEGAHIT is an ultra-fast and memory-efficient NGS assembler. It is optimized for metagenomes, but also works well on generic single genome assembly (small or mammalian size) and single-cell assembly.
