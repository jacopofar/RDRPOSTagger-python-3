## Treebank data and annotation

The Spoken Slovenian UD Treebank (SST) is the first syntactically annotated corpus of spoken Slovenian. The manual annotations have been performed on a representative sample of the reference Gos corpus of spoken Slovenian (Zwitter Vitez et al. 2013), a collection of transcribed audio recordings of monologic, dialogic and multi-party spontaneous speech in different everyday situations. The treebank is representative of speakers (sex, age, region, education), communication channels (TV, radio, telephone, personal contact) and communication settings (TV and radio shows, lectures, meetings, consultations, services, conversations between friends etc.). 

The spelling, tokenization and segmentation principles follow the transcription guidelines of the reference corpus (Verdonik et al. 2013) with the syntactic trees spanning over individual utterances (semantically, syntactically and acoustically delimited units, roughly corresponding to written sentences). The morphological and syntactic analysis in the SST treebank has been performed on top of normalized transcriptions that reduce the number of token types due to regional, colloquial and other pronunciation variation. However, information on pronunciation-based transcription and tokenization has been included as part of the MISC column.

The SST treebank includes manual annotations of lemmas, part-of-speech categories, morphological features and dependency relations in accordance with the Universal Dependencies annotation scheme. In addition to language-specific extensions, in line with the written Slovenian UD Treebank, the SST treebank also includes new speech-specific extensions to accommodate the structural and pragmatic particularities of spoken language syntax, such as disfluencies, fillers, parentheticals, general extenders etc.  More information on the treebank construction and annotation is given in Dobrovoljc and Nivre (2016).


## Size and data split
The current version of the SST treebank includes 3,188 utterances (sentences) or 29,488 tokens, produced by 606 speakers in 287 different speech events. The treebank has been linearly split into training (80%), development (10%) and test (10%) data. In future releases, however, the data split should be amended so as to reflect genre distributions.


## Contributors
Kaja Dobrovoljc (treebank construction and annotation)
Joakim Nivre (guidelines consulting)


## References
* Kaja Dobrovoljc and Joakim Nivre. 2016. The Universal Dependencies Treebank of Spoken Slovenian. In: Proceedings of the Tenth International Conference on Language Resources and Evaluation (LREC’16), Portorož, Slovenia.
* Darinka Verdonik, Iztok Kosem, Ana Zwitter Vitez, Simon Krek and Marko Stabej. 2013. Compilation, transcription and usage of a reference speech corpus: the case of the Slovene corpus GOS. Language Resources and  Evaluation, 47(4):1031–1048.
* Ana Zwitter Vitez, Jana Zemljarič Miklavčič, Simon Krek, Marko Stabej and Tomaž Erjavec. 2013. Spoken corpus Gos 1.0. Slovenian language resource repository CLARIN.SI. http://hdl.handle.net/11356/1040.


---- machine readable metadata ----
Documentation status: partial
Data source: manual
Data available since: UD v1.3
License: CC BY-NC-SA 4.0
Genre: spoken
Contributors: Dobrovoljc, Kaja; Nivre, Joakim
