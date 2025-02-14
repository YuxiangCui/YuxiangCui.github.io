---
layout: page
title: Learning World Transition Model for Socially Aware Robot Navigation
description: ICRA 2021
img: /assets/img/ICRA2021/framework.png
importance: 1
category: work
---

## Abstract
- Moving in dynamic pedestrian environments is one of the important requirements for autonomous mobile robots. We present a model-based reinforcement learning approach for robots to navigate through crowded environments. The navigation policy is trained with both real interaction data from multi-agent simulation and virtual data from a deep transition model that predicts the evolution of surrounding dynamics of mobile robots. A reward function considering social conventions is designed to guide the training of the policy. Specifically, the policy model takes laser scan sequence and robot's own state as input and outputs steering command. The laser sequence is further transformed into stacked local obstacle maps disentangled from robot's ego motion to separate the static and dynamic obstacles, simplifying the model training. We observe that the policy using our method can be trained with significantly less real interaction data in simulator but achieve similar level of success rate in social navigation tasks compared with other methods. Experiments are conducted in multiple social scenarios both in simulation and on real robots, the learned policy can guide the robots to the final targets successfully in a socially compliant manner.

<center>
<table>
    <tr>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/first.png" width="800" height="582" data-zoomable></center></td>
    </tr>
</table>
<div class="caption">
   Comparison
</div>
</center>

<center>
<table>
    <tr>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/framework.png" width="800" height="414" data-zoomable></center></td>
    </tr>
</table>
<div class="caption">
   Framework
</div>
</center>

<center>
<table>
    <tr>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/transition_model.png" width="800" height="234" data-zoomable></center></td>
    </tr>
</table>
<div class="caption">
   Transition Model
</div>
</center>

<center>
<table>
    <tr>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/ac_model.png" width="600" height="290" data-zoomable></center></td>
    </tr>
</table>
</center>
<div class="caption">
   Policy Model
</div>

<center>
<table>
    <tr>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_list.png" width="200" height="100" data-zoomable> prediction_list </center></td>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_ours.png" width="200" height="100" data-zoomable> prediction_ours </center></td>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_label.png" width="200" height="100" data-zoomable> prediction_label </center></td>
    </tr>
    <tr>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_list_2.png" width="200" height="100" data-zoomable> prediction_list_2 </center></td>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_ours_2.png" width="200" height="100" data-zoomable> prediction_ours_2 </center></td>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_label_2.png" width="200" height="100" data-zoomable> prediction_label_2 </center></td>
    </tr>
</table>
</center>
<div class="caption">
   Prediction
</div>

<center>
<table>
    <tr>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/comparison_curves_ver.png" width="400" height="600" data-zoomable> Training Curves </center></td>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/experiments.png" width="400" height="600" data-zoomable> Real Robot Experiments </center></td>
    </tr>
</table>
</center>
<div class="caption">
   Experiments
</div>


