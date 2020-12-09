# D7AP
Implementation of D7AP Communication
OS: Ubuntu 20.04.1

Instructions
1)Clone OSS-7 Code
2)Download Cmake
3)Download J-Link
4)Download a gcc compiler (GNU arm Embedded)
5)Create a build directory
6)Go to the build directory
7)Run cmake ../dash7-ap-open-source-stack/stack/ -DAPP_GATEWAY=y -DAPP_SENSOR_PUSH=y -DAPP_SENSOR_PULL=y -DAPP_SENSOR_ACTION=y -DTOOLCHAIN_DIR=../("path to gcc directory")
8)Run make
