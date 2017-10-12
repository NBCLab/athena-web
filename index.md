---
title: About ATHENA
feature_text: |
  ## ATHENA
  Automated Text Harvesting and Exploration of Neuroimaging Annotations
feature_image: "https://unsplash.it/1300/400?image=971"
excerpt: ""
---

ATHENA is a tool for classifying cognitive neuroscience studies according to the Cognitive Paradigm Ontology (CogPO).

## The Problem
Manually annotating neuroimaging papers is time-consuming and labor-intensive. With >40,000 studies in the literature, manual annotation is intractable.

## Our Solution
Using preexisting annotations and the text from associated articles, we are training classifiers to predict CogPO labels based on article text.

## Funding
ATHENA is funded via [NSF Grant 1631325](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1631325).

## Related Projects
* [The Cognitive Paradigm Ontology](http://www.cogpo.org): A top-down ontology for describing cognitive neuroscience experiments. This ontology is relatively high-level and static, making it a good source of labels for ATHENA.
* [Cognitive Atlas](http://www.cognitiveatlas.org): A crowdsourced (bottom-up) ontology for cognitive neuroscience. This ontology is very detailed, but is liable to change frequently as users contribute new knowledge or fill in blanks. As such, it is most useful as a source of features on which to train ATHENA classifiers.
* [BrainMap](http://www.brainmap.org): A database of manually annotated neuroimaging experiments.
* [Neurosynth](http://neurosynth.org): A large (>11000 studies) database of automatically annotated neuroimaging papers. The articles in Neurosynth are easily accessible, and are very likely to be fMRI studies, making it easier for us to identify papers to manually annotate for ATHENA's training corpus.
* [brainspell](https://brainspell.herokuapp.com): An application for crowdsourced annotation of neuroimaging experiments. All annotations are publicly available, so as brainspell becomes widely used we will be able to train ATHENA classifiers on its database, as well as to feed back predicted labels for new studies.
* [Neurovault](http://www.neurovault.org): A database of statistical images from neuroimaging experiments, often with manual annotations. Neurovault links CogPO and Cognitive Atlas labels to unthresholded data, along with identifiers that can be used to further link the labels to article texts.
