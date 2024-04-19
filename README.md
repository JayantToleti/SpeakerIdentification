
# Speaker Identification using Deep Learning Techniques
Speaker identification is a pivotal task across various domains, such as security
systems, forensic analysis, and personalized services. Historically, traditional methods for
speaker identification relied on handcrafted features and statistical modeling techniques.
However, with the advancements in deep learning, there has been a paradigm shift towards
leveraging deep neural networks for more precise and resilient speaker identification systems.
The efficacy of deep learning techniques in speaker identification can be attributed to their
capacity to automatically learn discriminative features from raw audio data, thereby obviating
the necessity for handcrafted features. Additionally, the scalability of deep learning models
empowers them to efficiently handle vast datasets, leading to enhanced generalization
performance.
This work explores the implementation of various Deep Learning (DL) techniques. 
Currently, the best-performing model in speaker identification is a custom convolutional neural
network (CNN) with an impressive accuracy of 97%. CNNs excel in this task due to several
inherent advantages. The remarkable performance of custom CNNs underscores their efficacy
in addressing the complexities of speaker identification tasks. Alongside the CNN this work
also experiments with a Sinc-Net, which incorporates learnable sinc-based filters in the first
layer of a neural network architecture. SincNet offers a unique approach to feature extraction
from raw audio waveforms, allowing the model to learn filters tailored to the specific
characteristics of speech signals.

Dataset: [Librispeech](https://openslr.org/12/) 
