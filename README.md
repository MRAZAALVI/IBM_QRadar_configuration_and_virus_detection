# IBM QRadar Configuration and Virus Detection Use Case

## Objective
To configure IBM QRadar SIEM for monitoring and detecting virus activity within an organization's network.

## Description
This project demonstrates the setup and configuration of IBM QRadar SIEM, including integration with network devices, log sources, and creation of custom rules to detect virus activity. The project includes a practical use case for detecting virus infections and generating alerts.

## Project Steps
1. **Introduction**
   - Overview of the project
   - Importance of SIEM in cybersecurity
   - Objectives and expected outcomes

2. **Environment Setup**
   - **Prerequisites**
     - IBM QRadar SIEM (installed and configured)
     - 250 GB Free storage for VM and 16GB RAM or at least 8 GB RAM for VM.
     - Access to network devices and log sources (e.g., firewalls, antivirus software)
   - **Installation**
     1. Double-click on the QRadar file.
     2. Name your VM and set the path.
     3. Right-click on the new VM and select "Properties."
     4. Increase the RAM allocation to a minimum of 8GB.
     5. Change the network adapter setting from "Bridging" to "Host-only."
     6. Add another network adapter (set to the default NAT).
     7. Click "OK" and power on the VM.
     8. Login as "root" and set your password.
     9. Type `./setup` in the command prompt.
     10. Follow the on-screen instructions to complete the setup.

3. **Configuring Log Sources**
   - **Adding Log Sources**
     - Steps to add log sources (e.g., firewalls, antivirus logs)
     - Configuring log source parameters (IP address, protocol, port, etc.)
   - **Verifying Log Source Integration**
     - Ensuring log sources are correctly sending logs to QRadar
     - Checking log source status in QRadar dashboard

4. **Implementing Virus Detection Use Case**
   - **Scenario Description**
     - Description of the virus detection scenario
   - **Data Simulation**
     - Simulating virus activity (e.g., using sample virus logs)
   - **Rule Testing**
     - Testing the custom rule to ensure it detects the simulated virus activity
     - Verifying alerts and log entries in QRadar

5. **Dashboard**
   - **Dashboards**
     - Steps to create a custom dashboard in QRadar
     - Adding relevant widgets (e.g., virus activity charts, alert summaries)

6. **Conclusion**
   - **Summary of the project**
     - This project focuses on configuring IBM QRadar to detect virus activities using log data from a PA Series firewall.
   - **Conclusion**
     - The successful completion of this project highlights the importance and effectiveness of using SIEM solutions like IBM QRadar in a cybersecurity framework.
