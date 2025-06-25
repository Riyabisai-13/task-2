# Phishing Email Analysis Report

## Phishing Link
**URL:** tiktok@cloud-notification-services[.]com  
**Target:** Credentials stealing (Fake Tik-tok Portal)  
**Found on:** CanIPhish

---

## Phishing Indicators

| Indicator Type      | Evidence |
|---------------------|----------|
| Spoofed Sender      | `tiktok@cloud-notification-services[.]com` (Not a legit Tiktok domain) |
| Suspicious Link     | Link text says "Reset Password", but leads to a spoofed website |
| Domain Mismatch     | `tiktok.com` is legit; this is `@cloud-notification-services` |
| Urgent Language     | "New Device Login", "Immediately", "Enter this code" |
| Email Header Issue  | Simulated SPF failure |
| Threat Tactic       | Unknown login attempt, Suspicious logiin attempt |
| Grammar/Language    | Reasonably correct (targeted attack) |

---

## Tools Used
- [VirusTotal](https://www.virustotal.com/)
- [MxToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)

---

## Summary
This phishing email impersonates a Tiktok domain to scare the target into clicking a malicious reset password link,in order to steal credentials.It uses a spoofed sender domain,immediate action needed notification in order to cause panic and stress and fraudulent url in order to look legitimate.
