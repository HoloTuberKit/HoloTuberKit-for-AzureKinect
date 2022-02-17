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
・Meta Quest<br>
・WindowsPC (DesktopAR with HoloSDK)<br>
 *You need to install HoloSDK. https://www.holo-sdk.com

## Capture Application
This application captures RGB and Depth image from Azure Kinect and generates RGB-D conbined image.<br>
To broadcast hologram, OBS Studio and your own YouTube account are also necessary.<br><br>
<b>OBS Studio:</b> https://obsproject.com/download  <br>
<b>YouTube:</b> https://www.youtube.com/  <br>

## Dlownload Page
https://github.com/HoloTuberKit/HoloTuberKit-for-AzureKinect/releases/tag/v.1.0.0
<br><br>
# How to Live Streaming with HoloTuber Kit
## Streaming Volumetric Video (PC -> YouTube)
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
14) Click OK.<br>
15) Select <b>[KinectCapture4PC.exe]: Viwer</b> from Window dropdown enu.<br>
16) Clik OK.<br>
    <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/10.jpg" alt="" width="400"><br>
17) Click <b>Start Streaming</b> button.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/11.jpg" alt="" width="400"><br>
18) Set information of streaming and click <b>Create broadcast and start streaming</b> button.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/06.jpg" alt="" width="400"><br>

<u>Note:</u><br>
Viewer application can receive not only YouTube Live streaming but also pre-recorded RGB-D video.<br>
If you want to use this feature please do following procedure instead of clicking <b>Start Streaming</b>.<br>
1) Open Settings of OBS Studio.
2) Click <b>Output</b> and select mp4 as recording format.
3) Click OK.
4) Click <b>Start Recording</b>. (Stop recording when recording is finished.)
5) Upload recorded video to YouTube by using web browser.

## Receiving Volumetric Video(YouTube -> AR Devices)
1) Open video in YouTube.
2) Click Share button.
3) Check the URL of the Streaming or Recorded Video.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/12.jpg" alt="" width="400"><br>
4) Launch viewer application on your device.<br>
5) Input content ID shown after "https://youtu.be/"
6) Tap Connect button.


<br><br>
# Give Me Your Feedback
I'm glad if you'll give me feedback, or tag me or use hash tag, #HoloTuberKit, when you share the video of your experience on SNS or other web-media.<br><br>
<b>Contact Me</b><br>
Twitter: @Tks_Yoshinaga (https://twitter.com/Tks_Yoshinaga)<br>
LinkedIn: Takashi Yoshinaga (https://www.linkedin.com/in/tks-yoshinaga/?locale=en_US)<br>
Instagram: tks_yoshinaga　(https://www.instagram.com/tks_yoshinaga/)<br>
<br><br>

