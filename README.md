# JSBridgeDemo

## Overview
This project demonstrates the integration of JavaScript and native Android code using JSBridge. Follow the steps below to set up and run the demo.

## Getting Started

### Step 1: Clone the Repository
```bash
git clone https://github.com/ncy5239/JSBridgeDemo.git
```

### Step 2: Open Project in Android Studio
1. Open Android Studio.
2. Navigate to **File -> Open** and select the `JSBridgeDemo` project folder.
3. Wait for the project to load and ensure it is viewed in **Android** mode.

### Step 3: Configure Network Settings
1. **Update IP Address in Network Security Config**  
   Open `app/res/xml/network_security_config.xml` and replace `"10.0.0.61"` with your own IPv4 address (e.g., `"192.168.123.32"`).

2. **Update IP Address in Main Activity**  
   Open `app/java/com.example.jsbridgedemo/MainActivity` and replace `"http://10.0.0.61:8080"` with your IPv4 address (e.g., `"http://192.168.123.32:8080"`).

### Step4: Start H5
```
cd H5
npm i
npm run dev
```

### Step 5: Run the App
Click **Run App** in Android Studio to launch the demo.

## How to Find Your Local IPv4 address
### Windows:
Open PowerShell/Terminal and run the command:
```bash
ipconfig
```
### Mac OS
```bash
ifconfig
```
