

IG-20 ieGeek IP camera video stream player for TouchDesigner, tested: 2022.32120. Comes with an `arp` scanner for local network and default blob track. The equipment has sensor-triggered night vision shown in the floating window.

```
(change incoming machine at:)
op('/project1/ig20_iegeekcam/video_display/stream_in').par.url
(camera working stream:)
rtsp://192.168.1.x/2
rtsp://192.168.1.x/11
```
![cam1](https://github.com/luisarandas/touchdesigner-ig20-iegeekcam/assets/30077568/cce1a459-8b02-4394-87a5-ec95b0da84be)

References:

https://derivative.ca/UserGuide/Interoperability  
https://derivative.ca/UserGuide/Video_Stream_In_TOP      
https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/arp  
