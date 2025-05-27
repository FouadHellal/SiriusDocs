The NEI subsystem provides a comprehensive overview of all end-devices connected to the network — both currently and historically. It offers a combination of real-time metrics and static information, helping administrators monitor user devices and analyze performance at the edge of the network.

### Features and Functionalities

#### End-Device Real-Time & Static Information

NEI displays key details about each connected device, offering both identification and operational insights.

Information includes:

*   **Brand Logo and Name**: Automatically detected or assigned for visual identification.
    
*   **MAC Address**: Unique hardware identifier of the device.
    
*   **Current IP Address**: IP address currently assigned to the device.
    
*   **Historical IP Addresses**: List of previously used IPs.
    
*   **Connected Switch and Interface**: Indicates where the device is connected in the network topology.
    
*   **24-Hour Bandwidth Usage**: Upload and download bandwidth consumption over the last 24 hours.
    
*   **Live Transfer Speed**: Real-time upload and download speed of the device.
    

#### End-Device Performance Monitoring

NEI allows for in-depth performance analysis of end-devices using dynamic line charts. These charts offer time-based visualization and allow administrators to hover over specific points in time to inspect metrics.

Monitored metrics include:

*   **Bandwidth Consumption Over Time**: Historical upload/download usage.
    
*   **Transmission/Reception Errors**: Number of errors recorded over time.
    
*   **Packet Loss Over Time**: Identifies reliability issues on a per-device basis.
    
*   **Broadcast Packets**: Count of broadcasted packets sent/received.
    
*   **Multicast Packets**: Count of multicast packets sent/received.
    
*   **Unicast Packets**: Count of unicast packets sent/received.
    

These features help administrators diagnose device-specific problems such as congestion, faulty network cards, or unusual traffic patterns.

### Future Enhancements

The NEI subsystem is planned to evolve with advanced tracking and control capabilities, including:

*   **Application Visibility**: View applications accessed by devices and the time spent on each (requires firewall integration).
    
*   **Bandwidth Usage by Application**: Identify the most bandwidth-hungry apps in the network (requires firewall).
    
*   **Operating System Vulnerability Detection**: Highlight devices running outdated or insecure operating systems.
    
*   **Browser Detection**: Show the web browser used by each device.
    
*   **Device Speed Control**: Provide administrators with the ability to throttle upload/download speeds of specific devices.