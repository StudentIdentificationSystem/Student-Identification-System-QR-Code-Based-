# Student-Identification-System-QR-Code-Based-

## Developers Name :  Bashayer Alghamdi

## Short Introduction : 

University campuses serve as a microcosm of society, attracting individuals from diverse backgrounds who converge to pursue educational and professional endeavors. While this diversity can be advantageous, it also introduces intricate security challenges, potentially resulting in unauthorized access and identity theft. The project's motivation is to automate and modernize the current student identification within Al-Imam University by implementing a digital card containing a Quick Response Code (QR Code) and essential student information such as the student's name, ID, and picture. The project's significance lies in enhancing security, safeguarding university resources and assets against theft, and defending the campus from potential intruders. The project introduces a campus security solution. It enhances the student identification system by using a smart door to scan the QR code embedded in the digital card.
Moreover, it includes a system to monitor students' check-in and check-out activities, ensuring proper usage of their cards and preventing unauthorized attempts. The smart door features an LED indicator that activates based on the access status. This cutting-edge technology proactively safeguards our university campus by preventing unauthorized access, ensuring safety and security. In conclusion, the project enhances the campus experience for students by making the identification process faster and more convenient

## Instructions for Hardware

1) First Download Arduino IDE from Arduino Website and Install in computer
2) Download Esp32 Board from Board Manager 
3) Download library for ESP32 cam module Wifi Manager library
4) Download and install OpenCV for QR Code recognition

## Instructions for Software 
```
first install python 3.9.13
pip insatll flask
pip install firebase_admin
pip install pyribase4
pip install yagmaill
pip install pyzbar
```

## Troubleshooting Issues 
Troubleshooting issues with an ESP32-CAM module not connecting to its server involves a systematic process to identify and address potential problems. Here's a step-by-step troubleshooting process:

1. *Power Supply:*
   - *Check Power Supply:* Ensure that the ESP32-CAM module is receiving the correct power supply voltage and current. An insufficient or unstable power supply can lead to connectivity issues.

2. *Hardware Connections:*
   - *Inspect Wiring:* Verify that all the wires and connections between the ESP32-CAM module and other components (like sensors, if any) are properly connected. Loose or incorrect connections can result in communication failures.

3. *Network Connectivity:*
   - *Wi-Fi Configuration:* Confirm that the Wi-Fi credentials (SSID and password) are correctly configured in the ESP32-CAM firmware.
   - *Signal Strength:* Check if the ESP32-CAM is within the range of the Wi-Fi network and has an adequate signal strength. Weak signals can cause intermittent connectivity problems.

4. *Internet Access:*
   - *Check Internet Connection:* Ensure that the Wi-Fi network providing internet access is functioning correctly. Test other devices on the same network to confirm internet connectivity.

5. *Server Configuration:*
   - *Server Availability:* Verify that the server the ESP32-CAM is trying to connect to is operational. Check server logs for any issues.
   - *Firewall/Port Forwarding:* Ensure that the server's firewall or router is not blocking the communication port used by the ESP32-CAM. If needed, configure port forwarding on the router.

6. *Camera Module:*
   - *Camera Module Initialization:* Ensure that the camera module is initialized correctly in the firmware. Check for any errors or warnings related to the camera module in the logs.
   - *Camera Lens:* Ensure the camera lens is clean and free from any obstructions that might interfere with image capture..
7. *Reset and Restart:*
   - *Hardware Reset:* Try resetting the ESP32-CAM by power cycling it or using the hardware reset button if available.
   - *Restart Router:* If the issue persists, restart the Wi-Fi router to ensure a fresh connection attempt.
 
8. *Environmental Factors:*
    - *Interference:* Check for any sources of interference in the environment, such as other electronic devices or physical obstacles that might affect Wi-Fi signals.

9. *Debugging Tools:*
    - *Wi-Fi Analyzer:* Use a Wi-Fi analyzer tool to check for nearby Wi-Fi networks and their signal strengths. Ensure that the ESP32-CAM is on a clear channel.
     
10. *Mobile Hotspot Configuration:*
    - *Check Hotspot Settings:* Verify that the mobile phone's hotspot is active and correctly configured. Ensure that the ESP32-CAM has the correct SSID and password for the mobile hotspot.

 


## Contact Information  :  Alghamdii.bi@gmail.com 
