<div align="center">
   <h1>License Plate Recognition Docker SDK</h1>
   <img src=https://miniai.live/wp-content/uploads/2024/02/logo_name-1-768x426-1.png alt="MiniAiLive Logo"
   width="300">
</div>

## Welcome to the [MiniAiLive](https://www.miniai.live/)!
Feel free to use our MiniAI License Plate Recognition software which uses deep neural networks to detect license plates and perform OCR.

# Demo Video

https://github.com/MiniAiLive/MiniAI-LPR-Docker/assets/153516004/5ace0784-f28b-478f-b96e-802d1abbfea7

In the above example it can be see that LPR was performed on the video and text number was extracted successfully from the license plate area.

An abundance of information such as bounding boxes, confidence scores etc are available in the raw JSON data published by the services and available to NodeRED and any other integrating service for consumption.

# Quick Start in 3 steps

The following instrctions assume you are running a linux flavor such as debian, ubuntu or popos!

## 1. Install [Docker](https://www.docker.com/get-started)
Goto https://www.docker.com/get-started and install the distribution relevant to your operating system. Consider using a convenience script to fast track the installation.
Also install docker-compose.

## 2. Clone this repo & start services
This step will take a few minutes depending on your internet connection speed. Use "bash" shell to issue the following commands

```
git clone https://github.com/MiniAiLive/MiniAI-LPR-Docker.git
cd MiniAI-LPR-Docker
docker-compose up -d
```

## 3. Open your browser and upload file to process

Use google chrome to navigate to the following address
http://localhost:5000/

## Face & IDSDK Online Demo, Resources
<div style="display: flex; justify-content: center; align-items: center;"> 
   <table style="text-align: center;">
      <tr>
         <td style="text-align: center; vertical-align: middle;"><a href="https://github.com/MiniAiLive"><img src="https://miniai.live/wp-content/uploads/2024/10/new_git-1-300x67.png" style="height: 60px; margin-right: 5px;" title="GITHUB"/></a></td> 
         <td style="text-align: center; vertical-align: middle;"><a href="https://huggingface.co/MiniAiLive"><img src="https://miniai.live/wp-content/uploads/2024/10/new_hugging-1-300x67.png" style="height: 60px; margin-right: 5px;" title="HuggingFace"/></a></td> 
         <td style="text-align: center; vertical-align: middle;"><a href="https://demo.miniai.live"><img src="https://miniai.live/wp-content/uploads/2024/10/new_gradio-300x67.png" style="height: 60px; margin-right: 5px;" title="Gradio"/></a></td> 
      </tr> 
      <tr>
         <td style="text-align: center; vertical-align: middle;"><a href="https://docs.miniai.live/"><img src="https://miniai.live/wp-content/uploads/2024/10/a-300x70.png" style="height: 60px; margin-right: 5px;" title="Documentation"/></a></td> 
         <td style="text-align: center; vertical-align: middle;"><a href="https://www.youtube.com/@miniailive"><img src="https://miniai.live/wp-content/uploads/2024/10/Untitled-1-300x70.png" style="height: 60px; margin-right: 5px;" title="Youtube"/></a></td> 
         <td style="text-align: center; vertical-align: middle;"><a href="https://play.google.com/store/apps/dev?id=5831076207730531667"><img src="https://miniai.live/wp-content/uploads/2024/10/googleplay-300x62.png" style="height: 60px; margin-right: 5px;" title="Google Play"/></a></td>
      </tr>
   </table>
</div>

## Our Products
No | Project | Feature
---|---|---|
1 | [FaceRecognition-LivenessDetection-Android-SDK](https://github.com/MiniAiLive/FaceRecognition-LivenessDetection) | Face Matching, 3D Face Passive Liveness
2 | [FaceRecognition-LivenessDetection-Windows-SDK](https://github.com/MiniAiLive/FaceRecognition-LivenessDetection-Windows-SDK) | Face Matching, 3D Face Passive Liveness
3 | [FaceLivenessDetection-Android-SDK](https://github.com/MiniAiLive/FaceLivenessDetection-Android-SDK) | 3D Face Passive Liveness
4 | [FaceLivenessDetection-Linux-SDK](https://github.com/MiniAiLive/FaceLivenessDetection-Linux-SDK) | 3D Face Passive Liveness
5 | [FaceLivenessDetection-Windows-SDK](https://github.com/MiniAiLive/FaceLivenessDetection-Windows-SDK) | 3D Face Passive Liveness
6 | [FaceMatching-Android-SDK](https://github.com/MiniAiLive/FaceMatching-Android-SDK) | 1:1 Face Matching
7 | [FaceMatching-Windows-Demo](https://github.com/MiniAiLive/FaceMatching-Windows-Demo) | 1:1 Face Matching
8 | [FaceAttributes-Android-SDK](https://github.com/MiniAiLive/FaceAttributes-Android-SDK) | Face Attributes
9 | [ID-Document-Recognition-Android-SDK](https://github.com/MiniAiLive/ID-Document-Recognition-Android-SDK) | ID Document, Credit, MRZ Recognition
10 | [ID-Document-Recognition-Linux-SDK](https://github.com/MiniAiLive/ID-Document-Recognition-Linux-SDK) | ID Document, Credit, MRZ Recognition
11 | [ID-Document-Recognition-Windows-SDK](https://github.com/MiniAiLive/ID-Document-Recognition-Windows-SDK) | ID Document, Credit, MRZ Recognition
12 | [ID-Document-LivenessDetection-Linux-SDK](https://github.com/MiniAiLive/ID-Document-LivenessDetection-Linux-SDK) | ID Document Liveness Detection
13 | [ID-Document-LivenessDetection-Windows-SDK](https://github.com/MiniAiLive/ID-Document-LivenessDetection-Windows-SDK) | ID Document Liveness Detection

## About MiniAiLive
[MiniAiLive](https://www.miniai.live/) is a leading AI solutions company specializing in computer vision and machine learning technologies. We provide cutting-edge solutions for various industries, leveraging the power of AI to drive innovation and efficiency.

## Contact US
For any inquiries or questions, please [Contact US](https://www.miniai.live/contact/)

<p align="center">
<a target="_blank" href="https://t.me/Contact_MiniAiLive"><img src="https://img.shields.io/badge/telegram-@MiniAiLive-blue.svg?logo=telegram" alt="www.miniai.live"></a>&emsp;
<a target="_blank" href="https://wa.me/+19162702374"><img src="https://img.shields.io/badge/whatsapp-MiniAiLive-blue.svg?logo=whatsapp" alt="www.miniai.live"></a>&emsp;
<a target="_blank" href="https://join.skype.com/invite/ltQEVDmVddTe"><img src="https://img.shields.io/badge/skype-MiniAiLive-blue.svg?logo=skype" alt="www.miniai.live"></a>&emsp;
</p>
