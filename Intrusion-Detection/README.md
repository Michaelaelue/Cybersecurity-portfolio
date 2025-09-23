# Intrusion Detection with Snort IDS

## Objective
To Configure and tune Snort IDS to detect common attack patterns such as port scans and brute-force attempts. This project demonstrates my ability to work with intrusion detection systems and map alerts to MITRE ATT&CK techniques.

## Tools & Technologies
- Snort IDS
- Kali Linux

## Methodology & Screenshots

1. **Snort Installation & Setup**  
   Installed Snort on Kali Linux and configured network interfaces for packet capture.

2. **Rule Creation & Tuning**  
   Wrote custom Snort rules to detect port scans and brute-force login attempts. Tuned rules to reduce false positives.

3. **Attack Simulation**  
   Simulated attacks using Nmap and Hydra to trigger alerts and validate rule effectiveness.

4. **Alert Analysis**  
   Captured and analyzed alerts using Snort logs and Wireshark. Verified detection accuracy.

5. **MITRE ATT&CK Mapping**  
   Mapped Snort alerts to MITRE ATT&CK techniques to contextualize threats and improve strategic visibility.

6. **Reporting & Recommendations**  
   Documented alert types, rule logic, and proposed improvements for detection fidelity and response workflows.

### 1. Snort Configuration
Configured Snort with custom rules to detect suspicious activity.

![Snort Config](screenshots/snort-config.png)
<img width="1581" height="1199" alt="Screenshot 2024-10-16 131813" src="https://github.com/user-attachments/assets/02fa162e-1060-471f-bc5a-5a98a5f56cd4" />
<img width="1505" height="1193" alt="Screenshot 2024-10-16 131653" src="https://github.com/user-attachments/assets/a85a8e74-6f96-4b7f-90d7-6881381db46b" />
<img width="1484" height="1199" alt="Screenshot 2024-10-16 131538" src="https://github.com/user-attachments/assets/f0203aba-590b-4686-a2bc-2eb2e836aa41" />
<img width="1567" height="1199" alt="Screenshot 2024-10-16 130400" src="https://github.com/user-attachments/assets/77bc6d8f-4305-4aae-acec-2e31cd035af3" />

### 2. Alert Generation
Simulated port scans and brute-force attacks to trigger alerts.

![Snort Alerts](screenshots/snort-alerts.png)
<img width="1295" height="966" alt="Screenshot 2024-10-16 165554" src="https://github.com/user-attachments/assets/a47e3ea8-8316-4fa7-b98e-26c9f09efc70" />
<img width="1462" height="1199" alt="Screenshot 2024-10-16 154742" src="https://github.com/user-attachments/assets/60500c4c-16af-4b77-b5f6-c78687c9849b" />

## Findings
- Successfully detected multiple attack types
- Reduced false positives through rule tuning
- Gained insight into threat behavior using MITRE mapping

## Key Takeaways
- Strengthened IDS configuration and alert analysis skills
- Learned how to align detection with threat intelligence frameworks
