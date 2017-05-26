# NPD face detector 
## ‘A Fast and Accurate Unconstrained Face Detector’
IEEE Transactions on Pattern Analysis and Machine Intelligence
*We propose a method to address challenges in unconstrained face detection, such as arbitrary pose variations and occlusions. First, a new image feature called Normalized Pixel Difference (NPD) is proposed. NPD feature is computed as the difference to sum ratio between two pixel values, inspired by the Weber Fraction in experimental psychology. The new feature is scale invariant, bounded, and is able to reconstruct the original image. Second, we learn the optimal subset of NPD features and their combinations via regression trees, so that complex face manifolds can be partitioned by the learned rules. This way, only a single cascade classifier is needed to handle unconstrained face detection. Furthermore, we show that the NPD features can be efficiently obtained from a look up table, and the detection template can be easily scaled, making the proposed face detector very fast (about 178 FPS for 640x480 resolution videos and 30 FPS for 1920x1080 resolution videos on a desktop PC, about 6 times faster than OpenCV). Experimental results on three public face datasets (FDDB, GENKI, and CMU-MIT) show that the proposed method outperforms the state-of-the-art methods in detecting unconstrained faces with arbitrary pose variations and occlusions in cluttered scenes.*

