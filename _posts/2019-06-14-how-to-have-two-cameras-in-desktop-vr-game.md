---
title: "Having two cameras in a VR-Desktop Unity game development"
classes: wide
date: 2019-10-07T12:00:00-05:00
categories:
  - Howtos
  - Development
  - Unity
tags:
  - unity
  - game development
  - HTC VIVE Pro
  - virtual reality
  - VR
  - two cameras
  - two players
---
Sometimes it is necessary to have two cameras in a Virtual Reality (VR) multiplayer game development. One is connected to the VR-Camera rig and the other one is connected to the desktop main display. Unity provides an easy solution to this end. 
{: style="text-align: justify;"}
<hr>
# 1. Check player settings
_"Virtual Reality Supported"_ option in the _player settings_ must be __checked__. Player settings in Unity is accessible under the following menu: 
<br />
"Edit -> Project settings -> Player"

# 2. Cameras settings
After adding a second camera (considered as the desktop camera) to your game scene, change its __"Target Eye"__ property to __"None (Main display)"__. Also, it is necessary to choose a __"Depth"__ greater than the VR camera rig depth.
{: style="text-align: justify;"}
![image-left]({{ site.url }}{{ site.baseurl }}/assets/images/mainDisplay.png){: .align-right}
![image-left]({{ site.url }}{{ site.baseurl }}/assets/images/VR.png){: .align-left}
asdadadad
{: style="text-align: justify;"}

<br />
<hr>
# Conclusion
{: style="text-align: justify;"}
This article tried to configure two cameras inside a Unity game in order to have two different camera perspectives at the same time, a VR head-mounted device camera perspective and a second camera perspective on the user's desktop.
{: style="text-align: justify;"}
