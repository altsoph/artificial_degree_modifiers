This is a supplementary code for the paper "[Connecting degree and polarity: An artificial language learning study](https://arxiv.org/abs/2109.06333)."

We extend the artificial language learning experimental paradigm from psycholinguistics and apply it to pre-trained language models -- specifically, BERT (Devlin et al., 2019). We treat the model as a subject in an artificial language learning experimental setting: in order to understand the relation between two linguistic properties, A and B, we introduce a set of new, non-existent linguistic items, give the model information about their variation along property A, then measure to what extent the model learns property B for these items as a result of training. We show this method at work for degree modifiers (expressions like "slightly", "very", "rather", "extremely") and test the hypothesis that the degree expressed by modifiers (low, medium, or high degree) is related to their sensitivity to sentence polarity (whether they show a preference for affirmative or negative sentences or neither). Our experimental results are compatible with existing linguistic observations that relate degree semantics to polarity sensitivity, including the main one: low degree semantics leads to positive polarity sensitivity (that is, to preference towards affirmative contexts). The method can be used in linguistics to elaborate on hypotheses and interpret experimental results, as well as for more insightful evaluation of linguistic representations in language models.
