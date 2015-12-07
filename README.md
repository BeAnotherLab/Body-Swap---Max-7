#Machine To Be Another - BodySwap experiment for Max 7

BeAnotherLab 2015, Creative commons non-commercial share alike. Based on the Oculus Max object by Graham Wakefield.
--

For the current Machine to Be Another hardware setup you need to do the following:

--
ON MAC 

Using Max

1. Install Oculus runtime ver. 0.44 - https://developer.oculus.com/downloads/
2. Install the oculus Max object - https://github.com/grrrwaaa/max_oculus

Standalone  

1. Install Oculus runtime ver. 0.44 - https://developer.oculus.com/downloads/
2. Download and unzip the app: http://marte.me/cloud/beanotherlab/bodyswap_mac.zip 
3. Open BodySwap.app

--
ON WINDOWS
(Runs only on 32 bit version of Max 7)

1. Install Oculus runtime ver. 0.44 - https://developer.oculus.com/downloads/
2. Install the oculus Max object - https://github.com/grrrwaaa/max_oculus

Standalone  

1. Install Oculus runtime ver. 0.44 - https://developer.oculus.com/downloads/
2. Download and unzip the exe: http://marte.me/cloud/beanotherlab/bodyswap_mac.zip
3. Open BodySwap.exe

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
