# RK5D remote control configuration

## 1. Software responsibilities
![software](gv/sw.png)

### Overview
Remote user connects to the controlling PC via free AnyDesk software - which provides full remote desktop control and sound streaming. Sound quality may be question for improvement, however current setup (namely an optical connection at the controlling - i.e. shack - side, and a GPON + WiFi at the client side) normally provide an acceptable connection speed for usage in both CW and SSB, given recorded messages are played back at the controlled PC for SSB. There was no need for connecting a remote microphone for us, however that's a point for further investigation.

Using the remote desktop approach instead of configuring each piece of software for network access provides more flexibility - as all software is used local mode, no limitations caused by usage over network are applied and all the network configuration changes - if any - have to be applied just to AnyDesk configuration rather than to all software as it would have been should we configure each application for remote usage individually. Moreover, any software not supporting network control may be used.

## 2. Hardware connections
![hardware](gv/hw.png)
