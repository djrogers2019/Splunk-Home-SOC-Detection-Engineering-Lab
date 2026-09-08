# Splunk Home SOC & Detection Engineering Lab

## Overview

This project documents the design and implementation of a home Security Operations Center using Splunk Enterprise.

The goal of the lab is to build hands-on experience with:

- Splunk Enterprise
- SPL
- Log ingestion
- Splunk Universal Forwarder
- macOS telemetry
- Security monitoring
- Detection engineering
- Dashboards
- Incident investigation
- MITRE ATT&CK

## Current Architecture

MacBook Neo
→ Splunk Universal Forwarder
→ Ubuntu 24.04 x86_64 VM
→ Splunk Enterprise
→ `index=macos`

## Current Progress

- [x] Created Ubuntu x86_64 VM using UTM
- [x] Installed Ubuntu Server 24.04
- [x] Installed Splunk Enterprise
- [x] Configured Splunk to start automatically
- [x] Enabled receiving on TCP 9997
- [x] Created the `macos` index
- [x] Installed Splunk Universal Forwarder on macOS
- [x] Forwarded macOS logs into Splunk
- [x] Created first Splunk report
- [x] Created Home SOC dashboard
- [ ] Add security datasets
- [ ] Build SPL detections
- [ ] Map detections to MITRE ATT&CK
- [ ] Conduct incident investigations
- [ ] Complete SOC portfolio documentation

## Dashboard

Current dashboard:

**Home SOC Overview**

Panels:

- macOS Event Volume
- Top macOS Log Sources

## Repository Status

This project is currently under active development.
