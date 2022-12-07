# NLP
<p align="center">
    <h4 align="center"> Work Inprogress </h4>

>Expectations : This Repo should be serving as CrashNotes or Quick Reference for most of the topics

Things required in a Natural Language Processor

#### Tokenization
* Splitting phrase,sentence, paragraph or an entire text document into smaller units called tokens
* Diffrent ways to do is...
```commandline
from nltk.tokenzie import word_tokenize     # input -> list of words
from nltk.tokenzie import sent_tokenize     # input -> list of sentences

from keras.preprocessing.text import text_to_word_sequence

from gensim.utils import tokenize     # convert the output to list -> list(tokenize(input))
```

#### Stemming
* We employ stemming to reduce words to their base form some time the output words are incorrect so we prefer to do *Lemmatization over Stemming*.
> not going into deep to save time if intrested look out for articels (not by me :)

#### Lemmatization
* In this the word generation after chopping is always meaningful.So, Lemmatization is better  than stemming ):
* Diffrent ways to do ...
```commandline

```

<p align="center">
    Encoding  text into Machine readable data!
</p>

