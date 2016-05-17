http://universaldependencies.github.io/docs/cs/overview/introduction.html

The Czech UD treebank is based on the Prague Dependency Treebank 3.0 (PDT),
created at the Charles University in Prague. The treebank consists of 87,913
sentences (1.5 M tokens) and its domain is mainly newswire, reaching also to
business and popular scientific articles from the 1990s. The treebank is
licensed under the terms of CC BY-NC-SA 3.0 and its original (non-UD) version
can be downloaded from

http://hdl.handle.net/11858/00-097C-0000-0023-1AAF-3.

The morphological and syntactic annotation of the Czech UD treebank is created
through a conversion of PDT data. The conversion procedure has been designed by
Dan Zeman.

NOTE: Earlier releases of the treebank had four training data files. This was
due to Github restrictions on file size. We have now re-joined the training
files in the official release package (beginning with UD v1.3), so there is
just one training file as in all other languages, and it is named
cs-ud-train.conllu. The four files in previous releases corresponded to the
four sources of the original texts; the sources may still be distinguished,
if desirable, by the prefixes of sentence ids. All of them are newspapers, but

* l (ln) and m (mf) are mainstream daily papers (news, commentaries, but also
  sports results and TV programs)
* c (cmpr) is a business weekly
* v (vesm) contains popular scientific articles (the hardest to parse: long
  sentences and unusual vocabulary)

The dev and test sets contain all four sources and their size is proportional
to the sizes of the respective training parts.


Acknowledgments

We wish to thank all of the contributors to the original PDT annotation effort,
including Eduard Bejček, Eva Hajičová, Jan Hajič, Pavlína Jínová,
Václava Kettnerová, Veronika Kolářová, Marie Mikulová, Jiří Mírovský,
Anna Nedoluzhko, Jarmila Panevová, Lucie Poláková, Magda Ševčíková,
Jan Štěpánek, and Šárka Zikánová.


References

* Eduard Bejček, Eva Hajičová, Jan Hajič, Pavlína Jínová, Václava Kettnerová,
  Veronika Kolářová, Marie Mikulová, Jiří Mírovský, Anna Nedoluzhko,
  Jarmila Panevová, Lucie Poláková, Magda Ševčíková, Jan Štěpánek,
  and Šárka Zikánová. 2013. Prague Dependency Treebank 3.0,
  LINDAT/CLARIN digital library at Institute of Formal and Applied Linguistics,
  Charles University in Prague,
  http://hdl.handle.net/11858/00-097C-0000-0023-1AAF-3.

* Eduard Bejček, Jarmila Panevová, Jan Popelka, Pavel Straňák, Magda Ševčíková,
  Jan Štěpánek, and Zdeněk Žabokrtský. 2012. Prague Dependency Treebank 2.5 –
  a revisited version of PDT 2.0.
  In: Proceedings of the 24th International Conference on Computational
  Linguistics (Coling 2012), Mumbai, India, pp. 231-246.
  http://www.aclweb.org/anthology/C/C12/C12-1015.pdf


Changelog

2016-05-15 v1.3
  * Fixed adverbs that were attached as nmod; correct: advmod.
  * Copulas with clausal complements are now heads.
  * Improved conversion of AuxY.
  * Relation of foreign prepositions changed to foreign.
2015-11-15 v1.2
  * Conversion procedure rewritten again (may result in minor differences in
    borderline cases)
  * Only one “root” relation per tree now enforced; some bugs around root fixed
  * The “name” relation goes now always left-to-right (in UD 1.1 it was family-
    to-given name)
  * Fixed bug with numeral-noun swapping that destroyed coordinations of
    numbers and caused the “conj” relation to go right-to-left
  * Fixed minor bugs around subordinating conjunctions
  * Changed dependency relation of reflexive pronouns attached to inherently
    reflexive verbs from compound:reflex to expl
  * Applied heuristics to distinguish at least some iobj from dobj
  * Fixed bugs around xcomp (future infinitives and subjects attached to
    controlled verbs)
2015-05-15 v1.1
  * Conversion procedure completely rewritten
  * Improved heuristics to distinguish DET and PRON
  * Improved treatment of comparative complements (conjunctions “než” and “jako”)
  * Remaining lemma extensions moved from LEMMA to MISC

=== Machine-readable metadata =================================================
Documentation status: complete
Data source: semi-automatic
Data available since: UD v1.0
License: CC BY-NC-SA 3.0
Genre: news
Contributors: Zeman, Daniel; Hajič, Jan
===============================================================================
