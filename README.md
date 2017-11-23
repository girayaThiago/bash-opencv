### This is a fork from https://github.com/brunojus/bash-opencv.git to download OpenCV version 2.4.13

                                First Step
                                
#### Clone this project
git clone https://github.com/girayaThiago/bash-opencv.git

                            Second Step
### cd bash-opencv/
### sudo chmod +x opencv.sh
### sudo ./opencv.sh

                            Third Step

#### Enter this in terminal
1) ```pkg-config --cflags opencv```
You probably see this 
```-I/usr/local/include/opencv -I/usr/local/include```


2) ``` pkg-config --libs opencv```
You probably this in terminal
```-L/usr/local/lib -lopencv_shape -lopencv_stitching -lopencv_objdetect -lopencv_superres -lopencv_videostab -lopencv_calib3d -lopencv_features2d -lopencv_highgui -lopencv_videoio -lopencv_imgcodecs -lopencv_video -lopencv_photo -lopencv_ml -lopencv_imgproc -lopencv_flann -lopencv_core```

#### To build all C++ program 
1) ```g++ programa.cpp -o program `pkg-config --cflags --libs opencv` ```
2) ./program

#### To build this tutorial present in repository. 
1) ```g++ test_opencv.cpp -o name `pkg-config --cflags --libs opencv` ```
2) ./name HappyFish.jpg







