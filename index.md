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
    form http://www.matrixscience.com/help/seq_db_setup_nr.html
The nr database is compiled by the NCBI (National Center for Biotechnology Information) as a protein database for Blast searches. It contains non-identical sequences from GenBank CDS translations, PDB, Swiss-Prot, PIR, and PRF. The strengths of nr are that it is comprehensive and frequently updated.
