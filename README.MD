<div align="center">
   <h1> MiniAiLive License Plate Recognition Docker SDK </h1>
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

## About MiniAiLive
[MiniAiLive](https://www.miniai.live/) is a leading AI solutions company specializing in computer vision and machine learning technologies. We provide cutting-edge solutions for various industries, leveraging the power of AI to drive innovation and efficiency.

## Contact US
For any inquiries or questions, please [Contact US](https://www.miniai.live/contact/)

<p align="center">
<a target="_blank" href="https://t.me/Contact_MiniAiLive"><img src="https://img.shields.io/badge/telegram-@MiniAiLive-blue.svg?logo=telegram" alt="www.miniai.live"></a>&emsp;
<a target="_blank" href="https://wa.me/+19162702374"><img src="https://img.shields.io/badge/whatsapp-MiniAiLive-blue.svg?logo=whatsapp" alt="www.miniai.live"></a>&emsp;
<a target="_blank" href="https://join.skype.com/invite/ltQEVDmVddTe"><img src="https://img.shields.io/badge/skype-MiniAiLive-blue.svg?logo=skype" alt="www.miniai.live"></a>&emsp;
</p>
