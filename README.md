# ccssd

Cucu's Self-Defense Guide is an open-source guide for ordinary users who want to protect their devices and accounts from common threats.

It focuses on practical security hygiene rather than absolute guarantees.

You don't have to be a hacker, but you should understand basic security risks and how to reduce them.

---

## Table of Contents

- Am I Being Monitored?
- Am I Being Tracked?
- My Device Is Being Monitored by Malware
- Can Malware Steal All of My Files?
- Isolating Untrusted Apps
- Security Fundamentals

---

## Am I Being Monitored?

Account compromise and device compromise are different problems. Start by checking accounts first.

### Checking Your Accounts

- Review account activity logs (Google, Microsoft, Facebook, etc.)
- Check connected devices and sessions
- Review third-party app access
- Verify recovery email and phone number

### Signs of Account Compromise

- Password reset emails you did not request
- Login attempts from unfamiliar locations
- Security settings changed without authorization
- Messages sent from your account that you did not send
- Unknown applications connected to your account

---

## Am I Being Tracked?

Tracking can occur through multiple layers: network, application, and account-level systems.

### Common Tracking Methods

**Location-based tracking**
- GPS services
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
- Analytics SDKs embedded in apps

### Checking Tracking Exposure

- Review app permissions regularly
- Check location and privacy settings
- Audit connected services and app authorizations
- Use browser privacy settings and tracker blocking

### Reducing Tracking

- Disable location services when not needed
- Limit app permissions to minimum required
- Use privacy-focused browsers and search engines
- Disable ad personalization where possible
- Review social media privacy settings periodically

---

## My Device Is Being Monitored by Malware

Possible signs include unusual battery drain, overheating, or abnormal network activity. These are indicators, not proof.

Modern Android systems provide built-in privacy indicators:

- Camera and microphone usage indicators
- Notifications for active recording on some devices
- System-level permission prompts

These features help detect common spyware behavior, but they are not complete guarantees of security.

---

## Can Malware Steal All of My Files?

On modern Android systems (Android 11+), storage access is restricted by scoped storage.

Applications cannot freely access all files by default.

Some apps may request elevated storage permissions ("All files access"). These should be reviewed carefully.

### Check storage access:

Settings → Privacy → Special App Access → All Files Access

Remove permissions from applications you do not trust or recognize.

---

## Isolating Untrusted Apps

If you must use untrusted or high-permission applications, isolation can reduce risk.

Recommended approach:

- Use a separate work profile
- Keep personal data separate from untrusted apps

Tools such as Shelter can create isolated work profiles on Android.

Isolation reduces exposure but does not eliminate risk.

---

## Security Fundamentals

All software, including operating systems, kernels, and central processing units, may contain vulnerabilities.

In practice, users cannot reliably determine whether a specific vulnerability is being exploited against them.

### Core security principles:

- Minimize attack surface by installing only necessary software
- Prefer trusted and maintained applications
- Keep system and applications updated regularly
- Limit permissions granted to applications
- Reduce exposure to unknown or untrusted software

These practices significantly reduce exposure to common threats but do not eliminate all risk.

Security is context-dependent, and different users may adopt different threat models based on their needs.

---

## Final Note

Security is not a fixed state but a continuous process of reducing exposure and managing risk.