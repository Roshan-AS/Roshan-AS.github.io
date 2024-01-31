---
layout: page
title: Wireless for Robotics
description: Developing novel Wireless Sensor modalities to aid Robot Automation.
img: assets/img/robotics.jpg
importance: 3
category: work
horizontal: true
related_publications: ayyalasomayajula2020locap, arun2022p2slam, arun2022viwid
---

A recent spur of interest in indoor robotics has increased the importance of robust simultaneous localization and mapping algorithms in indoor scenarios. This robustness is typically provided by the use of multiple sensors which can correct each others’ deficiencies. In this vein, exteroceptive sensors, like cameras and LiDAR’s, employed for fusion are capable of correcting the drifts accumulated by wheel odometry or inertial measurement units (IMU’s). However, these exteroceptive sensors are deficient in highly structured environments and dynamic lighting conditions. This letter will present WiFi as a robust and straightforward sensing modality capable of circumventing these issues.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/localization.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/viwid.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The idea is to be able to readily integrate Wi-Fi as an alternative to GPS for indoor navigation for robotics as shown above. We have  already demonstrated the use of WiFI for robotic navigation as shown above, where the robots movement over three timestamp are shown in the fiture at the center, and have also designed a toolbox that can readily integrate Wi-Fi for robotics into the existing SLAM algorithms.
</div>
