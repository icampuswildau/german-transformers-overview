# Transformer based language models for the German language

This document is intended to serve as a reference for possible data sources and parametrization for the training 
of [Transformer language models](https://arxiv.org/abs/1706.03762). The focus is set on models which have been 
trained specifically for the German language. Other languages, but also the combination of several languages, 
(_"multilingual"_) are not considered.

As with all machine learning and deep learning systems, the selection of suitable data is the most important basis 
for any further proceeding. Datasets that have been used so far are therefore briefly presented.

The creation of Transformer based Natural Language Processing (NLP) models is based on the generation of a 
general language model (`pre-training`) and the specialization on use cases (`domain specific tasks` aka. 
`fine-tuning`). Both types of models are therefore presented. In some cases, it is worthwhile to further train 
existing models and thus optimize them for individual purposes. The lists available here are meant to provide a basis 
for making a well reasoned decision.

## Table of contents
1. [Readme](README.md)
2. [Pre-Trained models](models_pretraining.md)
3. [Fine-Tuned models](models_finetuning.md)
4. [Datasets for custom training](models_datasets.md)


## When were the lists last updated?
The lists represent the data available from the 01.02.2021.

## How are the models selected?

The vast majority of Transformer training approaches are open source and can be performed by any machine learning 
enthusiast. For this reason it is almost impossible to know on which servers around the globe publicly available 
Transformer models are located.

To cut down the effort of searching for models, the [official list](https://huggingface.co/model) of Hugging Face 
is used as a data basis. With its open source library 
"[Hugging Face Transformers](https://github.com/huggingface/transformers)", the company has created a recognized 
platform for training and documentation of Transformer models. After fundraising, the company was able to acquire 
$15 million and aims to create the "[definitive natural language library](https://techcrunch.com/2019/12/17/hugging-face-raises-15-million-to-build-the-definitive-natural-language-processing-library/)"
(last visited: 2021/02/01).

Queries for models in Hugging Face's list are limited to German models via two methods: Either the model name contains 
the terms `german, deutsch, -de, de-, deu, ger` or the official tags, that can be defined for each model, contain 
these terms. The resulting list is then manually checked and false positives are sorted out.

Despite the restriction to partial terms, it cannot be ruled out that German-language models remain under the radar 
because they do not contain any indication of their classification.

Models that are optimized for several languages at the same time (_"multilingual"_) are currently not considered 
since optimizations for the German language are unlikely.

## What do the symbols (?, *, "") in the tables represent?

Whenever the symbol `*` appears in one of the tables, the given information was not explicitly mentioned in the 
description, but can be retrieved by investigation. For example, if an author writes something like 
_"We have used the same configuration as model FOO"_ or if a quick peek into one of the associated configuration 
files allows a statement to be made.

If `?` appears, then there is no way to determine this information without the help of the model creator.

In case you see something written in quotation marks (`""`) it is a quote from the documentation.
Quotations are mainly used when the author of a model uses an informal spelling.

## What sources are used?
Primarily the description, which is supplied in form of a `README` file. In addition, the model files 
(e.g. `config.json`, `vocab.txt`, ...) are analysed.
`Papers`, `Blogs` and other `publications` are also used when available.


## Acknowledgment
This project is a collaboration between [Technical University of Applied Sciences Wildau (TH Wildau)](https://en.th-wildau.de/) and [sense.ai.tion GmbH](https://senseaition.com/).
You can contact us via:
* [Philipp Müller (M.Eng.)](mailto:philipp.mueller@th-wildau.de); Author
* [Prof. Dr. Janett Mohnke](mailto:janett.mohnke@th-wildau.de); TH Wildau
* [Dr. Matthias Boldt, Jörg Oehmichen](mailto:info@SenseAItion.com); sense.AI.tion GmbH 


This project was funded by the European Regional Development Fund (EFRE) and the State of Brandenburg. Project/Vorhaben: "ProFIT: Natürlichsprachliche Dialogassistenten in der Pflege".

<img src="docs/EFRE Logo_rechts_oweb_en_rgb.jpg" alt="Logo of European Regional Development Fund (EFRE)" width="200" />

