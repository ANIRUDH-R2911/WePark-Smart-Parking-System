# WePark-Smart-Parking-System

WePARK is an intelligent parking management solution that leverages IoT, cloud services, and mobile technologies to solve urban parking challenges. Designed and implemented as part of the **SmartBridge Internet of Things Externship**, the system allows users to monitor, reserve, and navigate to parking slots in real time.

## Tech Stack

| Component            | Technology Used               |
|----------------------|--------------------------------|
| Simulation           | [Wokwi](https://wokwi.com)     |
| Microcontroller      | ESP32                          |
| Sensors              | Ultrasonic, PIR                |
| Logic & Integration  | Node-RED                       |
| Cloud Platform       | IBM Cloud, Firebase            |
| Mobile App           | MIT App Inventor               |
| Communication        | MQTT Protocol                  |


## Key Features

- **Real-Time Slot Monitoring**  
  Ultrasonic and PIR sensors detect vehicle presence and update parking status in real time.

- **Mobile Application**  
  Developed using MIT App Inventor, the app allows users to check availability, reserve slots, and receive live updates.

- **Cloud-Based Backend**  
  Uses IBM Cloud and Firebase to manage data, push updates, and store reservation info securely.

- **Automated Entry/Exit System**  
  Servo motors act as gates, opening and closing based on sensor data and reservation status.

- **MQTT Communication**  
  Enables seamless interaction between hardware, cloud, and mobile platforms.


# Wokwi Simulator
The Wokwi simulator and the code for it can be found in the following link: [Wokwi](https://wokwi.com/projects/368676828824469505)


## Future Enhancements

- **Payment Integration**  
  Add pay-per-use functionality for monetized parking.

- **Admin Analytics Dashboard**  
  Introduce usage statistics, peak hour tracking, and occupancy trends.

- **Hardware Deployment**  
  Scale the system to real-world parking lots with robust embedded setups.

- **User Authentication**  
  Secure login and role-based access control for users and admins.


