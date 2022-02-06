# HoloTuber Kit for Azure Kinect
This is a simple volumetric video capture &amp; AR visualization kit. Real-time 3D image is reconstructed from RGB-D images wihch are broadcasted via YouTube.<br>
<br>
[YouTube Video] <br>
[![](https://img.youtube.com/vi/IeaHt6bBw1o/0.jpg)](https://www.youtube.com/watch?v=IeaHt6bBw1o)
<br><br>
If you'd like to try HoloTuber Kit with WebRTC, please see following repository.<br>
https://github.com/HoloTuberKit/HoloTuberKit-WebRTC-for-AzureKinect
<br><br>

# Applications
## Viewer Applications
Following version of hologram viewer application are avairable.<br>
・ARCore <br>
・nreal light<br>
・HoloLens 2<br>

## Capture Application
This application captures RGB and Depth image from Azure Kinect and generates RGB-D conbined image.<br>
To broadcast hologram, OBS Studio and your own YouTube account are also necessary.<br><br>
<b>OBS Studio:</b> https://obsproject.com/download  <br>
<b>YouTube:</b> https://www.youtube.com/  <br>
<br>
# How to Live Streaming with HoloTuber Kit
## Sending Hologram (PC -> YouTube)
1) Set display scale to 100% in display setting of Windows.<br>
2) Download and unzip  <b>KinectCaptureApp.zip</b> <br>
3) Copy all files inclued in the directry of Azure Kinect SDK.<br>
  <i>C:\Program Files\Azure Kinect SDK v1.4.1\sdk\windows-desktop\amd64\release\bin</i><br>
  This application works with <b>AzureKinect 1.4.1!</b><br>
4) Connect a Azure Kinect with a PC.<br>
5) Launch <b>KinectCapture4PC.exe</b>.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/01.jpg" alt="" width="400"><br>
6) Launch <b>OBS Studio</b>.<br>
7) Open Settings<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/02.jpg" alt="" width="400"><br>
8) Open <b>Stream</b> and select <b>YouTube</b>.<br>
9) Click <b>Content Account(recommended)</b> button and connect to your YouTube accound.<br>
<img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/03.jpg" alt="" width="400"><br>

10) Open <b>Video</b> to set resolution referring to following information.<br>
   <b>Base Resolution</b> : 1280x576<br>
   <b>Output Resolution</b> : 1280x576<br>
<img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/04.jpg" alt="" width="400"><br>
11) Click <b>OK</b> button.
12) Click <b>Add</b> button of Source area placed lower area.<br>
<img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/05.jpg" alt="" width="400"><br>
13) Click <b>Window Capture</b>.<br>
17) Click OK.<br>
18) Select <b>[KinectCapture4PC.exe]: Viwer</b> from Window dropdown enu.<br>
19) Clik OK.<br>
    <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/10.jpg" alt="" width="400"><br>
20) Click <b>Start Streaming</b> button.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/11.jpg" alt="" width="400"><br>
21) Set information of streaming and click <b>Create broadcast and start streaming</b> button.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/11.jpg" alt="" width="400"><br>


## Receiving Hologram(YouTube -> Smartphone)
1) Check the URL of the Streaming or Recorded Video.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/12.jpg" alt="" width="400"><br>
2) Launch application on your smartphone.<br>
3) Tap the input text field and input URL of your YouTube live.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/13.jpg" alt="" width="400"><br>
4) Tap Connect button.

## Receiving Hologram(YouTube -> nreal light)
1) Read QR code of YouTube Live or Recorded Video.<br>
2) Click the button of controller of nreal light<br>
<b>example</b> <br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/qr.png" alt="" width="400"><br>

<br><br>
# Give Me Your Feedback
I'm glad if you'll give me feedback, or tag me or use hash tag, #HoloTuberKit, when you share the video of your experience on SNS or other web-media.<br><br>
<b>Contact Me</b><br>
Twitter: @Tks_Yoshinaga (https://twitter.com/Tks_Yoshinaga)<br>
LinkedIn: Takashi Yoshinaga (https://www.linkedin.com/in/tks-yoshinaga/?locale=en_US)<br>
Instagram: tks_yoshinaga　(https://www.instagram.com/tks_yoshinaga/)<br>
<br><br>

