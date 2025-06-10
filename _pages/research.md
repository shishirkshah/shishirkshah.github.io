---
layout: default
permalink: /research/
title: research
description: Research areas and projects in the Quantitative Imaging Lab
nav: true
nav_order: 2
---

# Human Motion and Behavior Analysis

<img src="{{ '/assets/img/research/5floor.png' | relative_url }}" alt="Human Motion Analysis" class="research-image-float">

<p>Human behavior has been extensively studied by sociologists to understand social interactions and crowd dynamics. It has been argued that characteristics that dictate human motion constitute a complex interplay between human physical, environmental, and psychosocial characteristics. It is a common observation that people, whenever free to move about in an environment, tend to respect certain patterns of movement. More often, these patterns of movement are dominated by social mechanisms.</p>

<p>While much of computer vision has focused on studies that try to model the physical and environmental characteristics, psychosocial influences have largely been overlooked. Broadly speaking, human motion attributed to psychological and sociological characteristics may be evaluated at three distinct levels; individual, interaction among individuals, and group dynamics.</p>

<p>Studies of collective locomotion have shown that social interactions play an important role in structuring human behavior, which in turn influences local human motion. Humans when together in large gatherings orient their actions to each other and move in concert with each other. In contrast, individuality of a human and the notion of accounting for independent decision making ability leads to possibilities of emergent behaviors.</p>

<p>Human movements are generally driven by purpose, making decisions locally based on the extent of information available and the cognitive capacity for calculation, prediction, and action. Each of these distinct observations have led to formalisms that either try to model human motion dynamics as a flow with fluid-like properties or consider human motion to be individualistic with local interactions leading to complex dynamics.</p>

<p>The prior formalism assumes the motion of individuals to follow the overall dynamics in an environment to maintain continuum while the latter focuses on self-organizing effects. In either case, our ability to increase our understanding of human motion and activity can be extended through the development of models and algorithms that integrate social cues that codify human behavior.</p>

<p>Our interests and research efforts in this area have led to contributions of algorithms that propose models to code human-human and human-environment interactions through fundamentals of proxemics. These have been successfully applied to problems in human tracking, detection of groups of people, human group activity recognition, and leveraging of group structures for re-identification of humans across distributed camera networks.</p>

<p>This research has been and continues to be supported in part by the National Institute of Standards and Technology, US Army Research Labs and the Department of Justice.</p>

<img src="{{ '/assets/img/research/network_structure.png' | relative_url }}" alt="Network Structure" class="research-img">

# Wide-Area Surveillance

<img src="{{ '/assets/img/research/frame418.png' | relative_url }}" alt="Wide-Area Surveillance" class="research-image-float">

<p>This effort is related to the problem of target acquisition, tracking, and recognition in a sparse sensor network. While multiple cameras with overlapping field of view can enhance the capability and performance of video surveillance applications, providing fault-tolerance and robustness for issues such as object occlusion by achieving overlapping field of views across a large multi-camera network is not always feasible.</p>

<p>This requires coordination and synchronization of cameras within the network, which is not dependent on the target object. In addressing these challenges, our research goals have been to develop an intelligent, non-obtrusive, real-time, continuous monitoring system for assessing activity and predicting emergent suspicious and criminal behavior across a network of distributed cameras.</p>

<p>The envisioned system consists of two main modules, namely:</p>
<ol>
  <li>A non-obtrusive tracking system that can continuously:
    <ul>
      <li>Track all objects across a network of distributed cameras</li>
      <li>Analyze the spatio-temporal movement pattern of each object</li>
      <li>Detect and measure descriptive information continuously of each tracked object</li>
    </ul>
  </li>
  <li>A decision system that can:
    <ul>
      <li>Correlate each object's spatio-temporal patterns with others and generate models of suspicious/criminal activity</li>
      <li>Generate activity alerts for security personnel who monitor and make critical decisions</li>
    </ul>
  </li>
</ol>

<p>To that extent, over the past 5 years, we have successfully:</p>
<ul>
  <li>Functionalized a state-of-the-art distributed surveillance camera network with over 25 cameras (indoors and outdoors) for data collection and validation studies</li>
  <li>Developed multi-human tracking algorithms capable of robust object label management and trajectory generation</li>
  <li>Developed algorithms for human reacquisition (re-identification) across non-overlapping cameras</li>
  <li>Developed models and algorithms for activity analysis</li>
  <li>More recently, developed algorithms for recovering (predicting) motion trajectories of tracked objects across non-overlapping cameras</li>
</ul>

<p>This research has been and continues to be supported in part by the US Army Research Labs, The Texas Advanced Research Program, National Science Foundation, and the Department of Justice.</p>

<img src="{{ '/assets/img/research/log_165.png' | relative_url }}" alt="Surveillance Log" class="research-img">

# Facial Analysis

<img src="{{ '/assets/img/research/Views.png' | relative_url }}" alt="Facial Analysis" class="research-image-float">

<p>Face recognition is one of the most attractive biometric since it can be done passively and unobtrusively at a comfortable distance. In addressing the challenges across the multitude of applications, many face recognition systems have been developed over the past few years.</p>

<p>Most facial matching systems rely on two-dimensional (2D) facial images and their performance is broadly affected by varying illumination conditions, change in pose, and poor image quality (e.g., blurry images, low resolution). Systems leveraging strictly 2D facial image analysis have high false accept/reject rates, suboptimal response time scaling with database size, and strict pose/illumination acquisition requirements.</p>

<p>On the other hand, three-dimensional (3D) face recognition does not suffer from inherent problems of pose and illumination variations. Nonetheless, it is not feasible to limit such systems to only 3D data. Thus, there is a technology gap between these two types of systems (2D vs. 3D).</p>

<p>Our research interests and goals have been to bridge this gap by specifically addressing facial matching under availability of 2D images. The driving hypothesis has been that through the use of 3D model of the face and by addressing variations related to pose, illumination, and resolution, it is possible to improve face matching and in general facial analysis.</p>

<p>To that extent, much of our research contributions have been related to developing methods and systems for:</p>
<ul>
  <li>Face recognition</li>
  <li>Facial image super-resolution</li>
  <li>Illumination modeling and correction</li>
  <li>Facial landmark detection</li>
  <li>Robust facial signature extraction</li>
</ul>

<p>This research has been and continues to be supported in part by the US Army Research Labs, and the Intelligence Advanced Research Projects Activity.</p>

<style>
/* Base styles */
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  line-height: 1.6;
  color: #333;
  max-width: 900px;
  margin: 0 auto;
  padding: 0 1em;
}

h1 {
  font-size: 2em;
  margin-top: 1.5em;
  margin-bottom: 1em;
  color: #2a5885;
  clear: both;
}

h2 {
  font-size: 1.5em;
  margin-top: 1.5em;
  margin-bottom: 1em;
  color: #2a5885;
}

p {
  margin-bottom: 1em;
}

ul, ol {
  margin-bottom: 1em;
  padding-left: 2em;
}

li {
  margin-bottom: 0.5em;
}

/* Image styles */
.research-image-float {
  float: right;
  width: 300px;
  margin: 0 0 1em 2em;
  border: 10px solid white;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.research-img {
  display: block;
  max-width: 100%;
  height: auto;
  margin: 2em auto;
  border: 10px solid white;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  clear: both;
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .research-image-float {
    float: none;
    width: 100%;
    max-width: 400px;
    margin: 1em auto;
  }
}
</style> 