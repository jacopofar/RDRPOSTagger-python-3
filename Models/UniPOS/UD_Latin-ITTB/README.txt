Latin data from the Index Thomisticus Treebank. It contains the complete work by Thomas Aquinas
(1225–1274; medieval Latin), and by 61 authors related to Thomas.

The UD_Latin-ITTB dataset results from conversion of the Index Thomisticus Treebank.
The data was first converted to the Prague dependency style as a part of HamleDT;
then it was automatically converted to Universal Dependencies (HamleDT 3.0, 2015). The first
release of Universal Dependencies that includes this treebank is UD v1.2 in November 2015. The
conversion of dependency relations and morphological features is almost identical to HamleDT
3.0. On the other hand, part of speech tags have been significantly improved. The original ITT
categories were based on a “tripartity” classification, which is based purely on inflectional
behavior of words, and distinguishes nominal inflection, participles, and verbal inflection.

In HamleDT 3.0, all nominally inflected words were tagged NOUN. In UD 1.2, they are further
divided according to their lemma. A lexicon was obtained from the latin lemmatizer LEMLAT, and
words not covered by the lexicon were manually disambiguated by Berta Gonzáles and Marco
Passarotti. Thus the nominally inflected words were retagged as NOUN, ADJ, PRON, DET or NUM.
Furthermore, the uninflected words, previously tagged PART, are now retagged as ADV, ADP, CONJ,
INTJ.



References:

http://itreebank.marginalia.it/ ... Index Thomisticus Treebank
http://ufal.mff.cuni.cz/hamledt ... HamleDT
http://ufal.mff.cuni.cz/treex ... Treex is the software used for conversion
http://ufal.mff.cuni.cz/interset ... Interset was used to convert POS tags and features

@article{lait,
  author    = {Passarotti, Marco and Dell’Orletta, Felice},
  title     = {Improvements in parsing the index thomisticus treebank. Revision, combination and a feature model for medieval Latin},
  journal   = {Training},
  volume    = {2},
  pages     = {61--024},
  year      = {2010}
}



Changelog

2016-05-15 v1.3
  * Fixed adverbs that were attached as nmod; correct: advmod.
  * Improved conversion of AuxY.
  * PROPN are now distinguished from NOUN.
  * Larger data: almost 2000 newly annotated sentences.
  * Manual fixes of annotation errors in the old data.
  * An exceptional one-time change of the train/dev/test data split was
    necessary to overcome past bad design and to reflect the evolution of the
    treebank. Beware: UD 1.2 dev/test data have become UD 1.3 train data and
    vice versa, the data split is thus not backwards compatible!



=== Machine-readable metadata =================================================
Documentation status: stub
Data source: automatic
Data available since: UD v1.2
License: CC BY-NC-SA 3.0
Genre: nonfiction
Contributors: Passarotti, Marco; Zeman, Daniel; Gonzáles Saavedra, Berta
===============================================================================
