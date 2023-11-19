

IG-20 ieGeek IP camera video stream player for TouchDesigner, tested: 2022.32120. Comes with an `arp` scanner for local network and default blob track. The equipment has sensor-triggered night vision shown in the floating window.

```
(change incoming machine at:)
op('/project1/ig20_iegeekcam/video_display/stream_in').par.url
(camera working stream:)
rtsp://192.168.1.x/2
rtsp://192.168.1.x/11
```
![cam1](https://github.com/luisarandas/touchdesigner-ig20-iegeekcam/assets/30077568/f696d623-999c-4711-a5ef-7e8963f42767)

References:

https://derivative.ca/UserGuide/Interoperability  
https://derivative.ca/UserGuide/Video_Stream_In_TOP      
https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/arp  
