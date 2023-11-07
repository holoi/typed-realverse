# reality-typography
# Abstract
This project contains all typography realities from holokit app, includes:

1. TypedRealityTheFlock
2. TypedRealityTheFingerRibbon
3. TypedRealityTheHair
4. TypedRealityTheRain
5. TypedRealityTheScanner
6. TypedRealityTheSculpture
7. TypedRealityTheTornado

# Demo

# How does it work

# System requirements
This project uses HoloKit SDK and aims to build an app runs on iOS device.
I created and built this project in Unity 2022.3.8f1, I highly recommand you use this version and above to open the project.
Make sure your Unity had install the iOS module:
  1. Some features from HoloKit SDK only works on platform of iOs. If you work on other platform, some code may fail to compile, preventing you from entering Play mode and significantly impacting your development experience.
  2. Build to an Xcode project needs iOS module.
I built this project to iPhone with Xcode 14.2.

# How to try it

# Design
## TypedRealityTheFlock

TypedRealityTheFlock creates an Stereo-AR experience, a flock of "birds" in a style of typography fly around the player and sing at same time.

### Features

To create a realistic experience, this reality uses boid algorithm to drive "birds" fly around the player.
It takes the head position (the position of the mobile device) as input to create circular movement.

In this scene, we used AR shadows on real-world ground to create a more realistic effect(shader included in this project). 

## TypedRealityTheFingerRibbon

TypedRealityTheFlock creates an Stereo-AR experience that ribbons flows along with your finger-tips.

### Features

TypedRealityTheFingerRibbon uses Hand-Tracking feature from HoloKit SDK.
Tracking the positions of all your finger-tip to create ribbons

## TypedRealityTheHair

TypedRealityTheHair creates an Stereo-AR experience that several Octopus-like long hair in a style of typography sways with your head movement.

### Features

In this scene, we use the player's head position as input to estimate the position of hair growth and attach physically responsive ribbons.

## TypedRealityTheRain

TypedRealityTheRain creates an Stereo-AR experience where a white cloud, styled like typography, follows the player(person in camera in Screen-AR mode), continuously dropping raindrops. These raindrops collide with the real-world ground, splitting and fading away.

### Features

In this reality, we use 3DBodyTracking Feature to track a person in camera in Screen-AR mode. In Stereo-AR mode, the cloud follows the player.

## TypedRealityTheScanner

TypedRealityTheScanner creates and Stereo-AR experience where  white rectangular ribbons in a style of typography on the surrounding floors, walls, and other environmental surfaces. These ribbons nest layer by layer, expanding over time.

### Features

In this reality, we use Meshing feature to get the mesh information of our surroundings in real-time, to change the material of mesh to render rectangular ribbons effect.

## TypedRealityTheSculpture

TypedRealityTheSculpture creates and Stereo-AR experience allows us to launch text particles from our fingertips, filling a human-shaped sculpture.

### Features

In this reality, we use Hand-Tracking feature from HoloKit SDK to capture player’s hand(all joints) in real-time, creating particle from index tip joint.

## TypedRealityTheTornado

This augmented reality experience creates a text storm that follows the target/player.

### Features

In this reality, we take head position as input, create a storm following the target(in Screen-AR mode)/player(in Stereo-AR mode).

# Reference

# License
