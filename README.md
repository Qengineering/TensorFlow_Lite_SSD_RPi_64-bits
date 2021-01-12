# TensorFlow_Lite_SSD_RPi_64-bits
![output image]( https://qengineering.eu/images/James_24.jpg )<br/>
## TensorFlow Lite SSD running at 24 FPS on a bare Raspberry Pi 4 64-OS <br/>
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)<br/><br/>

A fast C++ implementation of TensorFlow Lite on a bare Raspberry Pi 4 64-bit OS.
Once overclocked to 1925 MHz, the app runs a whopping 24 FPS!
Without any hardware accelerator, just you and your Pi.

https://arxiv.org/abs/1611.10012 <br/>
Training set: COCO <br/>
Size: 300x300 <br/>
Frame rate V1 Lite : 24 FPS (RPi 4 @ 1925 MHz - 64 bits OS) <br/>
Frame rate V1 Lite : 17 FPS (RPi 4 @ 2000 MHz - 32 bits OS) see [32-OS](https://github.com/Qengineering/TensorFlow_Lite_SSD_RPi_32-bits)<br/>
<br/>
Special made for a Raspberry Pi 4 see [Q-engineering deep learning examples](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html) <br/>
<br/>
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/TensorFlow_Lite_SSD_RPi_64-bits/archive/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
James.mp4 <br/>
COCO_labels.txt <br/>
detect.tflite <br/>
TestTensorFlow_Lite.cpb <br/>
MobileNetV1.cpp<br/>
 <br/>
Run TestTensorFlow_Lite.cpb with Code::Blocks. Remember, you also need a working OpenCV 4 on your Raspberry. <br/>
I fact you can run this example on any aarch64 Linux system. <br/><br/>
See the movie at: https://vimeo.com/393889226


