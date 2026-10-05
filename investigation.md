# Phishing Email Investigation

## Case Overview

This is a simulated SOC investigation created for cybersecurity training.

The objective is to analyze a suspicious email, identify indicators of phishing, assess the risk, and document the recommended response.

---

## 1. Email Details

| Field | Observation |
|---|---|
| Sender | IT Support `<it-support@example.test>` |
| Reply-To | `helpdesk@example.test` |
| Subject | Urgent: Account Verification Required |
| URL | `https://login.example.test/verify` |
| Attachment | None |
| Case Type | Simulated Phishing |

---

## 2. Investigation Findings

### Sender Analysis

The email uses an IT Support display name.

The sender identity should not be trusted based only on the display name. Further verification would normally be performed using email headers and organizational email security tools.

**Finding:** Sender identity requires verification.

### Reply-To Analysis

The Reply-To address differs from the apparent sender address.

This is an indicator that should be investigated because replies may be directed to a different mailbox.

**Finding:** Reply-To mismatch identified.

### Subject Analysis

The subject contains urgent language:

`Urgent: Account Verification Required`

This creates pressure for the recipient to act quickly.

**Finding:** Urgency-based social engineering indicator.

### URL Analysis

The email contains:

`https://login.example.test/verify`

The `.test` domain is intentionally used for this training scenario and does not represent a real website.

The link requests account verification.

**Finding:** Unexpected account-verification link.

### Social Engineering Analysis

The message warns that the account may face restrictions if the recipient does not act.

This creates fear and urgency, which are common social-engineering techniques.

**Finding:** Fear and urgency indicators identified.

---

## 3. Risk Assessment

| Risk Factor | Assessment |
|---|---|
| Sender identity | Suspicious |
| Reply-To | Suspicious |
| Urgency | Suspicious |
| Account verification request | Suspicious |
| Social engineering | Present |
| Overall risk | High |

---

## 4. Analyst Verdict

**Verdict: Likely Phishing — Simulated Case**

Multiple indicators were identified, including a Reply-To mismatch, urgency, an account-verification request, and social-engineering language.

The email should be treated as suspicious and investigated further in a real SOC environment.

---

## 5. Investigation Workflow

```text
Email Alert
    ↓
Analyze Sender
    ↓
Check Reply-To
    ↓
Inspect URL
    ↓
Identify Social Engineering
    ↓
Extract IOCs
    ↓
Assess Risk
    ↓
Determine Verdict
    ↓
Recommend Response
