## Virtually Enriched NYU Depth V2 Dataset for Monocular Depth Estimation:<br/> Do We Need Artificial Augmentation? 
D. Ignatov, A. Ignatov, R. Timofte. 
<br/>Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops, pages 6177-6186, 2024.

## Artifacts of the article:
- Virtually augmented NYU Depth V2 training dataset (<a href="https://drive.google.com/file/d/1nrsiowQW1L9IEYLWoiGfJAhD56nSA3Sx/view?usp=sharing" target="_blank">ANYU</a>) extended with 10% and 100% artificially modified images
- Virtually enriched (100 %) NYU Depth V2 <a href="https://drive.google.com/file/d/14FXyJHCUAxIxtbwlY5R4GkfOZp3_CeYm/view?usp=sharing" target="_blank">test set</a>: 2048 artificially modified RGB-D testing pairs of images 
- <a href="https://drive.google.com/file/d/1xl3_CwEmPWtbswuS5ZW8K-ad8Xi7GRMr/view?usp=sharing" target="_blank">Checkpoint</a> of the
<a href="https://github.com/wl-zhao/VPD" target="_blank">VPD</a> model: RMSE 0.2478
------------------------------------------------------------------------------------------------------------
Since the ANYU dataset contains RGB-D images from NYU depth v2, along with our paper [1] the original NYU article [2] should be cited:<br/>

@inproceedings{Ignatov:CVPR24, 
author = {Ignatov, Dmitry and Ignatov, Andrey and Timofte, Radu}, 
title = {Virtually Enriched NYU Depth V2 Dataset for Monocular Depth Estimation: Do We Need Artificial Augmentation?}, 
booktitle = {CVPR}, 
year = {2024},
pages = {6177-6186}}

@inproceedings{Silberman:ECCV12,
  author    = {Silberman, Nathan  and Hoiem, Derek and Kohli, Pushmeet and Fergus, Rob},
  title     = {Indoor Segmentation and Support Inference from RGBD Images},
  booktitle = {ECCV},
  year      = {2012}
}
