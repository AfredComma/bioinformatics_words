# Bioinformatics word explain

We can view the page on [bionformatics_words](https://afredcomma.github.io/bioinformatics_words) .

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## Raw reads preprocessing

###sequenced adapters
from biostar https://www.biostars.org/p/145032/
both PCR primers and sequence adaptors are artificial DNA oligonucleotides, generally of known sequence. The first are used to prime DNA replication reactions. Those used to amplify specific DNA sequences in vitro are called PCR primers. Sequence adaptors are any kind of short DNA sequence serving the scope of fishing a (generally unknown) DNA sequence of interest for various purposes; they are used in a variety of techniques, and sometimes can take part in a DNA replication step (e.g. in a 5'RACE). Depending on experimental protocols and following bioinformatics, both PCR primers and sequence adaptors can end up in raw sequence reads (for instance, this may occur if you are sequencing a DNA library).

###Low-complexity region
from wiki https://en.wikipedia.org/wiki/BLAST
"Low-complexity region" means a region of a sequence composed of few kinds of elements. These regions might give high scores that confuse the program to find the actual significant sequences in the database, so they should be filtered out. The regions will be marked with an X (protein sequences) or N (nucleic acid sequences) and then be ignored by the BLAST program. To filter out the low-complexity regions, the SEG program is used for protein sequences and the program DUST is used for DNA sequences. On the other hand, the program XNU is used to mask off the tandem repeats in protein sequences.

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/AfredComma/bioinformatics_words/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
