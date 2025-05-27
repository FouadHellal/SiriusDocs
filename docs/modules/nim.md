The Network Management System features a comprehensive inventory management section designed to streamline device addition, organization, and configuration. This section details the functionalities offered within the inventory page, ensuring that network administrators can efficiently manage their network inventory.

### Features and Functionalities of the NIM Subsystem

#### Single Device Addition

The inventory page provides a user-friendly interface for adding individual network devices (see Figure 1). Below is a breakdown of the information required when using the **"Add Device"** button:

*   **Name**: Assignable by the user for easy identification within the inventory and NTM map.
    
*   **IP Address**: Essential for network communication and remote access to the device.
    
*   **Login Credentials**:
    
    *   **Username**: Required for remote connection using protocols like Telnet or SSH.
        
    *   **Password**: Required for remote connection using Telnet or SSH.
        
    *   **Enable Password** (optional): Optional field specifically for switches and routers.
        
*   **Device Type**: Dropdown menu for specifying the device type.
    
*   **Layer** _(optional for switches)_: Specify whether it's core, distribution, or access.
    
*   **Vendor**: Identification of the device’s manufacturer.
    
*   **Port Number** _(optional)_: Specify the port used for remote access (e.g., SSH).
    

> **Note**: This step is essential to enable the complete functionality of the Network Operating System (NTM, NIM, NDM, NAS, NEI, and NCM).

#### Bulk Device Addition

While single device addition is ideal for smaller deployments, a **bulk device addition** feature is provided to simplify large-scale network setups. Users can input multiple device entries using a comma-separated format (see Figure 2), dramatically reducing the time needed to populate the inventory.

#### Inventory Table

Once devices are added (either individually or in bulk), they are listed in a dedicated **Inventory Table** (see Figure 3). This centralized table provides a complete view of all managed devices and easy access to their configuration and status.

**Key Features**:

*   Note: Sensitive data such as passwords is encrypted and not displayed.
    
*   **Device Management**:
    
    1.  **Edit Device**: Modify device details to keep the inventory up-to-date.
        
    2.  **Delete Device**: Remove obsolete or decommissioned devices for better accuracy.
        

### Future Broad Focus

The NIM subsystem is designed with scalability and extensibility in mind. Planned features include:

1.  **Configuration Management**: Direct access to configuration pages for each device.
    
2.  **Device Provisioning**: A dedicated interface for viewing detailed device status and health.
    
3.  **Report Generation**: Exporting PDF reports for devices, containing:
    
    *   Physical image or schematic
        
    *   Hardware specifications (e.g., port count, supported features)
        
    *   Firmware version and history
        
    *   Protocol status (enabled/disabled)
        
    *   System logs and alerts
        
    *   Audit trail of recent changes
        

These enhancements aim to empower network administrators with complete lifecycle management tools, from inventory creation to in-depth diagnostics and reporting.