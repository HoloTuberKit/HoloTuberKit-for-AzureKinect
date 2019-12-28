# HoloTuber Application
Simple Volumetric Video capture &amp; AR visualizer. 3D image is reconstructed from RGB-D images wihch are broadcasted via YouTube.<br>
[![](https://img.youtube.com/vi/IeaHt6bBw1o/0.jpg)](https://www.youtube.com/watch?v=IeaHt6bBw1o)

# Files Included
## Hologram Viewer
Following version of hologram viewer application which recieve and visualize hologram are avairable on Android devices.<br>
・ARCore <br>
・Vuforia<br>
・Aryzon<br>

## Hologram Capture
This application captures RGB and Depth image from Azure Kinect and generates RGB-D merged image to send YouTube.<br>
You can use normal version or middle resolution version. (Please note the middle resolution version is not stable so far)<br>
To broadcast hologram, OBS Studio and your own YouTube account are also necessary.<br>
OBS Studio: https://obsproject.com/ja/download  <br>
YouTube: https://www.youtube.com/  <br>

#How to Live Streaming with Capture Application
1) Download and unzip either file shown below.<br>
  <b>AzureKinectCapture.zip</b> or <b>AzureKinectCapture_MidResolution(Unstable).zip</b><br>
2) Copy all files inclued in the directry of Azure Kinect SDK.<br>
  <i>C:\Program Files\Azure Kinect SDK v1.3.0\sdk\windows-desktop\amd64\release\bin</i>
3) Connect a Azure Kinect with a PC.<br>
4) Launch <b>KinectCapture4PC.exe</b>.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/01.jpg" alt="" width="400"><br>

5) Open and login YouTube<br>
6) Click <b>Go live</b> button <br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/03.jpg" alt="" width="400"><br>
7) Click <b>CREATE STREAM</b> button after finishing to input a name of the streaming and set some propertis.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/04.jpg" alt="" width="400"><br>
8) Copy <b>Stream name</b><br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/05.jpg" alt="" width="400"><br>

9) Launch <b>OBS Studio</b>.<br>
10) Open Settings<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/02.jpg" alt="" width="400"><br>
11) Open <b>Stream</b> and select <b>YouTube</b>, <b>Primary TouTube ingest serever</b>.<br>
12) Paste Streaming Key which you copied earlier.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/06.jpg" alt="" width="400"><br>
13) Open <b>Video</b> to set resolution referring to following information.<br>
   <b>Base Resolution</b> : 640x288 (or 960x432 for Middle resolution)<br>
   <b>Output Resolution</b> : 640x288 (or 960x432 for Middle resolution)<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/07.jpg" alt="" width="400"><br>
14) Click Add button of Source area placed lower area.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/08.jpg" alt="" width="400"><br>
15) Click <b>Window Capture</b>.<br>
16) Click OK.<br>
17) Select <b>[KinectCapture4PC.exe]: Viwer</b> from Window.<br>
18) Clik OK.<br>
    <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/10.jpg" alt="" width="400"><br>
19) Click <b>Start Streaming</b><br>
 <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/10.jpg" alt="" width="400"><br>
