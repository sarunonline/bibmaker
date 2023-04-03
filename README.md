# bibmaker
bibmaker makes the bibtex database from the available user input. It is convenient to use when all the publication data are available.
# Pre-requisite
Use of bibtex database in LaTeX typesetting. Otherwise none.
# Usage
1. Type `bibmaker` in _cmd prompt_ and enter
2. Copy-paste the author names and other details from the journal as per the inputs requested
3. Press any key to Continue or press **'0'** to end the **bibmaker**
## BibTeX format
The most common BibTeX format is **@article** whose construct is given below. Other format types (@thesis, @report, @book, @website, @inbook) are not covered in present version.
```latex
@article{article_key,
    AUTHOR={Author1 and Author2 and Author3},
    TITLE={Title of the scientific article},
    JOURNAL={Journal name in which it is published},
    YEAR={Year of Publication},
    PAGE={Page numbers}
}
```
# Limitation
- The program only generate the reference style for articles (@article).
- doi cannot be added by the program. If desires, copy-paste the doi tag (` doi={}, `) after title tag (`title={} `) and the change the doi value inside the braces.

### ToDo: 
Other non common formats namely, @thesis, @report, @book, @website, are not included. 

# About
Author: Sarun Pallian Murikkoli (c) 2023
