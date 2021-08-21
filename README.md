# NeuralHash Classifier

This is a classifier for an output of Apple's [NeuralHash](https://www.apple.com/child-safety/pdf/CSAM_Detection_Technical_Summary.pdf) function.

The model is trained on the [NeuralHash of ILSVRC2012 dataset](https://github.com/kjsman/NeuralHash-Classifier/releases/tag/t).

Performance on the ImageNet validation dataset: (1,000 possible choices)
- Top-1 Accuracy:  5.25% (0.1%, if random)
- Top-5 Accuracy: 14.09% (0.5%, if random)

Now if you think Apple's NeuralHash is defective, please consider signing [an Open Letter Against Apple's Privacy-Invasive Content Scanning Technology](https://appleprivacyletter.com/).
