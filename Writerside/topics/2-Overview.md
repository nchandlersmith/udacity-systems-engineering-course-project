# Overview

## System Context

The Smart Home Security System (SHSS) operates within a residential environment, providing monitoring, event detection, and user alerting through a combination of local and cloud-connected services.

The system comprises a Central Control Unit (CCU), smart cameras, motion sensors, alarm devices, cloud services, and a mobile application. Cameras and sensors communicate with the CCU over the local residential network. The CCU handles local coordination, event processing, device management, and alarm control.

Cloud services support remote connectivity, notification delivery, and data synchronization, enabling homeowners and residents to monitor and control the system remotely through the mobile application. Core local security functions remain operational during temporary loss of internet connectivity.

Figure 2.1 shows the system context and the major interfaces between users, cloud services, and local system components.

![context diagram](../images/Context.drawio.png)

_Figure 2.1: System Context Diagram_

## System Functions

### Monitoring

SHSS continuously monitors the residential premises using connected sensing and surveillance devices, collecting motion events, video data, device status, connectivity information, and other security-related data.

### Event Detection

SHSS processes data from connected devices to detect security events such as motion, intrusion, and abnormal system conditions. Detected events are evaluated to determine appropriate alerting and alarm responses.

### Alerting and Notifications

SHSS delivers local audible alarms and remote push notifications to the mobile application for detected events and system conditions. Alert preferences and severity levels are user-configurable.

### Video Surveillance

SHSS provides authorized users with live video feeds and recorded footage through the mobile application. Recorded event video is available for review and playback.

### Remote Monitoring and Control

Authorized users can receive alerts, view live and recorded video, and manage system settings remotely through the mobile application.

### Device and System Management

SHSS manages connected devices through configuration, status monitoring, diagnostics, and maintenance support. The system performs self-diagnostics and reports system health, connectivity, and operational status through the mobile application.

## User Characteristics

### Residents

Residents are the primary occupants of the home. They use the SHSS mobile application to receive alerts, view live and recorded video, and perform limited system control functions such as arming and disarming. Residents may also manage their personal notification preferences. A typical installation supports 1–4 resident users.

### Homeowners / Admin

Homeowners or designated administrators have full access to SHSS management and monitoring functions. They are responsible for system configuration, user management, device management, and alert configuration. Each installation is expected to have 1–2 homeowner or admin accounts.

### Installers / Technicians

Installers and technicians handle initial installation, device provisioning, diagnostics, and maintenance using specialized tools and interfaces. Their access is limited to installation and maintenance functions and does not extend to normal system operation or user management. Installers are not concurrent users during regular system operation; they interact with the system only during installation and scheduled or corrective maintenance visits.
