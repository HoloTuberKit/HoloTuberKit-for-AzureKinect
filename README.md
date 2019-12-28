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
3) Connect a Azure Kinect with a PC.
4) Launch <b>KinectCapture4PC.exe</b>.
<img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/01.jpg" alt="サンプル" width="400">
