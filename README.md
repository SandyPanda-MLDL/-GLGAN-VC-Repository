# GLGAN-VC: Guided Loss based Generative Adversarial Network for  Many-To-Many Voice Conversion

***Sandipan Dhar, Student  Member,  IEEE, Nanda Dulal Jana, Member, IEEE, and Swagatam Das, Senior Member, IEEE.***

1. ***Some of the generated speech samples are presented at Google site ( link: [[https://drive.google.com/drive/folders/1WwTmvbvnfrdihNcDMm72WEsau4hd5QXf?usp=sharing](https://drive.google.com/drive/folders/1WwTmvbvnfrdihNcDMm72WEsau4hd5QXf?usp=sharing)](https://drive.google.com/drive/folders/1WwTmvbvnfrdihNcDMm72WEsau4hd5QXf?usp=sharing))***

***Links of the bench mark datasets used in this work are provided below***

1. ***VCC 2016 speech dataset link: https://datashare.ed.ac.uk/handle/10283/2211***
2. ***VCC 2018 speech dataset link: https://datashare.ed.ac.uk/handle/10283/3061***
3. ***VCC 2020 speech dataset link: https://github.com/nii-yamagishilab/VCC2020-database***
4. ***Emotional speech dataset link: https://github.com/HLTSingapore/Emotional-Speech-Data***
5. ***Google drive link of the generated speech samples: https://github.com/HLTSingapore/Emotional-Speech-Data***
6. *** Generated speech samples of PSR-StarGAN-VC are available at : https://xudongxiang.github.io/PSR-StarGAN-VC.html ***
******


******
# GLGAN-VC-code 
***Experimental details  :***

The implementation  of ***GLGAN-VC*** model and all the experiments are implemented in ***Python 3.6.9*** using ***Tensorflow 1.8***. Prepossessing of the speech samples are done using ***Librosa 0.7.2*** and ***Pyworld 0.2.8***. The ***Numpy*** version and ***Scikit-learn*** version considered here are ***1.16.1*** and ***1.0.1*** respectively. The whole process is executed in ***Dell precision 7820 workstation*** configured with ubuntu ***18.04*** ***64*** bit Operating System, ***Intel Xeon Gold 5215 2.5GHz processor***, ***96GB RAM***, and ***Nvidia 16GB Quadro RTX5000 graphics***.


The experiment was done in ***Python 3.6.9*** and packages used
here for building the ***ALGAN-VC*** model are ***Tensorflow 1.15.0***. For audio data preprocessing ***Librosa 0.7.2***
and ***Pyworld 0.2.8*** version was used. For storing the feature
information in ***.npz*** format, ***Numpy 1.15*** was used.

 - The GLGAN-VC code is developed based on the given repository code: [[https://github.com/leimao/Voice_Converter_CycleGAN](https://github.com/hujinsen/StarGAN-Voice-Conversion)](https://github.com/hujinsen/StarGAN-Voice-Conversion)
 - The objective evaluation codes are based on the given repository: https://github.com/r9y9/nnmnkwii

******

The code implementation (Jupyter Notebooks) for various objective evaluation metrics that have been used in this work are provided in this repository. The following evaluation metrics are included in this work for the performance evaluation of the VC models. 

* MCD 
* F0 RMSE
* log F0 RMSE
* MSD
* SNR
* PESQ
* GV
* MCEP Trajectory
* Modulation Spectrum
* Mean MCEP 
* MCEP Scatter Plot

# The Google form link for collecting the opinions for MOS test is available here
***Goolgle form link :***

* Google form link: https://drive.google.com/drive/folders/1WwTmvbvnfrdihNcDMm72WEsau4hd5QXf?usp=sharing
* The google site link for conducting the opinions for MOS test : https://sites.google.com/phd.nitdgp.ac.in/glgan-vc/home






 
