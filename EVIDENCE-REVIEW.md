# Screenshot Evidence Review

This file records corrections made while preparing the public portfolio version of the **ISM 4323 — Information Security and Risk Management** cybersecurity labs.

## Corrections applied

| Area | Issue | Correction |
|---|---|---|
| Incident response | `ir-1-time-graph.jpg` was captioned as a traffic activity graph, but actually showed a FileZilla SFTP client from the separate packet-analysis exercise. It duplicated another screenshot. | Removed it from the incident response write-up and from the repository. The remaining screenshots document the actual incident-response lab. |
| Network traffic | `pa-1-ftp-transfer.jpg` shows `sftp://` in FileZilla, not unencrypted FTP. | Renamed it `pa-1-sftp-transfer.jpg`, updated the Markdown link, and corrected the description. |
| Incident response | The email evidence screenshot exposed a simulated scenario's server/login credentials. | Covered the three credential lines in `ir-3-ftp-credential-email.jpg` without removing the rest of the email context. |
| Evidence language | Several original captions stated a stronger conclusion than a single screenshot established. | Rewrote the affected descriptions to separate what is visible from what requires additional case-study evidence. |

## Evidence inventory

- **Incident response:** 4 distinct screenshots — NetWitness session, redacted Autopsy email, Autopsy timeline, and Autopsy email/social-engineering evidence.
- **Packet analysis:** 5 distinct screenshots — FileZilla SFTP, Wireshark ICMP, Wireshark HTTP, Wireshark SSH, and a wireless deauthentication test.
- **Vulnerability assessment:** 6 distinct screenshots — Zenmap/Nmap scanning, Nessus summary, and traceroute.
- **Total:** **15 unique image files**. All Markdown image references were checked to resolve to files in this repository.

## Scope and limitations

This repository contains self-authored coursework summaries from controlled training environments. Screenshots show selected activities and artifacts; they do **not**, by themselves, verify every investigative conclusion or the full technical configuration. Public-facing screenshots and explanations should not be interpreted as production incidents, live targets, or a certification of professional penetration-testing work.
