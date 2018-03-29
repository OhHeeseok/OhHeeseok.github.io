---
layout: page
title: Heeseok Oh
---

Ph.D. in Electrical and Electronic Engineering<br>
Senior Researcher @[ETRI](http://etri.re.kr)<br>
<img src="http://ohheeseok.github.io/assets/img/DSC01682_h_1024x682.jpg" alt="Drawing" style="
      width: 1024px;
      border: 5px solid #ccc;
      border-radius: 10px;
      -moz-border-radius: 10px;
      -khtml-border-radius: 10px;
      -webkit-border-radius: 10px;
      "/><br>
> Tel.: +82-42-860-5501<br>
> Email: <ohhs@etri.re.kr><br>
> [**Curriculum Vitae**](http://ohheeseok.github.io/menu/heeseokoh-cv.pdf)

***
## Research Interests
- QoE of visual contents
- Image/video quality enhancement
- Deep generative model
- Vision science
- Human factors on VR/AR/MR

***

Affiliation
---------

- Sept. 2017 - Present
:   **Senior Researcher**
:	[ETRI (Electronics & Telecommunications Research Institute)](http://etri.re.kr)
- March 2017 - Aug. 2017
:   **Senior Engineer**
:	Samsung Electronics
- March 2012 - Feb. 2017
:   **Ph.D. candidate** (Supervised by [Prof. Sanghoon Lee](http://insight.yonsei.ac.kr))
:	[EE, Yonsei Universiy](http://ee.yonsei.ac.kr)
:	*Thesis: Deep visual discomfort predictor for stereoscopic 3D images*

***

## Achievements
### SCI Journals

- [**Blind deep S3D image quality evaluation via local to global feature aggregation**](http://ieeexplore.ieee.org/abstract/document/7973187/)<br>
**Heeseok Oh**, Sewoong Ahn, Jongyoo Kim and Sanghoon Lee<br>
*IEEE Transactions on Image Processing*<br>
  <details><summary>[abs]</summary>Previously, no-reference (NR) stereoscopic 3D (S3D) image quality assessment (IQA) algorithms have been limited to the extraction of reliable hand-crafted features based on an understanding of the insufficiently revealed human visual system or natural scene statistics. Furthermore, compared with full-reference (FR) S3D IQA metrics, it is difficult to achieve competitive quality score predictions using the extracted features, which are not optimized with respect to human opinion. To cope with this limitation of the conventional approach, we introduce a novel deep learning scheme for NR S3D IQA in terms of local to global feature aggregation. A deep convolutional neural network (CNN) model is trained in a supervised manner through two-step regression. First, to overcome the lack of training data, local patch-based CNNs are modeled, and the FR S3D IQA metric is used to approximate a reference ground-truth for training the CNNs. The automatically extracted local abstractions are aggregated into global features by inserting an aggregation layer in the deep structure. The locally trained model parameters are then updated iteratively using supervised global labeling, i.e., subjective mean opinion score (MOS). In particular, the proposed deep NR S3D image quality evaluator does not estimate the depth from a pair of S3D images. The S3D image quality scores predicted by the proposed method represent a significant improvement over those of previous NR S3D IQA algorithms. Indeed, the accuracy of the proposed method is competitive with FR S3D IQA metrics, having ~ 91% correlation in terms of MOS.</details>

- [**Enhancement of visual comfort and sense of presence on stereoscopic 3D images**](http://ieeexplore.ieee.org/abstract/document/7922601/)<br>
**Heeseok Oh**, Jongyoo Kim, Jinwoo Kim, Taewan Kim, Sanghoon Lee and Alan C. Bovik<br>
*IEEE Transactions on Image Processing*<br>
  <details><summary>[abs]</summary>Conventional stereoscopic 3D (S3D) displays do not provide accommodation depth cues of the 3D image or video contents being viewed. The sense of content depths is thus limited to cues supplied by motion parallax (for 3D video), stereoscopic vergence cues created by presenting left and right views to the respective eyes, and other contextual and perspective depth cues. The absence of accommodation cues can induce two kinds of accommodation vergence mismatches (AVM) at the fixation and peripheral points, which can result in severe visual discomfort. With the aim of alleviating discomfort arising from AVM, we propose a new visual comfort enhancement approach for processing S3D visual signals to deliver a more comfortable 3D viewing experience at the display. This is accomplished via an optimization process whereby a predictive indicator of visual discomfort is minimized, while still aiming to maintain the viewer's sense of 3D presence by performing a suitable parallax shift, and by directed blurring of the signal. Our processing framework is defined on 3D visual coordinates that reflect the nonuniform resolution of retinal sensors and that uses a measure of 3D saliency strength. An appropriate level of blur that corresponds to the degree of parallax shift is found, making it possible to produce synthetic accommodation cues implemented using a perceptively relevant filter. By this method, AVM, the primary contributor to the discomfort felt when viewing S3D images, is reduced. We show via a series of subjective experiments that the proposed approach improves visual comfort while preserving the sense of 3D presence.</details>

- [**Visual presence: viewing geometry visual information of UHD S3D entertainment**](http://ieeexplore.ieee.org/abstract/document/7468498/)<br>
**Heeseok Oh** and Sanghoon Lee<br>
*IEEE Transactions on Image Processing*<br>
  <details><summary>[abs]</summary>To maximize the presence experienced by humans, visual content has evolved to achieve a higher visual presence in a series of high definition (HD), ultra HD (UHD), 8K UHD, and 8K stereoscopic 3D (S3D). Several studies have introduced visual presence delivered from content when viewing UHD S3D from a content analysis perspective. Nevertheless, no clear definition has been presented for visual presence, and only a subjective evaluation has been relied upon. The main reason for this is that there is a limitation to defining visual presence via the use of content information itself. In this paper, we define the visual presence for each viewing environment, and investigate a novel methodology to measure the experienced visual presence when viewing both 2D and 3D via the definition of a new metric termed volume of visual information by quantifying the influence of the viewing geometry between the display and viewer. To achieve this goal, the viewing geometry and display parameters for both flat and atypical displays are analyzed in terms of human perception by introducing a novel concept of pixel-wise geometry. In addition, perceptual weighting through analysis of content information is performed in accordance with monocular and binocular vision characteristics. In the experimental results, it is shown that the constructed model based on the viewing geometry, content, and perceptual characteristics has a high correlation of about 84% with subjective evaluations.</details>

- [**Stereoscopic 3D visual discomfort prediction: a dynamic accommodation and vergence interaction model**](http://ieeexplore.ieee.org/abstract/document/7348693/)<br>
**Heeseok Oh**, Sanghoon Lee and Alan C. Bovik<br>
*IEEE Transactions on Image Processing*<br>
  <details><summary>[abs]</summary>The human visual system perceives 3D depth following sensing via its binocular optical system, a series of massively parallel processing units, and a feedback system that controls the mechanical dynamics of eye movements and the crystalline lens. The process of accommodation (focusing of the crystalline lens) and binocular vergence is controlled simultaneously and symbiotically via cross-coupled communication between the two critical depth computation modalities. The output responses of these two subsystems, which are induced by oculomotor control, are used in the computation of a clear and stable cyclopean 3D image from the input stimuli. These subsystems operate in smooth synchronicity when one is viewing the natural world; however, conflicting responses can occur when viewing stereoscopic 3D (S3D) content on fixed displays, causing physiological discomfort. If such occurrences could be predicted, then they might also be avoided (by modifying the acquisition process) or ameliorated (by changing the relative scene depth). Toward this end, we have developed a dynamic accommodation and vergence interaction (DAVI) model that successfully predicts visual discomfort on S3D images. The DAVI model is based on the phasic and reflex responses of the fast fusional vergence mechanism. Quantitative models of accommodation and vergence mismatches are used to conduct visual discomfort prediction. Other 3D perceptual elements are included in the proposed method, including sharpness limits imposed by the depth of focus and fusion limits implied by Panum's fusional area. The DAVI predictor is created by training a support vector machine on features derived from the proposed model and on recorded subjective assessment results. The experimental results are shown to produce accurate predictions of experienced visual discomfort.</details>

- [**Cooperative content and radio resource allocation for visual information maximization in a digital signage scenario**](https://www.sciencedirect.com/science/article/pii/S105120041500189X)<br>
**Heeseok Oh**, Hojae Lee, Inwoong Lee and Sanghoon Lee<br>
*Digital Signal Processing*<br>
  <details><summary>[abs]</summary>In this paper, we present a cooperative content and resource allocation algorithm that selects networks and sub-carriers for digital signage scenarios based on visual information. In these scenarios, both 2D and 3D content are handled in open space for the advertisement of commercial products. To quantify visual information, we propose a quality of visual service (QoVS) metric based on human perception. We then construct the expected QoVS problem to guarantee the maximum QoVS for service users. The QoVS is determined based on the level of 2D visual sensitivity, and on the ability to perform 3D binocular fusion by users located at various viewing distances. By utilizing the QoVS, we predict wireless packet errors and loss of visual information caused by limited radio resources. After 3D content is selected to be multicasted to users by means of the large displays, sub-carriers are optimally allocated for the remaining smartphone users to facilitate point-to-point communication through lossy wireless channels. Simulation results of the proposed scheme demonstrate the advantages of automatic control of visual information and radio resources for multiple users without additional interactions. Moreover, the method developed herein can be flexibly applied with low complexity to several visual application services provided over heterogeneous displays and channels, such as advertisements, exhibitions, and forums.</details>

- [**3D visual discomfort predictor: analysis of disparity and neural activity statistics**](http://ieeexplore.ieee.org/abstract/document/6990512/)<br>
Jincheol Park, **Heeseok Oh**, Sanghoon Lee and Alan C. Bovik<br>
*IEEE Transactions on Image Processing*<br>
  <details><summary>[abs]</summary>Being able to predict the degree of visual discomfort that is felt when viewing stereoscopic 3D (S3D) images is an important goal toward ameliorating causative factors, such as excessive horizontal disparity, misalignments or mismatches between the left and right views of stereo pairs, or conflicts between different depth cues. Ideally, such a model should account for such factors as capture and viewing geometries, the distribution of disparities, and the responses of visual neurons. When viewing modern 3D displays, visual discomfort is caused primarily by changes in binocular vergence while accommodation in held fixed at the viewing distance to a flat 3D screen. This results in unnatural mismatches between ocular fixations and ocular focus that does not occur in normal direct 3D viewing. This accommodation vergence conflict can cause adverse effects, such as headaches, fatigue, eye strain, and reduced visual ability. Binocular vision is ultimately realized by means of neural mechanisms that subserve the sensorimotor control of eye movements. Realizing that the neuronal responses are directly implicated in both the control and experience of 3D perception, we have developed a model-based neuronal and statistical framework called the 3D visual discomfort predictor (3D-VDP) that automatically predicts the level of visual discomfort that is experienced when viewing S3D images. 3D-VDP extracts two types of features: 1) coarse features derived from the statistics of binocular disparities and 2) fine features derived by estimating the neural activity associated with the processing of horizontal disparities. In particular, we deploy a model of horizontal disparity processing in the extrastriate middle temporal region of occipital lobe. We compare the performance of 3D-VDP with other recent discomfort prediction algorithms with respect to correlation against recorded subjective visual discomfort scores, and show that 3D-VDP is statistically superior to the other methods.</details>

- [**Visually weighted reconstruction of compressive sensing MRI**](http://www.mrijournal.com/article/S0730-725X(12)00437-7/abstract)<br>
**Heeseok Oh** and Sanghoon Lee<br>
*Magnetic Resonance Imaging*<br>
  <details><summary>[abs]</summary>Compressive sensing (CS) enables the reconstruction of a magnetic resonance (MR) image from undersampled data in k-space with relatively low-quality distortion when compared to the original image. In addition, CS allows the scan time to be significantly reduced. Along with a reduction in the computational overhead, we investigate an effective way to improve visual quality through the use of a weighted optimization algorithm for reconstruction after variable density random undersampling in the phase encoding direction over k-space. In contrast to conventional magnetic resonance imaging (MRI) reconstruction methods, the visual weight, in particular, the region of interest (ROI), is investigated here for quality improvement. In addition, we employ a wavelet transform to analyze the reconstructed image in the space domain and fully utilize data sparsity over the spatial and frequency domains. The visual weight is constructed by reflecting the perceptual characteristics of the human visual system (HVS), and then applied to ℓ1 norm minimization, which gives priority to each coefficient during the reconstruction process. Using objective quality assessment metrics, it was found that an image reconstructed using the visual weight has higher local and global quality than those processed by conventional methods.</details>

- [**Visually weighted compressive sensing: measurement and reconstruction**](http://ieeexplore.ieee.org/abstract/document/6374249/)<br>
Hyungkeuk Lee, **Heeseok Oh**, Sanghoon Lee and Alan C. Bovik<br>
*IEEE Transactions on Image Processing*<br>
  <details><summary>[abs]</summary>Compressive sensing (CS) makes it possible to more naturally create compact representations of data with respect to a desired data rate. Through wavelet decomposition, smooth and piecewise smooth signals can be represented as sparse and compressible coefficients. These coefficients can then be effectively compressed via the CS. Since a wavelet transform divides image information into layered blockwise wavelet coefficients over spatial and frequency domains, visual improvement can be attained by an appropriate perceptually weighted CS scheme. We introduce such a method in this paper and compare it with the conventional CS. The resulting visual CS model is shown to deliver improved visual reconstructions.</details>

### Conferences
- [**No-reference perceptual sharpness assessment for ultra-high-definition images**](http://ieeexplore.ieee.org/abstract/document/7532324/)<br>
Woojae Kim, Haksub Kim, **Heeseok Oh**, Jongyoo Kim and Sanghoon Lee<br>
*IEEE International Conference on Image Processing (ICIP) 2016*<br>
  <details><summary>[abs]</summary>Since ultra-high-definition (UHD) display has larger resolution and various display size, it is necessary to measure image sharpness considering variation in visual resolution caused by diverse viewing geometry. In this paper, we propose a no-reference perceptual sharpness assessment model of UHD images. The proposed model analyzes viewing geometry in terms of display resolution and viewing environment. Then, we measure the local adaptive sharpness score in accordance with the textural motion blur, texture, and edge. In addition, we propose a spatial pooling method associated with foveal regions, which is caused by nonuniform distribution of the photoreceptors on a human retina. Through the rigorous experiments, we demonstrate that the proposed model can measure the sharpness of UHD images more accurately than other image sharpness assessment methods.</details>

- **Human gait prediction method using Microsoft Kinect**<br>
Junghwan Kim, Doyoung Kim, Inwoong Lee, Jongyoo Kim, **Heeseok Oh** and Sanghoon Lee<br>
*International Workshop on Advance Image Technology (IWAIT) 2016*<br>
  <details><summary>[abs]</summary>Real-time monitoring of elderly movement can provide valuable information regarding an individual’s degree of functional rehabilitation. Many laboratory-based studies have described various gait detection systems with different wearable inertial sensors, but only limited number of papers addressed the issues by using some non-wearable sensors. A practical method of gait information detection and gait analysis is proposed in the paper using an inexpensive Microsoft Kinect fixed on the midpoint of lower extremity rehabilitation robot. The horizontal distances between Kinect plane and every mark pasted on lower extremity are acquired. Taken the characteristics of gait distance series into consideration, the Autoregressive Moving Average (ARMA) model is established to reflect the changing rule of gait status. Combined with the Kalman filter, gait information reflecting rehabilitation status at next moment is predicted accurately. The method regarding the gait detection and gait analysis is verified by amounts of gait experiments finally.</details>

- [**3D visual discomfort predictor based on neural activity statistics**](http://ieeexplore.ieee.org/document/7351467/)<br>
**Heeseok Oh**, Jongyoo Kim, Sanghoon Lee and Alan C. Bovik<br>
*IEEE International Conference on Image Processing (ICIP) 2015*<br>
  <details><summary>[abs]</summary>Visual discomfort assessment (VDA) on stereoscopic images is of fundamental importance for making decisions regarding visual fatigue caused by unnatural binocular alignment. Nevertheless, no solid framework exists to quantify this discomfort using models of the responses of visual neurons. Binocular vision is realized by means of neural mechanisms that subserve the sensorimotor control of eye movements. We propose a neuronal model-based framework called Neural 3D Visual Discomfort Predictor (N3D-VDP) that automatically predicts the level of visual discomfort experienced when viewing stereoscopic 3D (S3D) images. The N3D-VDP model extracts features derived by estimating the neural activity associated with the processing of binocular disparities. In this regard we deploy a model of disparity processing in the extra-striate middle temporal (MT) region of occipital lobe. We compare the performance of N3D-VDP with other recent VDA algorithms using correlations against reported subjective visual discomfort, and show that N3D-VDP is statistically superior to the other methods.</details>

- [**Implementation of human action recognition system using multiple Kinect sensors**](https://link.springer.com/chapter/10.1007/978-3-319-24075-6_32)<br>
Beom Kwon, Doyoung Kim, Junghwan Kim, Inwoong Lee, Jongyoo Kim, **Heeseok Oh**, Haksub Kim and Sanghoon<br>
*Advances in Multimedia Information Processing (PCM) 2015*<br>
  <details><summary>[abs]</summary>Human action recognition is an important research topic that has many potential applications such as video surveillance, human-computer interaction and virtual reality combat training. However, many researches of human action recognition have been performed in single camera system, and has low performance due to vulnerability to partial occlusion. In this paper, we propose a human action recognition system using multiple Kinect sensors to overcome the limitation of conventional single camera based human action recognition system. To test feasibility of the proposed system, we use the snapshot and temporal features which are extracted from three-dimensional (3D) skeleton data sequences, and apply the support vector machine (SVM) for classification of human action. The experiment results demonstrate the feasibility of the proposed system.</details>

- [**Prediction of visual fatigue from spatiotemporal characteristics in stereoscopic video**](http://ieeexplore.ieee.org/document/6365436/)<br>
**Heeseok Oh** and Sanghoon<br>
*3DTV-Conference 2012*<br>
  <details><summary>[abs]</summary>Along with the increasing demand of 3D technology, the visual fatigue issue from stereoscopic video comes to the fore, which has been actively discussed in literature. Nevertheless, it is difficult to find a definite prediction model of visual fatigue in stereoscopic video due to the complexity of the human visual system (HVS). In this paper, we analyze the spatiotemporal characteristics such as depth, spatial frequency and motion. In addition, the human factor like the zone of comfort is also included to predict the visual fatigue. Consequently, we propose a novel prediction model by integrating the weights of several characteristics in stereoscopic video and verify its reliability through a subjective assessment.</details>

- [**A new block compressive sensing to control the number of measurements**](http://ieeexplore.ieee.org/document/6116229/)<br>
Hyungkeuk Lee, **Heeseok Oh** and Sanghoon<br>
*IEEE International Conference on Image Processing (ICIP) 2011*<br>
  <details><summary>[abs]</summary>Compressive Sensing (CS) aims to recover a sparse signal from a small number of projections onto random vectors. Because of its great practical possibility, both academia and industries have made efforts to develop the CS's reconstruction performance, but most of existing works remain at the theoretical study. In this paper, we propose a new Block Compres-sive Sensing (nBCS), which has several benefits compared to the general CS methods. In particular, the nBCS can be dynamically adaptive to varying channel capacity because it conveys the good inheritance of the wavelet transform.</details>

### Patents
- **Method and apparatus for quantifying visual presence**<br>
*10-1829580, KR*
- **Digital contents identification and apparatus**<br>
*10-1437286, KR*

### Awards
- **IEEE Silver Best Paper award**<br>
*IEEE Seoul Section Student Paper Contest, 2016*
- **IEEE IVMSP Workshop 2013 Volunteer Award**<br>
*IEEE Signal Processing Society, 2013*

***
