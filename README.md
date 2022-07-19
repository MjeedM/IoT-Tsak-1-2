# IoT-Tsak-1-2
Task 1: HTML page that provides Speech to Text in Arabic language using JavaScript.

Task 2: The first Synchronous Mission; runing the ESP32 and Changing its blink frequency using the Arduino IDE Desktop App and Arduino Web editor.

## Table of Contents
* [Task 1: Speach to Text](#1)
* [Task 2: ESP32-Run-Algorithm](#2)

  - [1. Using Arduino IDE desktop APP](#3)
  
  - [2. Using Arduino Web editor](#4)

<a name= "1"></a>
## Task 1: Speach to Text
Converting the Arabic speech into a text was done by taking advantage of the definitions and functions presented on the MDN website.

The service works efficiently on these browsers:

### For Desktop:
- Chrome
- Edge

### For Mobile:
- Chrome Android
- Samsung Internet
- WebView Android

## Technologies Used
- Web APIs
## Resources
- [https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition)

<a name= "2"></a>
## Task 2: ESP32 Run Algorithm

<a name= "3"></a>
### 1. Using Arduino IDE desktop APP

### Step 1:
- Download and launch Arduino IDE.
### Step 2
- Add esp32 package by going to *[File > Preferences]* and uploading this URL: https://dl.espressif.com/dl/package_esp32_index.json in the *"Additional Boards Manager   URLs"* box.
### Step 3
- Install esp32 boards package by going to *[Tools > Board: "Arduino Uno" Boards Manager]* then searches for "ESP32" and install the package.
### Step 4
- Plugin the ESP32 into our device, and choose the board by going to *[Tools > Board: "Arduino Uno" > ESP32 Arduino]*

  and select *"WEMOS D1 MINI ESP32"*.
### Step 5
- Choose the Blink program by going to *[File > Examples > 01 Basics]* then select *"Blink"*.
### Step 6
- Select the port by going to *[Tools > Port]* and choose the required port.
### Step 7
- For adjusting the frequency of the LED light, the delay values in the loop function must be changed as required.


<a name= "4"></a>
## 2. Using Arduino Web editor:
In this case, first, the Arduino Create Agent must be downloaded and installed. The agent will provide:
- Recognize Arduino boards and other supported devices connected to your computer via USB;
- Upload sketches from your web browser to your boards via USB or through a network;
- Read data from serial monitor, as well as write to it.



