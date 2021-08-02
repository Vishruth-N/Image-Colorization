# Pix2Pix GAN Implemented on Maps dataset
A clean, simple and readable implementation of Pix2Pix in PyTorch. The results from this implementation I would say is on par with the paper, I'll include some examples results below.

## Results
The model was trained on the Maps dataset.

|1st row: Input / 2nd row: Generated / 3rd row: Target|
|:---:|
|![](results/results_maps.png)|

### Maps dataset
The dataset can be downloaded from Kaggle: [link](https://www.kaggle.com/vikramtiwari/pix2pix-dataset).

## Pix2Pix paper
### Image-to-Image Translation with Conditional Adversarial Networks by Phillip Isola, Jun-Yan Zhu, Tinghui Zhou, Alexei A. Efros

#### Abstract
We investigate conditional adversarial networks as a general-purpose solution to image-to-image translation problems. These networks not only learn the mapping from input image to output image, but also learn a loss function to train this mapping. This makes it possible to apply the same generic approach to problems that traditionally would require very different loss formulations. We demonstrate that this approach is effective at synthesizing photos from label maps, reconstructing objects from edge maps, and colorizing images, among other tasks. Indeed, since the release of the pix2pix software associated with this paper, this work suggests we can achieve reasonable results without hand-engineering our loss functions either.

