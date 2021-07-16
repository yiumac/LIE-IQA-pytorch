# LIE-IQA

The [Pytorch](https://pytorch.org/) implementattion of LIE-IQA. 

You can get the [MindSpore](https://www.mindspore.cn/) implementation here. It is worth noting that the MindSpore implementation of Image Intrinsic Decomposition (IID) Module is different from the Pytorch implementation , but there is not much difference in performance. Please refer to the specific code for details.

### Requirements

+ Python3
+ Pytorch 1.6
+ Torchvision
+ cuda 10.2

### Quality Assessment for Enhanced Low-light Image

+ LIE-IQA Framework

  <img src="fig/LIE-IQA-Framework.png" width="100%" />

+ Performance on LIE-IQA Dataset

  <img src="fig/performance-LIE-IQA-Dataset.png" width="80%"/>

+ Performance on General Scene IQA Dataset
  + LIVE, MDID, CSIQ
  
  <img src="fig/performance-IQA-Dataset.png" width="100%" />

### Quality Optimization for Low-light Image Enhancement

+ Optimization framework

  <img src="fig/optimization-framework.png" width="80%" />

+ Qualitative comparison of the quality optimization result

  + DALE[1]

   <img src="fig/LIEIQA-DALE-Optimization.png" width="100%" />


+ Quantitative comparison of the quality optimization result
  + SSIM, NIQE, DISTS, hyperIQA and our LIE-IQA

  <img src="fig/quantitative-comparison-result.png" width="80%" />

#### References

[1]Kwon, Dokyeong, Guisik Kim, and Junseok Kwon. "DALE: Dark Region-Aware Low-light Image Enhancement." arXiv preprint arXiv:2008.12493 (2020).

