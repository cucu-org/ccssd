ccssd

Cucu's Self-Defense Guide is an open-source guide for ordinary users who want to protect their devices and accounts from common threats.

It addresses practical questions such as:

- Am I being monitored?
- Has my device been compromised?
- Is this app safe to install?
- How do I recognize suspicious behavior?

«You don't have to be a hacker, but you should know when your device has been hacked.»

## Table of Contents

- [Am I Being Monitored?](#am-i-being-monitored)
- [Am I Being Tracked?](#am-i-being-tracked)
- [My Device Is Being Monitored by Malware](#my-device-is-being-monitored-by-malware)
- [Can Malware Steal All of My Files?](#can-malware-steal-all-of-my-files)
- [Isolating Untrusted Apps](#isolating-untrusted-apps)

## Am I Being Monitored?

First, determine whether your online accounts are being accessed by someone else, or whether your device itself has been compromised. These are two different problems.

### Checking Your Accounts

To determine if your accounts are being accessed without authorization:

1. **Review account activity logs** - Most services like Google, Facebook, and Microsoft provide security checkups and activity logs
2. **Check connected devices and sessions** - Look for unfamiliar devices or locations accessing your accounts
3. **Review connected apps** - Verify which third-party applications have access to your account
4. **Check recovery options** - Ensure your email and phone number haven't been changed without your permission

### Signs of Account Compromise

- Unexpected password reset emails
- Login attempts from unfamiliar locations
- Changed security settings you didn't authorize
- Friends reporting receiving messages from your account
- Unfamiliar apps connected to your account

## Am I Being Tracked?

Tracking can occur at multiple levels and through various methods. Understanding these will help you identify if you're being tracked.

### Digital Tracking Methods

**Location Tracking:**
- GPS tracking through your device's location services
- Cell tower triangulation by your mobile carrier
- WiFi-based location services
- Tracking through social media check-ins and posts

**Online Tracking:**
- Website cookies and tracking pixels
- Browser fingerprinting
- Advertising trackers across websites
- Social media tracking across the web

**App-Based Tracking:**
- Apps requesting location permissions
- Background location tracking even when the app is closed
- Device identifiers being sent to tracking services
- Analytics and telemetry in apps

### How to Check What's Tracking You

1. **Review app permissions** - Check which apps have access to your location, contacts, camera, and microphone
2. **Check privacy settings** - Review location sharing settings in your device settings and individual apps
3. **Review connected services** - Check which apps and websites have permission to access your account
4. **Monitor network activity** - Use network monitoring tools to see what data apps are sending

### Reducing Tracking

- Disable location services when not needed
- Review and restrict app permissions regularly
- Use privacy-focused browsers and search engines
- Consider using a VPN for additional privacy
- Review and disable advertising personalization in your accounts
- Opt out of data collection where possible
- Use privacy settings in social media and other services

## My Device Is Being Monitored by Malware

If malware is secretly recording your screen, taking photos, or listening through the microphone, one possible symptom is unusual overheating or battery drain. However, these are only warning signs, not definitive proof.

Modern Android devices provide several privacy indicators:

- When an app accesses the camera, Android displays a camera indicator and, on some devices, a notification showing which app is using it.
- The same applies to microphone access.
- Some Android manufacturers also notify users when screen recording or screen capture is taking place.

These indicators can help detect many common forms of spyware and eavesdropping malware.

## Can Malware Steal All of My Files?

On Android 11 and later, apps are restricted by scoped storage. By default, applications cannot freely access files outside their own private directories.

Apps that need broad access to storage must request the All Files Access permission. Therefore, if a malicious application is able to collect files across your device, it is likely that this permission has been granted.

You can review which apps have this permission by navigating to:

Settings → Privacy → Special App Access → All Files Access

If you find an unfamiliar or suspicious application, revoke its access.

Keep in mind that an app appearing legitimate does not guarantee that it is trustworthy.

## Isolating Untrusted Apps

If you must use an application that requires extensive storage permissions, consider isolating it from your personal files by using a separate work profile.

A recommended tool for this purpose is Shelter, which creates an isolated workspace and helps reduce the risk of exposing personal data to untrusted applications.

«No single symptom proves that a device has been hacked. Overheating, battery drain, or unusual network activity are warning signs, not evidence.»
