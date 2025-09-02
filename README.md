# **BAAL KAVACH: Child Tracking & Monitoring Device**

<br>

<img width="905" height="274" alt="logo" src="https://github.com/user-attachments/assets/27070681-d052-4d5f-8bda-fc55ea981661" />

<br>

## **Project Overview**

**BAAL KAVACH** is an IoT-based child safety and monitoring solution designed to empower parents with real-time tracking and emergency alert capabilities for their children. The device leverages GPS and GSM modules embedded within an ESP32 microcontroller system to provide reliable location updates and SOS alerting. Two physical device enclosures address different age groups: a tamper-resistant screw-mounted box for young children and a discreet portable variant for older kids.

The system transcends smartphone limitations by offering:

- Real-time GPS tracking with fallback to GSM cell tower triangulation.
- SOS emergency triggers via a dedicated button with immediate calling and alerting.
- Geofencing capability to notify when children stray beyond safe zones.
- Battery monitoring with warning alerts for low power.
- Secure, easy-to-access parental dashboard built on MERN stack for live tracking, location history, and emergency management.

<br>

<p align="center">
  <img width="500" alt="main_banner_bg_sm - Copy" src="https://github.com/user-attachments/assets/7b04eb74-2e59-429e-9d46-50e7fcf9d06b" />
  </p>

<br> 

By embedding the device into everyday child accessories like school bags, **BAAL KAVACH** provides a practical, scalable, and privacy-conscious child safety platform uniquely suited to Indian families and school environments.

## **Hardware Architecture**

### **Key Components**

- **•	Seeed Studio XIAO ESP32C3 Microcontroller**: Central processing and communication hub.
- **•	A9G GSM/GPRS + GPS Module**: Provides location positioning and cellular connectivity.
- **3.7V 1000mAh Li-Po Battery**: Optimizes battery life and incorporates low-power operation modes.
- **•	Tactile SOS Button (SMD)**: Long-press trigger for distress signals and calls.
- **Mini SPDT Slide Switch**: Turn ON/OFF Device.

### **Device Enclosures**

- **Screw-Mounted Variant**: Anti-tampering design ideal for young children
- **Portable Variant**: Lightweight, discreet, suitable for older kids
  
| Front View                       | Back View                        | Side View                       |
|---------------------------------|---------------------------------|--------------------------------|
| <img src="https://github.com/user-attachments/assets/ebb0fb5e-1937-4c64-be65-cbd5b3d54319" width="600" /> | <img src="https://github.com/user-attachments/assets/e8ade32e-bfb2-4448-83ac-c7a394b3db7c" width="800" /> | <img src="https://github.com/user-attachments/assets/6414d0e8-7d10-4ceb-b362-5e7b83193a11" width="800" /> |


## **Software Architecture (MERN Stack Web Portal)**

- **Frontend**: React-based UI for real-time child location display, history maps, route tracking, and emergency alert management.
- **Backend**: Node.js/Express server facilitates device data ingestion, API endpoints for mobile/web clients.
- **Database**: MongoDB stores geolocation history, user profiles, and device states securely.

| Home           | Login          | Products       | Cart           | My Orders      | 
|----------------|----------------|----------------|----------------|----------------|
| <img width="1280" height="701" alt="image" src="https://github.com/user-attachments/assets/1733743d-eae7-4797-bbd5-13323e82dbc5" /> | <img width="1280" height="702" alt="image" src="https://github.com/user-attachments/assets/bbd47795-6a13-485d-a947-548ebacfe093" /> | <img width="1280" height="701" alt="image" src="https://github.com/user-attachments/assets/1fb0d7de-623d-450b-b406-028f1d1f348e" /> | <img width="1280" height="699" alt="image" src="https://github.com/user-attachments/assets/1b53a7c3-2429-4e51-bddd-be419c2a6fd8" /> | <img width="1279" height="700" alt="image" src="https://github.com/user-attachments/assets/8eaca38a-3be4-4982-aaa5-8a575727fac8" /> |

| Dashboard      | Dashboard Location Map | Contact Us   | Work Flow             | About Us       |
|----------------|------------------------|--------------|-----------------------|----------------|
| <img width="1280" height="701" alt="image" src="https://github.com/user-attachments/assets/41832b58-3282-45aa-a5af-ad5cf5f6a6b8" /> | <img width="1280" height="699" alt="image" src="https://github.com/user-attachments/assets/cbb76c29-6843-49d5-8b6d-7e06a54e3d0b" /> | <img width="1280" height="701" alt="image" src="https://github.com/user-attachments/assets/0b18c694-d692-4391-8eae-39350fab3bed" /> | <img width="1280" height="700" alt="image" src="https://github.com/user-attachments/assets/c3417586-f545-47b0-b382-b826431d3775" /> |
