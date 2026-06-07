# SOC-Simulator-Phishing
An end-to-end incident response lab simulating an enterprise phishing attack vector. Documents email header triage, malicious payload hashing, and threat intelligence lookups using VirusTotal, alongside blue-team detection engineering, log ingestion, and alert generation within Elastic SIEM.

### Tools Used

* **Training Platform:** [TryHackMe SOC Simulator](https://tryhackme.com/soc-sim/scenarios)
* **SIEM Platform:** [Elastic Security](https://elastic.co)
* **Threat Intelligence:** [VirusTotal](https://www.virustotal.com/gui/home/upload)

### SOC Phishing Simulator & Incident Response Lab

* **Attack Simulation:** Simulated an enterprise phishing attack vector within an isolated sandbox environment to generate realistic endpoint and network telemetry.
* **Threat Intelligence:** Analysed raw email headers and extracted malicious payload hashes, leveraging **[VirusTotal](https://www.virustotal.com/gui/home/upload)** to validate indicators of compromise (IoCs).
* **SIEM Detection Engineering:** Developed custom queries and alert rules within **[Elastic SIEM](https://elastic.co)** to detect post-exploitation activity, suspicious process spawning, and unauthorized network connections.
* **SOC Analyst Workflow:** Completed hands-on training via the **[TryHackMe SOC Simulator](https://tryhackme.com/soc-sim/scenarios)** to master real-time queue management, alert prioritization, and threat triage.

#### Gained Core Competencies:
* **Email Artifact Triage:** Spotting advanced social engineering red flags, typosquatted domains, spoofed senders, and masked malicious hyperlinks.
* **Log Analysis & Correlation:** Cross-referencing endpoint events and network proxy logs to track user click-through behavior on link lures.
* **Incident Classification:** Differentiating between True Positives and False Positives to draft comprehensive, structured blue team incident reports.

# Steps and Actions

Image 1 - Dashboard used for incoming alerts

<img width="1437" height="717" alt="Screenshot 2026-06-07 at 20 04 52" src="https://github.com/user-attachments/assets/be8ab906-2792-43f1-8082-5eac4e804f18" />

Image 2 - First alert. False Posetive, following elastic seim and totalvirus investigations.

<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 05 26" src="https://github.com/user-attachments/assets/2d154df8-7b50-4192-a027-28c9224081da" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 05 38" src="https://github.com/user-attachments/assets/78fe7621-2fe6-4e9c-9998-eb8fc58f3afe" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 05 56" src="https://github.com/user-attachments/assets/4de427cb-c2ad-49d8-a23c-9a9d2604a15a" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 06 04" src="https://github.com/user-attachments/assets/b1615a94-4514-48e1-9039-951d7d8db7e5" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 07 06" src="https://github.com/user-attachments/assets/40e9d00f-82cf-4769-9acc-ee9ab95841a4" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 08 02" src="https://github.com/user-attachments/assets/1c33a8ad-d25c-4631-adee-998100192c09" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 09 26" src="https://github.com/user-attachments/assets/44870dcc-8869-4ec7-ab7c-a94439654054" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 09 38" src="https://github.com/user-attachments/assets/8562599f-fa4f-44d0-bbe2-2144a437979e" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 10 15" src="https://github.com/user-attachments/assets/9d3a6409-ef42-4eb2-8d8f-5d36ad298d3c" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 11 05" src="https://github.com/user-attachments/assets/717e0be4-3ad3-4f5c-bac5-c75d42d6890a" />







