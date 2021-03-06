<p align="center">
    <img src="https://github.com/h4x0rMadness/EC500_Triangle/blob/master/pics/下载.png" width="100%"/>
</p>


# EC500_TriangleProject

## Usage

### CyberWalk iOS version

```
git clone https://github.com/h4x0rMadness/EC500_Triangle.git
```
unzip this repo folder and go into `/CyberWalk` sub folder in it.

```
cd CyberWalk
```

open the `CyberWalk.xcodeproj` in `Xcode`

<p align="center">
    <img src="https://github.com/h4x0rMadness/EC500_Triangle/blob/master/pics/icon.jpg" width="20%"/>
</p>

build and run it on your `iOS` device (won't work for `simulator`)

### Adding Targets for the game (iOS)

[Download ARKit Scanner](https://developer.apple.com/documentation/arkit/scanning_and_detecting_3d_objects)

Using ARKit Scanner to scan and save `AR Object files`

Add your `AR Object files` into `CyberWalk.xcodeproj/Assets.xcassets/exampleObjects`

### CyberWalk Android version

```
git clone https://github.com/h4x0rMadness/EC500_Triangle.git
```
Then use Android Studio and open the **NativeAndroidApp** 

in the path **/EC500_Triangle/CyberWalk_Android/NativeAndroidApp**.

Connect your android phone with computer, and run this application to download apk in your phone

### [Unity source code](https://github.com/CyberWalkec500/objectdetection)

#### [Check release](https://github.com/CyberWalkec500/objectdetection/releases)

## Introduction to the Game

We would like to explore the possiblity combining **Augmented Reality** (AR) and **Object Detection** technologies and present them with a game, which encourages players to go outside (certainly not now, stay home!), explore certain **targets** as symbols to acquire **materials** from. 

With those materials (e.g. metal, wood and so on), players are able to upgrade their **reward**, which is a product displayed in AR way (which is really cool to show friends, right?) and owned by each user. For example, with upgrading, you can upgrade your little wood house into a huge spectacular castle, also we hope we have enough time to finish social functions, which allows people to check on their friends' rewards.

## Game Logic

<p align="center">
    <img src="https://github.com/h4x0rMadness/EC500_Triangle/blob/master/pics/archi.jpg" width="70%"/>
</p>

- Step 1:   Scan the object and then get the materials from this object
- Step 2:   View the materials collected
- Step 3:   Use materials to build architecture or Upgrade the current architecture.
- Step 4:   View the current architecture in the form of virtual image
- Step 5:   View the current architecture in the form of AR.


# Final Product 

<p align="center">
    <img src="https://github.com/h4x0rMadness/EC500_Triangle/blob/master/pics/demo.gif" width="40%"/>
</p>
<p align="center">
    This is iOS Version
</p>

<p align="center">
    <img src="https://github.com/h4x0rMadness/EC500_Triangle/blob/master/pics/demo_a.gif" width="40%"/>
</p>
<p align="center">
    This is Android Version
</p>

## User Story
- As a **game player**, I want to combine online games with real life. I not only can play games on the phone, but also can take physical activities outside.
- As a **sponsor**, I want to display my product in game to attract more customers.




## Minimum Valuable Product


- **Object Detection**

  - Recognize the objects and classify them by labeling. For example, if we use a camera to scan the wooden chair, and it will return what it is and label it with wood.

- **Profile page**
  - This is a visualization page for users to see what resources and the amount they have collected. Besides, they can use these resources to build their own architecture.

- **AR**
  - When users start their camera and point to the open area, the architecture will display here by AR.

## Tech: 
- Object Detection
- Augmented Reality, Unity
- Swift, C#, Python
- AWS


# Sprint 1: 

## Taskboard:

- [x] Determine details of the game 
- [x] Display basic (level 1) reward architecture
- [ ] Connect Object Detection
- [x] Have at least one sample conversion from acquired object to materials
- [ ] \*Login/logout

# Sprint 2:

## Taskboard:

- [ ] Deployment on iOS
- [x] Other pages in app
- [x] Connect with Object Detection 
- [ ] \*Server Configuration

# Sprint 3:

## Taskboard:

- [x] Create iOS and Android Profile Page
- [x] Realize iOS and Android object detection
- [x] Display Reward architecture in AR way
