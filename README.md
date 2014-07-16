SemanticZip
===========


A tool applying the ParagraphVectors construction from [1] to build an automatic summarizer.
ParagraphVectors can naturally be further abstracted to DocumentVectors. Applying some extra
supervised learning to a large collection of pre-summarized documents will ideally learn an
automatic summarization function. 

There are probably lots of sources of pre-summarized material but I can think of at least 
two for which there is definitely public access. First, arxiv.org hosts an enormous
collection of academic articles, each of which is equipped with an abstract. Second, most
modern newspaper articles are writtin with an "inverted pyramid" structure so that the first
paragraph is little more than a summary of the rest of the story. This isn't as perfect of a
data source as the arxiv but could work in a pinch.

Project on hold for now.


[1] [Distributed Representations of Sentences and Documents, Quoc V. Le, Tomas Mikolov](http://arxiv.org/abs/1405.4053)
