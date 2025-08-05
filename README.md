# Task-2
# 📧 Phishing Email Analysis – Cyber Security Internship Task 2

## Task Objective
The goal of this task is to analyze a suspicious email for phishing indicators and understand how attackers use spoofing, social engineering, and malicious links to deceive users.


## 📤 Sample Phishing Email

**Subject**:  Urgent: Your PayPal Account Has Been Limited  
**From**: security-update@secure-paypal.com  
**To**: your_email@example.com


---

## Phishing Indicators Identified

 # Indicator              | Description                                                                 

|  **Spoofed Email**    | Domain `@secure-paypal.com` is not an official PayPal domain.              
| **Urgent Language**  | Tries to create panic: "Immediate action required"                          
| **Suspicious Link**  | Fake URL disguised as PayPal verification link                              
| **Generic Greeting** | Uses "Dear Customer" instead of personalized name                           
| **Threatening Tone** | Threatens account suspension to pressure user to click                      
| **Social Engineering** | Exploits trust in PayPal and fear of losing account                        

---

## Email Header Analysis

Tool used: [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)

Sample header:
```text
Received: from unknown123.secure-login247.com ([192.168.1.15])
	by smtp.secure-paypal.com with SMTP id xYz123abc456;
	Wed, 27 May 2025 10:15:43 +0530
Received-SPF: softfail (google.com: domain of transitioning security-update@secure-paypal.com does not designate 192.168.1.15 as permitted sender)
Authentication-Results: spf=softfail smtp.mailfrom=security-update@secure-paypal.com
Return-Path: <security-update@secure-paypal.com>
...

## Analyze Header of Phishing email

<img width="898" alt="image" src="https://github.com/user-attachments/assets/125b9be8-7169-4ede-8cc7-f40eacb65d29" />
<img width="923" alt="image" src="https://github.com/user-attachments/assets/066e74bf-a89e-42e1-80c5-678e1a040a49" />


