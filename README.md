nlp seq2seq with attention. Loung is better than Bahdanau for choosing attention unit. 

Trained and tested on two data set, "small_vocab_en" and "small_vocab_fr" are datasets with around 400k sentences but only few hundred unique words. This model can achieve around 98% accuracy. 

"small_vocab_en_UN" and "small_vocab_fr_UN", with the bad naming I forget to change, are the meeting record of United Nations, while the original files are huge, i cropped them to around 800k sentences and 40k ish unique words. and there are still lots of translation error in them.

After discarded most words and leave only those words appears freqently (only few thoudsand of them)to train, this model is still too small to acheive a good result. This model proved the correctness of its function with easy dataset, and also proved that if a NLP model is needed to be used in a real world problem, the model have to be a huge one.
