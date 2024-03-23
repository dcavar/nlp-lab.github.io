# Quantum Natural Language Processing

Created: [Damir Cavar], 2023-06-12

Last change: [Damir Cavar], 2024-03-18


**The Quantum NLP Study Group meetings are in Ballantine Hall BLBH 105 every Friday at 4 PM.**


## TOC

- [Introduction](#Introduction)
- [Literature](#Literature)
- [Tools and Technologies](#tools_and_technologies)
- [Tutorials](#tutorials)
- [Conferences](#conferences)
- [Jobs and Internships](#jobs_internships)


## Introduction <a name="Introduction"></a>

The Quantum NLP project in the NLP Lab is currently a study group focusing on the most recent papers in Quantum NLP. Our goal is to familiarize everybody with the different tools and environments for QNLP and work on interesting questions related to Quantum and language-related computation or cognitive aspects of language processing and quantum models.

The study group meets independently of the NLP Lab weekly meeting at [IU-B](https://www.indiana.edu/). If you want to join this meeting, contact [Damir Cavar] directly.

- The [GitHub repo](https://github.com/dcavar/q).

At Indiana University there is the 

- [QSEc - Quantum Science and Engineering Center](https://qsec.sitehost.iu.edu/)


## Literature <a name="Literature"></a>

<a href="https://nlp-lab.org/quantumnlp/quantum.html" target="_blank">Bibliography</a>


### Papers:

The papers we are reading are:

- Coecke et al. (2010) [Mathematical Foundations for a Compositional Distributional Model of Meaning](https://arxiv.org/abs/1003.4394).
- Coecke (2019) [The Mathematics of Text Structure](https://arxiv.org/abs/1904.03478).
- Gogioso (2016) [A Corpus-based Toy Model for DisCoCat](https://arxiv.org/abs/1605.04013).
- Bradley et al. (2018) [Translating and Evolving: Towards a Model of Language Change in DisCoCat](https://arxiv.org/abs/1811.11041).
- Kartasaklis et al. (2021) [lambeq: An Efficient High-Level Python Library for Quantum NLP](https://arxiv.org/abs/2110.04236).
- Widdows et al. (2022) [Near-Term Advances in Quantum Natural Language Processing](https://arxiv.org/abs/2206.02171).
- Alexander and Widdows (2023) [Quantum Text Encoding for Classification Tasks](https://arxiv.org/abs/2301.03715).
- Lorenz et al. (2021) [QNLP in Practice: Running Compositional Models of Meaning on a Quantum Computer](https://arxiv.org/abs/2102.12846).
- Meichanetzidis et al. (2020) [Grammar-aware sentence classification on quantum computers](https://arxiv.org/abs/2012.03756).
- Bob Coecke (2023) [Our quest for finding the universality of language](https://medium.com/quantinuum/our-quest-for-finding-the-universality-of-language-d0f7a40b76e6)
- Widdows, Dominic and Stanley Peters (2003) *[Word Vectors and Quantum Logic Experiments with negation and disjunction](https://www.semanticscholar.org/paper/Word-Vectors-and-Quantum-Logic-Experiments-with-and-Widdows-Peters/5160cad9dc3d6b19ae26796d79f69c24cee0e676#cited-papers)*. 


### Books:

- Bob Coecke and Stefano Gogioso (2023) [Quantum in Pictures: A New Way to Understand the Quantum World](https://www.quantinuum.com/news/quantum-in-pictures), Quantinuum.
-  Bob Coecke and Aleks Kissinger (2017) [Picturing Quantum Processes: A First Course in Quantum Theory and Diagrammatic Reasoning](https://www.cambridge.org/core/books/picturing-quantum-processes/1119568B3101F3A685BE832FEEC53E52), Cambridge University Press.


Relevant literature from Cognitive Science and Psychology, related to language:

- Jerome R. Busemeyer and Peter D. Bruza (2012) *[Quantum Models of Cognition and Decision](https://www.cambridge.org/core/books/quantum-models-of-cognition-and-decision/75909428F710F7C6AF7D580CB83443AC)*. Cambridge University Press. (FYI: the second edition is coming out soon and it has a special chapter on Large Language Models!)


## Tools and Technologies <a name="tools_and_technologies"></a>

- [lambeq], Python library for experimental Quantum Natural Language Processing (QNLP)
- [tket], a quantum SDK
    - [pytket], a quantum computing toolkit and optimizing compiler by Quantinuum
    - [pytket-extensions], extension modules for [pytket]
- [Qiskit] - Open-Source Quantum Development


## Tutorials <a name="tutorials"></a>

- [From quantum picturalism to quantum NLP and quantum AI](https://www.youtube.com/live/pFc2PmxVMt8?feature=share) with Bob Coecke
- [An introduction to Quantum Natural Language Processing](https://medium.com/qiskit/an-introduction-to-quantum-natural-language-processing-7aa4cc73c674), Nov. 2022 by Amin Karamlou, Marcel Pfaffhauser, and James Wootton
    - [related presentation](https://youtu.be/mJSjAePB0Eo) from the QNLP 2022
- [PennyLane a software framework for Q ML - by Xanadu](https://pennylane.ai/qml/demonstrations/)
    - [Xanadu Quantum Codebook](https://codebook.xanadu.ai/)


## Conferences <a name="conferences"></a>

- [Quantum Natural Language Processing (QNLP) 2022](https://qnlp.cambridgequantum.com/conf2022/), Oxford, UK
- [Quantum Natural Language Processing (QNLP) 2023](https://qnlp.cambridgequantum.com/conf2023/), Gothenburg, Sweden
- [Quantum Physics and Logic (QPL) 2022](https://www.qplconference.org/) ([proceedings](https://cgi.cse.unsw.edu.au/~eptcs/content.cgi?QPL2022))
- [Quantum Physics and Logic (QPL) 2023](https://qpl2023.github.io/) ([proceedings](https://cgi.cse.unsw.edu.au/~eptcs/content.cgi?QPL2023))
- [Quantum Physics and Logic (QPL) 2024](https://qpl2024.dc.uba.ar/)


## Jobs and Internships <a name="jobs_internships"></a>

- [Quantinuum Quantum NLP positions](https://jobs.eu.lever.co/quantinuum)


## Cloud Services for Quantum Computation <a name="cloud_services"></a>

- [Amazon Bracket](https://aws.amazon.com/braket/)
- [IBM Quantum](https://www.ibm.com/quantum)
- [Microsoft Azure Quantum cloud service](https://azure.microsoft.com/en-us/products/quantum/)
- [Quantinuum](https://www.quantinuum.com/hardware)




[Damir Cavar]: http://damir.cavar.me/ "Damir Cavar"
[tket]:        https://github.com/CQCL/tket "tket, a quantum SDK"
[pytket]:      https://github.com/CQCL/pytket "pytket, quantum computing toolkit"
[pytket-extensions]: https://github.com/CQCL/pytket-extensions "pytket extension modules"
[Qiskit]: https://qiskit.org/ "Qiskit"
[lambeq]: https://cqcl.github.io/lambeq/ "Lambeq"
