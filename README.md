
<div align="center">
  <h1>Awesome Datasets</h1>
</div>

We're collecting (an admittedly opinionated) list of data annotated datasets in high quality. Most of the data sets listed below are free, however, some are not. They are classified by use case.

*We're only at the beginning, and you can help by contributing to this GitHub!*

<!-- omit in toc -->
## How Can I Help?

If you're interested in this area and would like to hear more, join our [Slack community (coming soon)](#)! We'd also appreciate if you could fill out this short [form (coming soon)](#) to help us better understand what your interests might be.

<!-- omit in toc -->
### Feedback

If you have ideas on how we can make this repository better, feel free to submit an issue with suggestions.

<!-- omit in toc -->
### Contributing

We want this resource to grow with contributions from readers and data enthusiasts. If you'd like to make contributions to this Github repository, please read our contributing guidelines.

<!-- omit in toc -->
# Table of Content

- [Document processing](#document-processing)
  - [Document Classification](#document-classification)
    - [English](#english)
  - [Key Information Extraction](#key-information-extraction)
    - [English](#english-1)
    - [Multilingual](#multilingual)
  - [Optical Character Recognition](#optical-character-recognition)
    - [English](#english-2)
  - [Document Layout Analysis](#document-layout-analysis)
    - [English](#english-3)
    - [Japanese](#japanese)
  - [Document Question Answering](#document-question-answering)
    - [English](#english-4)
- [Natural Language Processing](#natural-language-processing)
  - [Named-Entity Recognition](#named-entity-recognition)
    - [English](#english-5)
      - [Defense](#defense)
      - [Finance](#finance)
      - [Medical](#medical)
      - [News](#news)
      - [Queries](#queries)
      - [Social media](#social-media)
      - [Technology](#technology)
      - [Twitter](#twitter)
      - [Various](#various)
      - [Wikipedia](#wikipedia)
    - [French](#french)
      - [Medical](#medical-1)
      - [News](#news-1)
      - [Twitter](#twitter-1)
      - [Various](#various-1)
      - [Wikipedia](#wikipedia-1)
  - [Relation Extraction](#relation-extraction)

# Document processing

Documents are an essential part of many businesses in many fields such as law, finance and technology, among others. Automatic processing of documents such as invoices, contracts and resumes is lucrative and opens up many new business avenues. The fields of natural language processing and computer vision have seen considerable progress with the development of deep learning, so these methods have begun to be incorporated into contemporary document understanding systems.

Here is a curated list of datasets for intelligent document processing.

## Document Classification

### English

- [GHEGA](https://media.springernature.com/lw685/springer-static/image/chp%3A10.1007%2F978-3-030-57058-3_28/MediaObjects/493083_1_En_28_Fig1_HTML.png) contains two groups of documents: 110 data-sheets of electronic components and 136 patents. Each group is further divided in classes: data-sheets classes share the component type and producer; patents classes share the patent source.
  <details>
    <summary><i>Preview</i></summary>
    <img src="./images/GHEGA.jpeg" />
  </details>

- [RVL-CDIP Dataset](https://www.cs.cmu.edu/~aharley/rvl-cdip/) The RVL-CDIP dataset consists of 400,000 grayscale images in 16 classes (letter, memo, email, file folder, form, handwritten, invoice, advertisement, budget, news article, presentation, scientific publication, questionnaire, resume, scientific report, specification), with 25,000 images per class.
  <details>
    <summary><i>Preview</i></summary>
    <img src="https://production-media.paperswithcode.com/datasets/RVL-CDIP-0000000502-f579eaab_GQ7QoTc.jpg" />
  </details>

## Key Information Extraction

### English

- [CORD](https://github.com/clovaai/cord) The dataset consists of thousands of Indonesian receipts, which contains images and box/text annotations for OCR, and multi-level semantic labels for parsing. Labels are the bouding box position and the text of the key informations.
  <details>
    <summary><i>Preview</i></summary>
    <img src="https://guillaumejaume.github.io/FUNSD/img/two_forms.png" />
  </details>


- [FUNSD](https://guillaumejaume.github.io/FUNSD/) A dataset for Text Detection, Optical Character Recognition, Spatial Layout Analysis and Form Understanding. Its consists of 199 fully annotated forms, 31485 words, 9707 semantic entities, 5304 relations.
  <details>
    <summary><i>Preview</i></summary>
    <img src="https://github.com/clovaai/cord/raw/master/figure/sample.png" />
  </details>

- [NIST](https://www.nist.gov/srd/nist-special-database-2) The NIST Structured Forms Database consists of 5,590 pages of binary, black-and-white images of synthesized documents: 900 simulated tax submissions, 5,590 images of completed structured form faces, 5,590 text files containing entry field answers.
  <details>
    <summary><i>Preview</i></summary>
    <img src="https://www.nist.gov/sites/default/files/styles/2800_x_2800_limit/public/images/2019/04/27/sd2.jpg" />
  </details>

- [SROIE](https://drive.google.com/open?id=1ShItNWXyiY1tFDM5W02bceHuJjyeeJl2) Consists of a dataset with 1000 whole scanned receipt images and annotations for the competition on scanned receipts OCR and key information extraction (SROIE). Labels are the bouding box position and the text of the key informations.
  <details>
    <summary><i>Preview</i></summary>
    <img src="https://production-media.paperswithcode.com/datasets/Screenshot_2021-08-09_at_14.29.44.png" />
  </details>

### Multilingual

- [GHEGA](https://media.springernature.com/lw685/springer-static/image/chp%3A10.1007%2F978-3-030-57058-3_28/MediaObjects/493083_1_En_28_Fig1_HTML.png) contains two groups of documents: 110 data-sheets of electronic components and 136 patents. Each group is further divided in classes: data-sheets classes share the component type and producer; patents classes share the patent source.
  <details>
    <summary><i>Preview</i></summary>
    <img src="./images/GHEGA.jpeg" />
  </details>

- [XFUND](https://github.com/doc-analysis/XFUND) is a multilingual form understanding benchmark dataset that includes human-labeled forms with key-value pairs in 7 languages (Chinese, Japanese, Spanish, French, Italian, German, Portuguese).




## Optical Character Recognition

### English

- [FUNSD](https://guillaumejaume.github.io/FUNSD/) for Text Detection, Optical Character Recognition, Spatial Layout Analysis and Form Understanding. Its consists of 199 fully annotated forms, 31485 words, 9707 semantic entities, 5304 relations.
  <details>
    <summary><i>Preview</i></summary>
    <img src="https://github.com/clovaai/cord/raw/master/figure/sample.png" />
  </details>

- [RDCL2019](https://www.primaresearch.org/RDCL2019/) contains scanned pages from contemporary magazines and technical articles.
  <details>
    <summary><i>Preview</i></summary>
    <img src="./images/RDCL2019.png" />
  </details>

- [SROIE](https://drive.google.com/open?id=1ShItNWXyiY1tFDM5W02bceHuJjyeeJl2) consists of a dataset with 1000 whole scanned receipt images and annotations for the competition on scanned receipts OCR and key information extraction (SROIE). Labels are the bouding box position and the text of the key informations.
  <details>
    <summary><i>Preview</i></summary>
    <img src="https://production-media.paperswithcode.com/datasets/Screenshot_2021-08-09_at_14.29.44.png" />
  </details>

- [Synth90k](https://www.robots.ox.ac.uk/~vgg/data/text/#sec-synth) consists of 9 million images covering 90k English words.
  <details>
    <summary><i>Preview</i></summary>
    <img src="https://www.robots.ox.ac.uk/~vgg/data/text/synthflow.png" />
  </details>

- [Total Text Dataset](https://github.com/cs-chan/Total-Text-Dataset) consists of 1555 images with more than 3 different text orientations: Horizontal, Multi-Oriented, and Curved, one of a kind.
  <details>
    <summary><i>Preview</i></summary>
    <img src="https://github.com/cs-chan/Total-Text-Dataset/raw/master/ttstatistics.png" />
  </details>

## Document Layout Analysis

### English

- [DocBank](https://doc-analysis.github.io/docbank-page/index.html) includes 500K document pages, with 12 types of semantic units: abstract, author, caption, date, equation, figure, footer, list, paragraph, reference, section, table, title.
  <details>
    <summary><i>Preview</i></summary>
    <img src="./images/DocBank.png" />
  </details>

- [Layout Analysis Dataset](http://www.primaresearch.org/datasets/Layout_Analysis) contains realistic documents with a wide variety of layouts, reflecting the various challenges in layout analysis. Particular emphasis is placed on magazines and technical/scientific publications which are likely to be the focus of digitisation efforts.
  <details>
    <summary><i>Preview</i></summary>
    <img src="http://www.primaresearch.org/www/media/datasets/Layout_Analysis.png" />
  </details>

- [PubLayNet](https://github.com/ibm-aur-nlp/PubLayNet) is a large dataset of document images, of which the layout is annotated with both bounding boxes and polygonal segmentations.
  <details>
    <summary><i>Preview</i></summary>
    <img src="./images/PubLayNet.png" />
  </details>

- [TableBank](https://doc-analysis.github.io/tablebank-page/index.html) is a new image-based table detection and recognition dataset built with novel weak supervision from Word and Latex documents on the internet, contains 417K high-quality labeled tables.
  <details>
    <summary><i>Preview</i></summary>
    <img src="./images/TableBank.png" />
  </details>

### Japanese

- <p><a href="https://github.com/dell-research-harvard/HJDataset">HJDataset</a> contains over 250,000 layout element annotations of seven types. In addition to bounding boxes and masks of the content regions, it also includes the hierarchical structures and reading orders for layout elements for advanced analysis.</p>
  <details>
    <summary><i>Preview</i></summary>
    <img src="./images/HJDataset.png" />
  </details>

## Document Question Answering

### English

- <p><a href="https://www.docvqa.org/">DocVQA</a> contains 50 K questions and 12K Images in the dataset. Images are collected from UCSF Industry Documents Library. Questions and answers are manually annotated.</p>
  <details>
    <summary><i>Preview</i></summary>
    <img src="https://icdar2021.org/wp-content/uploads/docvqa_img.png" />
  </details>

# Natural Language Processing

## Named-Entity Recognition

Named-entity recognition (NER) (also known as (named) entity identification, entity chunking, and entity extraction) is a subtask of information extraction that seeks to locate and classify named entities mentioned in unstructured text into pre-defined categories such as person names, organizations, locations, medical codes, time expressions, quantities, monetary values, percentages, etc.

State-of-the-art NER systems for English produce near-human performance. For example, the best system entering MUC-7 scored 93.39% of F-measure while human annotators scored 97.60% and 96.95%.

### English

#### Defense

- [re3d](https://github.com/juand-r/entity-recognition-datasets/tree/master/data/re3d) focuses on entity and relationship extraction relevant to somebody operating in the role of a defence and security intelligence analyst.
  <details>
    <summary><i>Preview</i></summary>
    <img src="./images/re3d.png" />
  </details>

- [Malware](http://www.statnlp.org/paper/malwaretextdb-a-database-for-annotated-malware-articles.html) consists of texts about malware. It was developed by researchers at the Singapore University of Technology and Design and DSO National Laboratories.
  <details>
    <summary><i>Preview</i></summary>
    <img src="./images/Malware.png" />
  </details>

#### Finance

- [SEC-filings](https://github.com/juand-r/entity-recognition-datasets/tree/master/data/SEC-filings) is generated using CoNll2003 data and financial documents obtained from U.S. Security and Exchange Commission (SEC) filings.

#### Medical

- [AnEM](http://www.nactem.ac.uk/anatomy/data/AnEM-1.0.4.tar.gz) consists of abstracts and full-text biomedical papers.
- [CADEC](https://github.com/juand-r/entity-recognition-datasets/tree/master/data/CADEC) is a corpus of adverse drug event annotations.
- [i2b2-2006](https://github.com/juand-r/entity-recognition-datasets/tree/master/data/i2b2_2006) is the Deidentification and Smoking Challenge dataset.
- [i2b2-2014](https://github.com/juand-r/entity-recognition-datasets/tree/master/data/i2b2_2014) is the 2014 De-identification and Heart Disease Risk Factors Challenge.

#### News

- [CONLL 2003](https://deepai.org/dataset/conll-2003-english) is an annotated dataset for Named Entity Recognition. The tokens are labeled under one of the 9 possible tags.
- [MUC-6](https://catalog.ldc.upenn.edu/LDC2003T13) contains the 318 annotated Wall Street Journal articles, the scoring software and the corresponding documentation used in the MUC6 evaluation.
- [NIST-IEER](https://raw.githubusercontent.com/nltk/nltk_data/gh-pages/packages/corpora/ieer.zip)

#### Queries

- [MITMovie](https://github.com/juand-r/entity-recognition-datasets/tree/master/data/MITMovieCorpus) is a semantically tagged training and test corpus in BIO format.
- [MITRestaurant](https://github.com/juand-r/entity-recognition-datasets/tree/master/data/MITRestaurantCorpus) is a semantically tagged training and test corpus in BIO format.

#### Social media	

- [WNUT17](http://noisy-text.github.io/2017/emerging-rare-entities.html) is the dataset for the WNUT 17 Emerging Entities task. It contains text from Twitter, Stack Overflow responses, YouTube comments, and Reddit comments.

#### Technology

- [Assembly](https://github.com/carlosmccosta/Assembly-Named-Entity-Recognition-Dataset/tree/master/dataset) is a dataset for Named Entity Recognition (NER) from assembly operations text manuals.

#### Twitter

- [BTC](https://github.com/juand-r/entity-recognition-datasets/tree/master/data/BTC) is the Broad Twitter corpus, a dataset of tweets collected over stratified times, places and social uses.
- [Ritter](https://github.com/juand-r/entity-recognition-datasets/tree/master/data/Ritter) is the same as the training portion of WNUT16 (though with sentences in a different order).

#### Various

- [BBN](https://catalog.ldc.upenn.edu/LDC2005T33) contains approximately 24,000 pronoun coreferences as well as entity and numeric annotation for approximately 2,300 documents.
- [Groningen Meaning Bank (GMB)](https://gmb.let.rug.nl/data.php) comprises thousands of texts in raw and tokenised format, tags for part of speech, named entities and lexical categories, and discourse representation structures compatible with first-order logic.
- [OntoNotes 5](https://catalog.ldc.upenn.edu/LDC2013T19) is a large corpus comprising various genres of text (news, conversational telephone speech, weblogs, usenet newsgroups, broadcast, talk shows) in three languages (English, Chinese, and Arabic) with structural information (syntax and predicate argument structure) and shallow semantics (word sense linked to an ontology and coreference).

#### Wikipedia

- [GUM-3.1.0](https://github.com/amir-zeldes/gum) is the Georgetown University Multilayer Corpus.
- [wikigold](https://github.com/juand-r/entity-recognition-datasets/tree/master/data/wikigold) is a manually annotated collection of Wikipedia text.
- [WikiNEuRal](https://github.com/Babelscape/wikineural) is a high-quality automatically-generated dataset for Multilingual Named Entity Recognition.

### French

#### Medical

- [QUAERO French Medical Corpus](https://quaerofrenchmed.limsi.fr/) has been initially developed as a resource for named entity recognition and normalization.

#### News

- [ESTER](http://catalogue.elra.info/en-us/repository/browse/ELRA-S0241/) contains 100 hours of orthographically transcribed news broadcast, including annotations of named entities.
- [ESTER 2](http://catalogue.elra.info/en-us/repository/browse/ELRA-S0338/) contains a manually transcribed radio broadcast news corpus amounting about 100 hours.
- [Europeana Newspapers (Dutch, French, German)](https://github.com/EuropeanaNewspapers/ner-corpora) is a Named Entity Recognition corpora for Dutch, French, German from Europeana Newspapers.
- [Quaero Broadcast News Extended Named Entity Corpus](http://catalog.elra.info/en-us/repository/browse/ELRA-S0349/) is fully manually annotated according to the Quaero extended and structured named entity definition, which differentiates entity "types" and "components".
- [Quaero Old Press Extended Named Entity corpus](http://catalog.elra.info/en-us/repository/browse/ELRA-W0073/) is fully manually annotated according to the Quaero extended and structured named entity definition, which differentiates entity "types" and "components".

#### Twitter

- [CAp 2017 - (Twitter data)](http://cap2017.imag.fr/competition.html) concerns the problem of Named Entity Recognition (NER) for tweets written in French.

#### Various

- [ETAPE](http://catalogue.elra.info/en-us/repository/browse/ELRA-E0046/) consists of ca. 30 hours of French radio and TV data, selected to include mostly non planned speech and a reasonable proportion of multiple speaker data. All data were carefully transcribed, including named entity annotation.

#### Wikipedia

- [DBpedia abstract corpus](http://downloads.dbpedia.org/2015-04/ext/nlp/abstracts/) contains a conversion of Wikipedia abstracts in seven languages (dutch, english, french, german, italian, japanese and spanish) into the NLP Interchange Format (NIF).
- [DAWT dataset](https://github.com/klout/opendata/tree/master/wiki_annotation) is the Densely Annotated Wikipedia Texts across multiple languages.
- [WikiNER](https://figshare.com/articles/Learning_multilingual_named_entity_recognition_from_Wikipedia/5462500) is a multilingual named entity recognition dataset from Wikipedia.
- [WikiNEuRal](https://github.com/Babelscape/wikineural) is a high-quality automatically-generated dataset for Multilingual Named Entity Recognition.

## Relation Extraction

Coming soon! 😘