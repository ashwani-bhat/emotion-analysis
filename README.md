# sentiment-analysis-using-BERT

Sentiment Analysis for SMILE Twitter dataset is performed.

_Wang, Bo; Tsakalidis, Adam; Liakata, Maria; Zubiaga, Arkaitz; Procter, Rob; Jensen, Eric (2016): SMILE Twitter Emotion dataset. figshare. Dataset. https://doi.org/10.6084/m9.figshare.3187909.v2_


- Google colab was used with GPU as the runtime machine.
- The dataset is having following sentiment classes.

| Sentiment | Count |
| --------- | ----- |
| nocode | 1572 |
| happy | 1137|
| not-relevant|214|
|angry | 57 |
|surprise | 35 |
|sad| 32 |
|happy/surprise | 11 |
|happy/sad | 9 |
|disgust/angry | 7 |
|disgust | 6 |
|sad/disgust | 2 |
|sad/angry | 2 |
|sad/disgust/angry | 1 |

- The multiclass sentiments and the nocode (which doesn't represent any sentiment) was removed in the preprocessing stage.