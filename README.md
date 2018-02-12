
My Natural Language Processing references.

NLP Topics

1. [Natural Language processing](./docs/nlp.md)
2. [Text classification](./docs/text-classification.md)
3. [Text similarities](./docs/text-similarities.md)
4. [Research papers](research-papers)
5. [Frameworks](frameworks)

## NLP Jargons

| [CoNLL](https://github.com/vkosuri/NLPFaqs/blob/master/docs/nlp.md#conll)               | [Copora](https://github.com/vkosuri/NLPFaqs/blob/master/docs/nlp.md#copora)         | [Chunking](https://github.com/vkosuri/NLPFaqs/blob/master/docs/nlp.md#chunking) |
|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| [Lemmatizing](https://github.com/vkosuri/NLPFaqs/blob/master/docs/nlp.md#lemmatizing)   | [Stop words](https://github.com/vkosuri/NLPFaqs/blob/master/docs/nlp.md#stop-words) | [tf–idf](https://github.com/vkosuri/NLPFaqs/blob/master/docs/nlp.md#tfidf)      |
| [Tokenization](https://github.com/vkosuri/NLPFaqs/blob/master/docs/nlp.md#tokenization) |                                                                                     |                                                                                 |

## Popular Algorithms

| Algorithm                                                                                                                                                                                          | Category            |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------|
| [Levenshtein distance](https://en.wikipedia.org/wiki/Levenshtein_distance)                                                                                                                         | Text similarities   |
| [Jaccard similarity](https://en.wikipedia.org/wiki/Jaccard_index)                                                                                                                                  | Text similarities   |
| [Cosine similarity](https://www.youtube.com/watch?v=C3Jt14Se9Cg&feature=youtu.be)                                                                                                                  | Text similarities   |
| [Global Vectors for Word Representation](https://nlp.stanford.edu/projects/glove/)                                                                                                                 | Text similarities   |
| [word2vec](https://code.google.com/archive/p/word2vec/)                                                                                                                                            | Text similarities   |
| Support Vector Machines (SVM)                                                                                                                                                                      | Text classification |
| [Naive Bayes](https://en.wikipedia.org/wiki/Naive_Bayes_classifier)                                                                                                                                | Text classification |
| [Neural Networks](https://www.doc.ic.ac.uk/~nd/surprise_96/journal/vol4/cs11/report.html)                                                                                                          | Text classification |
| [Decision Trees](https://www.analyticsvidhya.com/blog/2016/04/complete-tutorial-tree-based-modeling-scratch-in-python/), [Lucid Page](https://www.lucidchart.com/pages/decision-tree)              | Text classification |
| [Random Forests](https://www.analyticsvidhya.com/blog/2014/06/introduction-random-forest-simplified/)                                                                                              | Text classification |
| [Boosting and Bagging algorithms](http://dni-institute.in/blogs/bagging-algorithm-concepts-with-example/), [Differnce](https://quantdare.com/what-is-the-difference-between-bagging-and-boosting/) | Text classification |
| Supervised Latent Dirichlet Allocation (SLDA), [Source](http://www.cs.cmu.edu/~chongw/slda/)                                                                                                       | Text classification |

## Popular Frameworks

| Framework                                                | Organisation | License     | Language    |
|----------------------------------------------------------|--------------|-------------|-------------|
| [fastText](https://github.com/facebookresearch/fastText) | Facebook     | BSD+Patents | C++         |
| [Tensorflow](https://github.com/tensorflow/tensorflow)   | Google       | Apache 2.0  | C++, Python |
| [PyTorch](http://pytorch.org/)                           | Facebook     | BSD+Patents | Python      |
| [GenSim](https://github.com/RaRe-Technologies/gensim)    | RaRe         | LGPL2.1     | Python      |
| [SpaCy](https://github.com/explosion/spaCy)              | explosion    | MIT         | Python      |
| [NLTK](https://github.com/nltk/nltk)                     | NLTK         | Apache 2.0  | Python      |
| [TextBlob](https://github.com/sloria/TextBlob)           |              | MIT         | Python      |
| [RASA NLU](https://github.com/RasaHQ/rasa_nlu)           |              | Apache 2.0  | Python      |

## Popular NLP Models
| Model                                               | Description                                                                                                                                                                                                                                                                                                                                                                                                                          | Resources                                                                                                                | Repo                                                                                              |
|-----------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| Seq2Seq                                             | A general-purpose encoder-decoder framework for Tensorflow that can be,used for Machine Translation, Text Summarization, Conversational,Modeling, Image Captioning, and more.                                                                                                                                                                                                                                                        | https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf                                 | https://github.com/google/seq2seq https://github.com/tensorflow/nmt                               |
| Seq2Seq Back propagation                            | We present two approaches that use unlabeled data to improve sequence,learning with recurrent networks. The first approach is to predict what,comes next in a sequence, which is a conventional language model in,natural language processing. The second approach is to use a sequence,autoencoder, which reads the input sequence into a vector and predicts,the input sequence again                                              | http://neuralnetworksanddeeplearning.com/chap2.html https://arxiv.org/abs/1409.3215 https://arxiv.org/pdf/1511.01432.pdf | https://github.com/mnielsen/neural-networks-and-deep-learning                                     |
| Memory end-end model                                | The architecture is a form of Memory Network but unlike the model in,that work, it is trained end-to-end, and hence requires significantly,less supervision during training, making it more generally applicable in,realistic settings.                                                                                                                                                                                              | https://arxiv.org/abs/1503.08895                                                                                         | https://github.com/facebookresearch/ParlAI https://github.com/facebook/MemNN                      |
| Deep Reinforcement Learning for Dialogue Generation | Recent neural models of dialogue generation offer great promise for,generating responses for conversational agents, but tend to be,shortsighted, predicting utterances one at a time while ignoring their,influence on future outcomes. Modeling the future direction of a,dialogue is crucial to generating coherent, interesting dialogues, a,need which led traditional NLP models of dialogue to draw on,reinforcement learning. | https://arxiv.org/pdf/1606.01541.pdf                                                                                     | https://github.com/liuyuemaicha/Deep-Reinforcement-Learning-for-Dialogue-Generation-in-tensorflow |

## Lectures

* https://github.com/oxford-cs-deepnlp-2017/lectures

* https://github.com/chiphuyen/stanford-tensorflow-tutorials

## Links

* [Paraphrase generation](https://scholar.google.co.il/scholar?as_sdt=0%2C5&hl=en&q=%22paraphrase+generation%22+&scisbd=1)

* [about arXiv](https://arxiv.org/help/general)

* [arXiv Computation and Language](https://arxiv.org/list/cs.CL/recent)

* [arXiv Artificial Intelligence](https://arxiv.org/list/cs.AI/recent)

* https://github.com/keon/awesome-nlp

* https://github.com/Kyubyong/nlp_tasks


> Contributions are welcome.

