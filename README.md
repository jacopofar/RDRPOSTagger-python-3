## RDRPOSTagger ##

**RDRPOSTagger** is a robust, easy-to-use and language-independent toolkit for POS and morphological tagging. It employs an error-driven approach to automatically construct tagging rules in the form of a binary tree. The main properties of RDRPOSTagger are as follows:

- RDRPOSTagger obtains fast performance in both learning and tagging process. For example, on the English Penn WSJ sections 22-24, RDRPOSTagger achieved tagging speeds of **5K** and **90K** words/second computed for *single threaded implementations* in **Python** and **Java** respectively, using a computer with *Core2Duo 2.4GHz and 3GB of memory*.

- RDRPOSTagger achieves a very competitive accuracy in comparison to the state-of-the-art results. See experimental results including performance speed and tagging accuracy for 13 languages in our *AI Communications* article.

- RDRPOSTagger supports pre-trained POS and morphological tagging models for Bulgarian, Czech, Dutch, English, French, German, Hindi, Italian, Portuguese, Spanish, Swedish, Thai and Vietnamese.  

The general architecture and experimental results of RDRPOSTagger can be found in our papers:

- Dat Quoc Nguyen, Dai Quoc Nguyen, Dang Duc Pham and Son Bao Pham. [RDRPOSTagger: A Ripple Down Rules-based Part-Of-Speech Tagger](http://www.aclweb.org/anthology/E14-2005). In *Proceedings of the Demonstrations at the 14th Conference of the European Chapter of the Association for Computational Linguistics*, EACL 2014, pp. 17-20, 2014. [[.PDF]](http://www.aclweb.org/anthology/E14-2005) [[.bib]](http://www.aclweb.org/anthology/E14-2005.bib)

- Dat Quoc Nguyen, Dai Quoc Nguyen, Dang Duc Pham and Son Bao Pham. [A Robust Transformation-Based Learning Approach Using Ripple Down Rules for Part-Of-Speech Tagging](http://content.iospress.com/articles/ai-communications/aic698). *AI Communications*, to appear (accepted for publication on 3/12/2015). [[CameraReadyVersion]](http://arxiv.org/abs/1412.4021)

Please cite our EACL2014 paper whenever RDRPOSTagger is used to produce published results or incorporated into other software! 

We would highly appreciate to have your bug reports, comments and suggestions about the RDRPOSTagger. As a free open-source implementation, RDRPOSTagger is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

RDRPOSTagger is also available to download (5MB .zip file) at: [https://sourceforge.net/projects/rdrpostagger/files/RDRPOSTagger_v1.2.1.zip](https://sourceforge.net/projects/rdrpostagger/files/RDRPOSTagger_v1.2.1.zip)

**FULL usage of RDRPOSTagger can be found at: [http://rdrpostagger.sourceforge.net/](http://rdrpostagger.sourceforge.net/)**

For a short description of the usage: please follow the `printHelp()` function in the `RDRPOSTagger.py` module in the `pSCRDRtagger` package, and the `printHelp()` method in the `RDRPOSTagger.java` class in the `jSCRDRtagger` package. Or simply run from command line/terminal:

- Example 1: `pSCRDRtagger$ python RDRPOSTagger.py`
- Example 2: `jSCRDRtagger$ java RDRPOSTagger`


