# Summary

The UD Turkish Treebank, also called the IMST-UD Treebank, is a semi-automatic conversion of the IMST Treebank (Sulubacak&Eryiğit, 2018; Sulubacak et al., 2016).


# Introduction

The UD Turkish Treebank, also called the IMST-UD Treebank, is a semi-automatic conversion of the IMST Treebank (Sulubacak & Eryiğit, 2018; Sulubacak et al., 2016), which is itself a reannotated version of the METU-Sabancı Turkish Treebank (Oflazer et al., 2003). All three treebanks share the same raw data, a set of 5635 sentences collected from daily news reports and novels.

Validation errors in the dataset were corrected by BOUN TABILAB/TULAP team in UD v2.11 release.

The sentences were reorganized by Furkan Akkurt for v2.13 based on the original [METU Turkish Corpus (MTC)](https://ii.metu.edu.tr/metu-corpora-research-group) so that sentences from the same document once again form a contiguous segment in the original order. Document ids were added and documents are no longer split between train, dev and test (that is, the data split had to be exceptionally changed between releases). Moreover, the new data split is compatible with the data split of the ITCC dataset in [CorefUD 1.1](https://ufal.mff.cuni.cz/corefud), which is partially based on the same documents from MTC. The scripts used to do the reorganization are kept [here](https://github.com/furkanakkurt1335/imst-mtc-reorganization).


# Acknowledgments

The IMST-UD Treebank is licensed under Creative Commons (BY-NC-SA 4.0). A summary for the terms of the license is given below (see here for more information). Under the terms of the license,

If you would use this treebank in any form of publication, please  cite the following papers:

-Umut Sulubacak, Gülşen Eryiğit. Implementing Universal Dependency, Morphology and Multiword Expression Annotation Standards for Turkish Language Processing. Turkish Journal of Electrical Engineering & Computer Sciences, DOI: 10.3906/elk-1706-81):1–23. May 2018.

-Umut Sulubacak, Memduh Gökırmak, Francis Tyers, Çağrı Çöltekin, Joakim Nivre, and Gülşen Eryiğit. Universal Dependencies for Turkish. In Proceedings of COLING 2016, the 26th International Conference on Computational Linguistics. Osaka, Japan, December 2016.

This treebank follows a set of morphosyntactic annotation guidelines based on those established by Çağrı Çöltekin, and later revised and restructured by Memduh Gökırmak, Francis Tyers, and Umut Sulubacak. The conversion from the IMST Treebank (available from  http://tools.nlp.itu.edu.tr/Datasets) was done by Umut Sulubacak. The contributors would also like to thank Birsel Karakoç, Hüner Kaşıkara, and Tuğba Pamay for their discussions and insights.



# Changelog

* 2023-11-15 v2.13
  * Reorganized sentences by docs using the original corpus (MTC).
* 2022-11-15 v2.11
  * Fixed validation errors.
* 2021-05-15 v2.8
  * The word "bir", if used as a determiner, gets corresponding UPOS and features.
  * Attachment of punctuation fixed using Udapi ud.FixPunct.
  * A number of other validation errors fixed.
  * Undocumented Aspect=DurPerf changed to Aspect=Dur.
* 2019-05-15 v2.4
  * Moved around a few sentences so that both dev and test have over 10K words again.
* 2018-07-01 v2.2
  * Repository renamed from UD_Turkish to UD_Turkish-IMST.
* 2017-03-01 v2.0
  * Conversion to UD v2 guidelines.
* 2016-11-15 v1.4
  * Fixed annotation and spelling mistakes in generated forms of multiword tokens.
* 2016-05-15 v1.3
  * First release in UD.

<pre>
=== Machine-readable metadata =================================================
Data available since: UD v1.3
License: CC BY-NC-SA 4.0
Includes text: yes
Genre: nonfiction news
Lemmas: converted from manual
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Türk, Utku; Özateş, Şaziye Betül; Marşan, Büşra; Akkurt, Furkan; Çöltekin, Çağrı; Cebiroğlu Eryiğit, Gülşen; Gökırmak, Memduh; Kaşıkara, Hüner; Sulubacak, Umut; Tyers, Francis
Contributing: elsewhere
Contact: memduhg@gmail.com
===============================================================================
</pre>
