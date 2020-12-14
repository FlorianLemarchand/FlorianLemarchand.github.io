---
layout: default
---


I am a PhD student at [IETR](https://www.ietr.fr/?lang=en) / [INSA Rennes](https://www.insa-rennes.fr/en.html). My PhD directed by [Maxime Pelcat](http://mpelcat.org/) and advised by [Erwan Nogues](https://www.linkedin.com/in/erwan-nogues-88090a5/) started in October 2018. My main interest is on learning-based image restoration.

The ultimate goal of my work is to push further the limits of noisy signal interpretation. A particular motivation is to interpret interception images issued from electro-magnetic side channel attacks. 

# Master Internship Proposal

We are seeking for candidates for an internship titled __*Implementation of Deep-Learning Based Restoration and Interpretation Methods for Electro-Magnetic Intercepted Images*__. Do not hesitate to share this proposal and contact me if interested. 

[Proposal](ressources/pdfs/PFE_Proposal_2021.pdf)

# Publications

## [_NoiseBreaker: Gradual Image Denoising Guided by Noise Analysis_](https://arxiv.org/pdf/2002.07487.pdf)

__F. Lemarchand__, T. Findeli, [E. Nogues](https://www.linkedin.com/in/erwan-nogues-88090a5/), [M. Pelcat](http://mpelcat.org/) 

IEEE International Workshop on Multimedia Signal Processing (MMSP 2020)

[Paper](https://arxiv.org/pdf/2002.07487.pdf) 

<div style="text-align: justify"> 
Fully supervised deep-learning based denoisers are currently the most performing image denoising solutions. However, they require clean reference images. When the target noise is complex, eg composed of an unknown mixture of primary noises with unknown intensity, fully supervised solutions are limited by the difficulty to build a suited training set for the problem. This paper proposes a gradual denoising strategy that iteratively detects the dominating noise in an image, and removes it using a tailored denoiser. The method is shown to keep up with state of the art blind denoisers on mixture noises. Moreover, noise analysis is demonstrated to guide denoisers efficiently not only on noise type, but also on noise intensity. The method provides an insight on the nature of the encountered noise, and it makes it possible to extend an existing denoiser with new noise nature. This feature makes the method adaptive to varied denoising cases.
</div>  
<br />


## [_Electro-Magnetic Side-Channel Attack Through Learned Denoising and Classification_](https://arxiv.org/pdf/1910.07201.pdf)

__F. Lemarchand__, [C. Marlin](https://www.linkedin.com/in/cyril-marlin-094a381/), F. Montreuil, [E. Nogues](https://www.linkedin.com/in/erwan-nogues-88090a5/), [M. Pelcat](http://mpelcat.org/) 

IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP 2020)

[Paper](https://arxiv.org/pdf/1910.07201.pdf) - [Dataset](https://github.com/opendenoising/interception_dataset)

<div style="text-align: justify"> 
This paper proposes an upgraded Electro Magnetic (EM) sidechannel attack that automatically reconstructs the intercepted data. A novel system is introduced, running in parallel with leakage signal interception and catching compromising data on the fly. Leveraging on deep learning and Character Recognition (CR) the proposed system retrieves more than 57% of characters present in intercepted signals regardless of signal type: analog or digital. The building of the learning database is detailed and the resulting data made publicly available. The solution is based on Software-Defined Radio (SDR) and Graphics Processing Unit (GPU) architectures. It can be easily deployed onto existing information systems to detect compromising data leakage that should be kept secret.
</div>  
<br />


## [_OpenDenoising: an Extensible Benchmark for Building Comparative Studies of Image Denoisers_](https://arxiv.org/pdf/1910.08328.pdf)

__F. Lemarchand__, [E. Fernandes Montesuma](https://www.linkedin.com/in/eddardd/), [E. Nogues](https://www.linkedin.com/in/erwan-nogues-88090a5/), [M. Pelcat](http://mpelcat.org/) 

IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP 2020)

[Code](https://github.com/opendenoising/opendenoising-benchmark) - [Paper](https://arxiv.org/pdf/1910.08328.pdf) 

<div style="text-align: justify"> 
Image denoising has recently taken a leap forward due to machine learning. However, image denoisers, both expert-based and learning-based, are mostly tested on well-behaved generated noises (usually Gaussian) rather than on real-life noises, making performance comparisons difficult in real-world conditions. This is especially true for learning-based denoisers which performance depends on training data. Hence, choosing which method to use for a specific denoising problem is difficult.This paper proposes a comparative study of existing denoisers, as well as an extensible open tool that makes it possible to reproduce and extend the study. MWCNN is shown to outperform other methods when trained for a real-world image interception noise, and additionally is the second least compute hungry of the tested methods. To evaluate the robustness of conclusions, three test sets are compared. A Kendall's Tau correlation of only 60% is obtained on methods ranking between noise types, demonstrating the need for a benchmarking tool.
</div>  
<br />

## [_ToxicIA: Apprentissage Profond Appliqué à l'Analyse des Signaux Parasites Compromettants_](https://hal.archives-ouvertes.fr/hal-02378314/file/Lemarchand_IA%26D_camera_ready.pdf)

__F. Lemarchand__, [C. Marlin](https://www.linkedin.com/in/cyril-marlin-094a381/), F. Montreuil, [E. Nogues](https://www.linkedin.com/in/erwan-nogues-88090a5/), [M. Pelcat](http://mpelcat.org/) 

European Cyber Week - C&ESAR - IA & Défense (ECW 2020)

[Manuscrit](https://hal.archives-ouvertes.fr/hal-02378314/file/Lemarchand_IA%26D_camera_ready.pdf) 

<div style="text-align: justify"> 
Cet article propose une attaque par canal auxiliaireélectro-magnétique capable de reconstruire automatiquement un signal de type image. Le système proposé permet l'extraction de données compromet-tantes embarquées dans le signal intercepté. Basé sur l'apprentissage pro-fond, le système est capable d'extraire sur le jeu de test proposé plus de 57% de l'information présente dans le signal intercepté, et ce pour différents type de signal vidéo qu'ils soient analogique ou numérique. Une extension du système est proposée ayant pour but l'audit d'un système d'information grâceà un mécanisme automatique d'alarme en cas de compromission du système d'information visé. Basée sur une architecture hétérogène radio-logicielle et processeur graphique, la solution est déployable facilement dans un système d'information existant manipu-lant de l'information devant rester secrète.
</div>  
<br />
