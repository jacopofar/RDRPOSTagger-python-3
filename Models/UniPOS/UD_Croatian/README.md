## Universal Dependencies for Croatian

The Croatian UD treebank is built on top of the [SETimes.HR dependency treebank of Croatian](https://github.com/ffnlp/sethr).
It comprises roughly 4,000 sentences of newspaper text from the
[Southeast European Times](http://en.wikipedia.org/wiki/Southeast_European_Times) news website taken from the
[SETimes parallel corpus](http://nlp.ffzg.hr/resources/corpora/setimes/).

The training set has 3,557 sentences (78,817 words) of newspaper text, while the development set contains 200 sentences
(4,823 words) from the same source. The test set has 200 sentences (4,125 words): the first 100 sentences are newspaper text,
while the other 100 sentences come from the Croatian Wikipedia.

Sentence and word segmentation was manually checked. The treebank does not include multiword tokens. No language-specific
features and relations were used. The POS tags and features were converted from
[Multext East v4](http://nlp.ffzg.hr/data/tagging/msd-hr.html) and manually checked.
The syntactic annotation was done manually.

When using the Croatian UD treebank, please cite the
[UD handle](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/LRT-1478) and the following paper:

* Željko Agić and Nikola Ljubešić. 2014.
  [The SETimes.HR Linguistically Annotated Corpus of Croatian](http://www.lrec-conf.org/proceedings/lrec2014/pdf/690_Paper.pdf).
  In Proc. LREC, pp. 1724--1727 ([bib](http://aclweb.org/anthology/L/L14/L14-1542.bib)).

See file LICENSE.txt for further licensing information.

### Changelog

No change since UD v1.1.



=== Machine-readable metadata =================================================
Documentation status: stub
Data source: semi-automatic
Data available since: UD v1.1
License: CC BY-SA 4.0
Genre: news wiki
Contributors: Agić, Željko; Ljubešić, Nikola
===============================================================================
