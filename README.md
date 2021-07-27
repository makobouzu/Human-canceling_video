## Human-canceling_video
This is a Pytorch re-implementation for the paper [Free-Form Image Inpainting with Gated Convolution](https://arxiv.org/abs/1806.03589).  

This repository contains "Gated Convolution", "Contextual Attention" and "Spectral Normalization".
## Requirement
- Python 3
- OpenCV-Python
- Numpy
- Pytorch 1.0+
- GPU memory > 16GiB (Google colab pro)
## Pretrained model
Download the pretrained model [here](https://drive.google.com/file/d/1uMghKl883-9hDLhSiI8lRbHCzCmmRwV-/view?usp=sharing) and put it in `./pretrained_model/`.
## Run
- Download this repository & move to Google drive.
- Run [Google colab project](https://github.com/makobouzu/Human-canceling_video/blob/master/human_canceling_video.ipynb).

## Detail
mp4 file input -> sequential numbered images & Human mask images -> inpainting images -> mp4 file output
## Acknowledgments
Thanks for [DeepFillv2 pytorch](https://github.com/piggy2303/DeepFillv2_Pytorch).  
The main code is based upon [deepfillv2](https://github.com/zhaoyuzhi/deepfillv2).  
The code of "Contextual Attention" is based upon [generative-inpainting-pytorch](https://github.com/daa233/generative-inpainting-pytorch).  
Thanks for their excellent works!
