# Summary

Bungo lo Lombi is a Universal Dependencies parsed corpus of modern spoken Gorontalo as spoken in Gorontalo City, Gorontalo Province, Indonesia. It comprises fieldwork samples obtained by Colleen Alena O'Brien.

# Introduction

Bungo lo Lombi is a corpus of modern spoken Gorontalo as spoken in Gorontalo City, Gorontalo Province, Indonesia. It comprises fieldwork samples obtained by Colleen Alena O'Brien. The complete data contains elicited examples and monologue and dialogue. At the moment, only elicited examples have been parsed.

The parsed data is different from other Austronesian languages in Universal Dependencies in the following ways:
* Dependency relations for core arguments use semantic sublabels in all verb phrases with voice-marking, e.g. _nsubj:actor_, _obj:patient_, _obj:agent_, etc. In this way, no voice is treated as default.
* Some feature values are replaced, e.g. `Voice=Pat` for patient voice instead of `Voice=Pass`. We refer to the paper in the README for more details. In practice, these new values can be losslessly mapped back to pre-existing ones in order to share labels with other corpora.

The name Bungo lo Lombi means "banana tree" in Gorontalo: a very useful, very versatile tree that provides a valuable fruit.

# Acknowledgments

* Key elicitation examples and explanations provided by Novi Usu.

## References

Cite as:

```
@inproceedings{dyer-obrien-2025-towards,
    title = "Towards better annotation practices for symmetrical voice in {U}niversal {D}ependencies",
    author = "Dyer, Andrew Thomas  and
      O{'}Brien, Colleen Alena",
    editor = {Bouma, Gosse  and
      {\c{C}}{\"o}ltekin, {\c{C}}a{\u{g}}r{\i}},
    booktitle = "Proceedings of the Eighth Workshop on Universal Dependencies (UDW, SyntaxFest 2025)",
    month = aug,
    year = "2025",
    address = "Ljubljana, Slovenia",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.udw-1.15/",
    pages = "137--142",
    ISBN = "979-8-89176-292-3",
    abstract = "Austronesian languages exhibit features that are challenging for Universal Dependencies: most notably, the symmetric voice system, whereby agent, patient, and instrumental arguments (among others) can be the pivot of a transitive structure {--} complicating the usual assumption that subjects of transitive sentences are semantic agents, and objects semantic patients. To showcase our ideas of how to address the representation of such systems in Universal Dependencies, we introduce a small treebank of sentences from texts and elicitation sessions in Gorontalo, an Austronesian language of Sulawesi (Indonesia), which exhibits a Philippine-type voice system. We discuss the annotation guidelines for this language, and the extensions of the Universal Dependencies guidelines that are needed to accommodate this and other Austronesian languages."
}
```
Andrew Thomas Dyer and Colleen Alena O’Brien. 2025. Towards better annotation practices for symmetrical voice in Universal Dependencies. In Proceedings of the Eighth Workshop on Universal Dependencies (UDW, SyntaxFest 2025), pages 137–142, Ljubljana, Slovenia. Association for Computational Linguistics.

# Changelog

* 2026-05-15 v2.18
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.18
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: TO-BE-SPECIFIED
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Dyer, Andrew Thomas; O'Brien, Colleen Alena
Contributing: here
Contact: andrew.dyer@uni-saarland.de
===============================================================================
</pre>
