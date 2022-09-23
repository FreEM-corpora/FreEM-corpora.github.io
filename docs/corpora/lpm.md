# FreEM<sub><i>LPM</i></sub>

FreEM<sub><i>LPM</i></sub> are several annotated corpora with lemma, POS, morphology and named-entities (cf. [here](https://freem-corpora.github.io/corpora/ner/) for NER).

## Online service

Annotate your text online: [https://dh.chartes.psl.eu/deucalion/api/freem/](https://dh.chartes.psl.eu/deucalion/api/freem/).

## Publications

Data (GitHub and Zenodo):

* Gabay, Simon, Thibault Clérice, Matthias Gille Levenson, Jean-Baptiste Camps, Jean-Baptiste Tanguy, _FreEM-corpora/FreEMlpm: FreEM LPM (Lemma, POS-tags, Morphology) corpus (4.0.1)_, GitHub, 2022, [https://github.com/FreEM-corpora/FreEMlpm](https://github.com/FreEM-corpora/FreEMlpm).
* Gabay, Simon, Thibault Clérice, Matthias Gille Levenson, Jean-Baptiste Camps, Jean-Baptiste Tanguy, _FreEM-corpora/FreEMlpm: FreEM LPM (Lemma, POS-tags, Morphology) corpus (4.0.1)_, Zenodo, 2022, [doi.org/10.5281/zenodo.6481300](https://doi.org/10.5281/zenodo.6481300).

Conference paper:

* Jean-Baptiste Camps, Simon Gabay, Paul Fièvre, Thibault Clérice, Florian Cafiero. Corpus and Models for Lemmatisation and POS-tagging of Classical French Theatre. Journal of Data Mining and Digital Humanities, Episciences.org, 2021, [⟨10.46298/jdmdh.6485⟩](https://dx.doi.org/10.46298/jdmdh.6485) and [⟨halshs-02591388v2⟩](https://halshs.archives-ouvertes.fr/halshs-02591388v2).
* Simon Gabay, Thibault Clérice, Jean-Baptiste Camps, Jean-Baptiste Tanguy, Matthias Gille-Levenson, "Standardizing linguistic data: method and tools for annotating (pre-orthographic) French", _Proceedings of the 2nd International Digital Tools & Uses Congress (DTUC '20)_, Oct 2020, Hammamet, Tunisia. [⟨10.1145/3423603.3423996⟩](https://dx.doi.org/10.1145/3423603.3423996) and [⟨hal-03018381⟩](https://hal.archives-ouvertes.fr/hal-03018381).

## Sources

Four different corpora are used:

* The _CornMol corpus_ is made of 41 comedies written in the 17th c., carefully sampled and proofread. Lemmas and POS have been manually corrected, morphology is reliable but not guaranteed.
* The _Frantext Démonstration_ corpus is composed of 32 texts, mainly written in the 18th (7 texts), 19th (24 texts) and 20th c. (4 texts). Because the corpus is already tagged and lemmatised (but not fully corrected) following other guidelines than ours, the lemmas have been aligned according to our standards and authority lists.
* The _Presto_ corpus:
	- A gold corpus is made of 60,000 tokens, taken from 5 texts written in the 16th (1 text), 17th (2 texts) and 18th c. (2 texts). Because the corpus is already tagged and lemmatised following other guidelines than ours, the lemmas have been aligned according to our standards.
	- The final Presto corpus is a three-fold one: noyau (“core”), contrôlé (“controlled”) and étendu (“extended”). We have limited ourselves to a selection of its [core version](http://presto.ens-lyon.fr/?page_id=48), whose lemmas have been corrected according to our standards and authority lists.

## Annotation

* Lemmas are aligned with the [LGeRM authority list](https://hdl.handle.net/11403/lgerm/v1). Additional tokens have been added and are [kept separately](https://github.com/FreEM-corpora/FreEMlpm/tree/master/Authority_list).
* POS tags and morphology are annotated following the [CATTEX](http://bfm.ens-lyon.fr/spip.php?article323)
* Cf. [here](https://freem-corpora.github.io/corpora/ner/) for NER annotation.
