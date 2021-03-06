# Summary

UD_Tagalog-TRG is a UD treebank manually annotated using sentences from a grammar book.

# Introduction

The Tagalog treebank, so far, consists of 55 sentences with sources from the grammar books Tagalog Reference Grammar (Schachter and Otanes 1972) and Essential Tagalog Grammar: A Reference for Learners of Tagalog (De Vos 2010). The annotations are done manually.

# Acknowledgments

The annotations were done by Stephanie Samson. Çağrı Çöltekin (University of Tübingen, Germany) with the UD guidelines and was a source of knowledge when there were any doubts regarding the annotation process.

# References

* De Vos, F. (2010). Essential Tagalog Grammar: A Reference for Learners of
Tagalog. Fiona de Vos. isbn: 9789081513500.

* Schachter, P. and F.T. Otanes (1972). Tagalog Reference Grammar. University
of California Press. isbn: 9780520017764.

# Changelog

* 2020-11-15 v2.7
    * Fixed a few validation errors.
    * Instead of the Focus attribute in MISC, verbal inflection now has the Voice feature.
    * Removed XPOS tags because they were uninformative (taken from the English Penn set).
    * Added the PronType=Prs feature to personal pronouns (also added Number, Person and Clusivity where missing).
    * Added the PronType=Art feature to determiners.
    * Added glosses in MISC.
* 2018-03-14 v0.1
    * First release in UD

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.2
License: CC BY-SA 4.0
Includes text: yes
Genre: grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Samson, Stephanie; Zeman, Daniel; Tan, Mary Ann C.
Contributing: here
Contact: stephsamson@protonmail.ch
===============================================================================
</pre>
