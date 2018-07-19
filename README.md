# BibTeX Style Files for Ecology Journals

I created these .bst files using the [custom-bib] package for LaTeX. Where
I could find my copy of the .dbj file I have included it as well. If you need
to, you can make modifications to the .dbj file and re-run them to create
modified .bst files.

I haven't tested these .bst files extensively, but they were adequate for my
needs writing manuscripts for these journals. They have mostly been tested with
journal articles, technical reports, and books.

All author-year style `.bst` files will require the natbib package to be loaded in the TeX preamble. For example:

```tex
\usepackage{natbib}
\bibpunct{(}{)}{;}{a}{}{;}
```

Current journals included:
- BioScience `bioscience.bst`
- Canadian Journal of Fisheries and Aquatic Sciences `cjfas.bst`
- Frontiers in Ecology and the Environment `frontecolenv.bst`
- ICES Journal of Marine Science `icesjms.bst`
- Journal of Crustacean Biology `jcrustbiol.bst`
- Methods in Ecology and Evolution `mee.bst`
- Proceedings of the Royal Society B: Biological Sciences `prsb.bst`
- Trends in Ecology and Evolution `tree.bst`
- Fish and Fisheries `fishfish.bst`
- Fisheries Research `fishres.bst` (by [@catarinawor](https://github.com/catarinawor))

These files are licensed under the [The LaTeX Project Public License].

[custom-bib]: http://www.ctan.org/tex-archive/macros/latex/contrib/custom-bib/
[The LaTeX Project Public License]: http://mirrors.rit.edu/CTAN/macros/latex/base/lppl.txt
