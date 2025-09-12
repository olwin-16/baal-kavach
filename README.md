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

<br>

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

## System Workflow
<br>
<p align="center">
  <img width="1000" alt="Steps" src="https://github.com/user-attachments/assets/c1eae50d-46c1-4791-9446-ab0a6f3a4220" />
  </p>

## **Software Architecture (MERN Stack Web Portal)**

- **Frontend**: React-based UI for real-time child location display, history maps, route tracking, and emergency alert management.
- **Backend**: Node.js/Express server facilitates device data ingestion, API endpoints for mobile/web clients.
- **Database**: MongoDB stores geolocation history, user profiles, and device states securely.

## Achievement

*BAAL KAVACH covered in **Divya Bhaskar**, highlighting the innovation in child safety technology and community impact.*

<br>

<p align="center">
  <img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/4f56b704-89b4-4131-abef-e71c791c3501" />
  </p>

## **Intellectual Property & Security Compliance**

This project is currently under Intellectual Property Rights (IPR) application; source code and schematics are confidential and withheld from public release to protect inventive methods and system security.

## Contact

For questions, feedback, or collaboration inquiries regarding the BAAL KAVACH project, please reach out:

**Email**: baalkavach@gmail.com

Feel free to open issues or discussions on this repository for project-related topics.
