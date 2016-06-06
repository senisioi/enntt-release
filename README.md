## [Europarl corpus of native, non-native and translated texts - ENNTT](https://github.com/senisioi/enntt-release/releases/tag/v1.0)
- Please check the release section for the latest version.
- The dataset is also available at the [Center for Computational Linguistics](http://nlp.unibuc.ro/resources.html)
- For the experiments in the paper Nisioi, S., Rabinovich, E., Dinu, L. P., and Wintner, S.: **A Corpus of Native, Non-native and Translated Texts** LREC, 2016, [PDF](http://www.lrec-conf.org/proceedings/lrec2016/pdf/902_Paper.pdf) dataset also available [here](http://nlp.unibuc.ro/resources/LREC2016_experiment.tar.gz).
- This is a monolingual English corpus of native, non-native and (human) translated texts extracted from the [European Parliament](http://www.statmt.org/europarl/). The translated texts from different source languages represent a subset of the [Haifa Corpus of Translationese](http://arxiv.org/abs/1509.03611). We preserved the same annotation style and included an ID and the EU state that each member of the European Parliament represents.
- We hope this dataset will facilitate a unified comparative study of translations and language produced by highly fluent non-native speakers, two closely-related phenomena that have only been studied in isolation so far.

If you use this work in your research, please cite:
```
@inproceedings{nnt-corpus,
	Author = {Sergiu Nisioi and Ella Rabinovich and Dinu, Liviu P. and Shuly Wintner},
	Booktitle = {Proceedings of the Tenth International Conference on Language Resources and Evaluation, {LREC}~2016},
	Location = {Portoro\u{z}, Slovenia},
	Title = {A Corpus of Native, Non-native and Translated Texts},
	Year = {2016}}
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

