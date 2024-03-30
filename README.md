# Image Forgery Datasets

Image Tampering Datasets, Image Manipulations Datasets... A repo intend to collect most of datasets (training and evaluation) for the image forgery detection and localization.

图像篡改检测定位数据集收集

## Summary

| Dataset name      | mask | Image Format | Post-processing | Forgery types                | Real/Forged Images | Train/Test Images | Download                          | Paper                                                        | Year                                                    |
| ----------------- | ------------ | --------------- | ---------------------------- | ----------------- | --------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------- | ----------------- |
| CASIA v1.0 | No | JPEG, TIFF |  | Splicing, copy move, removal | 800/921 |  |  |  |  |
| CASIA v2.0        | No | TIFF, JPEG, BMP | Yes             | Splicing, copy move, removal | 7491/5123 | 715/100           | http://forensics.idealtest.org/#/ , https://github.com/namtpham/casia1groundtruth , https://github.com/namtpham/casia2groundtruth | [CASIA Image Tampering Detection Evaluation Database](https://ieeexplore.ieee.org/document/6625374) | 2013 |
| Columbia Gray   | No | BMP | No | Splicing | 933/912 | 1845, 933 Authentic, 912 Spliced, 128 x 128 | https://www.ee.columbia.edu/ln/dvmm/downloads/AuthSplicedDataSet/AuthSplicedDataSet.htm | [A data set of authentic and spliced image blocks](https://www.semanticscholar.org/paper/A-Data-Set-of-Authentic-and-Spliced-Image-Blocks-Ng-Chang/78a604b9ff7968a12b42d6421fbbb0fb9523320f) | 2004 |
| Columbia Color    | Yes      | TIFF         | No              | Splicing                     | 183/180     | 125/45            | Columbia Uncompressed Image Splicing Detection Evaluation Dataset: https://www.ee.columbia.edu/ln/dvmm/downloads/authsplcuncmp/ | [Detecting Image Splicing using Geometry Invariants and Camera Characteristics Consistency](https://ieeexplore.ieee.org/document/4036658) | 2006 |
| NIST 2016(Nimble Challenge 2016 (NC16)), NC17, MFC18         |          | JPEG         | Yes             | Splicing, copy move, removal | 560/564     | 184/50            | NC17: https://www.nist.gov/itl/iad/mig/nimble-challenge-2017-evaluation; MFC18: https://www.nist.gov/itl/iad/mig/media-forensics-challenge-2018; REF: https://mfc.nist.gov/#pills-resources | [MFC Datasets: Large-Scale Benchmark Datasets for Media Forensic Challenge Evaluation](https://ieeexplore.ieee.org/document/8638296) | 2019 |
| Fantastic Reality |          | JPEG         | No              | Splicing                     | 16592/19423 | 12000/1000        | http://zefirus.org/MAG            | [The Point Where Reality Meets Fantasy: Mixed Adversarial Generators for Image Splice Detection](https://papers.nips.cc/paper_files/paper/2019/hash/98dce83da57b0395e163467c9dae521b-Abstract.html) | NeurIPS '19 |
| Carvalho          | yes | PNG | yes | splicing | 100/100 | 94, | http://www.ic.unicamp.br/tjose/files/database-tifs-small-resolution.zip (BROKEN) http://ic.unicamp.br/~rocha/pub/downloads/2014-tiago-carvalho-thesis/tifs-database.zip | [Exposing digital image forgeries by illumination color classification](https://ieeexplore.ieee.org/document/6522874) | TIFS '13 |
| Realistic Tampering                |  | TIFF |                 | object insertion , removal. |  | 220 | https://pkorus.pl/downloads/dataset-realistic-tampering | [Multi-scale analysis strategies in prnu-based tampering localization](https://ieeexplore.ieee.org/document/7776959) | TIFS '16 |
| COVERAGE                  |  | TIFF | No | Copy move |  | 100 pairs, 400 x486 | https://github.com/wenbihan/coverage | [COVERAGE — A novel database for copy-move forgery detection](https://ieeexplore.ieee.org/document/7532339) | ICIP '16 |
| [CoMoFoD](####CoMoFoD)  |              |              |        Yes         | Copy move                             |  260/260          |  260 sets                 | https://www.vcl.fer.hr/comofod/                                  |  [CoMoFoD — New database for copy-move forgery detection](https://ieeexplore.ieee.org/document/6658316) | 2013 |
|  MICC F220/F2000                 |              |              |                 | copy move | 110/110, 440/160, 1300/700 | 2200 |                                   | [A SIFT-Based Forensic Method for Copy–Move Attack Detection and Transformation Recovery](https://ieeexplore.ieee.org/document/5734842)                                                              | TIFS '11                                                     |
|   FAU/Manip          |              |              | Yes | Copy move |  | 48 | http://www5.cs.fau.de/research/data/image-manipulation/index.html | [An Evaluation of Popular Copy-Move Forgery Detection Approaches](https://arxiv.org/abs/1208.3665)                                                             | TIFS '12                                                    |
|  Dresden                 |              |              |                 |                              |                   |                   | http://forensics.inf.tu-dresden.de/ddimgdb/ |  [The Dresden Image Database for Benchmarking Digital Image Forensics](https://doi.org/10.1080/15567281.2010.531500)                                                            | SAC '10 |
| [GRIP](####GRIP) |              |              |                 | Copy move |                   |                   | http://www.grip.unina.it/download/prog/CMFD/ | [Efficient dense-field copy-move forgery detection](https://ieeexplore.ieee.org/document/7154457) | TIFS '15 |
| IMD2020 |              |              | Yes | Splicing, copy move, removal | 35000/35000 | 2010 | http://staff.utia.cas.cz/novozada/db/ | [An evaluation of popular copy-move forgery detection approaches](https://arxiv.org/abs/1208.3665) | WACV '20 |
| In the Wild | Yes |              |                 | Splicing | -/201 |                   | https://minyoungg.github.io/selfconsistency/ | [Fighting Fake News: Image Splice Detection via Learned Self-Consistency](https://arxiv.org/pdf/1805.04096.pdf) | ECCV '18 |
| DEFACTO | | | | Splicing, copy move, removal | -/229000 | | https://defactodataset.github.io/ | http://www.eurecom.fr/en/publication/5973/download/sec-publi-5973.pdf |  |
| PS-battles | | | | Splicing, copy move, removal | 11142/102028 | | https://github.com/tophatraptor/psdetector.git . Link: https://github.com/dbisUnibas/PS-Battles | [The PS-battles dataset—an image collection for image manipulation detection](https://arxiv.org/abs/1804.04866) | CoRR '18 |
| Wild Web | Yes | PNG | | splicing | 90/9657 | |  | [Detecting image splicing in the wild (WEB)](https://ieeexplore.ieee.org/abstract/document/7169839) | ICMEW '15 |
| VIPP Synth | yes | JPEG | | splicing | 4800/4800 | |  | [Image Forgery Localization via Block-Grained Analysis of JPEG Artifacts](https://ieeexplore.ieee.org/abstract/document/6151134) | TIFS '12 |
| VIPP Real | manual | JPEG | | splicing | 69/69 | |  | [Image Forgery Localization via Block-Grained Analysis of JPEG Artifacts](https://ieeexplore.ieee.org/abstract/document/6151134) | TIFS '12 |
| Reddit |  |  | |  |  | | | [Image Provenance Analysis at Scale](https://ieeexplore.ieee.org/abstract/document/8438504) | TIP '18 |
| AbhAS | | JPEG | | splicing | 45/48 | | | [AbhAS: A Novel Realistic Image Splicing Forensics Dataset](https://www.tandfonline.com/doi/full/10.1080/19361610.2020.1811059) | Journal of Applied Security Research '22 |
| MISD | Yes | JPEG | Yes | splicing | 618/300 | | https://zenodo.org/records/5525829 | [Multiple Image Splicing Dataset (MISD): A Dataset for Multiple Splicing](https://doi.org/10.3390/data6100102) | Data '21 |
| DSO-1 | Yes | JPEG |  | splicing | 100/100 | | https://recodbr.wordpress.com/code-n-data/#dso1_dsi1 | [Exposing digital image forgeries by illumination color classification](https://ieeexplore.ieee.org/abstract/document/6522874/) | TIFS '13 |
| DIS25k | Yes | JPG | deep image harmonization | splicing | 0/24964 | 21376/3588 | https://github.com/99eren99/DIS25k Dataset: https://www.kaggle.com/datasets/erentahir/dis25k |  | 2024 |
| tampCOCO | Yes |                 |                          |                              |                            |                                             | https://www.kaggle.com/datasets/qsii24/tampcoco              | [CAT-Net](https://github.com/mjkwon2021/CAT-Net) | IJCV '22 |
| compRAISE | Yes |                 |                          |                              |                            |                                             | https://www.kaggle.com/datasets/qsii24/compraise | [CAT-Net](https://github.com/mjkwon2021/CAT-Net) | IJCV '22 |
| CocoGlide |  |                 |                          |                              |                            |                                             | https://www.grip.unina.it/download/prog/TruFor/CocoGlide.zip | [TruFor: Leveraging all-round clues for trustworthy image forgery detection and localization](https://grip-unina.github.io/TruFor) | CVPR '23 |
|                                                      |        |                 |                          |                              |                            |                                             |                                                              |  | 2024 |




## Details

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

DEFACTO database

- Dataset contains over 200,000 forged images with different kind of manipulations.
- [Paper Link](http://www.eurecom.fr/en/publication/5973/download/sec-publi-5973.pdf)
- [Dataset Download Link](https://defactodataset.github.io/)

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

### Copy Move

#### GRIP

#### CPH

#### GRIP

#### CMH

#### CoMoFoD

Small image category database: 512 x 512, 200 image sets, 40 images per transformation type, total number of images with post-processed images = 10400. Large image category database (please contact us for downloading): 3000 x 2000, 60 image sets, 10/20 images per transformation type, total number of images with postprocessed images = 3120.

* Paper: [CoMoFoD — New database for copy-move forgery detection](https://ieeexplore.ieee.org/document/6658316)

* Project Page: https://www.vcl.fer.hr/comofod/download.html

* Download: 
  * https://www.vcl.fer.hr/comofod/comofod_small.rar (Official, for the 200 image sets of Small image category database) 
  * Large image category database, I would recommend you contact [sonja.grgic@fer.hr](mailto:sonja.grgic@fer.hr), a quick reply in one hour.



## Removal

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

