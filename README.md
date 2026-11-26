# Phising-Email-Analysis
**Overview**

This project demonstrates the analysis of a suspected phishing email. The objective was to identify indicators of phishing, evaluate the risk posed by the email, and determine whether it should be classified as malicious.

**What is Phishing?**

Phishing is a cyberattack technique used by threat actors to trick individuals into revealing sensitive information such as usernames, passwords, banking details, credit card information, or other personal data.

**Common phishing methods include:**

Fake emails impersonating trusted organizations such as banks, Microsoft, PayPal, or Netflix.
Fraudulent websites designed to steal login credentials.
SMS phishing (smishing) through malicious text messages.
Voice phishing (vishing) through fraudulent phone calls.
Investigation Summary

A suspicious email was analyzed to determine whether it was legitimate or a phishing attempt.

The email claimed that the recipient had won a prize and was required to click a link to claim the reward. This message used urgency and excitement-based social engineering techniques to pressure the recipient into taking immediate action without verifying the legitimacy of the email.

**Analysis Findings**
Social Engineering Indicators

The email contained several common phishing characteristics:

A prize claim intended to attract the recipient's attention.
Urgency encouraging immediate action.
A request to click an external link.
An attempt to create excitement and lower suspicion.
Sender Analysis

**The sender's information raised multiple red flags**:

The display name did not match the claimed organization.
The company branding was inconsistent.
The company name contained spelling or naming inconsistencies.
The sender's email address was unrelated to the organization it claimed to represent.

These inconsistencies are commonly observed in phishing campaigns that impersonate legitimate businesses.

**Indicators of Phishing Identified**
**Indicator	Observation**
Urgency	Encouraged immediate action
Prize Claim	Claimed the recipient had won a reward
Sender Mismatch	Display name did not match organization
Company Inconsistency	Company branding and name were inconsistent
Suspicious Email Address	Sender email unrelated to claimed company
External Link	Contained a link to an unknown destination
**URL Analysis**
VirusTotal Investigation

The embedded URL was extracted from the email and analyzed using VirusTotal.

Result: VirusTotal identified the URL as suspicious and potentially malicious.

This further supports the assessment that the email was designed to redirect users to a fraudulent or malicious website.

**Risk Assessment**

If a user interacted with the email, the following risks could occur:

Credential theft
Account compromise
Malware infection
Financial fraud
Identity theft

**Final Verdict**
✅ Classification: Phishing Email

**The email exhibits multiple indicators of a phishing attack, including**:

Urgency-based social engineering
Suspicious prize claim
Mismatched sender details
Inconsistent company information
Suspicious URL reputation

Based on these findings, the email should be classified as malicious and treated as a phishing attempt.

**Skills Demonstrated**
Phishing Email Analysis
Social Engineering Detection
Sender Verification
URL Analysis
IOC Identification
VirusTotal Investigation
Security Reporting
Threat Assessment
