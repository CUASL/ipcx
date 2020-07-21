# IPCx

IPCx is stand for Inter-process communication x.

The IPCx is a set of libraries and tools for Inter-process communication.
Our IPC type is publish–subscribe pattern. Now we are developing it with **matlab** and **python3** which are based on **ROS** .


## Version of Software
We developed on
software|version
----------- | -------------
WSL |Ubuntu 20.04 LTS
Python | Python 3.8.2 64 bit
Matlab| 2020a
ROS | ROS Noetic Ninjemys (ROS 1)



## Installation
1.Install WSL, Python3, Matlab 

2.Install [ROS](http://wiki.ros.org/noetic/Installation/Ubuntu)

3.Copy our library folder that located in [lib](https://github.com/CUASL/ipcx/tree/master/lib) on our github
to your project directory.

4.import our library in your code
    
python
```python
import ipcx
```
matlab
```matlab
addpath('ipcx')
```

## Usage

## Supported platforms and languages
- platforms
  - Windows 10 with WSL
  - Linux/Ubuntu
- Languages
  - Python3
  - Matlab
