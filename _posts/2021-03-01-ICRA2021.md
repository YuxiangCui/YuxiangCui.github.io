---
layout: post
title:  ICRA 2021 -- Learning World Transition Model for Socially Aware Robot Navigation
date: 2015-05-15 21:01:00
description: Learning World Transition Model for Socially Aware Robot Navigation
---
Learning World Transition Model for Socially Aware Robot Navigation.

<div class="row">
    <div class="col">
        <img class="img" src="{{ site.baseurl }}/assets/img/ICRA2021/framework.png" data-zoomable>
    </div>
</div>
<div class="caption">
    Framework.
</div>

<div class="row">
    <div class="col">
        <img class="img" src="{{ site.baseurl }}/assets/img/ICRA2021/transition_model.png" data-zoomable>
    </div>
</div>
<div class="caption">
    Transition Model.
</div>

<div class="row">
    <div class="col">
        <img class="img" src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_list.png" data-zoomable>
    </div>
    <div class="col">
        <img class="img" src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_ours.png" data-zoomable>
    </div>
    <div class="col">
        <img class="img" src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_label.png" data-zoomable>
    </div>
</div>
<div class="row">
    <div class="col">
        <img class="img" src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_list_2.png" data-zoomable>
    </div>
    <div class="col">
        <img class="img" src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_ours_2.png" data-zoomable>
    </div>
    <div class="col">
        <img class="img" src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_label_2.png" data-zoomable>
    </div>
</div>


<table>
    <tr>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_list.png" > prediction_list </center></td>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_ours.png" > prediction_ours </center></td>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_label.png" > prediction_label </center></td>
    </tr>

    <tr>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_list_2.png" > prediction_list_2 </center></td>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_ours_2.png" > prediction_ours_2 </center></td>
        <td ><center><img src="{{ site.baseurl }}/assets/img/ICRA2021/prediction_label_2.png" > prediction_label_2 </center></td>
    </tr>
</table>
<div class="caption">
    Prediction.
</div>


- Abstract
Moving in dynamic pedestrian environments is one of the important requirements for autonomous mobile robots. We present a model-based reinforcement learning approach for robots to navigate through crowded environments. The navigation policy is trained with both real interaction data from multi-agent simulation and virtual data from a deep transition model that predicts the evolution of surrounding dynamics of mobile robots. A reward function considering social conventions is designed to guide the training of the policy. Specifically, the policy model takes laser scan sequence and robot's own state as input and outputs steering command. The laser sequence is further transformed into stacked local obstacle maps disentangled from robot's ego motion to separate the static and dynamic obstacles, simplifying the model training. We observe that the policy using our method can be trained with significantly less real interaction data in simulator but achieve similar level of success rate in social navigation tasks compared with other methods. Experiments are conducted in multiple social scenarios both in simulation and on real robots, the learned policy can guide the robots to the final targets successfully in a socially compliant manner.
