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
  <img width="800" alt="Software Flowchart-2025-04-19-124629" src="https://github.com/user-attachments/assets/fadae3f9-efc1-46e7-b201-e14bdf4c4fb8" />
  </p>

<br> 

By embedding the device into everyday child accessories like school bags, **BAAL KAVACH** provides a practical, scalable, and privacy-conscious child safety platform uniquely suited to Indian families and school environments.

## **Hardware Architecture**

### **Key Components**

- **Seeed Studio XIAO ESP32C3 Microcontroller**: Central processing and communication hub.
- **A9G GSM/GPRS + GPS Module**: Provides location positioning and cellular connectivity.
- **3.7V 1000mAh Li-Po Battery**: Optimizes battery life and incorporates low-power operation modes.
- **Tactile SOS Button (SMD)**: Long-press trigger for distress signals and calls.
- **Mini SPDT Slide Switch**: Turn ON/OFF Device.

### **Device Enclosures**

- **Screw-Mounted Variant**: Anti-tampering design ideal for young children
- **Portable Variant**: Lightweight, discreet, suitable for older kids

## Video Demonstration

<a href="https://youtu.be/oVxxKt-42K8?si=YZpx2336I1ODqVJx" target="_blank">Watch Video</a>

<br>
  
| Front View                       | Back View                        | Side View                       |
|---------------------------------|---------------------------------|--------------------------------|
| <img src="https://github.com/user-attachments/assets/ebb0fb5e-1937-4c64-be65-cbd5b3d54319" width="600" /> | <img src="https://github.com/user-attachments/assets/e8ade32e-bfb2-4448-83ac-c7a394b3db7c" width="800" /> | <img src="https://github.com/user-attachments/assets/6414d0e8-7d10-4ceb-b362-5e7b83193a11" width="800" /> |

## System Workflow

<p align="center">
  <img width="800" alt="Steps" src="https://github.com/user-attachments/assets/c1eae50d-46c1-4791-9446-ab0a6f3a4220" />
  </p>

## **Software Architecture (MERN Stack Web Portal)**

- **Frontend**: React-based UI for real-time child location display, history maps, route tracking, and emergency alert management.
- **Backend**: Node.js/Express server facilitates device data ingestion, API endpoints for mobile/web clients.
- **Database**: MongoDB stores geolocation history, user profiles, and device states securely.

| Home           | Login          | Products       | Cart           | My Orders      | 
|----------------|----------------|----------------|----------------|----------------|
| <img width="1280" height="701" alt="image" src="https://github.com/user-attachments/assets/1733743d-eae7-4797-bbd5-13323e82dbc5" /> | <img width="1280" height="702" alt="image" src="https://github.com/user-attachments/assets/bbd47795-6a13-485d-a947-548ebacfe093" /> | <img width="1089" height="518" alt="image" src="https://github.com/user-attachments/assets/257c2c5b-e9d0-453b-a6b1-176105589f3b" /> | <img width="972" height="417" alt="image" src="https://github.com/user-attachments/assets/97a005af-83d6-4d3a-b914-eb798cebb149" /> | <img width="706" height="430" alt="image" src="https://github.com/user-attachments/assets/703785bc-88bf-4231-a485-32f2d8903aef" /> |

| Dashboard      | Dashboard Location Map | Contact Us   | System Workflow             | About Us       |
|----------------|------------------------|--------------|-----------------------|----------------|
| <img width="988" height="581" alt="image" src="https://github.com/user-attachments/assets/1806fe6e-de6d-4f92-a9a9-e9e993fc7e5e" /> | <img width="1280" height="699" alt="image" src="https://github.com/user-attachments/assets/cbb76c29-6843-49d5-8b6d-7e06a54e3d0b" /> | <img width="1037" height="474" alt="image" src="https://github.com/user-attachments/assets/7334909e-fa81-4632-ab93-d55181566197" /> | <img width="1070" height="608" alt="image" src="https://github.com/user-attachments/assets/58596665-4417-4fc3-9bdd-add7bbef930c" /> | <img width="887" height="497" alt="image" src="https://github.com/user-attachments/assets/78b91db2-d2d7-4b08-801a-10f6bea56964" /> |

## Achievement

*BAAL KAVACH covered in **Divya Bhaskar**, highlighting the innovation in child safety technology and community impact.*

<p align="center">
  <img width="500" alt="image" src="https://github.com/user-attachments/assets/4f56b704-89b4-4131-abef-e71c791c3501" />
  </p>

## **Intellectual Property & Security Compliance**

This project is currently under Intellectual Property Rights (IPR) application; source code and schematics are confidential and withheld from public release to protect inventive methods and system security.

## Contact

For questions, feedback, or collaboration inquiries regarding the BAAL KAVACH project, please reach out:

**Email**: baalkavach@gmail.com

Feel free to open issues or discussions on this repository for project-related topics.
