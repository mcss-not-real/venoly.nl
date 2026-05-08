# ⚠️ Warning: venoly.nl - Admitted GDPR Violations & Deceptive Privacy Practices

> This repository documents **publicly evidenced admissions** by the owner of [venoly.nl](https://venoly.nl) regarding illegal data collection, GDPR non-compliance, and practices that directly contradict the site's own Terms of Service and Privacy Policy.

---

## Summary

The operator of **venoly.nl** (Discord username: `mcss`) has openly admitted - in a **private direct message (DM)** to us - to:

- Collecting extensive user data without lawful basis
- Knowingly violating GDPR
- Deliberately obfuscating stored data to avoid detection
- Secretly transferring collected data to a private hard drive
- Logging emails and other sensitive information

These admissions stand in direct contradiction to whatever privacy policy or terms of service the site presents to users.

---

## A note on the evidence

We are aware that **screenshots can be fabricated**. We are not asking you to take them at face value alone.

That is why this repository also documents **independently verifiable issues** with venoly.nl that require no screenshots and cannot be dismissed as forgeries - see [Technical Red Flags](#technical-red-flags) below.

The screenshots are included because they originate from a **private DM** in which the site owner willingly and unprompted described their own practices in detail. We present them as supporting context, not as sole proof.

---

## Evidence - Conversations

The following screenshots are taken from a **private direct message** with the site's owner. They have not been edited.

### Screenshot 1 - Admitted data collection scope

[![venoly convo1](https://github.com/mcss-not-real/venoly.nl/blob/main/venoly%20convo1.png?raw=true)](https://github.com/mcss-not-real/venoly.nl/blob/main/venoly%20convo1.png)

The owner lists what data their panel collects per visitor:
- ISP and IP address
- Whether the user is on mobile
- VPN detection
- Browser languages
- Browser type and user agent
- **Device and browser fingerprinting**
- **Storage-based tracking**
- **Derived data**
- **Silent data harvesting**
- **"User assisted attack"** (their words)
- **System probing**

### Screenshot 2 - Admitted GDPR violation

[![venoly convo2](https://github.com/mcss-not-real/venoly.nl/blob/main/venoly%20convo2.png?raw=true)](https://github.com/mcss-not-real/venoly.nl/blob/main/venoly%20convo2.png)

When directly asked *"You know you're violating GDPR?"*, the owner responded:

> **"Yes. But GDPR can't verify it. Neither no one. No one has access. Databases are also mushed. So only a tool can open it. Custom tool I made."**

> **"And actual data are secretly transferred to an actual hard drive. That has 1TB storage. To store it all. Logs emails. Everything."**

This is a direct, voluntary admission of:
1. Knowing GDPR non-compliance
2. Deliberately obfuscating databases to prevent inspection
3. Covert offline data exfiltration
4. Logging email addresses

### Screenshot 3 - Discord selfbots

[![venoly convo3](https://github.com/mcss-not-real/venoly.nl/blob/main/venoly%20convo3.png?raw=true)](https://github.com/mcss-not-real/venoly.nl/blob/main/venoly%20convo3.png)

Shows the owner operating Discord selfbots (violating Discord's Terms of Service), demonstrating a broader pattern of disregard for platform rules and legal frameworks.

### Screenshot 4 - Abusive behavior toward users

[![venoly convo4](https://github.com/mcss-not-real/venoly.nl/blob/main/venoly%20convo4.png?raw=true)](https://github.com/mcss-not-real/venoly.nl/blob/main/venoly%20convo4.png)

When the operator's practices were questioned, he responded with racial slurs and invited others to join in.

This behavior speaks to the general conduct of the operator toward anyone who raises concerns.

---

## Technical Red Flags

These issues are **independently verifiable** and do not rely on screenshots.

### Fake status page - randomized uptime data

venoly.nl hosts a public status page at `venoly.nl/status` displaying uptime charts for the last 90 days. However, **the numbers change on every page refresh** - for the same historical time period.

Examples captured in two separate loads of the same page:

| Service    | Load 1   | Load 2   |
|------------|----------|----------|
| API        | 98.89%   | 100.00%  |
| Database   | 98.89%   | 97.78%   |
| Redis      | 96.67%   | 97.78%   |
| WebSocket  | 98.89%   | 100.00%  |
| CDN        | 97.78%   | 95.56%   |

Historical uptime data is, by definition, fixed - it represents the past. **There is no legitimate reason for these numbers to change between page loads.** The most likely explanation is that the values are generated randomly rather than pulled from real monitoring infrastructure.

This is both suspicious and deeply unprofessional. A platform presenting fake reliability metrics to potential users cannot be trusted.

You can verify this yourself using the archived snapshots below. Note: the Wayback Machine has had reliability issues archiving this site, so we are using archive.today instead.

- 🔗 [archive.today - venoly.nl/status (May 8, 2026)](http://archive.today/8EFEz)

We encourage others to **make additional snapshots** at [archive.today](https://archive.today) - particularly of the status page - to build a record of the changing values over time.

### Landing page changes daily

The venoly.nl landing page is replaced with a new design on an almost daily basis. As of writing, at least 4 different versions have appeared within the span of 2 days.

We are not sure what the purpose of this is - it may indicate the site is still in very early or experimental stages, or it may simply reflect instability in the project's direction. Either way, it is worth documenting.

An archived snapshot of the landing page from May 8, 2026 is available here:
- 🔗 [archive.today - venoly.nl (May 8, 2026)](http://archive.today/Qbuwr)

Note: the Wayback Machine has had reliability issues archiving this site, which is why we are using archive.today for all snapshots.

**We encourage others to make additional snapshots** at [archive.today](https://archive.today) - of both the landing page and the status page - as the site continues to change.

---



## What this means for users of venoly.nl

If you have visited or signed up on venoly.nl, you should be aware that:

- **Your IP, browser fingerprint, and device data have likely been collected** and stored without your knowledge
- **Your email may have been logged** and stored on a private hard drive with no transparency
- The site's privacy policy (if one exists) does not reflect actual data handling practices
- The operator has explicitly stated they believe this is undetectable and therefore acceptable
- The operator responds to user concerns with abuse and harassment

---

## What you can do

- **Do not use venoly.nl** or create accounts there
- **Report to your national data protection authority** if you are an EU/EEA resident:
  - 🇩🇪 Germany: [bfdi.bund.de](https://www.bfdi.bund.de)
  - Full list: [edpb.europa.eu/about-edpb/about-edpb/members_en](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en)
- **Share this repository** so others can make an informed decision

---

## Disclaimer

This repository contains unedited screenshots of **private direct messages** and quotes the site operator verbatim. The status page discrepancy is independently verifiable. No claims are made beyond what is directly evidenced in the provided material. The goal of this repository is consumer protection and public awareness, not harassment.

---

*Last updated: May 2026*
