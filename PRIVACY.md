# Privacy Policy — Process Network Usage

**Last updated: November 24, 2026**

Process Network Usage ("the app") is published by Cedar Byte Software. This policy explains what
information the app handles and where it goes.

**In short: everything the app sees stays on your PC. The app has no account system, no analytics,
no telemetry and no advertising, and it never sends any of your data to us.**

## What the app reads on your PC

To show which programs use your network, the app reads, on your computer only:

- the names, paths, publishers and digital signatures of running programs and Windows services;
- network activity per program: download/upload speeds and amounts, and the IP addresses, ports and
  host names of the computers they connect to;
- incoming connection attempts, firewall events and firewall rules;
- Windows Update / Delivery Optimization activity;
- network settings such as DNS servers, the router's MAC address and the Windows proxy (to alert you
  when they change).

## What the app stores, and where

The app saves its settings, usage history, timeline, incoming-connection history and alert settings
in your Windows user profile (`AppData\Local`) on your PC. This data never leaves your computer
unless you choose to export or email it (see below). You can delete it at any time by uninstalling
the app or removing that folder.

Files you export (CSV lists, HTML usage reports) are saved only where you choose.

## Network requests the app makes

The app itself contacts the internet only for these purposes:

| Purpose | What is sent | To whom |
|---|---|---|
| **Country database** (to show the country of a connection) | A normal download request for the free country database file, about once a month. No information about your connections is sent; country lookups happen on your PC. | db-ip.com |
| **Host names** (to show names instead of bare IP addresses) | Reverse-DNS lookups of the remote IP addresses your programs already connect to. | Your own DNS server (the one Windows uses) |
| **Server identification** (Pro, optional) | A standard secure-connection handshake with a remote server your programs already connect to, to read the name on its certificate. No data from your PC is sent. | That remote server |
| **Email alerts** (Pro, optional, off by default) | The alert text you chose to receive (for example a program name, an IP address or a data amount). | The email (SMTP) server **you** configure, to the address **you** enter |
| **Microsoft Store purchase and licence check** | The standard Store licence check for the Pro add-on. | Microsoft (Microsoft Store) |

**Email account details.** If you turn on email alerts, the app stores your email address, SMTP
server settings and password on your PC. The password is encrypted with Windows Data Protection
(DPAPI) so that only your Windows account on that PC can read it. These details are only ever sent
to the mail server you entered.

**VirusTotal.** When you click "Check on VirusTotal", the app opens the VirusTotal web page for that
file's fingerprint (SHA-256 hash) in your web browser. Nothing is uploaded by the app; what happens on
that website is governed by VirusTotal's own privacy policy.

## Purchases

Pro is sold through the Microsoft Store. Payment is handled entirely by Microsoft under the
[Microsoft Privacy Statement](https://privacy.microsoft.com/privacystatement). We never see your
payment details. Microsoft provides us with standard, aggregated sales reports.

Copies of the app downloaded outside the Store may use a licence key; the key is checked on your PC
and is not sent anywhere.

## Sharing, selling and children

We do not collect, sell, rent or share your personal information, because the app does not send it
to us. The app is a general-purpose utility and is not directed at children.

## Changes

If this policy changes, the new version will be published at this address with a new "Last updated"
date.

## Contact

Questions about this policy: open an issue at
<https://github.com/AlbertAssaad/ProcessNetworkUsage/issues>.
