PoseCamera C++ pacakge provides realtime and fast Human Pose Estimation. This package uses libtorch which is native wrapper of pytorch for deep learning model building & training. 

Repository page: https://github.com/Wonder-Tree/PoseCamera-cpp

## How to build
Clone the repo and edit cmake file `CMakeLists.txt` replace `d:/wondertree/opencv/build` & `d:/wondertree/libtorch` path to your own libs path. 

> You can download lib depency from following sites

* Libtorch https://pytorch.org/get-started/locally/
* OpenCV https://opencv.org/releases/

# Install cmake
For windows download binrary from https://cmake.org/download/ and ubuntu users can run this command `sudo apt-get install cmake`

# Build & Run

Fisrt create a build directory and go to build directory
```
mkdir build && cd build
```

Now configure project using cmake and build
```
cmake ..
make
```

Run the executable
```
./pose_camera_cpp <model-weight-file> <video-file>
```
