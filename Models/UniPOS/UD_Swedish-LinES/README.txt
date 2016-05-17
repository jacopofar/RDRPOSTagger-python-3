Swedish_LinES

This treebank is the Swedish half of the LinES Parallel Treebank 1.0
with the original dependency annotation first automatically converted
into Universal Dependencies and then partially reviewed. LinES
contains segments from seven different sources, three of which are
part of the Linköping Translation Corpus Corpus (Merkel, 1999). The
treebank was first developed in the project 'Micro- and macro-level
analysis of translations' funded by the Swedish Research Council
(Ahrenberg, 2007). It is being developed continuously.

All sub-corpora have English originals with Swedish translations. Five of them
are literary works:

Paul Auster: Stad av glas [City of Glass], Tiden, 1995. Translation by
Ulla Roseen.

Saul Bellow: Jerusalem tur och retur [To Jerusalem and back: a
personal accunt], Bonniers, 1977. Translation by Caj Lundgren.

Joseph Conrad: Mörkrets hjärta [Heart of darkness], Wahlström &
Widstrand, Stockholm, 1983. Translation by Margaretha Odelberg.

Nadine Gordimer: Hedersgästen [A Guest of Honour], Bonniers,
1991. Translation by Magnus K:son Lindberg.

J. K. Rowling: Harry Potter och Hemligheternas kammare [Harry Potter
and the Chamber of Secrets], Tiden, 2001. Translation by Lena
Fries-Gedin.

In addition the corpus includes segments from Microsoft Access 2002
Online Help and the Swedish part of the Europarl corpus (v.7).

DATA SPLITS

10% of the trees were randomly selected as test set, 10% as development set, and the rest as training set. The randomization applies in the same way to the English trees so that the order of corresponding trees is the same in the English and Swedish LinES files. The files are named

 - sv-lines-ud-test.conllu 
 - sv-lines-ud-dev.conllu
 - sv-lines-ud-train.conllu


BASIC STATISTICS

Tree count:  4564
Word count:  79812
Token count: 79812
Dep. relations: 38 of which 4 are language-specific
POS tags: 17
Category=value feature pairs: 0


TOKENIZATION

The tokenization is largely based on whitespace, but punctuation marks
except word-internal hyphens are treated as separate tokens. The
original file also has several multi-word tokens, but these are
separated in the UD version with all parts except the first assigned
the UD dependency function 'mwe'.


MORPHOLOGY

The morphological annotation in the Swedish LinES treebank is the same
as in the original LinES.  Nouns are annotated for case, number,
species, and definiteness (but not gender). Verbs are annotated for
tense and diathesis, adjectives for case, degree, definiteness, and
number. Pronouns are sub-divided in the morphological description into
Personal, Demonstrative, Interrogative, Indefinite, Relative, Total,
and Expletive, and are annotated for Case and Number, when relevant.

The mapping from language-specific part-of-speech tags to universal tags
was done automatically. There are no other tags than universal tags, but
there may be errors.

There is no feature annotation in this version.

SYNTAX

The syntactic annotation in the Swedish UD treebank follows the general 
guidelines but adds four language-specific relations, as in the first
Swedish UD treebank, Talbanken (Nivre

- acl:relcl for relative clauses
- compound:prt for verb particles
- nmod:agent for agents of passive verbs
- nmod:poss for possessive/genitive modifiers

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
