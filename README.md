# Named Entity recognition with phrase embedding
Named entity recognition (NER) is the process of identifying and categorizing key information (entities) in text. The entities can be any name such as person names, places, organization names etc.
The objective of the project is to perform different NER Models on word embedded and phrases embedded data and compare the results which performs better.

### Models used:
* Bi LSTM with CRF(Conditional Random Field)
* Bi LSTM
### Dataset
* We used Twitter dataset that is bilingual (Hindi-English mixed twitter text or tweets). Then, Tweets are pre-processed and annotated as per the 2 tags Noun and
Others.
* Dataset consists of 1000 Tweets.
  * eg tweet:  agar #notebandi ke time political party bhi #rti ke daayre me aa jati to #sukmaattack #kashmir me patthar attack na hote @PMOIndia
  * Phrases: political party, aa jati 
  
### Architecture
![](/BILSTM_architecture.png)

### Results
The models with Phrase embedding have shown better results than the word embedding. The f1-socre is increased by 3%

