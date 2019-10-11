# NeuralStyleTransfer
Implementation of neural style transfer based on https://arxiv.org/abs/1508.06576. (Pytorch)
In this notebook, I'll use a pre-trained VGG19 Net to extract content or style features from a passed in image. 
We'll then formalize the idea of content and style losses and use those to iteratively update our target image until we get a result that we want.

## Result
The result has been summarised in a blog [post](https://pswaldia.github.io/2018-12-11-second-post/)
