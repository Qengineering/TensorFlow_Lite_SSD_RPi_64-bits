# TensorFlow_Lite_RPi_64-bits
TensorFlow Lite running at 24 FPS on bare Raspberry Pi 4 with Ubuntu

A fast C++ implementation of TensorFlow Lite on a bare Raspberry Pi 4.
The Raspberry Pi 64 bits version of Ubuntu is used as operating system.
Once overclocked to 1925 MHz, the app runs a whopping 24 FPS!
Without any hardware accelerator, just you and your Pi.

https://arxiv.org/abs/1611.10012 <br/>
Training set: COCO <br/>
Size: 300x300 <br/>
Frame rate V1 Lite : 24 FPS (RPi 4 @ 1925 MHz - 64 bits OS) <br/>
Frame rate V1 Lite : 17 FPS (RPi 4 @ 2000 MHz - 32 bits OS) see https://github.com/Qengineering/TensorFlow_Lite_RPi_32-bits<br/>
<br/>
Special made for a bare Raspberry Pi see: https://qengineering.eu/install-ubuntu-18.04-on-raspberry-pi-4.html <br/>
<br/>
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/TensorFlow_Lite_RPi_64-bits/archive/master.zip <br/>
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
I fact you can run this example on any aarch64 Linux system. <br/>

![output image]( https://qengineering.eu/images/James_24.jpg )

See the movie at: https://vimeo.com/393889226


