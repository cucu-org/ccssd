# ccssd

Cucu's Self-Defense Guide is an open-source guide for ordinary users who want to protect their devices and accounts from common threats.

It focuses on practical security hygiene rather than absolute guarantees.

You don't have to be a hacker, but you should understand basic security risks and how to reduce them.

---

## Table of Contents

- [Account Compromise Detection](#account-compromise-detection)
- [Understanding Tracking](#understanding-tracking)
- [Malware Monitoring Behavior](#malware-monitoring-behavior)
- [File Access and Malware Risk](#file-access-and-malware-risk)
- [Isolating Untrusted Applications](#isolating-untrusted-applications)
- [Security Fundamentals](#security-fundamentals)
- [Final Note](#final-note)

---

## Account Compromise Detection

Account compromise and device compromise are different problems. Start by checking accounts first.

### Checking Your Accounts

- Review account activity logs (Google, Microsoft, Facebook, etc.)
- Check connected devices and active sessions
- Review third-party application access
- Verify recovery email and phone number

### Signs of Account Compromise

- Password reset emails you did not request
- Login attempts from unfamiliar locations
- Security settings changed without authorization
- Messages sent from your account that you did not send
- Unknown applications connected to your account

---

## Understanding Tracking

Tracking can occur across multiple layers: network, application, and account systems.

### Common Tracking Methods

**Location-based tracking**
- GPS location services
- Cell tower triangulation
- WiFi-based positioning
- App-based location sharing

**Online tracking**
- Cookies and tracking pixels
- Browser fingerprinting
- Cross-site advertising networks
- Social media tracking

**App-based tracking**
- Permission-based location access
- Background telemetry
- Device identifiers
- Embedded analytics SDKs

### Checking Tracking Exposure

- Review application permissions regularly
- Audit location and privacy settings
- Review connected services and account access
- Use browser privacy features and tracker blocking

### Reducing Tracking

- Disable location services when not needed
- Restrict app permissions to minimum required
- Use privacy-focused browsers and search engines
- Disable ad personalization settings
- Periodically review social media privacy controls

---

## Malware Monitoring Behavior

Possible signs of malware activity include unusual battery drain, overheating, or abnormal network usage. These are indicators, not proof of compromise.

Modern Android systems provide built-in privacy indicators:

- Camera and microphone usage indicators
- System notifications for active recording (on supported devices)
- Runtime permission prompts

These mechanisms help detect common spyware behavior but do not guarantee full protection.

---

## File Access and Malware Risk

On Android 11 and later, storage access is restricted using scoped storage.

Applications cannot freely access all files by default.

Some applications may request elevated storage permissions ("All files access"). These should be reviewed carefully.

### Check storage permissions:

Settings → Privacy → Special App Access → All Files Access

Remove permissions for applications you do not trust or recognize.

---

## Isolating Untrusted Applications

If you must use applications that require high permissions, isolation reduces exposure risk.

### Recommended approach:

- Use a separate work profile
- Keep personal and untrusted applications separated

Tools such as Shelter can create isolated work profiles on Android devices.

Isolation reduces risk but does not eliminate it.

---

## Security Fundamentals

All software, including operating systems, kernels, and central processing units, may contain vulnerabilities.

In practice, users cannot reliably determine whether a specific vulnerability is being exploited against them.

### Core security principles:

- Minimize attack surface by installing only necessary software
- Prefer trusted and maintained applications
- Keep system and applications updated regularly
- Limit application permissions
- Avoid untrusted or unknown software sources

These practices significantly reduce exposure to common threats but do not eliminate risk.

Security is context-dependent, and different users may adopt different threat models based on their needs.

---

## Final Note

Security is not a fixed state but an ongoing process of reducing exposure and managing risk.