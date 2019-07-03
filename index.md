# Bioinformatics word explain

We can view the page on [bionformatics_words](https://afredcomma.github.io/bioinformatics_words) .


## Raw reads preprocessing

### sequenced adapters
    from biostar https://www.biostars.org/p/145032/
both PCR primers and sequence adaptors are artificial DNA oligonucleotides, generally of known sequence. The first are used to prime DNA replication reactions. Those used to amplify specific DNA sequences in vitro are called PCR primers. Sequence adaptors are any kind of short DNA sequence serving the scope of fishing a (generally unknown) DNA sequence of interest for various purposes; they are used in a variety of techniques, and sometimes can take part in a DNA replication step (e.g. in a 5'RACE). Depending on experimental protocols and following bioinformatics, both PCR primers and sequence adaptors can end up in raw sequence reads (for instance, this may occur if you are sequencing a DNA library).

### Low-complexity region    
    from wiki https://en.wikipedia.org/wiki/BLAST
"Low-complexity region" means a region of a sequence composed of few kinds of elements. These regions might give high scores that confuse the program to find the actual significant sequences in the database, so they should be filtered out. The regions will be marked with an X (protein sequences) or N (nucleic acid sequences) and then be ignored by the BLAST program. To filter out the low-complexity regions, the SEG program is used for protein sequences and the program DUST is used for DNA sequences. On the other hand, the program XNU is used to mask off the tandem repeats in protein sequences.

## Database

### greengene
    from https://aem.asm.org/content/72/7/5069
A 16S rRNA gene database (http://greengenes.lbl.gov) addresses limitations of public repositories by providing chimera screening, standard alignment, and taxonomic classification using multiple published taxonomies.
