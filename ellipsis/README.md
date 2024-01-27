# Ellipsis and Elided Elements in Natural Language: The Hoosier Ellipsis Corpus

Created: [Damir Cavar], 2023-06-07

Last change: [Damir Cavar], 2024-01-27


[Ellipsis] and other phenomena where words in sentences and utterances are elided or omitted are extremely interesting from a theoretical linguistic and cognitive language faculty perspective. In general, we recommend looking at [The Oxford Handbook of Ellipsis](https://academic.oup.com/edited-volume/41718) and the numerous research articles, books, and dissertations discussed in the different sections of the handbook. There are also highly relevant articles mentioned below in the publications and on the websites from the various ellipsis corpus projects mentioned below.

There are various reasons why we are working on [ellipsis] and other word-omitting phenomena. Some of those are:

- [syntactic] parsers fail with such constructions, and such constructions are prevalent in highly relevant domains (e.g., social media interaction, dialogs, medical documents, financial reports)
- current State of the Art (SOTA) [Natural Language Processing] ([NLP]) and [Natural Language Understanding] ([NLU]) components, including [Large Language Models] ([LLMs]) are of limited use for advanced [semantic] and [pragmatic] processing due to a failure to deal with omitted words or phrases, what we call the "**Language**" or "**Linguistic Dark Matter**".

We will provide research reports here in the near future with quantified data related to these claims. These are strong claims, but our experience has shown that the limited use of phrase structure and dependency parsers significantly relates to the failure to process **Dark Matter in Language**. While certainly [semantic] and [pragmatic] approaches could be tried to reconstruct omitted linguistic content, we focus on [syntactic] and pattern-based methods with neural and symbolic algorithms, modeling the [fast and slow processing](https://en.wikipedia.org/wiki/Thinking,_Fast_and_Slow) of the human language faculty when it comes to elided linguistic content.

Our goals are ambitious:

- to develop a data set that provides enough corpus material to sufficiently document and represent the various manifestations of [ellipsis], and to provide enough data for the engineering of [NLP] solutions
- to engineer [NLP] components (parsers and language models) that can reconstruct the omitted words and that can provide theoretically adequate and computationally useful [syntactic] parse tree ([Phrase Structure Tree] and [Dependency Tree]) for constructions containing [ellipsis]
- all this we want to cover for English, Ukranian, Russian, Chinese, Japanese, Korean, Spanish, German...


And, no, [ChatGPT](https://openai.com/blog/chatgpt) is not the solution here...


## Online Resources

We identified the following resources online:

- [An annotated corpus for the analysis of VP ellipsis](http://www.let.rug.nl/bos/vpe/abstract.html), Johan Bos and Jennifer Spenader
- [The Brandeis-Simmons Corpus of English VP Ellipsis](https://sites.google.com/simmons.edu/vpe-corpus/about)
    - [VPE-Corpus Material](https://sites.google.com/simmons.edu/vpe-corpus), Lotus Goldberg and Amber Stubbs
    - [The Syntactic Corpus of English VP Ellipsis](https://sites.google.com/simmons.edu/vpe-corpus/nasslli2022), NASSLLI 2022 course
    - [The VP Ellipsis Corpus](https://osf.io/uv2tq/) at OSF
- [Santa Cruz Ellipsis Project](https://babel.ucsc.edu/SCEP/Downloads/index.html)
    - [Santa Cruz Ellipsis Consortium Sluicing Dataset 1.0](https://zenodo.org/record/1739702)
    - [Dataset of Zaitsu 2019](https://babel.ucsc.edu/SCEP/Downloads/zaitsu-whyVP-dataset.txt)
    - [Santa Cruz Ellipsis Consortium](https://thi.ucsc.edu/clusters/santa-cruz-ellipsis-consortium/)

If you have more links or if you want to share your data sets, please send us a note, damir at iu.edu.



### Indiana Multilingual Ellipsis Corpus

- GitHub repo

The current status of the corpus (still under development):

| lang             | count |
|------------------|-------|
| English          | 568   |
| Arabic           | 375   |
| Spanish          | 135   |
| Russian          | 122   |
| Japanese         | 113   |
| Hindi            | 112   |
| Polish           | 91   |
| Ukrainian        | 81   |
| German           | 79   |
| Korean           | 40   |
| Mandarin Chinese | 31   |
| Kumaoni          | 29   |
| Gujarati         | 9   |
| Swedish          | 8   |
| Navajo           | 8   |
| Croatian         | 6   |



## Publications

- [Damir Cavar], [Ludovic V. Mompelat](https://www.linkedin.com/in/ludovic-mompelat-8a1960b8/), [Muhammad S. Abdo](https://www.linkedin.com/in/muhsabrys/) (2024) The Typology of Ellipsis: A Corpus for Linguistic Analysis and Machine Learning Applications. Paper to be presented at the [ACL Special Interest Group on Typology](https://sigtyp.github.io/) ([SIGTYP](https://sigtyp.github.io/)) 2024, colocated with the [18th Conference of the European Chapter of the Association for Computational Linguistics](https://2024.eacl.org/), St Julian's, Malta (March, 2024). (full paper)


## Presentations

- [Damir Cavar], [Ludovic V. Mompelat](https://www.linkedin.com/in/ludovic-mompelat-8a1960b8/), [Muhammad S. Abdo](https://www.linkedin.com/in/muhsabrys/) (2024) The Typology of Ellipsis: A Corpus for Linguistic Analysis and Machine Learning Applications. Paper to be presented at the [ACL Special Interest Group on Typology](https://sigtyp.github.io/) ([SIGTYP](https://sigtyp.github.io/)) 2024, colocated with the [18th Conference of the European Chapter of the Association for Computational Linguistics](https://2024.eacl.org/), St Julian's, Malta. (full paper)

- [Damir Cavar], [Muhammad S. Abdo](https://www.linkedin.com/in/muhsabrys/), and [Billy Dickson](https://www.linkedin.com/in/billy-dickson/) (2024) Ellipsis in Arabic: Using Machine Learning to Detect and Predict Elided Words. Paper presented at the [Arabic Linguistic Society](https://arabic-linguistics-society.uwm.edu/annual-symposia-on-arabic-linguistics/guidelines-for-writing-abstracts/) ([ASAL](https://arabic-linguistics-society.uwm.edu/annual-symposia-on-arabic-linguistics/guidelines-for-writing-abstracts/)) 37 Conference, February 2024, New York City.




[Damir Cavar]: http://damir.cavar.me/ "Damir Cavar"
[NLP-Lab.org]: http://nlp-lab.org/ "NLP-Lab.org"
[Ellipsis]: https://en.wikipedia.org/wiki/Ellipsis_(linguistics) "Ellipsis"
[ellipsis]: https://en.wikipedia.org/wiki/Ellipsis_(linguistics) "Ellipsis"
[Natural Language Processing]: https://en.wikipedia.org/wiki/Natural_language_processing "Natural Language Processing"
[NLP]: https://en.wikipedia.org/wiki/Natural_language_processing "Natural Language Processing"
[Natural Language Understanding]: https://en.wikipedia.org/wiki/Natural-language_understanding "Natural Language Understanding"
[NLU]: https://en.wikipedia.org/wiki/Natural-language_understanding "Natural Language Understanding"
[Large Language Models]: https://en.wikipedia.org/wiki/Large_language_model "Large Language Models"
[LLMs]: https://en.wikipedia.org/wiki/Large_language_model "Large Language Models"
[Large Language Model]: https://en.wikipedia.org/wiki/Large_language_model "Large Language Model"
[LLM]: https://en.wikipedia.org/wiki/Large_language_model "Large Language Model"
[Phrase Structure Tree]: https://en.wikipedia.org/wiki/Phrase_structure_grammar "Phrase Structure Tree"
[Phrase Structure Grammar]: https://en.wikipedia.org/wiki/Phrase_structure_grammar "Phrase Structure Grammar"
[Dependency Tree]: https://en.wikipedia.org/wiki/Dependency_grammar "Dependency Tree"
[Dependency Grammar]: https://en.wikipedia.org/wiki/Dependency_grammar "Dependency Grammar"
[semantic]: https://en.wikipedia.org/wiki/Semantics "Semantics"
[pragmatic]: https://en.wikipedia.org/wiki/Pragmatics "Pragmatics"
[syntactic]: https://en.wikipedia.org/wiki/Syntax "Syntax"
