---
layout: page
title: Localization and Navigation
description: Enabling Indoor positioning, localization, navigation, and tracking using wireless sensors.
img: assets/img/user_example_extended.gif
importance: 1
category: work
horizontal: true
related_publications: ayyalasomayajula2020deep, zhao2021uloc, ayyalasomayajula2018bloc, wu2021sslide, wu2021sound
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/wireless_sensing.svg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


Location services, fundamentally, rely on two components: a mapping system and a positioning system. The mapping system provides the physical map of the space, and the positioning system identifies the position within the map. Outdoor location services have thrived over the last couple of decades because of well-established platforms for both these components (e.g. Google Maps for mapping, and GPS for positioning). In contrast, indoor location services haven’t caught up because of the lack of reliable mapping and positioning frameworks, as GPS is known not to work indoors. There are many important problems to be solved to enable real-time positioning and tracking for INdoors that can enable aplications ranging from **navigation and localization** that demand sub-meter accuracy, to **Robot Automatio, tracking, and last-mile delivery** that require sub-10cm accuracy to **VR Tracking and other Mixed Reality** systems that need sub-cm accurate tracking of either the users, user devices, robots or IoT devices.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/localization_issues.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
Two of the major issues for localization and navigation using wireless-sensors is the need to overcome two major issues with wireless transmissions: Multipath and Non-Line of Sight issues. My research focuses on solving these issues to achieve accurate indoor localization and navigation for Wi-Fi devices in [DLoc](https://wcsng.ucsd.edu/dloc/) and open-sourced the first largest dataset called [WILD](https://wcsng.ucsd.edu/wild/); also to achieve low-power localization using BLE devices in [BLoc](https://wcsng.ucsd.edu/bloc/); and UWB based industrial assets localization based on the upcoming industrial FiRa standards in [ULoc](https://wcsng.ucsd.edu/uloc/) that achieves 14x better battery life while achiieving 5x times better localization accuracy and stability compared to the COTS devices.