# About
I'm building this config to use on all my Apple devices (iOS, macOS) and Windows 10 PC. This list does a pretty good job of denying background queries by iCloud metrics and mobile apps (Google, Snapchat, Reddit, FB/Instagram), and blocking ads in mobile games when DNS settings are applied system wide on iOS.

# Getting Started
You'll need an account with [NextDNS](https://nextdns.io/). ***Remember to enable 2FA!***

# The Configuration
## Setup
I am using NextDNS for Windows and NextDNS Apple Configuration Profiles to install this DNS setting to my devices. Not tested on router-based install.

## Security
I have enabled everything *but* Cryptojacking Protection, which is known to cause some issues. 

You can see my list of Blocked Top-Level Domains (TLDs) [here](https://github.com/cullen-s/NextDNS-config/blob/main/blockedtlds.txt).

## Privacy
#### Blocklists
I am using oisd, 1Hosts (Lite) and Lightswitch05 - Ads & Tracking

#### Native Tracking Protection
I have enabled all of these. It blocks a pretty insignificant amount of queries overall, but hasn't broken anything.

#### Block Disguised Third-Party Trackers
Enabled

#### Allow Affiliate & Tracking Links
Disabled

## Parental Controls
I am not using these settings.

## Denylist
See my custom [denylist](https://github.com/cullen-s/NextDNS-config/blob/main/denylist.txt).

## Settings
#### Logs
Enabled, logging IPs and domains. I retain for 1 day for any necessary troubleshooting.

#### Block Page
Disabled, compatibility and performance issues.

#### Performance
Enable everything

#### Web3
Disabled
