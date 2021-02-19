# Corpora and Datasets for pre-training
The following table presents the datasets used by one or multiple pre-trained German models. 

Note: It is not guaranteed that the corpora are used exactly as seen here.
Often the data is filtered, preprocessed, or even sampled multiple times.

|                                      Corpus                                     |               approx. size               |                                                 characteristics                                                |
|:-------------------------------------------------------------------------------:|:----------------------------------------:|:--------------------------------------------------------------------------------------------------------------:|
| [CCNet](https://github.com/facebookresearch/cc_net)                             |    ? <br> (smaller than Common Crawl)    | - based on CommonCrawl with filtering (deduplication, language, perplexity)                                    |
| [Common Crawl](https://www.projekt-gutenberg.org/index.html)                    |        ? <br> (larger than OSCAR)        | - texts crawled from web (for many languages) <br> - gigantic size                                             |
| [Deutsches Textarchiv Korpus](https://www.deutschestextarchiv.de/download)      |                  2.5 GB                  | - texts from 16th to 20th century                                                                              |
| [EU Bookshop](http://opus.nlpl.eu/EUbookshop.php)                               |                   21 GB                  | - officially released documents from the European Union                                                        |
| [Europeana Newspapers](http://www.europeana-newspapers.eu/)                     |                   51 GB                  | - headlines, articles, advertisements, and opinion pieces  from European newspapers between 1618 to 1996       |
| [OSCAR Corpus](https://oscar-corpus.com/)                                       | 308 GB <br> (145 GB after deduplication) | - based on CommonCrawl with filtering (i.e. language)                                                          |
| [OpenLegalData](https://de.openlegaldata.io/pages/api/)                         |                  2.4 GB                  | - legal texts and verdicts                                                                                     |
| [OpenSubtitles](http://opus.nlpl.eu/OpenSubtitles2018.php)                      |                  1.3 GB                  | - tv show and movie subtitles                                                                                  |
| [ParaCrawl](https://paracrawl.eu/)                                              |                  7.7 GB                  | - web texts (for many languages)                                                                               |
| [Project Gutenberg](http://gutenberg.org)                                       |                     ?                    | - classical literature from the last centuries <br> - Note: german IPs blocked due to court order (copyright)  |
| [Projekt Gutenberg](https://www.projekt-gutenberg.org/index.html)               |                     ?                    | - classical literature from the last centuries <br> - payment required <br> - not related to Project Gutenberg |
| [WMT Crawl](http://data.statmt.org/news-crawl/de/)                              |                  16.4 GB                 | - news texts from the past few years <br> - originally created for translation fine-tuning                     |
| [Wikipedia](https://de.wikipedia.org/wiki/Wikipedia:Technik/Datenbank/Download) |                   6 GB                   | - wikipedia as know                                                                                            |

In addition to these datasets, which are used in the models previously presented, there are other 
corpora that have already been listed by other teams and are linked below:
 - [adbar/German-NLP](https://github.com/adbar/German-NLP)
   - The most comprehensive list on NLP for German (corpora, fine-tuning datasets, speech, models, tools, standards)
 - [Association for Computional Linguistics](https://aclweb.org/aclwiki/Resources_for_German)
   - a double-digit number of corpora and fine-tuning datasets 
 - [German Political Speeches Corpus](http://adrien.barbaresi.eu/corpora/speeches/#description)
   - political speeches starting in the 1990s
 - [HGC](https://www.ims.uni-stuttgart.de/en/research/resources/corpora/hgc/)
   - newspapers and law texts (but due to copyright not available)
 - [Humboldt University Berlin](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/links/korpora_links#deutsch)
   - showing 6 corpora for German but some multilingual and other languages, too
 - [Lionbridge](https://lionbridge.ai/datasets/20-best-german-language-datasets-for-machine-learning/)
   - presenting 20 corpora, some usable for fine-tuning, too
 - [One Million Posts Corpus](https://ofai.github.io/million-post-corpus/)
   - A small portion of this data (approx. 11000 posts) has been annotated and evaluated for sentiment.
     Usable for classification and sentiment detection.
 - [OPUS](http://opus.nlpl.eu/)
   - many different datasets, usable for pre-training and fine-tuning with focus on parallel translations between 
   multiple languages; also suitable for creating own datasets through the search interface 
 - [University Bologna](https://corpora.dipintra.it/)
   - released (de)WaCky, EPIC, Bulletin and GeLeCo for German; accessible via a custom corpus management tool
 - [University Giessen](https://www.uni-giessen.de/fbz/zmi/das-zmi/digitalhumanities/corpora)
   - list of more than 20 corpora and lexical resources; brief contents insights given
 - [University Hamburg](https://corpora.uni-hamburg.de/hzsk/en/repository-search?textQuery=&facetQuery=subjectLanguageNameOriginal%3A"German")
   - currently 21 hits related to German corpora; written and spoken; usage may be restricted
 - [Wikipedia Monolingual Corpora](https://linguatools.org/tools/corpora/wikipedia-monolingual-corpora/)
   - wiki texts with annotations like paragraph boundaries and categories
 - [Wortschatz Uni Leipzig](https://wortschatz.uni-leipzig.de/de/download/german)
   - news, web and wikipedia texts from the last few years

# Corpora and Datasets for fine-tuning
The following table shows the datasets used by one or multiple fine-tuned German models. 

Note: It is not guaranteed that the datasets are used exactly as seen here. Often the data is filtered or preprocessed.

|                                                        Dataset                                                       |   Size (approx.)   |                                                       Characteristics                                                      |
|:--------------------------------------------------------------------------------------------------------------------:|:------------------:|:--------------------------------------------------------------------------------------------------------------------------:|
| [10kGNAD](https://tblock.github.io/10kGNAD/)                                                                         | 10.000 sentences   | - Classification                                                                                                           |
| [CoNLL 2003](https://www.aclweb.org/anthology/W03-0419.pdf)                                                          | 310.000 tokens     | - Named Entity Recognition                                                                                                 |
| [DROC](https://gitlab2.informatik.uni-wuerzburg.de/kallimachos/DROC-Release)                                         | 390.000 tokens     | - Named Entity Recognition, Coreferences, Direct Speech, Speaker and Addressees (for direct speech)                        |
| [Fine-grained Named Entity Recognition in Legal Documents](https://github.com/elenanereiss/Legal-Entity-Recognition) | 2.100.000 tokens   | - Named Entity Recognition                                                                                                 |
| [German STSbenchmark](https://github.com/t-systems-on-site-services-gmbh/german-STSbenchmark)                        | 8.600 sentences    | - Semantic Textual Similarity <br> - based on english STSbenchmark which was auto translated by deepL and Amazon Translate |
| [GermEval 2014](https://sites.google.com/site/germeval2014ner/data)                                                  | 590.000 tokens     | - Named Entity Recognition                                                                                                 |
| [GermEval 2017](https://sites.google.com/view/germeval2017-absa/home)                                                | 22.000 sentences   | - Classification, Polarity, Extraction                                                                                     |
| [GermEval 2018](https://projects.fzai.h-da.de/iggsa/)                                                                | 8.5000 sentences   | - Classification                                                                                                           |
| [IWG_hatespeech_public](https://github.com/UCSM-DUE/IWG_hatespeech_public)                                           | 470 sentences      | - Classification <br>                                                                                                      |
| [LFT (Dr Friedrich Temann Library)](https://www.google.com/search?q=LFT+friedrich+temann+dataset)                    | 87.000 tokens      | - Named Entity Recognition <br> - download link not found                                                                  |
| [MLQA](https://github.com/facebookresearch/MLQA)                                                                     | 5000 pairs         | - Question Answering <br> - dataset contains samples for seven languages - usable for cross language question answering    |
| [ONB (Austrian National Library](https://www.google.com/search?q=ONB+austrian+national+library+dataset)              | 35.500 tokens      | - Named Entity Recognition <br> - download link not found                                                                  |
| [PAWS-X](https://github.com/google-research-datasets/paws/tree/master/pawsx)                                         | 53.800 pairs       | - Paraphrase Detection <br> - dataset contains samples for six langugages                                                  |
| [PotTS](https://github.com/WladimirSidorenko/PotTS)                                                                  | 8000 sentences     | - Classification, Sentiment Detection <br>                                                                                 |
| [SB10k](https://spinningbytes.com/announcement/release-of-sentiment-corpus-deutsch-sb-10k/)                          | 9800 sentences     | - Classification, Sentiment Detection <br> - not downloadable anymore                                                      |
| [SCARE](https://www.romanklinger.de/scare/)                                                                          | 1760 sentences     | - Classification, Sentiment Detection                                                                                      |
| [WMT](http://www.statmt.org/wmt19/)                                                                                  | ? <br> (thousands) | - Translation, Classification <br> - The link is referencing WMT 19 but the other ones are given on the website as well    |

Note: The model oliverguhr/german-sentiment-bert (see [here](models_finetuning.md)) refers to datasets named 
`Emotions, Filmstarts, holidaycheck` and `leipzig-wikipedia`. The first three data sets were generated by the authors 
themselves and have not yet been scientifically verified or reused in other models. Last one, `leipzig-wikipedia`,
is taken from [Wortschatz Uni Leipzig](https://wortschatz.uni-leipzig.de/de/download/german) and contains news
texts. So far, it has not been used as a fine-tuning task by any other model.

<hr style="border:2px solid gray"> </hr>

## Navigation:
0. [Readme](README.md)
1. [Pre-Trained models](models_pretraining.md)
2. [Fine-Tuned models](models_finetuning.md)
3. [Datasets for custom training](models_datasets.md)
