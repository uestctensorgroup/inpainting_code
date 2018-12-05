# inpainting_code
Tian-Hui Ma
------------------------------------------------------------------

Demo software for inpainting examples in

Tian-Hui Ma, Yifei Lou, Ting-Zhu Huang, and Xi-Le Zhao, 
Group-based truncated l_{1-2} model for image inpainting,
accepted by ICIP2017.

------------------------------------------------------------------

Copyright (c) Tian-Hui Ma, Yifei Lou, Ting-Zhu Huang, and Xi-Le Zhao
This work should be used only for nonprofit purposes.

------------------------------------------------------------------
Contents
------------------------------------------------------------------

The package comprises these files

*) demo.m		: a demo code for all examples
*) Group_DCA.m		: group-based truncated l_{1-2} minimization by DCA
*) DCA_add_noises.m	: generates noisy images
*) PSNR.m		: computes the peak signal to noise ratio
*) SSIM.m		: computes the Structural SIMilarity (SSIM) index
                          Copyright(c) 2009 Zhou Wang
*) images.mat		: contains test images for inpainting
*) result_block.mat	: results for filling missing blocks
*) result_pixel.mat	: results for filling missing pixels


Please cite the paper listed in the following BibTex if you use any part of our source code or data.

@INPROCEEDINGS{MaICIP2017, 
 author={Tian-Hui Ma and Yifei Lou and Ting-Zhu Huang and Xi-Le Zhao}, 
 booktitle={2017 IEEE International Conference on Image Processing (ICIP)}, 
 title={Group-based truncated $\ell_{1-2}$ model for image inpainting}, 
 year={2017}, 
 volume={}, 
 number={}, 
 pages={2079-2083}, 
}


@ARTICLE{ma2017truncated,
 author ={Tian-Hui Ma and Yifei Lou and Ting-Zhu Huang},
 title ={Truncated $\ell_{1-2}$ models for sparse recovery and rank minimization},
 journal ={{SIAM} Journal on Imaging Sciences},
 volume ={10},
 number ={3},
 pages ={1346--1380},
 year ={2017},
}


------------------------------------------------------------------
Feedback
------------------------------------------------------------------

If you have any comment, suggestion, or question, please do contact 
Tianhui Ma at: nkmth0307@126.com
or Yifei Lou at: first.last@utdallas.
