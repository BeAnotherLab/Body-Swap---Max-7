#Machine To Be Another - BodySwap experiment for Max 7

BeAnotherLab 2015, Creative commons non-commercial share alike. Based on the Oculus Max object by Graham Wakefield.
--

For the current Machine to Be Another hardware setup you need to do the following:

--
RUNS ON MAC AND 32-bit version of Max for WINDOWS


1. Install Oculus runtime ver. 0.44 - https://developer.oculus.com/downloads/
2. Install the oculus Max object - https://github.com/grrrwaaa/max_oculus
3. Open the appropriate patcher:
  - Swap.maxpat is the body swap setup: Enter the other computer's ip in LAN, start and go into full-screen mode.
  - OSC control is the instructions player and receiver of OSC messages from touchOSC.
    1. set the audio instructions folder by dragging and droping the correct folder. 
    2. set one computer to forward OSC messages (default) and one to receive-only.
    3. enter the receive-only computer's ip in the forwarded computers patcher. Enter the forwarder computer's ip in touch OSC.

--
HARDWARE
This is the hardware and space requirements you will need for a body swap setup. TouchOSC support wasn't added yet, so you won't need a tablet
![alt tag](https://github.com/BeAnotherLab/The-Machine-to-be-Another/blob/master/files/body%20swap%20rider.png?raw=true)

--
CURRENT FRAMERATE TESTS

On a MacBook pro i7, 16GB Ram, Intel Iris pro 2GB.
  On OS X: ~60 fps
  On Windows 8 ~35 fps
  
--
FOR OLDER/SLOWER COMPUTERS:
This are recommended solutions for slower computers:

1. Change your Max video engine to Quicktime, as it allows for more flexibility
2. In the video settings window/subpatcher, select a lower. resolution for the video input. 
3. Click the settings object and select a new compression type (MPEG-4 Video is recommended) in the new window.
4. Select a compression quality in the same window and press OK
5. Press the snd_settings object in the settings subpatcher.
