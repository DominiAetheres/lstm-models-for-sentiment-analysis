# Abstract

Aspect-based sentiment analysis can be used to extract the sentiment of a particular
aspect from a subject of some sample text such as the quality of food at a restaurant.
What makes this task difficult is the potential multipolarity of sentiments contained
within a given sample text related to different aspects. Basic LSTM networks fail to
capture this nuance within input strings as the hidden states and final output remains
constant for any given sentence. Therefore, it has no ability to make representations about
aspects within the network. This paper will introduce and test three aspect-embedded
LSTM networks: an attentionless aspect-embedded model, an aspect-embedded model
with attention, and a Seq2seq style model. The two models that contained attention
were the most accurate but displayed some uninterpretable encoding in the attention
mechanism.
