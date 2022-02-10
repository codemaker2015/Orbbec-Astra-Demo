# Orbbec Unity Sample

<img src="Demo/demo.gif" alt="preview gif" width="800"/>

## Prerequisites
* Windows machine
* Orbbec Astra
* Unity 2018.2.20f1 (could work for others, but only tested with this)
* Visual Studio 2019 (could work for others, but only tested with this)

## Features
* Depth stream visualiser
* Colour stream visualiser
* Body tracking (joints only). If you stand far back enough, spheres will appear representing joints
* VFX Graph example using both depth and colour streams

## Demos
SampleScene

## How to use
* The AstraController object will allow you to turn colour, depth and body streams on and off
* If you have a body tracking license, modify the line ` AstraSdkInterop.SetLicenceKey("<INSERT YOUR LICENCE KEY>");` in `AstraController.cs` with your license

## How to update
* Download the latest Orbbec Astra SDK ([Download](UnityPackage/AstraSDK-v2.1.3.unitypackage)). 
* Import the SDK into the project.