# Papers About DL

## Recent Advances in Recurrent Neural Networks([1801.01078.pdf](./1801.01078.pdf))

### Author

Hojjat Salehinejad, Julianne Baarbe, Sharan Sankar, Joseph Barfett, Errol Colak, Shahrokh Valaee

### Abstract

Recurrent neural networks (RNNs) are capable of learning features and long term dependencies from sequential and time-series data. The RNNs have a stack of non-linear units where at least one connection between units forms a directed cycle. A well-trained RNN can model any dynamical system; however, training RNNs is mostly plagued by issues in learning long-term dependencies. In this paper, we present a survey on RNNs and several new advances for newcomers and professionals in the field. The fundamentals and recent advances are explained and the research challenges are introduced.

## Deep Learning with Dynamic Computation Graphs([1702.02181.pdf](./1702.02181.pdf))

### Author

Moshe Looks, Marcello Herreshoff, DeLesley Hutchins, Peter Norvig

### Abstract

Neural networks that compute over graph structures are a natural fit for problems in a variety of domains, including natural language (parse trees) and cheminformatics (molecular graphs). However, since the computation graph has a different shape and size for every input, such networks do not directly support batched training or inference. They are also difficult to implement in popular deep learning libraries, which are based on static data-flow graphs. We introduce a technique called dynamic batching, which not only batches together operations between different input graphs of dissimilar shape, but also between different nodes within a single input graph. The technique allows us to create static graphs, using popular libraries, that emulate dynamic computation graphs of arbitrary shape and size. We further present a high-level library of compositional blocks that simplifies the creation of dynamic graph models. Using the library, we demonstrate concise and batch-wise parallel implementations for a variety of models from the literature.

## Learning phrase representations using RNN encoder-decoder for statistical machine translation([1406.1078.pdf](./1406.1078.pdf))

### Author

Cho, Kyunghyun
Van Merriënboer, Bart
Gulcehre, Caglar
Bahdanau, Dzmitry
Bougares, Fethi
Schwenk, Holger
Bengio, Yoshua

### Abstract

In this paper, we propose a novel neural network model called RNN Encoder-Decoder that consists of two recurrent neural networks (RNN). One RNN encodes a sequence of symbols into a fixed-length vector representation, and the other decodes the representation into another sequence of symbols. The encoder and decoder of the proposed model are jointly trained to maximize the conditional probability of a target sequence given a source sequence. The performance of a statistical machine translation system is empirically found to improve by using the conditional probabilities of phrase pairs computed by the RNN Encoder-Decoder as an additional feature in the existing log-linear model. Qualitatively, we show that the proposed model learns a semantically and syntactically meaningful representation of linguistic phrases.

## A Survey on Acceleration of Deep Convolutional Neural Networks([1802.00939.pdf](./1802.00939.pdf))

### Author

Jian Cheng, Peisong Wang, Gang Li, Qinghao Hu, Hanqing Lu

### Abstract

Deep Neural Networks have achieved remarkable progress during the past few years and are currently the fundamental tools of many intelligent systems. At the same time, the computational complexity and resource consumption of these networks are also continuously increasing. This will pose a significant challenge to the deployment of such networks, especially for real-time applications or on resource-limited devices. Thus, network acceleration have become a hot topic within the deep learning community. As for hardware implementation of deep neural networks, a batch of accelerators based on FPGA/ASIC have been proposed these years. In this paper, we provide a comprehensive survey about the recent advances on network acceleration, compression and accelerator design from both algorithm and hardware side. Specifically, we provide thorough analysis for each of the following topics: network pruning, low-rank approximation, network quantization, teacher-student networks, compact network design and hardware accelerator. Finally, we make a discussion and introduce a few possible future directions.
