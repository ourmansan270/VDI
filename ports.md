
### **Citrix XenApp / XenDesktop**

1. **Citrix XML Service**: 
   - Port **80** (HTTP) or **443** (HTTPS) for XML service communication.

2. **Citrix Broker Service**:
   - Port **443** (HTTPS) for communication with the Delivery Controllers.

3. **Citrix ICA (Independent Computing Architecture)**:
   - Port **1494** (TCP) for ICA traffic.
   - Port **2598** (TCP) for Session Reliability.

4. **Citrix Director**:
   - Port **443** (HTTPS) for accessing Citrix Director.

5. **Citrix Provisioning Services (PVS)**:
   - Port **6910** (TCP) for the PVS service.
   - Port **69** (UDP) for the TFTP service.

6. **Citrix NetScaler**:
   - Port **443** (HTTPS) for management and configuration.

### **FSLogix**

1. **FSLogix Profile Container**:
   - Port **445** (TCP) for SMB communication.
   - Port **135** (TCP) for RPC endpoint mapping.

2. **FSLogix Office Container**:
   - Port **445** (TCP) for SMB communication.
   - Port **135** (TCP) for RPC endpoint mapping.

### **Netscaler (Citrix ADC)**

1. **Management Interface**:
   - Port **443** (HTTPS) for management access.

2. **Client Access (SSL/TLS)**:
   - Port **443** (HTTPS) for secure client access.

3. **Load Balancing**:
   - Port **80** (HTTP) for non-secure traffic.
   - Port **443** (HTTPS) for secure traffic.

4. **SSL Offloading**:
   - Port **443** (HTTPS) for SSL traffic.

5. **NetScaler Gateway**:
   - Port **443** (HTTPS) for client connections.

### **Provisioning Server**

1. **Citrix Provisioning Services (PVS)**:
   - Port **6910** (TCP) for communication with the PVS server.
   - Port **69** (UDP) for TFTP service.

2. **Provisioning Services (PVS) Boot**:
   - Port **69** (UDP) for TFTP.

### **VMware vSphere / ESXi**

1. **vSphere Client**:
   - Port **443** (HTTPS) for accessing vSphere Web Client.

2. **vCenter Server**:
   - Port **443** (HTTPS) for vCenter management.

3. **ESXi Host Management**:
   - Port **443** (HTTPS) for ESXi management.

4. **VMware Tools**:
   - Port **902** (TCP) for VMware Tools communication.

5. **VMotion**:
   - Port **8000** (TCP) for VMotion.

6. **Storage I/O Control**:
   - Port **3260** (TCP) for iSCSI.

### **ControlUp**

1. **ControlUp Management Console**:
   - Port **443** (HTTPS) for accessing the ControlUp Console.

2. **ControlUp Agents**:
   - Port **443** (HTTPS) for communication with the ControlUp Management Console.

3. **ControlUp Monitoring**:
   - Port **3389** (TCP) for RDP if used for session monitoring.

### **HPE dHCI Platforms**

1. **HPE OneView**:
   - Port **443** (HTTPS) for accessing the OneView management console.

2. **HPE InfoSight**:
   - Port **443** (HTTPS) for communication with HPE InfoSight.

3. **HPE Nimble Storage**:
   - Port **443** (HTTPS) for management and configuration.
   - Port **2049** (TCP) for NFS.
   - Port **445** (TCP) for SMB/CIFS.

4. **HPE ProLiant Servers**:
   - Port **443** (HTTPS) for iLO management.
   - Port **22** (TCP) for SSH (if enabled).
