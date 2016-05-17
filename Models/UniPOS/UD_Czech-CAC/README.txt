The UD_Czech-CAC treebank is based on the Czech Academic Corpus 2.0 (CAC;
Český akademický korpus; ČAK), created at Charles University in Prague.
CAC consists both of written data and transcripts of spoken language. Only
the written part is included in this treebank as no syntactic annotation is
available for the spoken data. Out of 650,000 total CAC tokens, 493,306 appear
in the treebank.

The first version of CAC was created by a team from the Institute of the Czech
Language, Czechoslovak Academy of Sciences, led by Marie Těšitelová, in
1971-1985; its original name was “Korpus věcného stylu”. It was reshaped and
made compatible with the Prague Dependency Treebank between 2007 (CAC 1.0) and
2008 (CAC 2.0); these corpora are distributed by the Linguistic Data
Consortium. The corpus has now been converted to Universal Dependencies and
made freely available under the CreativeCommons license (see LICENSE.txt).

See the following websites for more information on CAC 2.0:

* http://ufal.mff.cuni.cz/rest/cac.html
* http://ufal.mff.cuni.cz/rest/CAC/doc-cac20/cac-guide/eng/html/index.html
* http://hdl.handle.net/11372/LRT-1061
* https://catalog.ldc.upenn.edu/LDC2008T22
* https://lindat.mff.cuni.cz//services/pmltq/#!/treebank/cac20/help
  (online query)

CAC contains mostly unabridged articles taken from a wide range of media.
These articles include newspapers, magazines and other sources covering
administration, journalism and scientific fields. These three genres can be
distinguished by the sentence id: in

# sent_id a-s20w-s55

the "s20w" part identifies the source document, where "w" means "written",
"20" is the document id number and "s" means scientific (while "a20w" is the
twentieth document from the administrative genre, and "n20w" from newspapers).

The texts are taken from the 1970s and 1980s and thus, the selection of texts
is influenced by the political and cultural climate of this time period.

The original data in “Korpus věcného stylu” omits all punctuation symbols,
numbers (only those expressed in digits; numeral words are preserved) and some
measure units and symbols. The missing tokens were manually restored in CAC;
however, for numbers and units, only a wildcard was inserted as the exact value
and form cannot be guessed without access to the primary document.


Acknowledgments

We wish to thank all of the contributors to the original annotation effort,
as well as the team responsible for the corpus' revival in 2008.


References

* Barbora Vidová Hladká, Jan Hajič, Jiří Hana, Jaroslava Hlaváčová,
  Jiří Mírovský, Jan Votrubec: Průvodce Českým akademickým korpusem 1.0/
  The Czech Academic Corpus 1.0 Guide. Karolinum, Praha, 2007. ISBN 978-80-246-1315-4.
* Barbora Vidová Hladká, Jan Hajič, Jiří Hana, Jaroslava Hlaváčová,
  Jiří Mírovský, Jan Raab: The Czech Academic Corpus 2.0 Guide.
  In: The Prague Bulletin of Mathematical Linguistics, No. 89, 
  Copyright © Univerzita Karlova, ISSN 0032-6585, pp. 41-96, Jun 2008.
  https://ufal.mff.cuni.cz/pbml/89/pbml89.pdf
* Marie Těšitelová: K jazyku věcného stylu z hlediska kvantitativního
  (On the language of non-fiction style from the quantitative point of view).
  In: Slovo a slovesnost, vol. 44, no. 4, pp. 275-283, Praha, 1983.
  http://sas.ujc.cas.cz/archiv.php?art=2911


=== Machine-readable metadata =================================================
Documentation status: complete
Data source: semi-automatic
Data available since: UD v1.3
License: CC BY-SA 4.0
Genre: news nonfiction legal reviews medical
Contributors: Hladká, Barbora; Zeman, Daniel
===============================================================================
Original CAC authors: Hladká, Barbora; Hajič, Jan; Hana, Jiří; Hlaváčová, Jaroslava; Mírovský, Jiří; Raab, Jan
Original KVS authors: Těšitelová, Marie
