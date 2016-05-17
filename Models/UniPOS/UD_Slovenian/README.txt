http://universaldependencies.github.io/docs/sl/overview/introduction.html

Original Treebank
The Slovenian UD Treebank is based on the ssj500k treebank (Krek et al. 2013),
a balanced collection of sampled texts from the FidaPLUS reference corpus of
written Slovene (Arhar and Gorjanc 2007). The original ssj500k corpus has been 
manually segmented, tokenized, lemmatized and morphosyntactically tagged within
JOS project, in which the annotation guidelines have also been developed (Erjavec et
al. 2010). Additionally, approximately one half of the ssj500k treebank
has been manually annotated for dependency relations, according to the JOS syntactic
annotation scheme. The syntactically annotated part of the ssj500k corpus 
(known as ssj200k), consisting of 11,411 annotated sentences and 235,864 tokens,
has been used as the basis for conversion to the Slovenian UD Treebank.

Conversion and Size
The conversion from ssj200k to the Slovenian UD Treebank was completely automatic, 
based on a large set of rules for both morphosyntactic and syntactic layer,
which include different lexical, morphological and dependency features. Due to the
specifics of the original JOS syntactic annotation scheme, not all dependency relations
from the original ssj200k treebank could be converted automatically, resulting in a
smaller UD treebank size. The current version of the Slovenian UD Treebank thus contains
7,996 sentences with 140,418 tokens taken from various text types, e.g. fiction,
non-fiction and periodicals, dating from 1990-2000. The original JOS annotations are
included as part of the POSTAG (JOS morphosyntactic tags) and MISC (JOS dependency
heads and labels) columns in the CONLLU format.


Data Split
The corpus is linearly split into training (80%), development (10%) and test
(10%) data.

Changelog
2016-05-15 v1.3
-- Added PronType to possessive pronouns
-- Added PronType to some determiners
-- Fixed a few minor issues in the conversion script based on content validation
-- Fixed a few errors in the original ssj500k treebank 
-- Fixed the SpaceAfter=No bug

References:
Simon Krek, Tomaž Erjavec, Kaja Dobrovoljc, Sara Može, Nina Ledinek and Nanika Holz.
2013. Training corpus ssj500k 1.3. http://hdl.handle.net/11356/1029.

Špela Arhar and Vojko Gorjanc. 2007. Korpus FidaPLUS: nova generacija
slovenskega referenčnega korpusa (The FidaPLUS corpus: a new
generation of the Slovene reference corpus). Jezik in slovstvo, 52(2).

Tomaž Erjavec, Darja Fišer, Simon Krek and Nina Ledinek. 2010. The JOS
Linguistically Tagged Corpus of Slovene. In: Proceedings of the
Seventh International Conference on Language Resources and Evaluation
(LREC'10), Malta, 2010.

Acknowledgments:
We wish to thank all of the contributors to the original ssj500k
training corpus: Kristina Bizjak, Živa Blaževič, Klara Canzutti, Lea
Cibrič, Kaja Dobrovoljc, Tadeja Dušej, Tomaž Erjavec, Ivana Fekeža,
Nanika Holz, Urška Kamenšek, Simon Krek, Andreja Košir, Robert Kuret,
Nina Ledinek, Andrej Lovšin, Boštjan Marhold, Nina Mikulin, Barbara
Modrijan, Sara Može, Tanja Novak, Lea Peršič, Tanja Radovič, Simona
Šinkovec, Urška Vranjek, Jerneja Umer, Petra Žalodec.


Documentation status: partial
Data source: automatic
Data available since: UD v1.2
License: CC BY-NC-SA 4.0
Genre: news nonfiction fiction
Contributors: Dobrovoljc, Kaja; Erjavec, Tomaž; Krek, Simon
