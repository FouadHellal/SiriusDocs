
## Network Topology Mapper (NTM)
-----------------------------------

As mentioned, the NTM is a sophisticated software tool designed to enhance the visualization and management of complex network infrastructures. This section details the functionalities and capabilities of the NTM, emphasizing its role in network provisioning, management, and configuration within a single-pane-of-glass user graphical interface (See Figure 3.7).

### Features and Functionalities of the NTM Subsystem

The NTM offers a comprehensive suite of features designed to streamline network visualization and management capabilities. Before diving into the detailed exploration of each feature, let’s provide an overview of the core functionalities offered by the NTM:

1.  Dynamic Topology Mapping Discovery (ATMD)
2.  Manual Adjustments of the Discovered Topology Map
3.  Advanced Network Management through Context Menu
4.  Future Broad Focus

Now, let’s delve into each feature to understand its functionality in detail and explore additional capabilities it offers.

#### Automated Topology Mapping Discovery (ATMD)

The NTM facilitates the creation of a network topology map through the "Create New Map" function. This feature automates the visualization process, providing a detailed map (See Figure 3.7) that includes:

*   **Device Interconnections**: The topology map illustrates how devices are connected within the network.
    *   Green: The device is functioning with no issue
    *   Red: The device has an issue
    *   Blue: Status unknown (manually added device)
*   **Hierarchical Views**: The system automatically generates a hierarchical network topology map, intelligently classifying devices based on their layer (core, distribution, access, and end-device).
*   **Automatic End Device Discovery**: The ATMD automatically links discovered end devices (including end-users, VoIP devices, and servers) to their corresponding switches. It displays valuable information like:
    *   **Switch Port**: Identifies the switch port where the end device is connected.
    *   **Configured Speed**: Displays the configured speed (e.g., 100 Mbps, 1 Gbps).
    *   **VLAN Number**: Indicates the VLAN membership, aiding network segmentation.

#### Manual Adjustments of the Topology Map

In dynamic network environments, changes and errors are inevitable. The NTM allows users to address these through manual adjustments. Figure 3.8 illustrates various functions available for manual editing.

One notable feature is **Drag-and-Drop Device Positioning**, where users can move devices on the map to improve clarity or layout. This is particularly useful when:

1.  Devices overlap, hindering readability.
2.  Users want to explore alternate layouts for better visualization or presentation.

During drag-and-drop operations, links connected to the device are updated automatically, maintaining a consistent network representation.

#### Advanced Network Management Through Context Menu

NTM offers a range of features accessible directly from the GUI. Right-clicking on a device reveals a context menu (See Figure 3.9) with management and configuration options such as:

##### Option 1: Preview Device Information

Clicking "Preview" displays a tab (Figure 3.10) showing various device insights:

*   **Physical and Logical Views**: Understand both physical placement and logical connections.
*   **Real-Time Interface Status**: See the on/off status, names, and roles of interfaces.
*   **Real-Time Alerts Monitoring**: View current alerts for proactive issue resolution.
*   **Enabled Protocols**: See which protocols are active (future feature).

This section is customizable, allowing tailored information displays.

##### Option 2: Granular Device Interaction Using CLI

This option includes powerful configuration tools:

*   **Command Line Interface**: Execute commands such as "show mac address-table" directly, enabling full device control (See Figure 3.11).
*   **AI-Powered Assistance**: Enhances CLI usability with:
    *   **Command Suggestions**
    *   **Argument Assistance** (? prompts next argument)
    *   **Command Explanations** with examples (See Figure 3.12)

##### Option 3: Device Interfaces

This option provides detailed interface data:

*   View names, types, speeds, duplex, VLAN membership, traffic stats.
*   Use color coding to indicate status.
*   Support advanced control: interface up/down, speed/duplex changes, VLAN assignment.

Additional context menu options can be tailored based on user requirements.

#### Network Inventory Overview and Classification

Beyond mapping and configuration, NTM provides categorized inventory views (See Figure 3.1), allowing insights into:

*   **Routers**: Models, IPs, additional details
*   **Switches**: Brands, models, IPs
*   **Firewalls**: Models, IPs
*   **IoT Devices**: Vendors, IPs
*   **End-users**: Computers and smartphones, IPs, VLANs, potential OS info
*   **VoIP Phones**: Brands and IPs

> **NTM can detect and classify up to 29,631 different devices**, ensuring robust visibility and control across heterogeneous environments.

### Future Broad Focus

In future iterations, we aim to expand NTM’s capabilities to:

*   Handle large and complex networks
*   Provide **seamless multi-vendor compatibility** (Cisco, Huawei, Aruba, Nokia, Juniper, etc.)

This would allow:

*   **Simplified Management**: Centralize control across all devices
*   **Reduced Complexity**: Eliminate the need for multiple vendor tools
*   **Improved Efficiency**: Optimize operations and troubleshooting in diverse environments

In the next sections, we will explore other key components of our NOS, detailing their features, functionalities, and operational benefits. Each module builds upon the foundation laid by the NTM, offering a comprehensive network management solution.
