# poc-gcp-serverless-drone-stream-ai
- see https://github.com/ObrienlabsDev/drone-streaming-extraction
## Use Cases
### UC 1: Runway Surface Inspection using AM/ML on realtime RTMP Drone Streaming Video

### UC 2: Runway Surface Inspection using AM/ML on Drone based IPhone Lidar Scanning


### UC 3: Entity Extraction using AM/ML on realtime RTMP Drone Streaming Video

### UC 10: Drone Tracking via DroneID and SDR

### UC 11: Drone Tracking via attached Iphone/Android and GPS blackbox app

### UC 20: Generative-AI: Prompt for spatial or SQL queries

### UC 21: Generative-AI: Prompt for summary of High/Low entity/problem reports


## Requirements

## Introduction
A POC around a GCP AI serverless infrastructure and drone stream client
<img width="899" alt="Screenshot 2023-03-20 at 15 05 41" src="https://user-images.githubusercontent.com/24765473/226440916-3986c48d-0ab5-414d-b2fc-e333352a8926.png">

<img width="314" alt="Screenshot 2023-03-20 at 15 06 12" src="https://user-images.githubusercontent.com/24765473/226441046-7850e2c8-e1f6-4775-be8e-fccffcf55746.png">

# GPS Drone Tracking
## GPS Drone Tracking: attached iPhone 13 mini or Samsung S23
## GPS Drone Tracking: SDR - DroneID Capture
- DroneID https://github.com/RUB-SysSec/DroneSecurity/issues/2

step 1: new to SDR - setting up my B205mini using a VMware Ubuntu VM on one of older Mac's (intel chip)
Following Whitney's tutorials

- https://www.hackster.io/whitney-knitter/getting-started-with-the-ettus-b205mini-in-gnu-radio-e0d3ea
- https://www.hackster.io/whitney-knitter/basic-rf-test-verification-on-the-b205mini-with-gnu-radio-1cd612

<img width="1124" alt="Screenshot 2023-05-01 at 15 26 19" src="https://user-images.githubusercontent.com/24765473/235515634-08b90504-8220-4089-b388-efccf6722f44.png">

# Architecture

# Design
## Criteria
- Speed
- Flexibility
- Serverless

## AI Integration
Vertex AI is for custom AI development.  AutoML is for out of the box pretrained models.

## Injestion
## Preparation
Vertex AI data prep
## Entity Extraction


# Design Issues
## DI 1: GCP Infrastructure Design
## DI 2: Realtime or Offline Processing
## DI 3: Streaming Video Processing
## DI 4: LIDAR Processing
## DI 5: Network upload bandwidth issues for 5G and LTE
## DI 6: Use Drone with built in SDK/Cloud capability
Choosing a drone with built in CSP/SDK support will change the implementation.  For example the Mavic 3 Classic has the same physical characteristics as the Mavic 3 Enterprise - but without centimeter GPS, the FLIR camera or the built in Cloud SDK.
If using a lower model then an attached smartphone can replace some of this functionality.
## DI 7: Use Drone with centimeter GPS
## DI 8: Use Drone with built in FLIR camera
## DI 9: Use Drone with attached FLIR camera
There is an iphone FLIR camera available.


# Implementation

# Deliverables

# BOM : Bill of Materials

## Smartphone Hardware
## Drone Hardware
### Transport Canada Drone Pilot License
### Transport Canada Drone Registration
## Cloud Provider
## Development Environments



# FinOps

# Field Testing

# Links

# References
- https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/AVFoundationPG/Articles/04_MediaCapture.html
- 
