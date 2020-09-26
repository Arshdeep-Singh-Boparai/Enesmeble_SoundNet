# Enesmeble_SoundNet

This code is an ensemble framework on intermediate representations of SoundNet for audio scence classification [1].

Flow chart of the code:
(a) Extract intermediate representations from various interediate layers using raw-audio as input. Apply global average pooling across each feature map.
(b) Train classifier using npn-linear SVM and apply late fusion.




References:
1. Singh, Arshdeep, et al. "A layer-wise score level ensemble framework for acoustic scene classification." 2018 26th European Signal Processing Conference (EUSIPCO).IEEE, 2018.
