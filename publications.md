---
layout: page_pubs
title: Publications
permalink: /publications/
---
<br>
<img src="/assets/publications_img/icra17_adapnet1.gif" style="float: left;padding-right:2%;" width="48%">
### __AdapNet: Adaptive Semantic Segmentation in Adverse Environmental Conditions__
[Abhinav Valada](http://www2.informatik.uni-freiburg.de/~valada/), [Johan Vertens](http://www2.informatik.uni-freiburg.de/~vertens/), __Ankit Dhall__, [Wolfram Burgard](http://www2.informatik.uni-freiburg.de/~burgard/)  
*ICRA, 2017*  

<a href="javascript:void(0);" onclick="myFunction('icra17')">abstract</a> | [pdf](/assets/papers/AdapNet_icra17.pdf) | [project page + web demo](https://deepscene.cs.uni-freiburg.de) | videos [[1]](https://www.youtube.com/watch?v=E6gij6IS8n0 "AdapNet: Adaptive Semantic Segmentation in Adverse Environmental Conditions") [[2]](https://www.youtube.com/watch?v=7teAwVMTCho "cityscapes demo") [[3]](https://www.youtube.com/watch?v=cV-k0gkVfuY "autonomous navigation experiments")
<div id="icra17" style="display:none; padding-left:50%; text-align:justify;">
    Robust scene understanding of outdoor environments using passive optical sensors is an onerous and essential task for autonomous navigation. The problem is heavily characterized by changing environmental conditions throughout the day and across seasons. Robots should be equipped with models that are impervious to these factors in order to be operable and more importantly to ensure safety in the real-world. In this paper, we propose a novel semantic segmentation architecture and the convoluted mixture of deep experts (CMoDE) fusion technique that enables a multi-stream deep neural network to learn features from complementary modalities and spectra, each of which are specialized in a subset of the input space. We present results from experimentation on three publicly available datasets that contain diverse conditions including rain, summer, winter, dusk, fall, night and sunset, and show that our approach exceeds the state-of-the-art. In addition, we evaluate the performance of autonomously traversing several kilometers of a forested environment (see the video links for more info) using only the segmentation for perception.
</div>
<br><br><br><br>
<br>

<img src="/assets/publications_img/iros16_ws.gif" style="float: left;padding-right:2%;" width="48%">
### __Convoluted Mixture of Deep Experts for Robust Semantic Segmentation__
[Abhinav Valada](http://www2.informatik.uni-freiburg.de/~valada/)\*, __Ankit Dhall\*__, [Wolfram Burgard](http://www2.informatik.uni-freiburg.de/~burgard/)  
*State Estimation and Terrain Perception for All Terrain Mobile Robots Workshop at IROS, 2016*  

\* equal contribution  
<a href="javascript:void(0);" onclick="myFunction('iros16')">abstract</a> | [pdf](/assets/papers/CMoDE_iros16.pdf) | [project page + web demo](https://deepscene.cs.uni-freiburg.de)  
<div id="iros16" style="display:none; padding-left:50%; text-align:justify;">
    In this paper, we propose Convoluted Mixture of Deep Experts (CMoDE) model that enables a multi-stream deep neural network architecture to learn features from complementary modalities and spectra that are resilient to commonly observed environmental disturbances. Some of these disturbances include shadows, snow, rain and glare which vary depending with season and time of the day. Our model first adaptively weighs features from each of the individual experts and then further learns fused representations that are robust to these disturbances. We comprehensively evaluate the CMoDE model against several other existing fusion approaches and show that our proposed model exceeds the state-of-the-art.
</div>
<br><br><br><br><br>

<img src="/assets/publications_img/hcomp15.gif" style="float: left;padding-right:2%;" width="48%">
### __On Optimizing Human-Machine Task Assignments__
[Andreas Veit](https://www.cs.cornell.edu/~andreas/) , [Michael Wilber](http://mjwilber.org/) , [Rajan Vaish](https://stanford.edu/~rvaish/), [Serge Belongie](https://vision.cornell.edu/se3/people/serge-belongie/) , [Prof. James Davis](https://users.soe.ucsc.edu/~davis/), ..., __Ankit Dhall__, et al.  
*Work-in-Progress at HCOMP, 2015*  

<a href="javascript:void(0);" onclick="myFunction('hcomp15')">abstract</a> | [pdf](/assets/papers/humanMachine_hcomp15.pdf) | [arXiv](https://arxiv.org/abs/1509.07543)  <br><br>
<br>
<div id="hcomp15" style="display:none; padding-left:50%; text-align:justify;">
    When crowdsourcing systems are used in combination with machine inference systems in the real world, they benefit the most when the machine system is deeply integrated with the crowd workers. However, if researchers wish to integrate the crowd with "off-the-shelf" machine classifiers, this deep integration is not always possible. This work explores two strategies to increase accuracy and decrease cost under this setting. First, we show that reordering tasks presented to the human can create a significant accuracy improvement. Further, we show that greedily choosing parameters to maximize machine accuracy is sub-optimal, and joint optimization of the combined system improves performance.
</div>

<script>
    function myFunction(pub_name) {
        var x = document.getElementById(pub_name);
        if (x.style.display === 'none') {
            x.style.display = 'block';
        } else {
            x.style.display = 'none';
        }
}
</script>





