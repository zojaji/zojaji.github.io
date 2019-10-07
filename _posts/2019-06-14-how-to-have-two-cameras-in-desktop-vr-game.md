---
title: "How To Have Two Cameras In A VR-Desktop Game Development Using Unity?"
classes: wide
date: 2019-10-07T12:00:00-05:00
categories:
  - Howtos
tags:
  - unity
  - game development
  - HTC VIVE Pro
  - virtual reality
  - VR
  - two cameras
  - two players
---
Sometimes it is necessary to have two cameras in a Virtual Reality (VR) multiplayer game development. One is connected to the VR-Camera rig and the otherone is connected to the desktop main display. Unity provides an easy solution to handle this situation. 
{: style="text-align: justify;"}
<hr>
# 1. Check player settings
"Virtual Reality Supported" option in the player settings must be checked. Player settings in Unity is accessible under the following menu: 
<br />
"Edit -> Project settings -> Player"

# 2. Cameras settings
After adding a second camera (considered as the desktop camera) to your game scene, change its __"Target Eye"__ property to __"None (Main display)"__. Also, It is necessary to choose a __"Depth"__ greater than the VR camera rig.
{: style="text-align: justify;"}
![image-left]({{ site.url }}{{ site.baseurl }}/assets/images/mainDisplay.png){: .align-right}
![image-left]({{ site.url }}{{ site.baseurl }}/assets/images/VR.png){: .align-left}
# 3. VR camera rig settings
. 
{: style="text-align: justify;"}
