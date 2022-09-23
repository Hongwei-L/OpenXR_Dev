# Lenovo ThinkReality A3 PCAR App Dev

## Overview

Lenovo ThinkReality A3 is an AR glass that could tether to either PC or phone for productivity. 
See [product introduction here](https://www.lenovo.com/us/en/thinkrealitya3). 

With the release of 3.0.xxx, A3 PCAR version supports the openXR industry standard, 
which means you can develop your own XR app and run with the device. 
For app rendering interface, it supports DirectX 11/12 extension on windows. 
Support for 3DOF controller will come soon, currently you can use game controller, like XBox360 to allow user 
interact with you application.

## Quick start 
Lenovo openXR runtime supports various app development environment. All of them are based on OpenXR API.

Here are the respective sample code/project for C++,Unity, and Unreal engine.
1. **C++** Hello_xr is an C++ example to discover, load, and draw some simple geometry. https://github.com/KhronosGroup/OpenXR-SDK-Source/tree/main/src/tests/hello_xr.  
Please follow this [guide](https://github.com/KhronosGroup/OpenXR-SDK-Source/blob/main/BUILDING.md) to build it.
2. **Unity** Please follow the office guidance of Unity https://docs.unity3d.com/Packages/com.unity.xr.openxr@1.5/manual/index.html
3. **Unreal Engine** Please follow the office guidance of Unreal Engine. https://docs.unrealengine.com/5.0/en-US/developing-for-head-mounted-experiences-with-openxr-in-unreal-engine/

## Prerequisites
- **Device**    Lenovo ThinkReality A3
- **Runtime**   [PCAR Version](https://support.lenovo.com/us/en/downloads/vdm)
- **Development Software** 

   | Software     | Recommended version |
	|--------------|---------------------|
	| Visual studio |   2019 or above    |
	| Unreal Engine |  4.27 or above     |
	| Unity         |                    |

## Components in PCAR version
- Lenovo XR Shell£º Application manages to allow user start/stop openXR based application. To make your own app appear here, you should 
 xxx[**to do**]
- Lenovo VDM£º an openXR based App that manages the multiple virtual screens
- Lenovo Launcher 3D£ºAn openXR based App which has the similar functions as Lenovo XR Shell




 
