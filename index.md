---
title: About ATHENA
feature_text: |
  ## ATHENA
  Automated Text Harvesting and Exploration of Neuroimaging Annotations (ATHENA) is a tool for classifying cognitive neuroscience studies according to the Cognitive Paradigm Ontology (CogPO).
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
* [BrainMap](http://www.brainmap.org): A database of manually-annotated neuroimaging experiments.
* [brainspell](https://brainspell.herokuapp.com): An application for crowdsourced annotation of neuroimaging experiments. All annotations are publicly available, so as brainspell becomes widely used we will be able to train ATHENA classifiers on its database and to feed back predictions for unlabeled studies.
* [Cognitive Atlas](http://www.cognitiveatlas.org): A crowdsourced ontology for cognitive neuroscience. The Cognitive Atlas provides a dictionary of terms and their synonyms that can be used as features for training ATHENA classifiers.
* [Neurosynth](http://neurosynth.org): A large (>11000 studies) database of automatically-annotated neuroimaging papers. The articles in Neurosynth are easily accessible, and are very likely to be fMRI studies, making it easier for us to identify papers to manually annotate for ATHENA's training corpus.
* [Neurovault](http://www.neurovault.org): A database of statistical images from neuroimaging experiments, often with manual annotations.
