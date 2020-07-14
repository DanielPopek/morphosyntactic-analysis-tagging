# Tagger impact on sentiment cattegories classification

The aim of this project was to inspect impact of specific NLP taggers on quality of sentiment classification of texts. 

Only Polish text were classified. 

The CLARIN-PL plemo2.0-no-segm.txt corpus was uses as sentiment classification training set. 

## Subtasks:
1. Preparation of morpho-sysntacic analysis (from segmentation to potential tags)
2. Preparation of concrete taggers for Polish language
3. Implementation of Naive Bayes, SVN and neural text sentiment classifiers basing on frequency statistics concearniong parts of speech: verbs, nouns and adjectives 
4. Comparison of impact  of taggers on classification task 

## Taggers used:
- krnnt 
- morphodita
- ml CLARIN tagger
- WCRF1 tagger (with morpheusz morphosytactic analyzer)
- WCRF2 tagger (with morpheusz morphosytactic analyzer)