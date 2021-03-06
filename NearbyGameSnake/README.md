# NearbyGameSnake
English|[中文]()

[![](https://camo.githubusercontent.com/ce1c195eb2524e4e67a2e74bf6e9619555aa0913/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f63732d686d736775696465732d627269676874677265656e)](https://developer.huawei.com/consumer/en/doc/development/HMSCore-Guides/introduction-0000001050040566)

## Table of contents
 * [Introduction](#introduction)
 * [More Scenarios](#more-scenarios)
 * [Procedure](#procedure)
 * [Supported Environment](#supported-environment)
 * [License](#license)
 
## Introduction
The NearbyGameSnake program demonstrates a simple online snake game with Nearby Connection. Through Nearby Connection, it is easy for two smart phones to establish connection, and then play the online game together.

Game Lobby:
<img src="result_1.jpg">

In the game:
<img src="result_2.jpg">

## More Scenarios


## Procedure
* Installation
1. Register as a developer.
Register a [HUAWEI account](https://developer.huawei.com/consumer/en/).
2. Create an app.
Create an app and enable Nearby Service by referring the [Nearby Service Preparations](https://developer.huawei.com/consumer/en/doc/development/HMSCore-Guides/config-agc-0000001050040578).
3. Build the demo.

(1) To build this demo, please first import the demo in the Android Studio (3.x+). 

(2) Then download the file "agconnect-services.json" of the app on AGC, and add the file to the app root directory(\app) of the demo. Please refer to the Chapter [Integrating HMS SDK](https://developer.huawei.com/consumer/en/doc/development/HMSCore-Guides/android-integrating-sdk-0000001050126093) of the Development Guide.

(3) Change the value of applicationid in the app-level build.gradle file of the sample project to the package name of your app.

(4) Prepare two Huawei phones, and install this app by adb command to phones.

* Getting Started

1. open the app on both phones, one side clicks "Create Game", and another side clicks "Join Game" to start discovering each other.
2. After discovery is successful, the host clicks "Go" to start the game.

## Supported Environments
Android Studio 3.X or a later version is recommended.

## License
Nearby Service Connection sample is licensed under the [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

