# FortiGate Traffic Shaping Lab

## Overview

This lab demonstrates how to configure **Traffic Shaping** on a FortiGate firewall using PNETLab.

Traffic Shaping is used to control network bandwidth and limit the speed of specific traffic.

## Lab Objectives

- Configure Traffic Shapers.
- Limit network bandwidth.
- Set traffic priority.
- Apply traffic-shaping policies.
- Test and monitor network speed.

## Configuration

### 1. Firewall Policy

A firewall policy allows traffic to pass from the internal network to the Internet through the FortiGate firewall.

### 2. Traffic Shapers

Traffic Shapers control how much bandwidth network traffic can use.

- **Maximum Bandwidth:** Sets the maximum allowed speed.
- **Guaranteed Bandwidth:** Defines the bandwidth intended to be reserved for traffic.
- **Priority:** Determines which traffic receives preference when bandwidth is limited.

### 3. Traffic-Shaping Policy

A traffic-shaping policy applies bandwidth limits to selected traffic.

In this lab, the `limit` shaper is configured with a maximum bandwidth of **100 Kbps**.

## Verification

Traffic shaping is tested using a browser-based speed test and the FortiGate dashboard.

The dashboard helps monitor bandwidth usage and traffic statistics.

The lab screenshots show speed-test results of approximately **120 Kbps** and **1.5 Mbps**. These are observed results and may vary depending on the active configuration.

## Conclusion

This lab demonstrates how FortiGate Traffic Shaping can limit bandwidth, manage traffic priority, and monitor network performance.

## Technologies Used

- FortiGate Firewall
- PNETLab
- Traffic Shaping
- Bandwidth Management

---

**Author:** Abdalla Mohamed Nieam
