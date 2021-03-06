#Pig Usage

##Parameters
* user_input
* output_path

##Execution
* Script name : `sentence_search.pig`

* Execute the pig sentence search script (Local).
```sh
pig -x local -param user_input="input.txt" -param output_path=output_search -f sentence_search.pig
```

Where `input.txt` and `output_search` is the input/output file/folder (generated depends on request).

* Execute the pig sentence search script (Map-Reduce)
```sh
pig -param user_input="input.txt" -param output_path=output_search -f sentence_search.pig
```

Where `input.txt` and `output_search` is the input/output file/folder (generated depends on request).

##Input

* Input Format
```sh
input_sentence1
input_sentence2
...
```

* Example Input
```
The Project Gutenberg EBook of The Bab Ballads, by W. S. Gilbert (#3 in our series by W. S. Gilbert)  Copyright laws are changing all over the world.
Be sure to check the copyright laws for your country before downloading or redistributing this or any other Project Gutenberg eBook.
This header should be the first thing seen when viewing this Project Gutenberg file.
```

##Output
* Output Format
```sh
bookname sentence_id sentence
```

* part of Example Output
```sh
brnte10	2	This header should be the first thing seen when viewing this Project Gutenberg file.
morem10	1	Be sure to check the copyright laws for your country before downloading or redistributing this or any other Project Gutenberg eBook.
```

##Searching Pool
* Uses a sentence breaker library from `nltk.corpus.Gutenberg` and generate modified version book files.
(Special thanks to [WebApp8](https://github.com/vasupol11/219351_homework) group for the sentence breaker)
* Folder name(Searching pool) : `GTB`(See in the [script](sentence_search.pig))
* modified version of book files have the following structure
```sh
bookname{_}sentence_id{_}sentence
bookname{_}sentence_id{_}sentence
...
```

##Limitation
* The input-searching-sentence must be exactly the same as in searching pool.



##Issues
* Cannot run pig in map-reduce mode
![alt text](img/issue1.png "Issue 1")
(Already configured the name `hadoop-master` to specific ip in `etc/hosts` and `hdfs` service is already started)
![alt text](img/issue2.png "Issue 2")
(ERROR when trying to run pig in map-reduce mode)
