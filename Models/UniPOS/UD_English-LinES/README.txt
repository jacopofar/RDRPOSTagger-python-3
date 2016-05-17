English_LinES

This treebank is the English half of the LinES Parallel Treebank 1.0
with the original dependency annotation first automatically converted
into Universal Dependencies and then partially reviewed. LinES
contains segments from seven different sources, three of which are
part of the Linköping Translation Corpus Corpus (Merkel, 1999). The
treebank was first developed in the project 'Micro- and macro-level
analysis of translations' funded by the Swedish Research Council
(Ahrenberg, 2007). It is being developed continuously.

All sub-corpora are English originals with Swedish translations found in
the treebank Swedish_Lines. If you would like to get files with word
alignments, please contact Lars Ahrenberg.

Five of the sub-corpora are taken from literary works:

Paul Auster: City of Glass. The New York Trilogy, Volume One. First
published by Faber & Faber in 1985.

Saul Bellow: To Jerusalem and back: a personal accunt. First published
in 1976.

Joseph Conrad: Heart of darkness. First published in 1899 as a serial
in Blackwood's Magazine, in 1902 as a book.

Nadine Gordimer: A Guest of Honour. First published in 1970.

J. K. Rowling: Harry Potter and the Chamber of Secrets. First published
in 1998.

In addition the corpus includes segments from Microsoft Access 2002
Online Help and the Englsh part of the Europarl corpus (v.7).

DATA SPLITS

Before splitting all segments were scrambled. From this scrambled
version, 10% were randomly selected as test set, 10% as development set, and the rest as training set. The files are named

 - en-lines-ud-test.conllu 
 - en-lines-ud-dev.conllu
 - en-lines-ud-train.conllu

English_LinES and Swedish_LinES have been split the same way.


BASIC STATISTICS

Tree count: 4564
Word count: 82821
Token count: 82821
Dep. relations: 37 of which 4 language specific
POS tags: 17
Category=value feature pairs: 0

TOKENIZATION

The tokenization is largely based on whitespace, but punctuation marks
except word-internal hyphens are treated as separate tokens. The
original file also has several multi-word tokens, but these are
separated in the UD version with all parts except the first assigned
the UD dependency function 'mwe'.

MORPHOLOGY

The morphological annotation in the English LinES treebank is the same
as in the original LinES with the exception of nouns that are not
annotated for case, only number.  Verbs are annotated for tense and,
adjectives for degree. Pronouns are sub-divided in the morphological
description into Personal, Demonstrative, Interrogative, Indefinite,
Relative, Total, and Expletive, and are annotated for Number, Person
and Case, when relevant.

The mapping from language-specific part-of-speech tags to universal tags
was done automatically. There are no other tags than universal tags, but
there may be errors.

There is no feature annotation in this version.

SYNTAX

The syntactic annotation in the English UD treebank follows the
general guidelines but adds three language-specific relations, as in
the Englsh UD treebank

- acl:relcl for relative clauses
- compound:prt for verb particles
- nmod:poss for possessive/genitive modifiers

The language-specific relations det:predet and nmod:npmod are not used.

The syntactic annotation has been automatically converted from the original 
LinES annotation scheme as described in Ahrenberg (2015).

There may be occasional deviations from the general guidelines.


REFERENCES

Lars Ahrenberg, 2007. LinES: An English-Swedish Parallel
Treebank. Proceedings of the 16th Nordic Conference of Computational
Linguistics (NODALIDA, 2007).

Lars Ahrenberg, 2015. Converting an English-Swedish Parallel Treebank
to Universal Dependencies. Proceedings of the Third International
Conference on Dependency Linguistics (DepLing 2015), Uppsala, August
24-26, 2015, pp. 10-19. ACL Anthology W15-2103.

Magnus Merkel, 1999: Understanding and enhancing translation by
parallel text processing. Linköping Studies in Science and Technology,
Dissertation No. 607.


--- Machine readable metadata ---

Documentation status: partial
Data source: semi-automatic
Data available since: UD v1.3
License: CC BY-NC-SA 4.0
Genre: fiction nonfiction spoken
Contributors: Ahrenberg, Lars
