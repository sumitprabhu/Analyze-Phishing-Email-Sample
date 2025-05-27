# Analyze-Phishing-Email-Sample
Task 2

# Phishing Email Analysis

This project documents the step-by-step analysis of a suspicious phishing email to identify key indicators of a phishing attempt. The goal is to understand and recognize social engineering tactics and technical red flags within email communications.

## Tools Used

- Outlook (Email Client)
- ✅ **MxToolbox Email Header Analyzer** – https://mxtoolbox.com/EmailHeaders.aspx
- ✅ **Browser Inspect Tool** – to view actual link destinations
- ✅ **Phishing Email Screenshot** – sample provided for analysis

## Email Sample
![image002](https://github.com/user-attachments/assets/cfb65d54-1a29-4973-bc25-f3098848f60d)

## Analysis Steps & Findings
1. Sender's Email Address
   - The sender's email address was "hr@gpdrejinds.com".
   - The email address is not legitimate, since the official domain would be "hr@godrejinds.com"
     ![Phishing Ananlysis](https://github.com/user-attachments/assets/a2695ce3-9206-4c34-92b3-1d2eccfb4e9e)

2. Discrepancy in Email Header
   - MessageID -> 1369113ee.b84beaa7@psm.knowbe4.com
   - SPF (Sender Policy Framework) -> Fail (Likely spoofed)
   - DKIM (DomainKeys Identified Mail) -> Fail (Possible Forgery)
   - From and Return Path don't match
     ![Screenshot 2025-05-27 210230](https://github.com/user-attachments/assets/fe653350-d04a-476e-bc88-01182e0a4a97)

3. Urgent Message
   - Tickets will be allocated on first-come, first-served basis, so don't miss out!
     
## Summary of Phishing Indicators

- **Spoofed sender domain**
- **Urgency tactic**
- **Potential link spoofing**
- **Lack of DKIM/SPF info**
- **Minor grammar issues**

## References

- Google Message Header Analyzer
