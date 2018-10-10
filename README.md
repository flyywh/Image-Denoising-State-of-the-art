# Image Denoising State-of-the-art

**A curated list of image denoising resources and a benchmark for image denoising approaches.**

**This list is maintained by:** **Wenhan Yang** **[[STRUCT]](http://www.icst.pku.edu.cn/struct/struct.html) PKU (PI: Prof. Jiaying Liu)**


## State-of-the-art algorithms
#### Filter
 * BM3D [[Web]](http://www.cs.tut.fi/~foi/GCF-BM3D/) [[Code]](http://www.cs.tut.fi/~foi/GCF-BM3D/BM3D.zip) [[PDF]](http://www.cs.tut.fi/~foi/GCF-BM3D/SPIE08_deblurring.pdf)
   * Image restoration by sparse 3D transform-domain collaborative filtering (SPIE Electronic Imaging 2008), Dabov et al.
 * Activity-tuned Image Filtering [[PDF]](https://arxiv.org/pdf/1707.02637.pdf)
   * Local Activity-tuned Image Filtering for Noise Removal and Image Smoothing (Arxiv 2017), Lijun Zhao, Jie Liang, Huihui Bai, Lili Meng, Anhong Wang, and Yao Zhao.

#### Sparse Coding
 * KSVD [[Web]](http://www.cs.technion.ac.il/~ronrubin/software.html) [[Code]](https://github.com/jbhuang0604/SelfSimSR/tree/master/Lib/KSVD) [[PDF]](http://www.egr.msu.edu/~aviyente/elad06.pdf)
   * Image Denoising Via Sparse and Redundant Representations Over Learned Dictionaries (TIP2006), Elad et al.
 * SAINT [[Web]](http://see.xidian.edu.cn/faculty/wsdong/wsdong_Publication.htm) [Code] [[PDF]](http://see.xidian.edu.cn/faculty/wsdong/Papers/Journal/TIP_LASSC.pdf)
   * Nonlocal image restoration with bilateral variance estimation: a low-rank approach (TIP2013), Dong et al.
 * NCSR [[Web]](http://www4.comp.polyu.edu.hk/~cslzhang/NCSR.htm) [[Code]](http://www4.comp.polyu.edu.hk/~cslzhang/code/NCSR.rar) [[PDF]](http://www4.comp.polyu.edu.hk/~cslzhang/paper/NCSR_TIP_final.pdf)
   * Nonlocally Centralized Sparse Representation for Image Restoration (TIP2012), Dong et al.
 * LSSC [[Web]](http://www.di.ens.fr/~fbach/) [Code] [[PDF]](http://www.di.ens.fr/~fbach/iccv09_mairal.pdf)
   * Non-local Sparse Models for Image Restoration (ICCV2009), Mairal et al.
 * TWSC [[Web]](https://github.com/csjunxu/TWSC-ECCV2018) [Code] [[PDF]](http://openaccess.thecvf.com/content_ECCV_2018/papers/XU_JUN_A_Trilateral_Weighted_ECCV_2018_paper.pdf)
   * A Trilateral Weighted Sparse Coding Scheme for Real-World Image Denoising (ECCV2018), Xu et al.

#### Effective Prior
 * EPLL [[Web]](https://people.csail.mit.edu/danielzoran/) [[Code]](https://people.csail.mit.edu/danielzoran/epllcode.zip) [[PDF]](http://people.ee.duke.edu/~lcarin/EPLICCVCameraReady.pdf)
   * From Learning Models of Natural Image Patches to Whole Image Restoration (ICCV2011), Zoran et al.
 * Bayesian Hyperprior [[PDF]](https://arxiv.org/pdf/1706.03261.pdf)
   * A Bayesian Hyperprior Approach for Joint Image Denoising and Interpolation with an Application to HDR Imaging, Cecilia Aguerrebere, Andres Almansa, Julie Delon, Yann Gousseau and Pablo Muse.
 * External Prior Guided [[PDF]](https://arxiv.org/pdf/1705.04505.pdf)
   * External Prior Guided Internal Prior Learning for Real Noisy Image Denoising, Jun Xu, Lei Zhang, and David Zhang.
 * Multi-Layer Image Representation [[PDF]](https://arxiv.org/pdf/1707.02194.pdf)
   * A Multi-Layer Image Representation Using Regularized Residual Quantization: Application to Compression and Denoising, Sohrab Ferdowsi, Slava Voloshynovskiy, Dimche Kostadinov.
 * A Faster Patch Ordering [[PDF]](https://arxiv.org/ftp/arxiv/papers/1704/1704.08090.pdf)
   * A Faster Patch Ordering Method for Image Denoising, Badre Munir.
  
#### Low Rank
 * WNNM [[Web]](https://sites.google.com/site/shuhanggu/home) [[Code]](http://www4.comp.polyu.edu.hk/~cslzhang/code/WNNM_code.zip) [[PDF]](https://pdfs.semanticscholar.org/6d55/6272625b672ba54b5ab3d9e6474088a4b78f.pdf)
   * Weighted Nuclear Norm Minimization with Application to Image Denoising (CVPR2014), Gu et al.
 * Low-rank MoG filter [[PDF]](http://openaccess.thecvf.com/content_cvpr_2016/papers/Zhu_From_Noise_Modeling_CVPR_2016_paper.pdf)
   * From Noise Modeling to Blind Image Denoising (CVPR2016), Zhu et al.
 * Multi-channel Weighted Nuclear Norm [[Web]](https://github.com/csjunxu/MCWNNM-ICCV2017) [Code] [[PDF]](https://arxiv.org/pdf/1705.09912.pdf)
   * Multi-channel Weighted Nuclear Norm Minimization for Real Color Image Denoising (ICCV2017), Jun Xu, Lei Zhang, David Zhang, and Xiangchu Feng.
 * Multi-Scale Weighted Nuclear Norm [[PDF]](https://tomer.net.technion.ac.il/files/2018/04/MS-WNNM-IR.pdf)
   * Multi-Scale Weighted Nuclear Norm Image Restoration (CVPR2018), Noam Yair, Tomer Michaeli.

#### Deep Learning
 * TNRD [[Web]](http://www.icg.tugraz.at/Members/Chenyunjin/about-yunjin-chen) [[Code]](https://www.dropbox.com/s/8j6b880m6ddxtee/TNRD-Codes.zip?dl=0) [[PDF]](https://arxiv.org/pdf/1508.02848.pdf)
   * Trainable nonlinear reaction diffusion: A flexible framework for fast and effective image restoration (TPAMI2016), Chen et al.
 * DnCNN [[Web]](https://github.com/cszn/DnCNN) [[PDF]](https://arxiv.org/pdf/1608.03981v1.pdf)
   * Beyond a Gaussian Denoiser: Residual Learning of Deep CNN for Image Denoising (TIP2017), Zhang et al.
 * DAAM [[Web]](https://arxiv.org/abs/1612.06508) [[PDF]](https://arxiv.org/pdf/1612.06508.pdf)
   * Deeply Aggregated Alternating Minimization for Image Restoration (Arxiv2016), Youngjung Kim et al.
 * Adversirial Denoising [[PDF]](https://arxiv.org/pdf/1708.00159.pdf)
   * Image Denoising via CNNs: An Adversarial Approach (Arxiv2017), Nithish Divakar, R. Venkatesh Babu.
 * Unrolled Optimization Deep Priors [[PDF]](https://arxiv.org/pdf/1705.08041.pdf)
   * Unrolled Optimization with Deep Priors (Arxiv2017), Steven Diamond, Vincent Sitzmann, Felix Heide, Gordon Wetzstein.
 * Recurrent Inference Machines [[PDF]](https://arxiv.org/pdf/1706.04008.pdf)
   * Recurrent Inference Machines for Solving Inverse Problems(Arxiv2017), Patrick Putzky, Max Welling.
 * Kernel Prediction [[PDF]](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/3761.pdf)
   * Burst Denoising With Kernel Prediction Networks (CVPR2018), Ben Mildenhall, Jonathan T. Barron, Jiawen Chen, Dillon Sharlet, Ren Ng, Robert Carroll.
 * GAN-Based Noise Modeling [[PDF]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Image_Blind_Denoising_CVPR_2018_paper.pdf)
   * 	Image Blind Denoising With Generative Adversarial Network Based Noise Modeling (CVPR2018), Jingwen Chen, Jiawei Chen, Hongyang Chao, Ming Yang. 
 * Universal Denoising Networks [[PDF]](https://arxiv.org/pdf/1711.07807.pdf)
   * 	Universal Denoising Networks : A Novel CNN Architecture for Image Denoising (CVPR2018), Stamatios Lefkimmiatis.
 * Non-Local Recurrent Network [[PDF]](https://arxiv.org/pdf/1806.02919.pdf)
   * 	Non-Local Recurrent Network for Image Restoration (Arxiv2018), Ding Liu, Bihan Wen, Yuchen Fan, Chen Change Loy, Thomas S. Huang.
 * Recurring Patterns Network [[PDF]](https://arxiv.org/pdf/1806.05229.pdf)
   * 	Identifying Recurring Patterns with Deep Neural Networks for Natural Image Denoising (Arxiv2018), Zhihao Xia, Ayan Chakrabarti.
 * Dynamically Unfolding Recurrent Restorer [[PDF]](https://arxiv.org/pdf/1805.07709.pdf)
   *  Dynamically Unfolding Recurrent Restorer: A Moving Endpoint Control Method for Image Restoration (Arxiv2018), Xiaoshuai Zhang, Yiping Lu, Jiaying Liu, Bin Dong.
 * Pixel Adaptive Image Denoiser [[PDF]](https://arxiv.org/pdf/1807.07569.pdf)
   *  Fully Convolutional Pixel Adaptive Image Denoiser (Arxiv2018), Sungmin Cha and Taesup Moon.
 * Convolutional Blind Denoising [[PDF]](https://arxiv.org/pdf/1807.04686.pdf) [[WEB]](https://github.com/GuoShi28/CBDNet)
   *  Toward Convolutional Blind Denoising of Real Photographs (Arxiv2018), Shi Guo, Zifei Yan, Kai Zhang, Wangmeng Zuo, Lei Zhang.
 * Noise2Noise [[PDF]](https://arxiv.org/pdf/1803.04189.pdf)
   *  Noise2Noise: Learning Image Restoration without Clean Data (ICML2018), Jaakko Lehtinen, Jacob Munkberg, Jon Hasselgren, Samuli Laine, Tero Karras, Miika Aittala, Timo Aila.
   
   
#### Combined with High-Level Tasks
 * Meets High-level Tasks [[PDF]](https://arxiv.org/pdf/1706.04284.pdf)
   * When Image Denoising Meets High-Level Vision Tasks: A Deep Learning Approach, Ding Liu (IJCAI2018), Bihan Wen, Xianming Liu, Thomas S. Huang.
 * Class-Specific Denoising [[PDF]](https://arxiv.org/pdf/1706.02867.pdf)
   * Class-Specific Poisson Denoising By Patch-Based Importance Sampling (Arxiv2017), Milad Niknejad, Jose M. Bioucas-Dias, Mario A. T. Figueiredo.
 * Class-Aware Denoising [[PDF]](https://arxiv.org/pdf/1808.06562.pdf)
   * Class-Aware Fully-Convolutional Gaussian and Poisson Denoising (Arxiv2018), Tal Remez, Or Litany, Raja Giryes, and Alex M. Bronstein.
 * Image Denoising + High Level [[PDF]](https://arxiv.org/pdf/1809.01826.pdf)
   * Connecting Image Denoising and High-Level Vision Tasks via Deep Learning (Arxiv2018), Ding Liu, Bihan Wen, Jianbo Jiao, Xianming Liu, Zhangyang Wang, and Thomas S. Huang.

#### Benchmark
 * ReNOIR [[PDF]](https://arxiv.org/pdf/1409.8230.pdf) [[WEB]](http://ani.stat.fsu.edu/~abarbu/Renoir.html)
   * RENOIR - A Dataset for Real Low-Light Image Noise Reduction (JVCIR2018), Josue Anaya, Adrian Barbu.
 * Darmsdadt [[PDF]](https://arxiv.org/pdf/1707.01313.pdf) [[WEB]](https://noise.visinf.tu-darmstadt.de/)
   * Benchmarking Denoising Algorithms with Real Photographs (CVPR2017), Tobias Plotz, Stefan Roth.
 * Smartphone Cameras Dataset [[PDF]](http://www.cse.yorku.ca/~mbrown/pdf/sidd_cvpr2018.pdf)
   * A High-Quality Denoising Dataset for Smartphone Cameras (CVPR2018), Abdelrahman Abdelhamed, Stephen Lin, Michael S. Brown.
 * PolyU [[PDF]](https://arxiv.org/pdf/1804.02603.pdf) [[WEB]](https://github.com/csjunxu/PolyU-Real-World-Noisy-Images-Dataset)
   * Real-world Noisy Image Denoising: A New Benchmark (Arxiv2018), Jun Xu, Hui Li, Zhetong Liang, David Zhang, and Lei Zhang.

