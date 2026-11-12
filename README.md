
# Microsoft CyberSHEcurity Challenge 2026

## Overview

**Event:** Microsoft CyberSHEcurity Challenge<br>
**Date:** November 11, 2026  
**Hosted by:** Microsoft and Women in CyberSecurity (WiCyS)  
**Focus:** Cybersecurity Awareness, Threat Identification, and Risk Assessment

## Event Description

The Microsoft CyberSHEcurity Challenge was an interactive cybersecurity event focused on identifying common security threats and making informed security decisions.

The event included scenarios involving phishing, social engineering, identity protection, and data security. Participants were challenged to recognize suspicious activity, identify potential risks, and explain their reasoning.

This write-up covers four missions from the event.

## Mission 1: Salt or Sugar?

**Objective:** Determine whether different situations were safe (Sweet), suspicious (Salty), or required additional verification.

| Scenario | Assessment | Reasoning |
|---|---|---|
| Voicemail from the CFO requesting an urgent wire transfer | Salty | Unexpected financial requests can indicate executive impersonation or business email compromise (BEC). |
| A colleague shares a presentation link that unexpectedly opens a login page | Verify | An unexpected login prompt could indicate credential phishing, even when the link comes from a known contact. |
| Software update on a managed device | Sweet | Updates distributed through an approved management system can include security patches and vulnerability fixes. |
| Event QR code offering free career resources | Verify | QR codes can redirect users to malicious websites or credential-harvesting pages. |
| Recruiter requesting sensitive personal information off-platform | Salty | Requests for sensitive information outside approved recruiting channels may indicate a recruitment scam. |

## Mission 2: Phish Detective
<img width="887" height="663" alt="Screenshot 2026-11-11 104117" src="https://github.com/user-attachments/assets/00171196-225c-4b11-bc73-af750d3afea8" />

**Objective:** Identify phishing indicators in a suspicious email.

The scenario involved an email appearing to originate from an executive office. The message claimed that account access would expire unless the recipient immediately completed an account review.

| Indicator | Observation | Security Concern | Recommended Action |
|---|---|---|---|
| Sender | `Executive Office <office@microsooft-alert.example>` | Lookalike domain attempting to impersonate a legitimate organization. | Inspect sender addresses for impersonation and lookalike domains. |
| Urgency | "Urgent account review required" | Creates pressure to act without evaluating the message. | Verify the request through an official communication channel. |
| Deadline | "Your access expires today" | Uses a short deadline to discourage careful review. | Confirm account status through the organization's official portal. |
| Credentials | "Open the attached form and confirm your password immediately" | Attempts to obtain account credentials through an untrusted form. | Never provide passwords through unsolicited emails or attachments. |
| Link | "Open secure portal" | The visible link text does not reveal the actual destination. | Inspect the URL without opening it and access the official portal directly. |
| Attachment | `Account_Review.zip` | An unexpected compressed attachment could contain malicious files. | Do not open unexpected attachments without verifying their legitimacy. |

**Key Takeaway:** Phishing attempts often combine impersonation, urgency, suspicious links, and credential requests to convince recipients to take unsafe actions.


## Mission 3: Build Her Digital Shield

**Objective:** Identify security controls that would help protect individuals in different professional situations.

### Scenario 1: Traveling Cybersecurity Professional

A cybersecurity professional traveling to a conference had a laptop that automatically connected to a wireless network.

**Recommended Protection:**
- Verify wireless network legitimacy before connecting.
- Disable automatic connections to unfamiliar networks.
- Prefer trusted networks or approved secure connectivity options.

**Risk:** Untrusted wireless networks can expose users to malicious network activity, including rogue access points and attempts to intercept insecure communications.

### Scenario 2: New Employee

A new employee needed to configure multiple business accounts and considered reusing passwords containing personal information.

**Recommended Protection:**
- Enable multifactor authentication (MFA).
- Use a password manager to generate and store strong, unique passwords.
- Avoid including personal information in passwords.

**Risk:** Reused or predictable passwords increase the likelihood and potential impact of account compromise.

### Scenario 3: Senior Business Leader

A senior leader received a message appearing to come from the CFO requesting financial information. The sender instructed the recipient not to call.

**Recommended Protection:**
- Independently verify unusual requests through a trusted communication channel.
- Confirm the identity of the requester before sharing sensitive information.
- Use MFA to strengthen account security.

**Risk:** The request could represent executive impersonation or business email compromise.

### Scenario 4: Researcher

A researcher collaborating with an external university was preparing to upload project findings to a shared folder.

**Recommended Protection:**
- Review organizational data classification requirements.
- Confirm the information is approved for external sharing.
- Verify that external collaborators have appropriate access permissions.

**Risk:** Sensitive research data could be exposed through unauthorized sharing or improperly configured access permissions.

**Key Takeaway:** Security controls should address the specific risks associated with an individual's responsibilities, access, and activities.

## Mission 4: Cyber Myth Smash

<img width="1438" height="628" alt="Screenshot 2026-11-11 105418" src="https://github.com/user-attachments/assets/44fb62a5-26ad-475e-a8b7-9a2801d86458" />

**Objective:** Distinguish cybersecurity facts from common misconceptions.

| Statement | Answer | Explanation |
|---|---|---|
| A known person is automatically safe | Myth | Trusted accounts can be compromised or impersonated. |
| Report suspicious activity even if you did not click | Fact | Reporting helps security teams identify and investigate potential threats. |
| Software updates can include security fixes | Fact | Updates may address vulnerabilities and security weaknesses. |
| MFA provides protection beyond a password | Fact | Additional authentication factors reduce reliance on passwords alone. |
| Only technical employees are targeted | Myth | Social engineering attacks can target employees in any role. |
| Questions strengthen security culture | Fact | Security awareness and communication help employees recognize and report threats. |

**Key Takeaway:** Cybersecurity awareness is important for all employees, regardless of their technical knowledge or job responsibilities.

## Skills Practiced

- Phishing and social engineering identification
- Threat recognition and risk assessment
- Business email compromise awareness
- Identity and access security
- Data classification and protection
- Security decision-making
- Communicating security risks

## Key Takeaways

The CyberSHEcurity Challenge reinforced the importance of evaluating suspicious activity instead of relying on appearances or familiarity.

Several scenarios demonstrated how attackers use urgency, impersonation, and trusted communication channels to influence decisions. The event also emphasized the role of preventive security controls, including MFA, password managers, independent verification, and data classification.

Overall, the challenge provided an opportunity to practice identifying security risks and selecting appropriate responses across different workplace scenarios.

