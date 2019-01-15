## OpenCV Qt MinGW Development
* [OpenCV Built Using MinGW](https://github.com/huihut/OpenCV-MinGW-Build)
* Qt Creator Project `.pro` file
```sh
INCLUDEPATH += C:\Tools\OpenCV\include

LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_calib3d400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_core400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_dnn400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_features2d400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_flann400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_gapi400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_highgui400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_imgcodecs400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_imgproc400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_ml400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_objdetect400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_photo400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_stitching400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_video400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\libopencv_videoio400.dll
LIBS += C:\Tools\OpenCV\x64\mingw\bin\opencv_ffmpeg400_64.dll

LIBS += -LC:\Tools\OpenCV\x64\mingw\lib \
        -lopencv_calib3d400 \
        -lopencv_core400 \
        -lopencv_dnn400 \
        -lopencv_features2d400 \
        -lopencv_flann400 \
        -lopencv_gapi400 \
        -lopencv_highgui400 \
        -lopencv_imgcodecs400 \
        -lopencv_imgproc400 \
        -lopencv_ml400 \
        -lopencv_objdetect400 \
        -lopencv_photo400 \
        -lopencv_stitching400 \
        -lopencv_video400 \
        -lopencv_videoio400
```

