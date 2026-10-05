# Incident Response

## Case

Simulated phishing email investigation.

The following response plan is based on the findings from the simulated phishing investigation.

---

## 1. Report and Contain

The suspicious email should be reported through the organization's approved security reporting channel.

The security team should quarantine or remove the message from affected mailboxes where appropriate.

---

## 2. Determine the Scope

The SOC analyst should determine whether the email was received by:

- One employee
- Multiple employees
- A larger group of users

The analyst should also check whether any users interacted with the email or its link.

---

## 3. Investigate User Activity

The investigation should determine:

- Whether the link was clicked
- Whether credentials were entered
- Whether additional suspicious activity occurred
- Whether relevant security alerts or logs were generated

In a real environment, the analyst would correlate available email, identity, endpoint, and network telemetry.

---

## 4. Analyze Security Evidence

If security logs are available, the analyst should investigate:

- Source IP address
- User account involved
- Authentication activity
- Sign-in location and timing
- Related security alerts
- Other affected systems or accounts

The source IP should be investigated using the organization's approved security tools and threat intelligence sources.

---

## 5. If Credentials Were Compromised

If a user entered their credentials, the security team should:

1. Reset or revoke the affected credentials.
2. Revoke active sessions where appropriate.
3. Review recent authentication activity.
4. Check for suspicious account activity.
5. Investigate whether other accounts were affected.
6. Continue monitoring for related activity.

---

## 6. Impact Assessment

The SOC team should determine:

- Which users were affected
- Whether credentials were exposed
- Whether unauthorized access occurred
- What systems or data may have been exposed
- Whether additional incidents are connected to the phishing email

---

## 7. Recovery and Prevention

After containment and investigation, the organization should use the findings to improve its defenses.

Possible improvements include:

- Strengthening email security controls
- Improving detection rules
- Reviewing identity security controls
- Increasing security awareness training
- Conducting tabletop exercises
- Improving incident response procedures
- Applying defense-in-depth principles

---

## 8. Analyst Lesson Learned

A phishing incident should not only be closed after removing the email.

The organization should use the incident to identify weaknesses, improve detection and response capabilities, and reduce the likelihood of similar incidents in the future.

**SOC mindset:**

Detect → Investigate → Contain → Recover → Learn → Improve
