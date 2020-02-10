# Summary

This is the edited version of a UD_Turkish-PUD treebank which was originally a part of the Parallel Universal Dependencies (PUD) treebanks created for the [CoNLL 2017 shared task on Multilingual Parsing from Raw Text to Universal Dependencies](http://universaldependencies.org/conll17/). For the original treebank, please visit [UD_Turkish-PUD github](https://github.com/UniversalDependencies/UD_Turkish-PUD/). In [TABILAB](http://http://tabilab.cmpe.boun.edu.tr/)'s project supported by the Scientific and Technological Research Council of Turkey (TÜBİTAK) under grant number 117E971, we have manually edited the syntactic relations within the original treebank.

# More

We have discussed the revisions that we made to this treebank in [our paper](https://www.aclweb.org/anthology/W19-4019.pdf) published in the proceedings of ACL LAW XIII.

Under the [guidelines](https://github.com/boun-tabi/UD_TURKISH-BPUD/tree/master/guidelines/)  directory, you can find our new proposed guidelines to the guidelines that can be found in the [UD website](https://universaldependencies.org/u/dep/all.html)

You can also find our change history and R scripts to apply the changes under the [more](https://github.com/boun-tabi/UD_TURKISH-BPUD/tree/master/more/) directory

# Citation

If you use our data or code for academic purposes, please cite:

```
@inproceedings{turk-etal-2019-turkish,
    title = "{T}urkish Treebanking: Unifying and Constructing Efforts",
    author = {T{\"u}rk, Utku  and
      Atmaca, Furkan  and
      {\"O}zate{\c{s}}, {\c{S}}aziye Bet{\"u}l  and
      K{\"o}ksal, Abdullatif  and
      Ozturk Basaran, Balkiz  and
      Gungor, Tunga  and
      {\"O}zg{\"u}r, Arzucan},
    booktitle = "Proceedings of the 13th Linguistic Annotation Workshop",
    month = aug,
    year = "2019",
    address = "Florence, Italy",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/W19-4019",
    doi = "10.18653/v1/W19-4019",
    pages = "166--177",
    abstract = {In this paper, we present the current version of two different treebanks, the re-annotation of the Turkish PUD Treebank and the first annotation of the Turkish National Corpus Universal Dependency (henceforth TNC-UD). The annotation of both treebanks, the Turkish PUD Treebank and TNC-UD, was carried out based on the decisions concerning linguistic adequacy of re-annotation of the Turkish IMST-UD Treebank (T{\"u}rk et. al., forthcoming). Both of the treebanks were annotated with the same annotation process and morphological and syntactic analyses. The TNC-UD is planned to have 10,000 sentences. In this paper, we will present the first 500 sentences along with the annotation PUD Treebank. Moreover, this paper also offers the parsing results of a graph-based neural parser on the previous and re-annotated PUD, as well as the TNC-UD. In light of the comparisons, even though we observe a slight decrease in the attachment scores of the Turkish PUD treebank, we demonstrate that the annotation of the TNC-UD improves the parsing accuracy of Turkish. In addition to the treebanks, we have also constructed a custom annotation software with advanced filtering and morphological editing options. Both the treebanks, including a full edit-history and the annotation guidelines, and the custom software are publicly available under an open license online.},
}

```
