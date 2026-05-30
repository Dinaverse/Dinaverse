# Challenge: SOC Network - DNS Exfiltration

## Overview
- **Category:** CTF Training - Hard / SOC
- **Points:** 350
- **Difficulty:** Medium
- **Status:** Validated

## Description
Investigate unusual DNS queries to detect potential data exfiltration.

## Solution
1. **Initial Investigation:** Analyze network traffic (likely using Wireshark, Zeek, or ELK) to investigate reported unusual, encrypted-looking DNS queries.
2. **DNS Traffic Analysis:** Examine DNS query patterns and volumes from specific hosts. Look for non-standard DNS query names (e.g., long, randomized strings or unusual domains) that indicate exfiltration rather than standard resolution.
3. **Log/Packet Inspection:** Inspect the payload of these DNS queries. Exfiltration via DNS often involves encoding data (e.g., Base64 or Base32) directly within the DNS request subdomain (e.g., `<encoded_data>.attacker.com`).
4. **Data Reconstruction:** Extract the encoded strings from the DNS queries, reassemble the data stream, and decode it to reveal the exfiltrated sensitive content, including the flag.

## Conclusion
Learned how DNS protocol can be abused as a covert channel for data exfiltration. This emphasizes the importance of monitoring DNS traffic for unusual patterns, such as high-volume or anomalous query strings, as a key component of network-based threat detection.

## Flag
[REDACTED]
