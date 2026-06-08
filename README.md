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

# Alert 1 - False posetive after Elastic (Seim) and TotalVirus investigations
<img width="1437" height="717" alt="Screenshot 2026-06-07 at 20 04 52" src="https://github.com/user-attachments/assets/be8ab906-2792-43f1-8082-5eac4e804f18" />
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

# Alert 2 - True Posetive follwing a link in email being identified as a threat on TotalVirus.
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 11 15" src="https://github.com/user-attachments/assets/fbcdcccc-2987-4357-be11-3e78eea21173" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 11 24" src="https://github.com/user-attachments/assets/7424888e-bb59-4e9f-a10f-973be2f3fa9b" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 11 35" src="https://github.com/user-attachments/assets/53d0b0ed-bbf7-4854-9c76-7f1f0215f534" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 12 07" src="https://github.com/user-attachments/assets/5bdbcd01-075d-4d87-94e5-5cab0cffb303" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 12 46" src="https://github.com/user-attachments/assets/30fab7ca-4a25-4c7d-8935-787b77bc1098" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 13 06" src="https://github.com/user-attachments/assets/39b3788e-d825-46ea-bf02-ecab6fa317e2" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 17 48" src="https://github.com/user-attachments/assets/5cd9b136-e9b7-47d0-b693-1acc2a8d64c9" />


# Alert 3 - True Posetive following Firewall breach
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 18 07" src="https://github.com/user-attachments/assets/66f9e77b-1d57-4c41-a37b-a89d3caf498f" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 18 31" src="https://github.com/user-attachments/assets/efa92c1c-6263-41c2-9b7c-b98c986d4205" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 19 09" src="https://github.com/user-attachments/assets/c22fded4-d1bc-4160-ad74-8066a114edcb" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 19 15" src="https://github.com/user-attachments/assets/3348f7ef-338c-4fc4-8c4d-327bc0495dda" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 22 43" src="https://github.com/user-attachments/assets/cbcf4343-1199-4d35-bc19-7c1201999418" />


# Alert 4 - True Posetive following email from company masquerading as microsoft adding a link that has been flagged as a threat.
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 23 00" src="https://github.com/user-attachments/assets/3e9a60a5-c56f-47f3-b93a-1ca4450584d6" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 23 09" src="https://github.com/user-attachments/assets/d231b99a-bccb-4ecc-9098-27d73b945a3c" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 23 40" src="https://github.com/user-attachments/assets/17c069e8-3ee0-4aba-b5ee-114d2086a755" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 24 24" src="https://github.com/user-attachments/assets/a656f6ae-689c-4478-8ac8-2f23ea668f00" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 24 39" src="https://github.com/user-attachments/assets/112bb91a-b514-4600-b2ee-f1499431882f" />
<img width="1470" height="739" alt="Screenshot 2026-06-07 at 20 27 14" src="https://github.com/user-attachments/assets/14ab6111-a1c7-4973-8669-3457e7b7b283" />

                                                                                                                                                               


# Simulation result 

<img width="1470" height="572" alt="Screenshot 2026-06-07 at 20 28 18" src="https://github.com/user-attachments/assets/7ba87964-ee89-4432-a8d8-ad6e8c4c0120" />








