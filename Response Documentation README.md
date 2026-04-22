Week2 Practical 2: Response Documentation

1. Incident Response Template (Phishing Case)

Executive Summary
A phishing email containing a malicious link was detected during security monitoring. The email attempted to trick users into revealing sensitive credentials. No confirmed compromise occurred.

Timeline

| Timestamp        | Event                   |
|------------------|-------------------------|
| 2026-04-22 10:00 | Phishing email detected |
| 2026-04-22 10:05 | Alert generated         |
| 2026-04-22 10:15 | Email analyzed          |
| 2026-04-22 10:30 | Users notified          |

Impact Analysis
- No confirmed credential theft  
- Potential risk to users via malicious link  
- No system compromise detected  

Remediation Steps
- Blocked malicious URL  
- Updated email filtering rules  
- Notified affected users  
- Increased monitoring for similar emails  

Lessons Learned
- Improve phishing detection mechanisms  
- Enhance user awareness training  
- Strengthen email filtering policies  
- Implement automated link scanning  


2. Investigation Log

| Timestamp | Action                                |
|-----------|---------------------------------------|
| 10:10     | Email headers analyzed                |
| 10:15     | Checked link reputation               |
| 10:20     | Identified affected users             |
| 10:25     | Simulated endpoint isolation          |
| 10:30     | Collected evidence (logs/screenshots) |



3. Phishing Checklist

- [x] Confirm email headers  
- [x] Check link reputation (VirusTotal)  
- [x] Identify affected users  
- [x] Verify sender domain  
- [x] Alert users  


4. Post-Mortem
The phishing incident demonstrated the importance of structured response and early detection. Although no compromise occurred, the event highlighted gaps in user awareness and email filtering. Improvements in automated detection and training are required to reduce future phishing risks.

5. Connection to Practical 1
This incident is based on security monitoring and alert analysis performed using SIEM logs in Practical 1. The classification and response workflow follows MITRE ATT&CK methodology and SOC incident response principles.
