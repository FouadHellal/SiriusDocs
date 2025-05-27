The Network Device Monitoring subsystem provides a dedicated device page for each discovered network device, enabling in-depth monitoring of device information, configurations, and troubleshooting.

### Features and Functionalities

Upon selecting a specific device from the **Device Provisioning** page, users are directed to a comprehensive **Device Monitoring Page**. This page serves as an information hub, offering insights into the device’s health, operational status, and configuration. Key categories include:

#### Physical & Logical View of Device Interfaces

*   **Physical Device Image**: Displays a visual representation of the actual device, helping with physical identification and layout understanding.
    
*   **Interface Status with Color Coding**: Each interface is displayed with an operational status color:
    
    *   🟢 **Green** – Interface is up and functioning normally
        
    *   🔴 **Red** – Interface is down or in error
        
    *   ⚪ **Grey** – Interface does not exist
        
    *   🟠 **Orange** – Interface is experiencing an anomaly
        

#### Detailed Interface Information and Control

Administrators can access a detailed table listing each interface's critical information:

*   Interface name and ID
    
*   Link speed and duplex mode (e.g., 100 Mbps, 1 Gbps, full/half duplex)
    
*   VLAN membership
    
*   Real-time traffic statistics (incoming/outgoing bytes and packets)
    

Each interface row also includes a toggle switch for enabling or disabling the interface, simplifying control and operational management.

#### Anomaly Detection and Visualization

A built-in anomaly detection system continuously monitors device behavior and visually flags irregularities:

*   🟠 **Orange Interface Color**: Indicates an anomaly has been detected.
    
*   **Hover for Details**: Hovering over the orange interface provides a tooltip describing the detected issue.
    

> _Note: The current prototype focuses on a single anomaly (interface protection mode). However, this system is extendable to cover additional detections like HTTP port status._

#### Syslog Monitoring and Filtering

A dedicated section of the NDM page displays recent **syslog entries**, offering valuable insights into device events and issues.

*   **Detailed Syslog View**: Shows the 10 most recent entries by default, with descriptions and severity levels.
    
*   **Severity Classification**: Logs are classified from 0 (Critical) to 7 (Informational).
    
*   **Pagination & Filtering**:
    
    *   Navigate through logs in pages of 10
        
    *   Future versions may include filtering by:
        
        *   Severity level
            
        *   Precise time range (down to seconds)
            

By integrating these features, the NDM Device Page gives network administrators a centralized interface for device monitoring, anomaly detection, and operational oversight.

### Future Enhancements

To further enrich the monitoring experience, future versions of NDM are planned to include:

#### Device Health and Performance Monitoring

*   **CPU Usage**: Monitor trends in CPU load to identify performance issues.
    
*   **CPU Temperature**: Track thermal conditions to prevent overheating.
    
*   **Error Statistics**: Log TX/RX error rates to detect potential data integrity problems.
    
*   **Packet Loss**: Monitor for network reliability issues caused by lost packets.
    

#### History of Connected End Devices

*   **Device Info**: MAC address, IP, and type of connected devices.
    
*   **Port Utilization**: Record of which port each device used and for how long.