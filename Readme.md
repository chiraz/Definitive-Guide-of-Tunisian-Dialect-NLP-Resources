## Introduction

The Tunisian dialect is an under-resourced language. This project is a personal effort to put scattered sources of information, 
resources, and tools related to automated processing of text written in the Tunisian dialect in one place for all to use. 

Hopefully it will save NLP practitioners valuable time spent otherwise chasing after information scattered all over the Web.

I have categorized this information into the following categories:

1. Publicly Available Corpora and Lexicons
2. NLP Software
3. Scientific Papers and Articles
4. Books
5. Web Articles & Links


If you would like to contribute or add your own listing, please either send a git pull request or email me at chiraz.benabdelkader@gmail.com



## Publicly Available Corpora and Lexicons

- The MADAR Arabic Dialect Corpus and Lexicon, H. Bouamor et al., http://nlp.qatar.cmu.edu/madar/
    "The latest version of the lexicon is available for browsing online."

- Tunisian Arabic Corpus, by Karen McNeil and Miled Faiza, http://www.tunisiya.org
	"There are currently 2,006 texts in the corpus, comprising 881,964 words.
	The main categories currently included are 
	1) traditional written sources (folklore, songs, folk poetry, proverb collections, screenplays)
	2) new written sources (blogs, email, Facebook, forum postings) -- currently the dominant source
	3) transcribed audio (e.g. from radio programming)."
	"The corpus is available freely online at tunisiya.org, where users can perform complex concordance 
	searches and view search results in context, with access to the full text. "

- DID-LREC-2018: Training and test data for the Arabic dialect identification (DID) shared task at LREC 2018, https://github.com/drelhaj/ArabicDialects/tree/master/ArabicSharedTask

- AOC: Arabic online commentary dataset, https://github.com/sjeblee/AOC
  "The AOC dataset was created by crawling the websites of three Arabic newspapers,
  and extracting online articles and readers' comments.  The readers' comments are
  arguably more "interesting", which is why we call this the *commentary* dataset,
  but the articles themselves are also included."

- TSAC: Tunisian sentiment analysis corpus, https://github.com/fbougares/TSAC
  "About 17k user comments manually annotated to positive and negative polarities. 
  This corpus is collected from Facebook users comments written on official pages 
  of Tunisian radios and TV channels namely Mosaique FM, JawhraFM, Shemes FM, 
  HiwarElttounsi TV and Nessma TV. The corpus is collected from a period spanning 
  January 2015 until June 2016."

- CODA Seed Lexicon, https://sites.google.com/a/nyu.edu/coda/dialect-specific


## NLP Software

### Open-source

- FARASA toolkit, http://qatsdemo.cloudapp.net/farasa/
  "Farasa (which means “insight” in Arabic), is a fast and accurate text processing toolkit for Arabic text. 
  Farasa consists of the segmentation/tokenization module, POS tagger, Arabic text Diacritizer, and Dependency Parser. 
  We measure the performance of the segmenter in terms of accuracy and efficiency, in two NLP tasks, namely Machine Translation (MT) 
  and Information Retrieval (IR). Farasa outperforms or equalizes state-of-the-art Arabic segmenters (Stanford and MADAMIRA), 
  while being more than one order of magnitude faster."


- BAMA morphological analyzer

- CODA (Conventional Orthography for Dialectal Arabic), https://sites.google.com/a/nyu.edu/coda/

### Free online demo-only tools

- ADIDA: Automatic Dialect Identification for Arabic, https://adida.abudhabi.nyu.edu/
 "This interface is a demo of the MADAR project dialect identification system developed by Salameh, Bouamor and Habash (2018).
  The system is able to distinguish amongst 25 cities (from Rabat to Muscat) in addition to Modern Standard Arabic.
  To use the demo enter text in Standard or Dialectal Arabic. The cities and regions that our system identifies will be lit up.
  The ADIDA web interface is described in the paper by Obeid, Salameh, Bouamor and Habash (2019). "

- Farasa demo version, http://qatsdemo.cloudapp.net/farasa/demo.html


### Commercial tools & resources

- Ramitechs (http://www.ramitechs.com/) , a company that creates and annotates several types of corpora and lexicons using expert linguists.



## Scientific Papers and Articles


### General survey papers

- S. Harrat, K. Meftouh, K. Smaıli, "Maghrebi Arabic dialect processing: an overview",
in International Conference on Natural Language, Signal and Speech Processing (ICNLSSP), 2017
Index Terms: Arabic dialect, Maghrebi Arabic dialects, Tunisian Arabic, Algerian Arabic, Moroccan Arabic, survey paper

- Abdulhadi Shoufan and Sumaya Al-Ameri, "Natural Language Processing for Dialectical Arabic: A Survey", 
in Proceedings of the Second Workshop on Arabic Natural Language Processing, pages 36–48, 2015

- Kareem Darwich and Walid Magdy, "Arabic Information Retrieval", in Foundations and Trends in Information Retrieval, 2014



### Construction of corpora and linguistic resources

- Houda Bouamor, Nizar Habash,y Mohammad Salameh, Wajdi Zaghouani, Owen Rambow, Dana Abdulrahim, Ossama Obeid, 
Salam Khalifa, Fadhl Eryani, Alexander Erdmann, Kemal Oflazer, "The MADAR Arabic Dialect Corpus and Lexicon", 
In Proceedings of the International Conference on Language Resources and Evaluation (LREC), 2018

- W. Zaghouani and A. Charfi, "ArapTweet: A Large Multi-Dialect Twitter Corpus for Gender, Age and Language Variety Identification",
In Proceedings of the International Conference on Language Resources and Evaluation (LREC), 2018.

- Jihene Younes and Emna Souissi, "A quantitative view of Tunisian dialect electronic writing", 2015.
  Index terms:  dialect, Tunisian, corpus, language, electronic writing, translation, normalization
	"This paper focuses specifically on electronic writing with Latin letters in Tunisian dialect. 
	We describe the methodology used for the construction of a dialectal corpus, 
	present the characteristics of this new form of writing and detail its peculiarities with numbers.
	The built corpus, consisting of 43222 messages."
	"We showed that over 60% of the extracted messages are written in Latin letters, 64% of which
	contain Tunisian dialect words ... and the majority of words containing numbers are in dialect."
	"it would be interesting to make an automatic identification tool for the words written in dialect using the
	Latin alphabet and then proceed to either its translation or normalization. "

- I. Zribi, M. Ellouze, L. H. Belguith, and P. Blache, “Spoken Tunisian Arabic corpus” STAC”: Transcription and annotation.”
In Research in Computing Science, vol. 90, pp. 123–135, 2015
  "transcribed 5 hours of spontaneous Tunisian Arabic speech enriched with morpho-syntactic and disfluencies annotations."

- Jihene Younes, Hadhemi Achour and Emna Souissi, "Constructing linguistic resources for the Tunisian dialect using textual user-generated content on the social web", 
In Proceedings of the 1st International Workshop on Natural Language Processing for Informal Text (NLPIT), pp. 3-14, 2015.

- J. Younes, H. Achour, and E. Souissi, "Constructing Linguistic Resources for the Tunisian Dialect Using Textual User-Generated Contents on the Social Web",
In Cham: Springer International Publishing, pp. 3–14, 2015.
	"The authors extracted textual user-generated content from social networks that they filtered and classified 
	automatically. From the built corpora they drew a picture of the main features related to the Tunisian dialect."

- A. Masmoudi, Y. Esteve, M. E. Khmekhem, F. Bougares, and L. H. Belguith, “Phonetic tool for the Tunisian Arabic,” 
In Spoken Language Technologies for Under-Resourced Languages, 2014.
	"The authors generated automatically phonetic dictionaries for the Tunisian dialect by using a rules-based approach. 
	The work is part of an automatic speech recognition framework for  Tunisian Arabic in the field of railway transport."

- A. Hamdi, N. Gala, and A. Nasr, “Automatically building a Tunisian lexicon for deverbal nouns,” in Proceedings of the First
In Workshop on Applying NLP Tools to Similar Languages, Varieties and Dialects, pp. 95–102, 2014.
	"The authors presented a bilingual lexicon of deverbal nouns between MSA and Tunisian dialect that has been created automatically. 
	They extended an existing Tunisian verbal lexicon by using a table of  deverbal patterns in order to generate pairs of Tunisian and MSA deverbal nouns."

- Rihab Bouchlaghem and Aymen Elkhlifi, "Tunisian dialect Wordnet creation and enrichment using web resources and other Wordnets", 2014.
	"we propose TunDiaWN (Tunisian dialect Wordnet) a lexical resource for the dialect language spoken in Tunisia. 
	Our TunDiaWN construction approach is founded, in one hand, on a corpus based method to analyze and extract Tunisian dialect words. 
	A CLUSTERING technique is adapted and applied to mine the possible relations existing between the Tunisian dialect extracted words and
	to group them into meaningful groups."

- Ryan Cotterell and Chris Callison-Burch, "A Multi-Dialect, Multi-Genre Corpus of Informal Written Arabic", 
In Proceedings of the International Conference on Language Resources and Evaluation (LREC), 2014.

- J. Karoui, M. Graja, M. Boudabous, and L. H. Belguith, “Domain ontology construction from a Tunisian spoken dialogue corpus,”
In International Conference on Web and Information Technologies, ICWIT’2013, 2013.
	"This work is related to the construction of a railway domain ontology from a Tunisian speech corpus. The authors used a
	statistical method for term and concept extraction whereas for semantic relation extraction they choose a linguistic approach."

- I. Zribi, M. E. Khemakhem, and L. H. Belguith, “Morphological analysis of Tunisian dialect,” 
In International Joint Conference on Natural Language Processing, pp. 992–996, 2013.
	"proposes a morphological analyzer for the Tunisian dialect based on a MSA  morphological analyzer, 
	as well as a lexicon for the Tunisian dialect as an expansion of an exisiting MSA lexicon."

- O. F. Zaidan and C. Callison-Burch, “The Arabic online commentary (AOC) dataset: an annotated dataset of informal arabic with high dialectal content,” 
In Proceedings of the Association for Computational Linguistics, Portland, Oregon, USA, 2011.
	"a small portion of this corpus contains Tunisian dialect text ..."



### Transcription of dialectal speech

- I. Zribi, M. Ellouze, L. H. Belguith, and P. Blache, “Spoken Tunisian Arabic corpus” STAC”: Transcription and annotation.”
In Research in Computing Science, vol. 90, pp. 123–135, 2015.
	"transcribed 5 hours of spontaneous Tunisian Arabic speech enriched with morpho-syntactic and disfluencies annotations."


### Orthography (standard rules of writing)

- I. Zribi, R. Boujelbane, A. Masmoudi, M. Ellouze, L. H. Belguith, and N. Habash, “A conventional orthography for Tunisian Arabic.” 
In Proceedings of the International Conference on Language Resources and Evaluation (LREC), pp. 2355–2361, 2014.
	"Adapts the CODA map (Conventional Orthography for Dialectal Arabic) to the Tunisian dialect."

- I. Zribi, M. Graja, M. E. Khmekhem, M. Jaoua, and L. H. Belguith, “Orthographic transcription for spoken Tunisian Arabic,” in
In International Conference on Intelligent Text Processing and Computational Linguistics. Springer, pp. 153–163, 2013.
	"Presented orthography guidelines for transcribing Tunisian speech corpora based on the standard Arabic transcription conventions."

- N. Habash, M. T. Diab, and O. Rambow, “Conventional orthography for dialectal Arabic.” in Proceedings of the International 
In Conference on Language Resources and Evaluation (LREC), pp. 711–718, 2012.



### Morphological segmentation & analysis

- I. Zribi, M. Ellouze, L. Hadrich-Belguith, and P. Blache, “Morphological disambiguation of Tunisian dialect,” 
In Journal of King Saud University - Computer and Information Sciences, vol. 29, no. 2, pp. 147 – 155, 2017.
	"proposes a method to disambiguate the output of the morphological analyzer of Zribi et al. (2013) by using machine-learning techniques."

- Ahmed Abdelali, Kareem Darwish, Nadir Durrani, Hamdy Mubarak, "A Fast and Furious Segmenter for Arabic",
In Proceedings of NAACL-HLT 2016 (Demonstrations), pages 11–16, 2016.

- Salam Khalifa, Nasser Zalmout and Nizar Habash, "YAMAMA: Yet Another Multi-Dialect Arabic Morphological Analyzer",
In Proceedings of COLING 2016, the 26th International Conference on Computational Linguistics: System Demonstrations, pp. 223–227, 2016.

- A. Hamdi, A. Nasr, N. Habash, and N. Gala, “POS-tagging of Tunisian Dialect Using Standard Arabic Resources and Tools,”
In Workshop on Arabic Natural Language Processing, Beijing, China, pp. 59 – 68, 2015.
	"exploits the closeness between standard Arabic and Tunisian dialect to develop a POS tagger by converting a Tunisian 
	sentence to MSA lattice, followed by a disambiguation step; a MSA target sentence is then produced and tagged simply with a MSA tagger."

- R. Boujelbane, M. Mallek, M. Ellouze, and L. Hadrich-Belguith,  “Fine grained POS tagging of spoken Tunisian dialect corpora,” 
In International Conference on Applications of Natural Language to Data Bases/Information Systems. Springer, pp. 59–62, 2014.
	"uses the lexicon of Zribi et al (2013) to convert a standard Arabic corpus 
	for creating a large Tunisian dialect corpus in order to train a POS tagger."

- I. Zribi, M. E. Khemakhem, and L. Hadrich-Belguith, “Morphological analysis of Tunisian dialect,” 
In International Joint Conference on Natural Language Processing, pp. 992–996, 2013.
	"proposes a morphological analyzer for the Tunisian dialect based on a MSA  morphological analyzer, 
	as well as a lexicon for the Tunisian dialect as an expansion of an exisiting MSA lexicon."

- Karen McNeil, Tunisian Arabic Morphological Parser, Working Paper (?), 2012


### Language identification for Arabic language and its dialects

#### Word-level

- Heba Elfardy and Mona Diab, "Sentence Level Dialect Identification in Arabic", 
In Proceedings of the 51st Annual Meeting of the Association for Computational Linguistics, pages 456–461, 2013

- Ben King and Steven Abney, "Labeling the Languages of Words in Mixed-Language Documents using Weakly Supervised Methods", 
In Proceedings of NAACL-HLT 2013, pages 1110–1119, 2013.

- Heba ElFardy and Mona Diab, "Token Level Identification of Linguistic Code Switching"
In Proceedings of COLING 2012: Posters, pages 287–296, 2012.


#### Sentence-level

- Ossama Obeid, Mohammad Salameh, Houda Bouamor, Nizar Habash, "ADIDA: Automatic Dialect Identification for Arabic", 
In Proceedings of NAACL-HLT 2019: Demonstrations, pages 6–11, 2019

- Mohammad Salameh, Houda Bouamor, Nizar Habash, "Fine-Grained Arabic Dialect Identification", 
In Proceedings of the 27th International Conference on Computational Linguistics, pages 1332–1344, 2018

- Samantha Wray, "Classification of Closely Related Sub-dialects of Arabic Using Support-Vector Machines", 
In Proceedings of the International Conference on Language Resources and Evaluation (LREC), 2018

- Fei Huang, "Improved Arabic Dialect Classification with Social Media Data", in EMNLP, 2015
	"focuses on the classification of MSA (msa) and 3 Arabic dialects: Egyptian (egy), Gulf (gul) and Levantine (lev). See p.4 for more details ..."
	"uses semi-supervised learning as well ..."

- Kareem Darwish, Hassan Sajjad, Hamdy Mubara, "Verifiably Effective Arabic Dialect Identification", 2014
	"classifies Egyptian dialect (ARZ) vs. MSA, using random forests, and using lexical, morphological, and phonological features as classification features"
	"We show that effective dialect identification requires that we account for the distinguishing lexical, morphological, and phonological phenomena of dialects."
	"There seems to be a necessity to identify lexical and linguistic features that discriminate between MSA and different dialects. In this paper, we highlight some such features that help in separating between MSA and ARZ."
	"We identify common ARZ words that do not overlap with MSA and identify specific linguistic phenomena that exist in ARZ, and not MSA, such as morphological patterns, word concatenations, and verb negation constructs"

- Christoph Tillmann, Yaser Al-Onaizan, Saab Mansour, "Improved Sentence-Level Arabic Dialect Classification",
In Proceedings of the First Workshop on Applying NLP Tools to Similar Languages, Varieties and Dialects, pages 110–119, 2014.
	"Extends work of Zaidan and Callison-Burch (2014) and Elfardy and Diab (2013)"

- Omar F. Zaidan and Chris Callison-Burch, "Arabic Dialect Identification", Journal of Computational Linguistics, 2014.


### Sentiment analysis

- S. Medhaffar, F. Bougares, Y. Esteve, and L. Hadrich-Belguith, “Sentiment analysis of Tunisian dialects: Linguistic ressources and experiments,” pp. 55–61, 2017



### Translation approach for handling dialectal Arabic

- F. Sadat, F. Mallek, M. Boudabous, R. Sellami, and A. Farzindar,  “Collaboratively constructed linguistic resources for language variants and their exploitation in nlp application, the case of Tunisian Arabic and the social media,” 
In Proceedings of the Workshop on Lexical and Grammatical Resources for Language Processing, pp. 102–110, 2014.
	"translate Tunisian dialect text of social media into MSA by using a bilingual lexicon and a set of grammatical mapping rules and a disambiguation step."



### Transliterated forms of Arabic dialects; romanized Arabic

- Jihene Younes and Emna Souissi, "A quantitative view of Tunisian dialect electronic writing", 2015.
Index terms:  dialect, Tunisian, corpus, language, electronic writing, translation, normalization
	"This paper focuses specifically on electronic writing with Latin letters in Tunisian dialect. 
	We describe the methodology used for the construction of a dialectal corpus, 
	present the characteristics of this new form of writing and detail its peculiarities with numbers.
	The built corpus, consisting of 43222 messages."



## Books

- Nizar Habash, "Introduction to Arabic Natural Language Processing", https://www.morganclaypool.com/doi/abs/10.2200/s00277ed1v01y201008hlt010, 2010.
  "This book provides system developers and researchers in natural language processing and computational linguistics with the necessary 
  background information for working with the Arabic language."




## Web Articles & Links

- Derja: Tunisian Association of the Tunisian Dialect, http://www.bettounsi.com/index.html

- Tunisian Arabic, Wikipedia entry, https://en.wikipedia.org/wiki/Tunisian_Arabic

- Tunisian Arabic, by Turki, H., Zribi, R., Gibson, M., & Adel, E. , Wikimedia Foundation,  https://www.academia.edu/28846187/Tunisian_Arabic, 2015.

- Tunisian Arabic: A Wonderful Mosaic of Dialects, by Lilia Khachrou, https://lingualism.com/arabic/tunisian-arabic/tunisian-arabic-wonderful-mosaic-dialects/

