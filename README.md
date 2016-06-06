## [Europarl corpus of native, non-native and translated texts - ENNTT](https://github.com/senisioi/enntt-release/releases/latest)
- Please check the [release](https://github.com/senisioi/enntt-release/releases) section for the latest version, also available at the [Center for Computational Linguistics](http://nlp.unibuc.ro/resources.html)
- A complete description of this resource is available [here](http://www.lrec-conf.org/proceedings/lrec2016/summaries/902.html): **A Corpus of Native, Non-native and Translated Texts**, LREC, 2016, [PDF](http://www.lrec-conf.org/proceedings/lrec2016/pdf/902_Paper.pdf)
- For the experiments presented in the ACL 2016 paper, please check the dataset available [here](https://github.com/senisioi/enntt-release/releases/download/v1.2/ACL2016.tar.gz)
- For the experiments presented in the [LREC 2016](http://www.lrec-conf.org/proceedings/lrec2016/summaries/902.html) paper, please check the dataset available [here](/resources/LREC2016_experiment.tar.gz)

### Short description:
- This is a monolingual English corpus of native, non-native and (human) translated texts extracted from the [European Parliament](http://www.statmt.org/europarl/). The translated texts from different source languages represent a subset of the [Haifa Corpus of Translationese](http://arxiv.org/abs/1509.03611). We preserved the same annotation style and included an ID and the EU state that each member of the European Parliament represents.
- We hope this dataset will facilitate a unified comparative study of translations and language produced by highly fluent non-native speakers, two closely-related phenomena that have only been studied in isolation so far.
- For updates, please check the [official repository](https://github.com/senisioi/enntt-release)



If you use this work in your research, please cite:
```
@InProceedings{enntt-corpus,
  author = {Sergiu Nisioi and Ella Rabinovich and Liviu P. Dinu and Shuly Wintner},
  title = {A Corpus of Native, Non-native and Translated Texts},
  booktitle = {Proceedings of the Tenth International Conference on Language Resources and Evaluation (LREC 2016)},
  year = {2016},
  month = {may},
  date = {23-28},
  location = {Portoro\u{z}, Slovenia},
  publisher = {European Language Resources Association (ELRA)},
  isbn = {978-2-9517408-9-1},
  language = {english}
 }
```

### File description:
-	*.tok files contain tha actual text uttered either in English by natives and non-natives or translated to English from other languages
-	*.dat files contain the annotations corresponding to each line in the *.tok files.

### Description of annotations:
-	NAME - speaker's name as it appears in the written session 
-	LANGUAGE - original language in which the sentence was uttered 
-	SESSION_ID - the name of the corresponding protocol source file 
-	SEQ_SPEAKER_ID - sequential number of the speaker within a session 

### Sentences uttered in English are annotated with additional information:
-	STATE - the EU state represented by the MEP 
-	MEPID - the ID used by the Europarl website to display the MEPs online images

For more details about this particular dataset, mailto:sergiu.nisioi at gmail com or mailto:ellarabi at csweb dot haifa dot ac dot il

