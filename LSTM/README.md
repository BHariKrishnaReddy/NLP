### FakeNewsClassifierLSTM
Dataset : kaggle

### Flow
In this while loading data i came to know about a parameter `encoding='utf-8'` apart from it everything normal.we have used various pakages from `nltk` and `Tensorflow` like

Stemming
* PorterStemmer
```commandline
from nltk.stem.porter import PorterStemmer
```

Metrics
* confusion_matrix
* accuracy_score
```commandline
from sklearn.metrics import confusion_matrix
from sklearn.metrics import accuracy_score
```

Layers
* Dense
* Embedding
* LSTM
* Dropout

Encoding Text
* one_hot

and `pad_sequences` from utils is used maintain a constant input size.
```commandline
from tensorflow.keras.utils import pad_sequences
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Dense,Embedding,LSTM,Dropout
from tensorflow.keras.preprocessing.text import one_hot
```

