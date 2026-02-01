# Suspicious Email Analysis

## Scenario
A suspicious email was reported by a user. The objective was to determine whether the email was malicious, identify indicators of compromise (IOCs), and recommend appropriate response actions.

---

## Initial Observations
- Email contained unexpected attachment and urgent language
- Sender domain appeared similar to a legitimate organisation
- User had not previously interacted with the sender

---

## Analysis Performed
- Reviewed email headers for sender IP, SPF/DKIM results, and routing anomalies
- Analysed attachment metadata and hash values
- Checked URLs against known threat intelligence sources
- Looked for signs of social engineering or credential harvesting

---

## Indicators Identified
- Suspicious sender domain
- Malicious URL redirect
- Attachment hash matched known malware signature

---

## Assessment
The email was assessed as **malicious phishing** with a high likelihood of credential compromise if interacted with.

---

## Recommended Actions
- Block sender domain and associated IPs
- Reset affected user credentials
- Remove email from all user mailboxes
- Raise awareness with users via internal comms

---

## Reflection
This exercise reinforced the importance of structured triage, header analysis, and clear reporting to support timely decision-making in SOC environments.
