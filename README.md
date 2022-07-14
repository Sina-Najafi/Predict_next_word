# Predict_next_word
this model tries to predict the nth word based on previous n-1 words based on what it has learned!
the way I have approached is that I have made the problem into a multiclass classification. let's say
we have 5000 unique tokens(words in this case) in our train data. we can pick the number of classes to be 100
or 5000. each has its own problems. the words that are not in our output classes are considered  oov tokens. if we
pick the output classes to be 100, there will be a lot of oov in our data and the model will definitelly be overfit!
if we pick 5000 then we have little data for a lot of classes and the model can't learn them properly. we can also pick
something in the middle more towards 5000 which is what I have done :)
please pay attention that after two specific words there is no right word and we have multiple right choices, it all 
depends on what someone wants to write!
