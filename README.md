# Iris Liveness Detection Using a Cascade of Dedicated Deep Learning Networks
Juan Tapia, Sebastian Gonzalez, Christoph Busch

In this paper, we present the approach that won the LivDet-Iris 2020 competition using two-class scenarios (bona fide iris images vs. presentation attack iris images). Additionally, we propose new three-class and four-class scenarios that complement the competition results. These methods use a serial architecture based on a MobileNetV2 modification, trained from scratch to classify bona fide iris images versus presentation attack images. The bona fide class consists of live iris images, whereas the attack presentation instrument classes consist of cadaver, printed, and contact lenses images, for a total of four species. All the images were pre-processed and weighted per class to present a fair evaluation. This approach is primarily focused on detecting the bona fide class over improving the detection of presentation attack instruments. For the two, three, and four classes scenarios BPCER10 values of 0.99%, 0.16%, and 0.83% were obtained respectively, whereas for the BPCER20 values of 3.09%, 0.16%, and 3.77% were obtained, with the best model overall being the proposed 3-class serial model. This work reaches competitive results according to the reported results in the LivDet-Iris 2020 competition.


## Database:

Iris-printed-CL1, containing high- quality presentation attack images of printed PAIs was created. The goal of this database is to increase the challenge of the printed irises species, due to the noticeable visible patterns in the printed images from the LivDet-Iris 2020 database, which makes them trivial to distinguish from bona fide images. See Figure 1. The iris-printed-CL1 database contains 1,800 images captured with two smartphone devices (900 images each one): a Nokia 9 PureView device, with an image resolution of 1280 × 957 pixels, and a Motorola Moto G4 Play device, with an image resolution of 1280 × 960 pixels. Only the red channel was used.

<p align="center">

<img width="456" alt="Captura de pantalla 2022-10-11 a las 8 57 14 a  m" src="https://user-images.githubusercontent.com/45126159/195017615-118dcdf5-3607-4453-b866-8cc34cb3839b.png">

</p>

Download -Iris Printed (1,8K): [here](https://www.dropbox.com/s/ultjbevfre61gfl/Iris_printed_CL1.zip?dl=0).
Download -Iris Bonafide (10K):[here](https://www.dropbox.com/s/6sjejdym61hceu6/Livdet-bonafide-new.zip?dl=0).
## Cite:

```
@ARTICLE{9634048,
  author={Tapia, Juan E. and Gonzalez, Sebastian and Busch, Christoph},
  journal={IEEE Transactions on Information Forensics and Security}, 
  title={Iris Liveness Detection Using a Cascade of Dedicated Deep Learning Networks}, 
  year={2022},
  volume={17},
  number={},
  pages={42-52},
  doi={10.1109/TIFS.2021.3132582}}

```

## Disclaimer
This dataset is available only for research purpose.
Questions: juan.tapia-farias@h-da.de
