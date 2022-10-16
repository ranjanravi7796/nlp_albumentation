# nlp_albumentation
NLP Albumentation - Applying Data Augmentation techniques on text data

Have you ever wanted to build some cool NLP projects like Text summarization, Question Answering bots, finding semantic meaning in the text and got poor performance from the model simply because of the lack of training data. Of course, with the current growth in NLP, these projects can be implemented quickly with the help of models that are available in platforms like HuggingFace which are pretrained in large volumes of text data. Since these models are trained on generic datasets like Wikipedia, Stack Exchange, Yahoo answers etc, they would have average performance on the domain-specific tasks. For example, if we are dealing with the medical data, then it is recommended to take these pretrained models and then fine tune it for medical datasets.

But the challenge here is to collect the data for training. These models would require huge volumes of text data for training. In this case, similar to the data augmentation techniques in Computer Vision, there is a technique called NLP Albumentation. These techniques are applied to the text data using which we can increase the size of the training set. This increase in size of the training data would improve the model performance on the NLP tasks.

This notebook contains some of the techniques on NLP Albumentation in generating more training data from the existing data using some of the NLP Albumentation techniques.
