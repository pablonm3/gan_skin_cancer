## Synthetic skin cancer image generation using GANS: done during AI Hackaton

The well talked problem for AI in healthcare is sparse data, medical data have several governament regulations(HIPPA) and it is very sensitive information of patients. The one that we can think to solve this problem is generating synthetic data which mimic the real data. This solution  mantains the security and also achieve accurate results for AI models. 

In this hackathon we have tried to generate synthetic skin cancer images using Generative adversal networks(GAN's). we have obtained the data from [ISIC 2018 data archive](https://challenge2018.isic-archive.com). We have employed [DCGAN](https://arxiv.org/pdf/1511.06434.pdf) for this purpose.


#### How you can recreate work
* Download the data unsinf the following command
`$sh download_data.sh`
* Run the jupyter notebook `skin_cancer_data_gan.ipynb`
`


 

