# tx2
## 시작
 * https://developer.nvidia.com/embedded/jetpack
   * JetPack 설치
     * JetPack 3.3
     * [설치](https://docs.nvidia.com/jetson/archives/jetpack-archived/jetpack-33/index.html#jetpack/3.3/install.htm%3FTocPath%3D_____3)
## ROS
 *  L4T 28.2 기반
```bash
$ git clone https://github.com/jetsonhacks/installROSTX2.git
$ cd installROSTX2

$ ./installROS.sh -p ros-kinetic-desktop -p ros-kinetic-rgbd-launch 

$ ./setupCatkinWorkspace.sh [optionalWorkspaceName]
```
