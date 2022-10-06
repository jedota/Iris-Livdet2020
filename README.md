# Iris Liveness Detection Using a Cascade of Dedicated Deep Learning Networks

Iris pattern recognition has significantly improved the biometric authentication field due to its high stability and uniqueness. Such physical characteristics have played an essential role in security applications and other related areas. However, presentation attacks, also known as spoofing techniques, can bypass biometric authentication systems using artefacts such as printed images, artificial eyes, textured contact lenses, etc. Many liveness detection methods that improve the robustness of these systems have been proposed. The first International Iris Liveness Detection competition, where the effectiveness of liveness detection methods is evaluated, was first launched in 2013, and its latest iteration was held in 2020. In this paper, we present the approach that won the LivDet-Iris 2020 competition using two-class scenarios (bona fide iris images vs. presentation attack iris images). Additionally, we propose new three-class and four- class scenarios that complement the competition results. These methods use a serial architecture based on a MobileNetV2 modification, trained from scratch to classify bona fide iris images versus presentation attack images. The bona fide class consists of live iris images, whereas the attack presentation instrument classes consist of cadaver, printed, and contact lenses images, for a total of four species. All the images were pre-processed and weighted per class to present a fair evaluation. This approach is primarily focused on detecting the bona fide class over improving the detection of presentation attack instruments. For the two, three, and four classes scenarios BPCER10 values of 0.99%, 0.16%, and 0.83% were obtained respectively, whereas for the BPCER20 values of 3.09%, 0.16%, and 3.77% were obtained, with the best model overall being the proposed 3-class serial model. This work reaches competitive results according to the reported results in the LivDet-Iris 2020 competition

