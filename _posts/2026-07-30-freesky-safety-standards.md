---
title: "Freesky Safety Standards"
date: 2026-07-30 00:00:00 +0000
categories: [tech-nerd]
description: "CSAE safety policy for Freesky — how we combat child sexual abuse material in an end-to-end encrypted messaging app"
---

*Last updated: 2026-07-30*

## 1. Introduction

Freesky is an end-to-end encrypted community messaging application. This policy describes our commitment to preventing, detecting, and responding to any content that promotes, solicits, or depicts the sexual exploitation of children (CSAE).

**Contact:** daniootsutsuki@gmail.com

---

## 2. Our Commitment

Freesky is committed to combating CSAE. While Freesky's end-to-end encryption means we cannot read user messages, we take the following measures to combat CSAE.

---

## 3. What We Cannot Do

- **Freesky cannot decrypt user content.** All post content is encrypted end-to-end with AES-256-GCM. Only community members with the group key can read posts. This means Freesky has no technical ability to review message content.
- **Freesky has no user account information.** Registration uses only a cryptographic public key generated on-device. No email, phone number, real name, or age verification is collected.

---

## 4. What We Can Do

### 4.1 Reporting Mechanism

- Users can report posts. When a report is submitted, the reported post's ID and the reporter's public key are sent to the server.
- Server logs (IP address, connection timestamps, public keys) are retained for investigation purposes.

### 4.2 Server-Side Monitoring

- The server operator monitors reports and investigates flagged content.
- The server operator cooperates with law enforcement and NCMEC (National Center for Missing & Exploited Children) when legally required.

### 4.3 Encryption Limitations

- Because content is encrypted, we rely on **post-registration metadata** and **user reports** to identify problematic activity.
- We cannot proactively scan encrypted content. We depend on our community to use the reporting mechanism.

---

## 5. Age Restrictions

Freesky is not directed at children under 13. Users must be at least 13 years old to register. We do not knowingly collect information from children.

---

## 6. Law Enforcement Cooperation

Freesky's server operator will respond to valid legal requests from law enforcement and will preserve server logs (IP addresses, public keys, timestamps) for investigation of CSAE-related offenses.

---

## 7. Third-Party Reporting

Suspected CSAE content can also be reported to NCMEC via their CyberTipline: https://report.cybertip.org

---

## 8. Policy Updates

Updates will be posted at [https://walawe.fun/freesky-safety-standards](https://antinormies.github.io/tech-nerd/freesky-safety-standards/)
