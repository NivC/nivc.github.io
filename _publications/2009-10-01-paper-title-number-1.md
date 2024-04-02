---
title: "PANDA: Adapting Pretrained Features for Anomaly Detection and Segmentation"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2021
venue: 'CVPR'
paperurl: [cvf](https://openaccess.thecvf.com/content/CVPR2021/papers/Reiss_PANDA_Adapting_Pretrained_Features_for_Anomaly_Detection_and_Segmentation_CVPR_2021_paper.pdf)
citation: 'Tal Reiss*, **Niv Cohen***</b>, Liron Bergman, Yedid Hoshen. *Conference on Computer Vision and Pattern Recognition (CVPR)*, 2021.
---

Anomaly detection methods require high-quality features. In recent years, the anomaly detection community has attempted to obtain better features using advances in deep self-supervised feature learning. Surprisingly, a very promising direction, using pre-trained deep features, has been mostly overlooked. In this paper, we first empirically establish the perhaps expected, but unreported result, that combining pre-trained features with simple anomaly detection and segmentation methods convincingly outperforms, much more complex, state-of-the-art methods. In order to obtain further performance gains in anomaly detection, we adapt pre-trained features to the target distribution. Although transfer learning methods are well established in multi-class classification problems, the one-class classification (OCC) setting is not as well explored. It turns out that naive adaptation methods, which typically work well in supervised learning, often result in catastrophic collapse (feature deterioration) and reduce performance in OCC settings. A popular OCC method, DeepSVDD, advocates using specialized architectures, but this limits the adaptation performance gain. We propose two methods for combating collapse: i) a variant of early stopping that dynamically learns the stopping iteration ii) elastic regularization inspired by continual learning. Our method, PANDA, outperforms the state-of-the-art in the OCC, outlier exposure and anomaly segmentation settings by large margins.
