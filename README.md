# Summary

The UD Turkish Treebank, also called the IMST-UD Treebank, is a semi-automatic conversion of the IMST Treebank (Sulubacak&Eryiğit, 2018; Sulubacak et al., 2016).

# Introduction

The UD Turkish Treebank, also called the IMST-UD Treebank, is a semi-automatic conversion of the IMST Treebank (Sulubacak&Eryiğit, 2018; Sulubacak et al., 2016), which is itself a reannotated version of the METU-Sabancı Turkish Treebank (Oflazer et al., 2003). All three of the treebanks share the same raw data, a set of 5 635 sentences collected from daily news reports and novels.

Validation errors in the dataset were corrected by BOUN TABILAB/TULAP team in UD v2.11 release.

# Acknowledgments
The IMST-UD Treebank is licensed under Creative Commons (BY-NC-SA 4.0). A summary for the terms of the license is given below (see here for more information). Under the terms of the license,

If you would use this treebank in any form of publication, please  cite the following papers:

-Umut Sulubacak, Gülşen Eryiğit. Implementing Universal Dependency, Morphology and Multiword Expression Annotation Standards for Turkish Language Processing. Turkish Journal of Electrical Engineering & Computer Sciences, DOI: 10.3906/elk-1706-81):1–23. May 2018.

-Umut Sulubacak, Memduh Gökırmak, Francis Tyers, Çağrı Çöltekin, Joakim Nivre, and Gülşen Eryiğit. Universal Dependencies for Turkish. In Proceedings of COLING 2016, the 26th International Conference on Computational Linguistics. Osaka, Japan, December 2016.


This treebank follows a set of morphosyntactic annotation guidelines based on those established by Çağrı Çöltekin, and later revised and restructured by Memduh Gökırmak, Francis Tyers, and Umut Sulubacak. The conversion from the IMST Treebank (available from  http://tools.nlp.itu.edu.tr/Datasets) was done by Umut Sulubacak. The contributors would also like to thank Birsel Karakoç, Hüner Kaşıkara, and Tuğba Pamay for their discussions and insights.



# Changelog

* 2022-11-05 UD v2.11
  * Fixed validation errors.
* UD 2.8
  * The word "bir", if used as a determiner, gets corresponding UPOS and features.
  * Attachment of punctuation fixed using Udapi ud.FixPunct.
  * A number of other validation errors fixed.
  * Undocumented Aspect=DurPerf changed to Aspect=Dur.
* UD 2.4
  * Moved around a few sentences so that both dev and test have over 10K words again.
* UD 2.2
  * Repository renamed from UD_Turkish to UD_Turkish-IMST.
* UD 2.1
  * No change.
* UD 2.0
  * Conversion to UD v2 guidelines.
* UD 1.4
  * Fixed annotation and spelling mistakes in generated forms of multiword tokens.
* UD 1.3
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
Contributors: Türk, Utku; Özateş, Betül; Marşan, Büşra; Akkurt, Salih Furkan; Çöltekin, Çağrı; Cebiroğlu Eryiğit, Gülşen; Gökırmak, Memduh; Kaşıkara, Hüner; Sulubacak, Umut; Tyers, Francis
Contributing: elsewhere
Contact: memduhg@gmail.com
===============================================================================
</pre>
