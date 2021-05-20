# business-relation-dataset
BizRel, our business relation dataset is composed of 10k instances in two languages **english** and **french**, for relation extraction task at the sentence level. Each instance is a tuple **(Sentence, entity1, entity2, relation_type)**, where: 
1. **entity1** and **entity2** are named entities of type **Organization (ORG)**, identified by two entity taggers [spaCy](https://spacy.io/) and [Stanford NLP NER](https://stanfordnlp.github.io/CoreNLP/ner.html). 
2. **sentences** are collected from the web by quering search engine APIs.
3. **relation_types** are manually annotated by crowdsourcing using the plateform [Isahit](https://isahit.com/).   

A part of this dataset can be used for research purposes. Commercial use is not allowed as well as third party distribution.

To have access to the dataset, please fill this [form](https://docs.google.com/forms/d/1uR4kude36XSRqrEgg_YafD4lsoJ3HjfY3I0JrimLRTQ/prefill). For further information, please refer to amin@geotrend.fr 
