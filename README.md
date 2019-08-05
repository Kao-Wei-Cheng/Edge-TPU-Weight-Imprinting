# Introduction
There are two kind of Transfer Learning on Dev Board - Backpropogation and Imprinted weight.
You can use the slide below to implentment easily.

# Update Dev Board Python library
Make sure that the Python library has already updated to *2.11.1.*
Updated Edge TPU Python library: https://coral.withgoogle.com/news/updates-07-2019/.

# Backpropogation
Retrain the classification model by backpropogation.
Backpropagation will update the in weights in every where.
If you use this way, the accuracy will be higher than Imprinted weight.

# Weight Imprinting
Weight imprinting is a technique for retraining a classification models using a small set of sample data.
It's based on : Low-Shot Learning with Imprinted Weights https://arxiv.org/pdf/1712.07136.pdf.
Weight Impringting require very few sample images (fewer than 10 training samples can achieve high accuracy).
Nevertheless, it has difficulty learning from datasets with large intra-class variation.If your use-case expects data with high intra-class variance, consider instead using on-device transfer learning with backpropagation

# *Slide with implement detail*
*Implement Transfer Learning on Dev Board:
https://drive.google.com/open?id=16TA87fefz00IRBdtywsvjkbUp5M6-wWJ*

# *Reference*
*Google official website:*
*https://coral.withgoogle.com/docs/edgetpu/retrain-classification-ondevice/*

*Low-Shot Learning with Imprinted Weights:*
*https://arxiv.org/pdf/1712.07136.pdf*

*Updated Edge TPU Python library:*
*https://coral.withgoogle.com/news/updates-07-2019/*

