# Image Forgery Datasets

Image Tampering Datasets, Image Manipulations Datasets... A repo intend to collect most of datasets (training and evaluation) for the image forgery detection and localization.

图像篡改检测定位数据集收集

| Dataset name      | Image Format | Post-processing | Forgery types                | Train/Test Images | Download                          | Paper                                                        | Year                                                    |
| ----------------- | ------------ | --------------- | ---------------------------- | ----------------- | --------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| CASIA v2.0        | TIFF, JPEG   | Yes             | Splicing, copy move, removal | 715/100           | http://forensics.idealtest.org/#/ | [CASIA Image Tampering Detection Evaluation Database](https://ieeexplore.ieee.org/document/6625374) |  |
| Columbia          | TIFF         | No              | Splicing                     | 125/45            | Columbia Uncompressed Image Splicing Detection Evaluation Dataset: https://www.ee.columbia.edu/ln/dvmm/downloads/authsplcuncmp/ | [Detecting Image Splicing using Geometry Invariants and Camera Characteristics Consistency](https://ieeexplore.ieee.org/document/4036658) | 2006 |
| NIST 2016(Nimble Challenge 2016 (NC16)), NC17, MFC18         | JPEG         | Yes             | Splicing, copy move, removal | 184/50            |  NC17: https://www.nist.gov/itl/iad/mig/nimble-challenge-2017-evaluation; MFC18: https://www.nist.gov/itl/iad/mig/media-forensics-challenge-2018                                 | [MFC Datasets: Large-Scale Benchmark Datasets for Media Forensic Challenge Evaluation](https://ieeexplore.ieee.org/document/8638296) | 2019 |
| Fantastic Reality | JPEG         | No              | Splicing                     | 12000/1000        | http://zefirus.org/MAG            | [The Point Where Reality Meets Fantasy: Mixed Adversarial Generators for Image Splice Detection](https://papers.nips.cc/paper_files/paper/2019/hash/98dce83da57b0395e163467c9dae521b-Abstract.html) |  |
| Carvalho          |              |                 |                              |                   | http://www.ic.unicamp.br/tjose/files/database-tifs-small-resolution.zip (BROKEN) | [Exposing digital image forgeries by illumination color classification](https://ieeexplore.ieee.org/document/6522874) | 2013 |
| Columbia          | bmp | No | Splicing | 1845, 933 Authentic, 912 Spliced, 128 x 128 | https://www.ee.columbia.edu/ln/dvmm/downloads/AuthSplicedDataSet/AuthSplicedDataSet.htm | [A data set of authentic and spliced image blocks](https://www.semanticscholar.org/paper/A-Data-Set-of-Authentic-and-Spliced-Image-Blocks-Ng-Chang/78a604b9ff7968a12b42d6421fbbb0fb9523320f) | 2004 |
| Realistic Tampering                | TIFF |                 |                              | 220 | https://pkorus.pl/downloads/dataset-realistic-tampering | [Multi-scale analysis strategies in prnu-based tampering localization](https://ieeexplore.ieee.org/document/7776959) |  |
| COVERAGE                  | TIFF | No | Copy move | 100 pairs, 400 x486 | https://github.com/wenbihan/coverage | [COVERAGE — A novel database for copy-move forgery detection](https://ieeexplore.ieee.org/document/7532339) | ICIP '16 |
| CoMoFoD                   |              |        Yes         | Copy move                             |  260 sets                 | https://www.vcl.fer.hr/comofod/                                  |  [CoMoFoD — New database for copy-move forgery detection](https://ieeexplore.ieee.org/document/6658316) | 2013 |
|  MICC F220/F2000                 |              |                 |                              |                   |                                   | [A SIFT-Based Forensic Method for Copy–Move Attack Detection and Transformation Recovery](https://ieeexplore.ieee.org/document/5734842)                                                              | TIFS '11                                                     |
|   FAU/Manip          |              | Yes | Copy move | 48 | http://www5.cs.fau.de/research/data/image-manipulation/index.html | [An Evaluation of Popular Copy-Move Forgery Detection Approaches](https://arxiv.org/abs/1208.3665)                                                             | TIFS '12                                                    |
|  Dresden                 |              |                 |                              |                   |                                   |  [The Dresden Image Database for Benchmarking Digital Image Forensics](https://doi.org/10.1080/15567281.2010.531500)                                                            |                                                              |
| GRIP |              |                 | Copy move |                   | http://www.grip.unina.it/download/prog/CMFD/ | [Efficient dense-field copy-move forgery detection](https://ieeexplore.ieee.org/document/7154457) | TIFS '15 |
| IMD2020 |              |                 |                              | 2010 | http://staff.utia.cas.cz/novozada/db/ | [An evaluation of popular copy-move forgery detection approaches](https://arxiv.org/abs/1208.3665) | WACV '20 |
|                   |              |                 |                              |                   |                                   |                                                              |                                                              |



## Overall

#### CASIA v2

#### Fantasatic Reality

#### IMD2020

Paper: [IMD2020: A Large-Scale Annotated Dataset Tailored for Detecting Manipulated Images](https://ieeexplore.ieee.org/document/9096940)

Project Page: http://staff.utia.cas.cz/novozada/db/

Download: http://staff.utia.cas.cz/novozada/db/

#### NC16 Splicing



Appear in: [1]P. Zhuang, H. Li, S. Tan, B. Li, and J. Huang, “Image Tampering Localization Using a Dense Fully Convolutional Network,” *Ieee T Inf Foren Sec*, vol. 16, pp. 2986–2999, 2021, doi: 10.1109/tifs.2021.3070444.

1. Artificial PS dataset with post-processing on boundary (PS-boundary)

2. Artificial PS dataset with arbitrary post-processing (PS-arbitrary)
3. NIST 2016 dataset (NIST-2016)

## Image Splicing

### Train

#### Dresden(16961 images)

Paper: [The 'Dresden Image Database' for benchmarking digital image forensics](https://doi.org/10.1145/1774088.1774427) SAC '10

Official: http://forensics.inf.tu-dresden.de/dresden_image_database/ (Cannot be ACCESSED)



#### Vision(34427 images)

#### Socrates(8742 images)

#### FODB (23106 images)

#### Kaggle (2750 images)

### Test

#### Columbia (363 images, 180 spliced)

https://www.ee.columbia.edu/ln/dvmm/newDownloads.htm

Columbia Uncompressed Image Splicing DetectionColumbia Uncompressed Image Splicing Detection: https://www.dropbox.com/sh/786qv3yhvc7s9ki/AACbEEzGPrD3_y38bpWHzgdqa?dl=0

Columbia Image Splicing Detection Evaluation Dataset: https://www.dropbox.com/s/bo10et4p1zg08aj/ImSpliceDataset.rar?dl=0

#### Carvalho/DSO (200 images, 100 spliced)

#### Realistic Tampering (RT)/Korus (440 images, 220 spliced)

Description: This dataset contains 220 realistic forgeries created by hand in modern photo-editing software (GIMP and Affinity Photo) and covers various challenging tampering scenarios involving both object insertion and removal...

Citation: Pawel Korus and Jiwu Huang. **Multi-scale analysis strategiesin prnu-based tampering localization**. Trans. Info. For. Sec.,12(4):809–824, apr 2017.

Page: https://pkorus.pl/downloads/dataset-realistic-tampering

Download: [realistic-tampering-dataset.zip](https://drive.google.com/open?id=0B73Fq3C_nT4aOThud0NYWUR2MTQ) via google drive (1.7 GB)  *you'll need request access*



## Copy Move

#### GRIP

#### CPH

#### GRIP

#### CMH

#### CoMoFoD

Official: https://www.vcl.fer.hr/comofod/download.html



## Removal

## 

## Image Inpainting

## DeepFake

## Useful Link

1. [Information Forensics and Security](https://signalprocessingsociety.org/community-involvement/information-forensics-and-security/resources)
2. [Forensics Dataset](https://phdtopic.com/dataset/forensics/)
3. Pattern Recognition Lab, FAU,  https://lme.tf.fau.de/category/dataset/



| Name     | Paper | Project | Download | Type | Remarks |
| -------- | ----- | ------- | -------- | ---- | ------- |
| Columbia |       |         |          |      |         |
| CASIA    |       |         |          |      |         |
| MICC     |       |         |          |      |         |
| IMD      |       |         |          |      |         |
| CoMoFoD  |       |         |          |      |         |
| COVERAGE |       |         |          |      |         |
| GRIP     |       |         |          |      |         |
| FAU      |       |         |          |      |         |
|          |       |         |          |      |         |

