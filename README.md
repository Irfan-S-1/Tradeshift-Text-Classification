# Tradeshift-Text-Classification


The data contains features extracted from text similar to the one shown
below.

You have to create a ML model that predict the probability that a piece of
text belongs to a particular class.

Data extraction
Fro the documents nGrams have been extracted, Each row in the
Train.csvcorresponds to one such nGram.

Features
For a given nGram several features have been extracted (145). These
features have been saved in the train.csvand test.csv. They have
parsing, spatial, content and relative information.
• Content: The cryptographic hash of the raw text.
• Parsing: nGram is a number, text, alphanumeric, etc.
• Spatial: Position and size of the nGram
• Relational: details of text nearby the nGram
The feature values can be:

• Numbers. Continuous/discrete numerical values.
• Boolean. The values include YES (true) or NO (false).
• Categorical. Values within a finite set of possible values.

Labels
This are the labels corresponding to the probability that the current
sample belongs to the given class. This is multilabel problem and hence
a given sample can belong to more than one class.
