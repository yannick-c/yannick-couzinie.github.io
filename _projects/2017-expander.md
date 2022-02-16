---
title: "Expander"
excerpt: "Python script to expand common contractions in the English language
([github](https://github.com/yannick-couzinie/expander))."
date: 2017-05-10
collection: projects
---

[See the source code here](https://github.com/yannick-couzinie/expander)

Part of my work at Cognostics ([see the CV]({{base_path}}/cv/)) involved natural
language processing. We had spoken input data that we
transcribed with text-to-speech software to text. In order to automatically
organise and classify the spoken text we needed to sanitize the input of which
one part was to expand common contractions like _don't_ or _shan't_ to _do not_
and _shall not_.

When we realised there was not definitive solution for this problem, it was
suggested at Cognostics to use deep learning methods. I thought this was a bit
exaggerated for the problem at hand and my code served as a
proof of concept that a simple statistical analysis based on Stanford's
[POS-tagging](https://nlp.stanford.edu/software/tagger.shtml) and
[NER-tagging](https://nlp.stanford.edu/software/CRF-NER.shtml) models was
enough, rather than try to create a model from scratch.

The main idea behind the solution is to start with the [list of common english
contractions](https://en.wikipedia.org/wiki/Wikipedia:List_of_English_contractions).
If the expansion of a contraction is unambiguous (like _shan't_ to _shall not_) 
we are done. For the ambiguous expansions we download [sentence corpora included
in NLTK](https://www.nltk.org/book/ch02.html). These sentences contain no
contractions, so we take all relevant sentences, contract them and look at the
resulting POS-tags to see which function in a sentence a certain contraction
has. This results in a [dictionary that I also
share](https://github.com/yannick-couzinie/expander/blob/master/disambiguations.yaml)
that contains the statistical distribution of expansions based on the
grammatical role of the contraction as identified by the POS-tagger.

This problem has been mentioned on stackoverflow but aside from a few basic
solutions did not contain any satisfying answers so that I provided my code
as answers to it (see
[here](https://stackoverflow.com/questions/24788566/python-nlp-expand-english-contractions-like-dont-thats-etc/46808018#46808018)
or [here](https://stackoverflow.com/questions/19790188/expanding-english-language-contractions-in-python/46807947#46807947)).

This code has since fallen into disrepair.
