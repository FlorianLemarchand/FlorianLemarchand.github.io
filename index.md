---
layout: default
---

I am currently working at CEA-Leti in Grenoble as Engineer-Researcher. I develop learning-based algorithms for biology as part of the [H2020 REVEAL project](https://reveal-h2020.eu/).

I pursued my PhD at [IETR](https://www.ietr.fr/?lang=en) / [INSA Rennes](https://www.insa-rennes.fr/en.html). My PhD, defended on the 29th of September 2021, was directed by [Maxime Pelcat](http://mpelcat.org/) and advised by [Erwan Nogues](https://www.linkedin.com/in/erwan-nogues-88090a5/). The manuscript entitled "Deep-learning based Exploitation of Eavesdropped Images" is available following [this link](https://tel.archives-ouvertes.fr/tel-03475345).


# "Image and AI" Reading Group


With the objective to collectively develop a better general understanding of Artificial Intelligence applied to image processing, I proposed to my former team the creation of a lecture group on that topic. The group at that time met every two weeks. Each session lasts around one hour and consists of a member presenting a concept or a paper followed by discussions. 


Nicolas Beuve PhD student in the Vaader team is now in charge of the animation and keeps a [website updated here](https://beuve.github.io/vaader-air/). Do not hesitate to contact him if you wish to participate.


<br />

# "Towards Eavesdropped Image Denoising" Course

<div style="text-align: justify">

This course is an introduction to image denoising with an application to eavesdropped images restoration. It is made for beginners in image processing. The course has been designed for a 2 hours lecture and 2 practical work sessions of 1 hour and 45 minutes each.

 </div>

<div style="text-align: justify">

The first practical work (PW1) introduces some Python manipulations for image processing and presents basic filterings. At the end of PW1, BM3D is used as an expert-based denoising method. 

 </div>

<div style="text-align: justify">

PW2 unrolls the prototyping of a learning-based denoiser for Additive White Gaussian Noise (AWGN), namely DnCNN. PyTorch framework is used. Pre-trained models are given to avoid hardware issues and long waiting. Once the entire pipeline experienced, the denoiser is adapted to deal with eavesdropped images. Performance comparison is done with basic filters used in PW1. 

 </div>

<div style="text-align: justify">

Do not hesitate to contact me if you would like to discuss the content of this course.  

 </div>

<br />

[Lecture Slides](./ressources/pdfs/2020-06-11-Towards_Eavesdropped_image_denoising.pdf)

[PWs GitHub link](https://github.com/FlorianLemarchand/formation_eavesdropping_denoising)


<br />

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
