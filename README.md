# IMDB-Movie-Review

IMDB Movie Review using NLP and Pytorch

### Corrections

<b>Notes to myself</b>

Ok, so i was going through the notebook as on (01/07/2020) and saw the val_acc hovering at 82% approx (yeah that's a crappy result) and realized that i was using MSE as my loss function (IKR!!!) and damn I was using Tfidf as my features for my NN... Please don't do that to the model... 

Improve by using Embedding layer (possibly pretrained) and LSTMs or GRUs (if u feel LSTMs computationally expensive)... If Attention is to be used don't just go and add it, remember to convert ur LSTM to a Bidirectional LSTM... 

If you see an LSTM model then probably I have modified it, else please bear with me...
