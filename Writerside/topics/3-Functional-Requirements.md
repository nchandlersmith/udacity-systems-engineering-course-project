# Functional Requirements

## Motion Detection

MD1: The SHSS shall monitor for motion events using connected motion sensors.
MD2: The SHSS shall generate motion detection events containing timestamp and device location information.
MD3: The SHSS shall record motion detection event data for historical review.
MD4: The SHSS shall provide authorized users with access to motion event history through the mobile application.

## Video Surveillance

VS1: The SHSS shall collect video data from connected smart cameras.
VS2: The SHSS shall provide authorized users with access to live video feeds through the mobile application.
VS3: The SHSS shall record video footage associated with detected security events.
VS4: The SHSS shall provide authorized users with access to recorded video footage through the mobile application.

## Alarm System

AS1: The SHSS shall trigger local audible alarms for detected security events based on configured alert preferences and severity levels.
AS2: The SHSS shall allow authorized users to enable or disable local audible alarms for specific event types and severity levels through the mobile application.
AS3: The SHSS shall maintain local alarm functionality during temporary loss of internet connectivity, ensuring that local audible alarms are triggered for detected events based on configured preferences and severity levels even when cloud connectivity is unavailable.

## User Notifications

UN1: The SHSS shall provide remote user notifications through the mobile application for detected security events.
UN2: The SHSS shall provide remote user notifications through the mobile application for device status and health conditions.
UN3: The SHSS shall classify notifications by the following severity levels: Information, Warning, Critical.
UN4: The SHSS shall allow authorized users to configure notification preferences by event type and severity level for security events, video surveillance events, and device status conditions.
UN5: The SHSS shall generate a notification when the system detects loss of connectivity between the CCU and cloud services.
UN6: The SHSS shall generate a notification when connectivity is restored between the CCU and cloud services.
UN7: The SHSS shall maintain a time-ordered notification history accessible to authorized users through the mobile application.

## Central Control Unit
CCU1: The SHSS shall use the Central Control Unit (CCU) to coordinate local data collection, event processing, and alarm control functions for connected devices.
CCU2: The SHSS shall use the CCU to perform local event evaluation and rule processing based on data received from connected devices.
CCU3: The SHSS shall use the CCU to manage local device connectivity and communication with connected devices, ensuring reliable data collection and command execution.
CCU4: The SHSS shall maintain core local security functionality during temporary loss of internet connectivity, ensuring that local event processing, alarm control, and device management functions continue to operate based on locally available data and configured rules even when cloud connectivity is unavailable.
CCU5: The SHSS shall synchronize data and system state with cloud services when internet connectivity is available to support remote monitoring and control functions through the mobile application.

## User Authentication
UA1: The SHSS shall require user authentication for access to the mobile application.
UA2: The SHSS shall support secure authentication mechanisms for access to the mobile application.
UA3: The SHSS shall allow homeowners / admins to manage user accounts and permissions through the mobile application.
UA4: The SHSS shall restrict access to system management functions to authorized users with appropriate permissions.

## Configuration and Management
CM1: The SHSS shall allow homeowners / admins to configure system settings through the mobile application, including device management, alert preferences, and user management.
CM2: The SHSS shall provide device management functions for connected devices, including status monitoring, diagnostics, and maintenance support.
CM3: The SHSS shall perform self-diagnostics and provide feedback regarding system health, connectivity, and operational status through the mobile application.
CM4: The SHSS shall allow authorized users to view system status and health information through the mobile application.
